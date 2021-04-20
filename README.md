# A multimodal cell census and atlas of the mammalian primary motor cortex
## BRAIN Initiative Cell Census Network (BICCN)

![https://user-images.githubusercontent.com/39201252/115289683-b517a200-a107-11eb-977e-bf7a557c826a.png|alt=c826a]

**Resources associated with "A multimodal cell census and atlas of the mammalian primary motor cortex", *Nature*, August 10, 2021**

## Abstract
We report the generation of a multimodal cell census and atlas of the mammalian primary motor cortex (MOp or M1) as the initial product of the BRAIN Initiative Cell Census Network (BICCN). This was achieved by coordinated large-scale analyses of single-cell transcriptomes, chromatin accessibility, DNA methylomes, spatially resolved single-cell transcriptomes, morphological and electrophysiological properties, and cellular resolution input-output mapping, integrated through cross-modal computational analysis. The study reveals a unified molecular genetic landscape of cortical cell types that congruently integrates their transcriptome, open chromatin and DNA methylation maps. Second, cross-species analysis achieves a unified taxonomy of transcriptomic types and their hierarchical organization that are conserved from mouse to marmoset and human. Third, cross-modal analysis provides compelling evidence for the epigenomic, transcriptomic, and gene regulatory basis of neuronal phenotypes such as their physiological and anatomical properties, demonstrating the biological validity and genomic underpinning of neuron types and subtypes. Fourth, in situ single-cell transcriptomics provides a spatially-resolved cell type atlas of the motor cortex. Fifth, integrated transcriptomic, epigenomic and anatomical analyses reveal the correspondence between neural circuits and transcriptomic cell types. We further present an extensive genetic toolset for targeting and fate mapping glutamatergic projection neuron types toward linking their developmental trajectory to their circuit function. This page provides a guide to access accessing data and tools associated with this work 


## Main Figures
Data and supporting codes related to analyses in figures.

1. [Figure 1: Summary of experimental and computational approaches taken and as well as community resources generated by BICCN.](#figure-1-summary-of-experimental-and-computational-approaches-taken-and-as-well-as-community-resources-generated-by-BICCN)

2. [Figure 2: MOp consensus cell type taxonomy.](#figure-2-mop-consensus-cell-type-taxonomy)

3. [Figure 3: In situ cell-type-identification, spatial mapping and projection mapping of individual cells in the MOp by MERFISH.] (#figure-3-in-situ-cell-type-identification-spatial-mapping-and-projection-mapping-of-individual-cells-in-the-MOp-by-MERFISH)

4. [Figure 4: Correspondence between transcriptomic and morpho-electrical properties of mouse MOp neurons by Patch-seq, and cross-species comparison of L5 ET neurons.] 

5. [Figure 5: Epi-Retro-Seq links molecular cell types with distal projection targets.](#figure-5-Epi-Retro-Seq-links-molecular-cell-types-with-distal-projection-targets) 

6. [Figure 6: Genetic tools for targeting cortical glutamatergic projection neuron types.](#figure-6-Genetic-tools-for-targeting-cortical-glutamatergic-projection-neuron-types)

7. [Figure 7: Global wiring diagram and anatomical characterization of MOp-ul neuron types.] 

8. [Figure 8: Existence of L4 excitatory neurons in MOp.] 

9. [Figure 9: Two distinct L5 ET projection neuron types in MOp.]

10. [Figure 10: An integrated multimodal census and atlas of cell types in the primary motor cortex of mouse, marmoset and human.]

 

### Figure 1: Summary of experimental and computational approaches taken and as well as community resources generated by BICCN

Technique and methods references

#### Single cell mRNA sequencing
[Tasic et al, 2018](https://www.nature.com/articles/s41586-018-0654-5/)

[Yao et al, 2020](https://www.biorxiv.org/content/10.1101/2020.03.31.016972v2)

#### Single nucleus mRNA sequencing

[Bakken et al, 2020](https://www.biorxiv.org/content/10.1101/2020.03.31.016972v1)

[Hodge et al, 2019](https://www.nature.com/articles/s41586-019-1506-7)

### Figure 2: MOp consensus cell type taxonomy

#### High-resolution primary data			
[Panel 2a](http://data.nemoarchive.org/publication_release/MOp_MiniAtlas_2020/)

Panels 2b-2g: 
- [10x V3 macaque](http://data.nemoarchive.org/biccn/lab/lein/lein/transcriptomic/sncell/raw/)
- [10x V3 human (10X159-1 through 10x160-8)](http://data.nemoarchive.org/biccn/lab/linnarsson/transcriptome/sncell/10X/raw/10X159-1/)
- [10x V3 marmoset (bi005_m1, bi006_m1)](http://data.nemoarchive.org/biccn/lab/feng/transcriptome/sncell/raw/)
- [10x V3 mouse broad data (files with prefix pBICCNsMMrMOp)](http://data.nemoarchive.org/biccn/grant/huang/macosko/transcriptome/sncell/raw)
	
#### Intermediate analysis and code for main figure			
[Panel 2a](https://github.com/mukamel-lab/BICCN-Mouse-MOp/tree/master/flagship_fig2a)	

Panel 2b:	Dendrogram reproduced from companion paper (Bakken et al. 2020)		

[Panel 2c](http://data.nemoarchive.org/brain/biccn/lab/lein/2020_M1_study_analysis/Transcriptomics/flagship/dendrogram_barplot)

[Panels 2d, 2e](http://data.nemoarchive.org/brain/biccn/lab/lein/2020_M1_study_analysis/Transcriptomics/flagship/dendrogram_heatmap)

Panels 2f, 2g:	Reproduced from companion paper (Bakken et al. 2020)

[Panel 2h](http://data.nemoarchive.org/biccn/lab/lein/2020_M1_study_analysis/Transcriptomics/flagship/cross_species_heatmap/GABAergic_avg_CP100K_expr.csv.gz)

[Panel 2i: Custom UCSC browser of all M1 tracks](https://genome.ucsc.edu/s/sarojas/hg38-mop-dense)	

#### Analysis and code for extended or supplementary data figures			
[Panel 2j: Browser](https://brainome.ucsd.edu/annoj/BICCN_MOp/)		

[Extended Data Figure 1](http://data.nemoarchive.org/brain/biccn/lab/lein/2020_M1_study_analysis/Transcriptomics/flagship/cluster_overlap_plots)		



### Figure 3: In situ cell type identification spatial mapping and projection mapping of individual cells in the MOp by MERFISH

#### High-resolution primary data	
[MERFISH raw data and processed data](https://download.brainimagelibrary.org/02/26/02265ddb0dae51de/)


#### Intermediate analysis and code for main figure	
[MERFISH data processing pipeline](https://github.com/ZhuangLab/MERlin)

[Panel 3b](https://github.com/ZhuangLab/BICCN_MOp_2021/tree/main/flagship)

### Figure 4: Correspondence between transcriptomic and morpho-electrical properties of mouse MOp neurons by Patch-seq, and cross-species comparison of L5 ET neurons

### Figure 5: Epi-Retro-Seq links molecular cell types with distal projection targets

### Figure 6: Genetic tools for targeting cortical glutamatergic projection neuron types

### Figure 7: Global wiring diagram and anatomical characterization of MOp-ul neuron types

### Figure 8: Existence of L4 excitatory neurons in MOp

### Figure 9: Two distinct L5 ET projection neuron types in MOp

### Figure 10: An integrated multimodal census and atlas of cell types in the primary motor cortex of mouse, marmoset and human

