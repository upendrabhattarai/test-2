## Day 2 Homework Exercises

### Data wrangling

```r
# 1. Extract only those elements in `samplegroup` that are not KO (*nesting the logical operation is optional*).
idx <- samplegroup != "KO"
samplegroup[idx]

# 2. Use the `samplegroup` factor we created in a previous lesson, and relevel it such that KO is the first level followed by CTL and OE.
factor(samplegroup, levels = c("KO", "CTL", "OE"))

### Packages and Libraries

# 1. Install the tidyverse package (it is actually a suite of packages). NOTE: This suite of packages is only available in CRAN.
install.packages("tidyverse")

# 2. Load the tidyverse library. Do you see anything unusual when it loads?
library(tidyverse)
#Some functions from dyplyr (part of tidyverse package) mask the same functions from the basic stats. But that is fine! If you need to use filter function from stats, you can type 'stats::filter()'

# 3. Run sessionInfo().
sessionInfo()
```



### Data wrangling: data frames, matrices, and lists

```r
# 1. Return the genotype and replicate column values for Sample2 and Sample8.
metadata[c("sample2", "sample8"), c("genotype", "replicate")] # or
metadata[c(2,8), c(1,3)]

# 2. Return the fourth and ninth values of the replicate column.
metadata$replicate[c(4,9)] # or
metadata[c(4, 9), "replicate"]

# 3. Extract the replicate column as a data frame.
metadata[, "replicate", drop = FALSE]

# 4. Subset the metadata dataframe to return only the rows of data with a genotype of KO.
idx <- which(metadata$genotype=="KO")
metadata[idx, ]

# 5. Create a list named random with the following components: metadata, age, list1, samplegroup, and number.
random <- list(metadata, age, list1, samplegroup, number)

# 6. Extract the samplegroup component.
random[[4]]

# 7. Set names for the random list you created in the last exercise.
names(random) <- c("metadata", "age", "list1", "samplegroup", "number")

# 8. Extract the age component using the $ notation
random$age
```


### The %in% operator

```r
# 1. Using the A and B vectors created above, evaluate each element in B to see if there is a match in A
B %in% A

# 2. Subset the B vector to only return those values that are also in A.
B[B %in% A]

# 3. We have a list of 6 marker genes that we are very interested in. Our goal is to extract count data for these genes using the %in% operator from the rpkm_data data frame, instead of scrolling through rpkm_data and finding them manually.

#       i. First, let’s create a vector called important_genes with the Ensembl IDs of the 6 genes we are interested in:
        
        important_genes <- c("ENSMUSG00000083700", "ENSMUSG00000080990", "ENSMUSG00000065619", "ENSMUSG00000047945", "ENSMUSG00000081010", "ENSMUSG00000030970")
        
#       ii. Use the %in% operator to determine if all of these genes are present in the row names of the rpkm_data data frame.
important_genes %in% rownames(rpkm_data)
        
#       iii. Extract the rows from rpkm_data that correspond to these 6 genes using [] and the %in% operator. Double check the row names to ensure that you are extracting the correct rows.
idx <- rownames(rpkm_data) %in% important_genes
ans <- rpkm_data[idx, ]
idx2 <- which(rownames(rpkm_data) %in% important_genes)
ans2 <- rpkm_data[idx2, ]

#       iv. Bonus question: Extract the rows from rpkm_data that correspond to these 6 genes using [], but without using the %in% operator.
ans3 <- rpkm_data[important_genes, ]

```    

        
### Reordering and matching

```r
# 1. Now that we know how to reorder using indices, let’s try to use it to reorder the contents of one vector to match the contents of another. Let’s create the vectors first and second as detailed below:
first <- c("A","B","C","D","E")
second <- c("B","D","E","A","C")  # same letters but different order
        
#        How would you reorder the second vector to match first?
second[c(4, 1, 5, 2, 3)]
     
# 2. After talking with your collaborator, it becomes clear that sample2 and sample9 were actually from a different mouse background than the other samples and should not be part of our analysis. Create a new variable called subset_rpkm that has these columns removed from the rpkm_ordered data frame.
subset_rpkm <- rpkm_ordered[ , c(1,3:8,10:12)]  #or
subset_rpkm <- rpkm_ordered[ , -c(2,9)]

# 3. Use the match() function to subset the metadata data frame so that the row names of the metadata data frame match the column names of the subset_rpkm data frame.  
idx <- match(colnames(subset_rpkm), rownames(metadata))
metadata[idx, ]
```                

***

!!! quote "Attribution notice"
    * *This lesson has been developed by members of the teaching team at the [Harvard Chan Bioinformatics Core (HBC)](http://bioinformatics.sph.harvard.edu/). These are open access materials distributed under the terms of the [Creative Commons Attribution license](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0), which permits unrestricted use, distribution, and reproduction in any medium, provided the original author and source are credited.*

    * *The materials used in this lesson are adapted from work that is Copyright © Data Carpentry (http://datacarpentry.org/).*
    
    * *All Data Carpentry instructional material is made available under the [Creative Commons Attribution license](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0).*