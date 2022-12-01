# misscvd

```
DESeq2.R -> Differential expression analysis with DESeq2.
```
```
coexp_analysis_quantile.R -> Co-expression analysis with coexp heatmap using bicor function of WGCNA.
```
```
coexp_cutree_ModulePreservation.R -> Module preservation analysis with WGCNA, clusters obtained with cutree.
```
```
coexp_filtered_dist_rank_analysis.R -> Rank each gene by euclidean distance score between correlations of two condition where correlations bigger than 0.3 considered.

coexp_find_mostdiff_genes.R -> Rank each gene between 2 comparison, using previous results between 2 conditions. Ex. control male vs control female VS case 
male vs case female.

coexp_topn_genes.R -> Find N genes closest to a gene in terms of euclidean distance in coexp heatmaps.
```
```
diffexp_case_control.R -> Check the genes which have significantly differentialy expressed in case comparison but not in control comparison.

diffexp_case_control.R -> Check the genes which have significantly differentialy expressed in male comparison but not in female comparison.

diffexp_male_female.R -> Check the genes which change significantly in the opposite direction in male case/control comparison vs female case/control comparison.
```
