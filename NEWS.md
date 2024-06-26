# pathfindR.data 2.1.0

## Major changes
- Updated hsa KEGG pathways gene set objects `kegg_genes` and `kegg_descriptions`
- Updated mmu KEGG pathways gene set objects `mmu_kegg_genes` and `mmu_kegg_descriptions`
- Updated Reactome gene set objects `reactome_genes` and `reactome_descriptions`
- Updated BioCarta gene set objects `biocarta_genes` and `biocarta_descriptions`
- Updated GO gene set objects `go_all_genes` and `GO_all_terms_df`
- Updated the BioGRID PIN adjacency list `biogrid_adj_list`
- Updated the KEGG adjacency list `kegg_adj_list`
- Updated the STRING adjacency lists `mmu_string_adj_list` and `string_adj_list`
- Updated the example data: `example_custom_genesets_result`, `example_pathfindR_output`, `example_pathfindR_output_clustered`, `example_comparison_output` and `example_mmu_output`
- Updated the `example_active_snws` data
- updated the manifest data frame `pathfindR.data_updates`


# pathfindR.data 2.0.0

## Major changes
- Renamed example input/output data for better organization and easier access

# pathfindR.data 1.1.3

## Major changes
- Updated (hsa) KEGG pathways gene set objects `kegg_genes` and `kegg_descriptions`
- Updated mmu KEGG pathways gene set objects `mmu_kegg_genes` and `mmu_kegg_descriptions`
- Updated Reactome gene set objects `reactome_genes` and `reactome_descriptions`
- Updated BioCarta gene set objects `biocarta_genes` and `biocarta_descriptions`
- Updated GO gene set objects `go_all_genes` and `GO_all_terms_df`
- Updated the BioGRID PIN adjacency list `biogrid_adj_list`
- Updated the KEGG adjacency list `kegg_adj_list`
- Updated the IntAct PIN adjacency list `intact_adj_list`
- Updated the example data: `RA_output`, `RA_clustered`, `RA_comparison_output` and `myeloma_output`

***

# pathfindR.data 1.1.2

## Major changes
- Updated (hsa) KEGG pathways gene set objects `kegg_genes` and `kegg_descriptions`
- Updated mmu KEGG pathways gene set objects `mmu_kegg_genes` and `mmu_kegg_descriptions`
- Updated Reactome gene set objects `reactome_genes` and `reactome_descriptions`
- Updated BioCarta gene set objects `biocarta_genes` and `biocarta_descriptions`
- Updated GO gene set objects `go_all_genes` and `GO_all_terms_df`
- Updated example data `RA_output`, `RA_clustered`, `RA_comparison_output` and `myeloma_output`
- Updated the BioGRID PIN adjacency list `biogrid_adj_list`
- Updated the STRING PIN adjacency list `string_adj_list`
- Updated the mmu STRING PIN adjacency list `mmu_string_adj_list`
- Updated the GeneMania PIN adjacency list `genemania_adj_list`
- Updated the KEGG adjacency list `kegg_adj_list`
- Updated the IntAct PIN adjacency list `intact_adj_list`
- Updated example custom enrichment results data frame `custom_results`

## Minor changes and bug fixes
- Updated `kegg_genes` and `kegg_descriptions` so that there are no duplicated term descriptions
- Updated `mmu_kegg_genes` and `mmu_kegg_descriptions` so that there are no duplicated term descriptions

***

# pathfindR.data 1.1.1

## Major changes
- Added the data frame of data `pathfindR.data_updates`, containing all the data for pathfindR along with descriptions and last update dates
- Updated example data `RA_output`, `RA_clustered`, `RA_comparison_output` and `myeloma_output` after addition of the 'support' column

## Minor changes and bug fixes
- Updated BioGRID PIN so that it does not contain self-interactions

***

# pathfindR.data 1.1.0

## Major changes
- Updated (hsa) KEGG pathways gene set objects `kegg_genes` and `kegg_descriptions`
- Updated mmu KEGG pathways gene set objects `mmu_kegg_genes` and `mmu_kegg_descriptions`
- Updated Reactome gene set objects `reactome_genes` and `reactome_descriptions`
- Updated BioCarta gene set objects `biocarta_genes` and `biocarta_descriptions`
- Updated GO gene set objects `go_all_genes` and `GO_all_terms_df`
- Updated Human Cell Markers gene set objects `cell_markers_gsets` and `cell_markers_descriptions`
- Updated the BioGRID PIN adjacency list `biogrid_adj_list`
- Updated the IntAct PIN adjacency list `intact_adj_list`
- Updated the KEGG adjacency list `kegg_adj_list`
- Updated example data `RA_output`, `RA_clustered`, `RA_comparison_output` and `myeloma_output`

***

# pathfindR.data 1.0.0

## Major changes
- Moved all data and related documentation from the main package `pathfindR` to this package
