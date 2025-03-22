# Table of Contents

## Reports 2024 Data

### A. 01_Quality_Assessment
- **QC_report.Rmd**  
  Presents the quality assessment report of the dataset.

### B. 02_Differential_Expression
- **00_DGE_summary_report.Rmd**  
  Summary of DGE analysis with the number of DE genes in each comparison for 2024 datasets.
- **01_DGE_report_additive_n_interactions.Rmd**  
  DGE analysis with additive effect and interaction models presented separately.
- **02_DGE_report_Multiplicative.Rmd**  
  DGE analysis with a multiplicative model.
- **03_2024_DGE_Cortex_heatmap_additive.Rmd**  
  List of differentially expressed genes and their heatmaps in all samples, males only, and females only in Cortex for Q175 vs WT comparison.
- **04_2024_DGE_Striatum_heatmap_additive.Rmd**  
  List of differentially expressed genes and their heatmaps in all samples, males only, and females only in Striatum for Q175 vs WT comparison.
- **05_2024_DGE_Cortex_volcano_plot_additive.Rmd**  
  Volcano plots for CR3KO vs WT, Q175CR3KO vs Q175, and Q175 vs WT in Cortex. All samples, Males, and Females presented separately.
- **06_2024_DGE_Striatum_volcano_plot_additive.Rmd**  
  Volcano plots for CR3KO vs WT, Q175CR3KO vs Q175, and Q175 vs WT in Striatum. All samples, Males, and Females presented separately.
- **07_2024_DGE_Cortex_volcano_plot2_additive.Rmd**  
  Some aesthetic changes made on volcano plots above (05).
- **08_2024_DGE_Striatum_volcano_plot2_additive.Rmd**  
  Some aesthetic changes made on volcano plots above (06).
- **09_2024_DGE_Cortex_zscatter_plot_additive.Rmd**  
  Various z-scatterplots from Cortex, including CR3 ablation effect, for All samples, Male, and Female, presented separately.
- **10_2024_DGE_Striatum_zscatter_plot_additive.Rmd**  
  Various z-scatterplots from Striatum, including CR3 ablation effect, for All samples, Male, and Female, presented separately.
- **11_2024_DGE_volcano_plots3.Rmd**  
  Various volcano plots replotted with some aesthetic changes for both Striatum and Cortex.

### C. 03_Functional_Analysis
- **01_FA_GO_analysis_selected_comparisons.Rmd**  
  Over-representation analysis with GO database for CR3KO vs WT, Q175CR3KO vs Q175 comparison. Analysis for All samples, Males, and Females separately for Cortex and Striatum.
- **02_FA_ORA_Q175CR3kovsQ175.Rmd**  
  Over-representation analysis with GO database for Q175CR3KO vs Q175 comparison. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Male, Female, and All samples, for both Cortex and Striatum.
- **03_FA_ORA_Q175CR3kovsWTCR3ko.Rmd**  
  Over-representation analysis with GO database for Q175CR3KO vs CR3KO comparison. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Male, Female, and All samples, for both Cortex and Striatum.
- **04_FA_ORA_Q175vsWT.Rmd**  
  Over-representation analysis with GO database for Q175 vs WT comparison. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Male, Female, and All samples, for both Cortex and Striatum.
- **05_FA_ORA_WTCR3kovsWT.Rmd**  
  Over-representation analysis with GO database for CR3KO vs WT comparison. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Male, Female, and All samples, for both Cortex and Striatum.
- **06_FA_GSEA_Q175CR3kovsQ175.Rmd**  
  GSEA analysis with KEGG database for Q175CR3KO vs Q175 for Male and Female separately.
- **07_FA_GSEA_Q175CR3kovsWTCR3ko.Rmd**  
  GSEA analysis with KEGG database for Q175CR3KO vs CR3KO for Male and Female separately.
- **08_FA_GSEA_Q175vsWT.Rmd**  
  GSEA analysis with KEGG database for Q175 vs WT for Male and Female separately.
- **09_FA_GSEA_WTCR3kovsWT.Rmd**  
  GSEA analysis with KEGG database for CR3KO vs WT for Male and Female separately.
- **10_FA_ORA_2024_Cortex_Comp1_F_vs_M_WT.Rmd**  
  Over-representation analysis with GO database for Female vs Male in WT genotype. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Cortex.
- **11_FA_ORA_2024_Cortex_Comp3_F_vs_M_Q175.Rmd**  
  Over-representation analysis with GO database for Female vs Male in Q175 genotype. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Cortex.
- **12_FA_ORA_2024_Cortex_Comp17_WTCR3KO_vs_WT_All.Rmd**  
  Over-representation analysis with GO database for CR3KO vs WT in all samples. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Cortex.
- **13_FA_ORA_2024_Striatum_Comp1_F_vs_M_WT.Rmd**  
  Over-representation analysis with GO database for Female vs Male in WT genotype. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **14_FA_ORA_2024_Striatum_Comp3_F_vs_M_Q175.Rmd**  
  Over-representation analysis with GO database for Female vs Male in Q175 genotype. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **15_FA_ORA_2024_Striatum_Comp5_WTCR3KO_vs_WT_Male.Rmd**  
  Over-representation analysis with GO database for CR3KO vs WT in Males. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **16_FA_ORA_2024_Striatum_Comp6_WTCR3KO_vs_WT_Female.Rmd**  
  Over-representation analysis with GO database for CR3KO vs WT in Females. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **17_FA_ORA_2024_Striatum_Comp7_Q175_vs_WT_Male.Rmd**  
  Over-representation analysis with GO database for Q175 vs WT in Males. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **18_FA_ORA_2024_Striatum_Comp8_Q175_vs_WT_Female.Rmd**  
  Over-representation analysis with GO database for Q175 vs WT in Females. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **19_FA_ORA_2024_Striatum_Comp11_Q175CR3KO_vs_Q175_Male.Rmd**  
  Over-representation analysis with GO database for Q175CR3KO vs Q175 in Males. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **20_FA_ORA_2024_Striatum_Comp12_Q175CR3KO_vs_Q175_Female.Rmd**  
  Over-representation analysis with GO database for Q175CR3KO vs Q175 in Females. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **21_FA_ORA_2024_Striatum_Comp17_WTCR3KO_vs_WT_All.Rmd**  
  Over-representation analysis with GO database for CR3KO vs WT in all samples. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **22_FA_ORA_2024_Striatum_Comp18_Q175CR3KO_vs_Q175_All.Rmd**  
  Over-representation analysis with GO database for Q175CR3KO vs Q175 in all samples. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.

### D. 04_WGCNA
- **01_WGCNA.Rmd**  
  Weighted correlation network analysis on the 2024 dataset. Modules with the biggest differences across genotypes analyzed with a linear model.
- **02_WGCNA-Cortex-Part2.Rmd**  
  Weighted correlation network analysis on the 2024 Cortex dataset. Various selected modules are further analyzed and plotted, including functional analysis with ORA in the GO database.
- **03_WGCNA-Striatum-Part2.Rmd**  
  Weighted correlation network analysis on the 2024 Striatum dataset. Various selected modules are further analyzed and plotted, including functional analysis with ORA in the GO database.
- **04_WGCNA-Cortex-Part3.Rmd**  
  Additional modules functionally analyzed and plotted, continuing from the report (02) above.
- **05_WGCNA-Striatum-Part3.Rmd**  
  Additional modules functionally analyzed and plotted, continuing from the report (03) above.
- **06_WGCNA-Cortex-Part4.Rmd**  
  Additional modules functionally analyzed and plotted, continuing from the report (04) above.
- **07_WGCNA-Striatum-Part4.Rmd**  
  Additional modules functionally analyzed and plotted, continuing from the report (05) above.
- **08_Boxplots_WGCNA_Cortex_2024.Rmd**  
  Boxplots for various modules in Cortex 2024 plotted with aesthetic changes.
- **09_Boxplots_WGCNA_Striatum_2024.Rmd**  
  Boxplots for various modules in Striatum 2024 plotted with aesthetic changes.
- **10_Heatmaps_WGCNA-Cortex-Data_2024.Rmd**  
  Heatmaps for module-genotype association for selected modules plotted for Male and Female separately.
- **10_Heatmaps_WGCNA-Striatum-Data_2024.Rmd**  
  Heatmaps for module-genotype association for selected modules plotted for Male and Female separately.
- **11_GO_ORA_cortex_2024.Rmd**  
  Over-representation analysis with the GO database for selected modules with two different p-value cutoffs.
- **12_GO_ORA_striatum_2024.Rmd**  
  Over-representation analysis with the GO database for selected modules with two different p-value cutoffs.
- **13_Reactome_ORA_cortex_2024.Rmd**  
  Over-representation analysis with the Reactome database for selected modules with two different p-value cutoffs.
- **14_Reactome_ORA_striatum_2024.Rmd**  
  Over-representation analysis with the Reactome database for selected modules with two different p-value cutoffs.
- **15_WGCNA_module_preservation_Cortex_Ref_2022.Rmd**  
  Module preservation analysis in Cortex samples between 2024 and 2022 datasets, with the 2022 dataset as a reference.
- **16_WGCNA_module_preservation_Striatum_Ref_2022.Rmd**  
  Module preservation analysis in Striatum samples between 2024 and 2022 datasets, with the 2022 dataset as a reference.
- **17_WGCNA_module_preservation_Striatum_Ref_2024.Rmd**  
  Module preservation analysis in Striatum samples between 2024 and 2022 datasets, with the 2024 dataset as a reference.
- **18_WGCNA-module_preservation_Cortex_Ref_2024.Rmd**  
  Module preservation analysis in Cortex samples between 2024 and 2022 datasets, with the 2024 dataset as a reference.
- **19_WGCNA_crosstabulation_cortex.Rmd**  
  Cross-tabulation analysis between modules of 2024 and 2022 Cortex samples. Module overlaps presented in a heatmap.
- **20_WGCNA_crosstabulation_striatum.Rmd**  
  Cross-tabulation analysis between modules of 2024 and 2022 Striatum samples. Module overlaps presented in a heatmap.
- **21_Boxplots_WGCNA_Cortex_2024.Rmd**  
  Boxplots for various modules in Cortex 2024 plotted with aesthetic changes.
- **22_Boxplots_WGCNA_Striatum_2024.Rmd**  
  Boxplots for various modules in Striatum 2024 plotted with aesthetic changes.
- **23_GO_ORA_cortex_2024.Rmd**  
  Over-representation analysis with the GO database for selected modules from Cortex 2024, analyzed with two different p-value cutoffs.
- **24_GO_ORA_striatum_2024.Rmd**  
  Over-representation analysis with the GO database for selected modules from Striatum 2024, analyzed with two different p-value cutoffs.
- **25_Reactome_ORA_cortex_2024.Rmd**  
  Over-representation analysis with the Reactome database for selected modules from Cortex 2024, analyzed with two different p-value cutoffs.
- **26_Reactome_ORA_striatum_2024.Rmd**  
  Over-representation analysis with the Reactome database for selected modules from Striatum 2024, analyzed with two different p-value cutoffs.

### E. 05_MarkerGene_Analysis
- **01_2024_ABA_neuron_enriched_genes_striatum.Rmd**  
  Heatmaps with ABA neuron-enriched genes in Striatum plotted with p-values through permutation test presented in a bar plot.
- **02_2024_ABA_striatal_marker_genes_heatmap_striatum.Rmd**  
  Heatmaps with ABA striatal marker genes in Striatum plotted with p-values through permutation test presented in a bar plot.
- **03_2024_ABA_neuron_enriched_genes_striatum_v2.Rmd**  
  Heatmap of Z statistics for selected comparisons plotted for ABA neuron-enriched genes.
- **04_2024_ABA_striatal_marker_genes_heatmap_striatum_v2.Rmd**  
  Heatmap of Z statistics for selected comparisons plotted for ABA striatal marker genes.
- **05_2024_ABA_neuron_enriched_genes_striatum_v3.Rmd**  
  For the heatmap in (03), Male and Female plotted separately.
- **06_2024_ABA_striatal_marker_genes_heatmap_striatum_v3.Rmd**  
  For the heatmap in (04), Male and Female plotted separately.
- **07_2024_ABA_neuron_enriched_genes_striatum_v4.Rmd**  
  Heatmaps plotted with aesthetic changes and comparing Male and Female for ABA neuron-enriched genes.
- **08_2024_ABA_striatal_marker_genes_heatmap_striatum_v4.Rmd**  
  Heatmaps plotted with aesthetic changes and comparing Male and Female for ABA striatal marker genes.

---

## Reports 2022 Data

### A. 01_Differential_Expression
- **01_2022_DGE_multiplicative_analysis.Rmd**  
  Differential gene expression analysis with a multiplicative model. Striatum and Cortex analyzed separately.
- **02_2022_DGE_Cortex_heatmap_additive.Rmd**  
  List of differentially expressed genes and their heatmaps in all samples, males only, and females only in Cortex for Q175 vs WT comparison.
- **03_2022_DGE_Striatum_heatmap_additive.Rmd**  
  List of differentially expressed genes and their heatmaps in all samples, males only, and females only in Striatum for Q175 vs WT comparison.
- **04_2022_DGE_Cortex_volcano_plot_additive.Rmd**  
  Volcano plots for CR3KO vs WT, Q175CR3KO vs Q175, and Q175 vs WT in Cortex. All samples, Males, and Females presented separately.
- **05_2022_DGE_Striatum_volcano_plot_additive.Rmd**  
  Volcano plots for CR3KO vs WT, Q175CR3KO vs Q175, and Q175 vs WT in Striatum. All samples, Males, and Females presented separately.
- **06_2022_DGE_Cortex_volcano_plot2_additive.Rmd**  
  Some aesthetic changes in volcano plot from (04).
- **07_2022_DGE_Striatum_volcano_plot2_additive.Rmd**  
  Some aesthetic changes in volcano plot from (05).
- **08_2022_DGE_Cortex_zscatter_plot_additive.Rmd**  
  Various z-scatterplots from Cortex, including CR3 ablation effect, for All samples, Male, and Female, presented separately.
- **09_2022_DGE_Striatum_zscatter_plot_additive.Rmd**  
  Various z-scatterplots from Striatum, including CR3 ablation effect, for All samples, Male, and Female, presented separately.
- **10_2022_DGE_volcano_plot3.Rmd**  
  Various volcano plots replotted with some aesthetic changes for both Striatum and Cortex.

### B. 02_Functional_Analysis
- **01_FA_ORA_2022_Cortex_Comp1_F_vs_M_WT.Rmd**  
  Over-representation analysis with GO database for Female vs Male in WT genotype. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Cortex.
- **02_FA_ORA_2022_Cortex_Comp3_F_vs_M_Q175.Rmd**  
  Over-representation analysis with GO database for Female vs Male in Q175 genotype. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Cortex.
- **03_FA_ORA_2022_Cortex_Comp5_WTCR3KO_vs_WT_Male.Rmd**  
  Over-representation analysis with GO database for CR3KO vs WT in Male. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Cortex.
- **04_FA_ORA_2022_Cortex_Comp6_WTCR3KO_vs_WT_Female.Rmd**  
  Over-representation analysis with GO database for CR3KO vs WT in Female. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Cortex.
- **05_FA_ORA_2022_Cortex_Comp7_Q175_vs_WT_Male.Rmd**  
  Over-representation analysis with GO database for Q175 vs WT in Male. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Cortex.
- **06_FA_ORA_2022_Cortex_Comp8_Q175_vs_WT_Female.Rmd**  
  Over-representation analysis with GO database for Q175 vs WT in Female. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Cortex.
- **07_FA_ORA_2022_Cortex_Comp11_Q175CR3KO_vs_Q175_Male.Rmd**  
  Over-representation analysis with GO database for Q175CR3KO vs Q175 in Male. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Cortex.
- **08_FA_ORA_2022_Cortex_Comp12_Q175CR3KO_vs_Q175_Female.Rmd**  
  Over-representation analysis with GO database for Q175CR3KO vs Q175 in Female. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Cortex.
- **09_FA_ORA_2022_Cortex_Comp17_WTCR3KO_vs_WT_All.Rmd**  
  Over-representation analysis with GO database for CR3KO vs WT in All samples. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Cortex.
- **10_FA_ORA_2022_Cortex_Comp18_Q175_vs_WT_All.Rmd**  
  Over-representation analysis with GO database for Q175 vs WT in All samples. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Cortex.
- **11_FA_ORA_2022_Striatum_Comp1_F_vs_M_WT.Rmd**  
  Over-representation analysis with GO database for Female vs Male in WT genotype. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **12_FA_ORA_2022_Striatum_Comp3_F_vs_M_Q175.Rmd**  
  Over-representation analysis with GO database for Female vs Male in Q175 genotype. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **13_FA_ORA_2022_Striatum_Comp5_WTCR3KO_vs_WT_Male.Rmd**  
  Over-representation analysis with GO database for CR3KO vs WT in Male. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **14_FA_ORA_2022_Striatum_Comp6_WTCR3KO_vs_WT_Female.Rmd**  
  Over-representation analysis with GO database for CR3KO vs WT in Female. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **15_FA_ORA_2022_Striatum_Comp7_Q175_vs_WT_Male.Rmd**  
  Over-representation analysis with GO database for Q175 vs WT in Male. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **16_FA_ORA_2022_Striatum_Comp8_Q175_vs_WT_Female.Rmd**  
  Over-representation analysis with GO database for Q175 vs WT in Female. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **17_FA_ORA_2022_Striatum_Comp11_Q175CR3KO_vs_Q175_Male.Rmd**  
  Over-representation analysis with GO database for Q175CR3KO vs Q175 in Male. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **18_FA_ORA_2022_Striatum_Comp12_Q175CR3KO_vs_Q175_Female.Rmd**  
  Over-representation analysis with GO database for Q175CR3KO vs Q175 in Female. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **19_FA_ORA_2022_Striatum_Comp17_WTCR3KO_vs_WT_All.Rmd**  
  Over-representation analysis with GO database for CR3KO vs WT in All samples. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.
- **20_FA_ORA_2022_Striatum_Comp18_Q175_vs_WT_All.Rmd**  
  Over-representation analysis with GO database for Q175 vs WT in All samples. All significant DEGs, Up DEGs, and Down DEGs analyzed separately for Striatum.

### C. 03_WGCNA
- **01_WGCNA_Cortex_2022.Rmd**  
  Weighted correlation network analysis on the 2022 Cortex dataset. Modules with the biggest differences across genotypes analyzed with a linear model.
- **02_WGCNA_Striatum_2022.Rmd**  
  Weighted correlation network analysis on the 2022 Striatum dataset. Modules with the biggest differences across genotypes analyzed with a linear model.
- **03_WGCNA_Cortex_2022_Part2.Rmd**  
  Weighted correlation network analysis on the 2022 Cortex dataset. Various selected modules are further analyzed and plotted, including functional analysis with ORA in the GO database.
- **04_WGCNA_Striatum_2022_Part2.Rmd**  
  Weighted correlation network analysis on the 2022 Striatum dataset. Various selected modules are further analyzed and plotted, including functional analysis with ORA in the GO database.
- **05_Boxplots_WGCNA_Cortex_2022.Rmd**  
  Boxplots for various modules in Cortex 2022 plotted with some aesthetic changes.
- **06_Boxplots_WGCNA_Striatum_2022.Rmd**  
  Boxplots for various modules in Striatum 2022 plotted with some aesthetic changes.
- **07_Heatmaps_WGCNA_Cortex_2022.Rmd**  
  Heatmaps for module-genotype association for selected modules plotted for Male and Female separately.
- **08_Heatmaps_WGCNA_Striatum_2022.Rmd**  
  Heatmaps for module-genotype association for selected modules plotted for Male and Female separately.
- **09_FA_GO_ORA_WGCNA_cortex_2022.Rmd**  
  Over-representation analysis with the GO database for selected modules with two different p-value cutoffs.
- **10_FA_GO_ORA_WGCNA_striatum_2022.Rmd**  
  Over-representation analysis with the GO database for selected modules with two different p-value cutoffs.
- **11_FA_Reactome_ORA_WGCNA_cortex_2022.Rmd**  
  Over-representation analysis with the Reactome database for selected modules with two different p-value cutoffs.
- **12_FA_Reactome_ORA_WGCNA_striatum_2022.Rmd**  
  Over-representation analysis with the Reactome database for selected modules with two different p-value cutoffs.
- **13_Boxplots_WGCNA_Cortex_2022.Rmd**  
  Boxplots for various modules in Cortex 2022 plotted with aesthetic changes.
- **14_Boxplots_WGCNA_Striatum_2022.Rmd**  
  Boxplots for various modules in Striatum 2022 plotted with aesthetic changes.
- **15_FA_GO_ORA_cortex_2022.Rmd**  
  Over-representation analysis with the GO database for selected modules from Cortex 2022, analyzed with two different p-value cutoffs.
- **16_FA_GO_ORA_striatum_2022.Rmd**  
  Over-representation analysis with the GO database for selected modules from Striatum 2022, analyzed with two different p-value cutoffs.
- **17_FA_Reactome_ORA_cortex_2022.Rmd**  
  Over-representation analysis with the Reactome database for selected modules from Cortex 2022, analyzed with two different p-value cutoffs.
- **18_FA_Reactome_ORA_striatum_2022.Rmd**  
  Over-representation analysis with the Reactome database for selected modules from Striatum 2022, analyzed with two different p-value cutoffs.

### D. 04_MarkerGene_Analysis
- **01_2022_ABA_neuron_enriched_genes_striatum.Rmd**  
  Heatmaps with ABA neuron-enriched genes in Striatum plotted with p-values through permutation test presented in a bar plot.
- **02_2022_ABA_striatal_marker_genes_striatum.Rmd**  
  Heatmaps with ABA striatal marker genes in Striatum plotted with p-values through permutation test presented in a bar plot.
- **03_2022_ABA_neuron_enriched_genes_striatum_v2.Rmd**  
  Heatmap of Z statistics for selected comparisons plotted for ABA neuron-enriched genes.
- **04_2022_ABA_striatal_marker_genes_striatum_v2.Rmd**  
  Heatmap of Z statistics for selected comparisons plotted for ABA striatal marker genes.
- **05_2022_ABA_neuron_enriched_genes_striatum_v3.Rmd**  
  For the heatmap in (03), Male and Female plotted separately.
- **06_2022_ABA_striatal_marker_genes_striatum_v3.Rmd**  
  For the heatmap in (04), Male and Female plotted separately.
- **07_2022_ABA_neuron_enriched_genes_striatum_v4.Rmd**  
  Heatmaps plotted with aesthetic changes and comparing Male and Female for ABA neuron-enriched genes.
- **08_2022_ABA_striatal_marker_genes_striatum_v4.Rmd**  
  Heatmaps plotted with aesthetic changes and comparing Male and Female for ABA striatal marker genes.
