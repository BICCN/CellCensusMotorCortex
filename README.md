# A multimodal cell census and atlas of the mammalian primary motor cortex
## BRAIN Initiative Cell Census Network (BICCN)

![[https://user-images.githubusercontent.com/39201252/115289683-b517a200-a107-11eb-977e-bf7a557c826a.png|alt=c826a]]

**Resources associated with "A multimodal cell census and atlas of the mammalian primary motor cortex", *Nature*, August 10, 2021**

## Abstract
We report the generation of a multimodal cell census and atlas of the mammalian primary motor cortex (MOp or M1) as the initial product of the BRAIN Initiative Cell Census Network (BICCN). This was achieved by coordinated large-scale analyses of single-cell transcriptomes, chromatin accessibility, DNA methylomes, spatially resolved single-cell transcriptomes, morphological and electrophysiological properties, and cellular resolution input-output mapping, integrated through cross-modal computational analysis. The study reveals a unified molecular genetic landscape of cortical cell types that congruently integrates their transcriptome, open chromatin and DNA methylation maps. Second, cross-species analysis achieves a unified taxonomy of transcriptomic types and their hierarchical organization that are conserved from mouse to marmoset and human. Third, cross-modal analysis provides compelling evidence for the epigenomic, transcriptomic, and gene regulatory basis of neuronal phenotypes such as their physiological and anatomical properties, demonstrating the biological validity and genomic underpinning of neuron types and subtypes. Fourth, in situ single-cell transcriptomics provides a spatially-resolved cell type atlas of the motor cortex. Fifth, integrated transcriptomic, epigenomic and anatomical analyses reveal the correspondence between neural circuits and transcriptomic cell types. We further present an extensive genetic toolset for targeting and fate mapping glutamatergic projection neuron types toward linking their developmental trajectory to their circuit function. This page provides a guide to access accessing data and tools associated with this work 


## Figure list
Data and supporting codes related to analysis in figures.

[Figure 2: MOp consensus cell type taxonomy](#figure-2-mop-consensus-cell-type-taxonomy)

[Figure 3: In situ cell-type identification, spatial mapping and projection mapping of individual cells in the MOp by MERFISH] 

[Figure 4: Figure 4. Correspondence between transcriptomic and morpho-electrical properties of mouse MOp neurons by Patch-seq, and cross-species comparison of L5 ET neurons] 

[Figure 5: Epi-Retro-Seq links molecular cell types with distal projection targets] 

[Figure 6: Figure 6. Genetic tools for targeting cortical glutamatergic projection neuron types] 

[Figure 7: Global wiring diagram and anatomical characterization of MOp-ul neuron types] 

[Figure 8: Existence of L4 excitatory neurons in MOp] 

[Figure 9: Two distinct L5 ET projection neuron types in MOp] 



## Figure 2: MOp consensus cell type taxonomy

#### High-resolution primary data			
[panel a](http://data.nemoarchive.org/publication_release/MOp_MiniAtlas_2020/)

panels b-g: 
- [10x V3 macaque](http://data.nemoarchive.org/biccn/lab/lein/lein/transcriptomic/sncell/raw/)
- [10x V3 human (10X159-1 through 10x160-8)](http://data.nemoarchive.org/biccn/lab/linnarsson/transcriptome/sncell/10X/raw/10X159-1/)
- [10x V3 marmoset (bi005_m1, bi006_m1)](http://data.nemoarchive.org/biccn/lab/feng/transcriptome/sncell/raw/)
- [10x V3 mouse broad data (files with prefix pBICCNsMMrMOp)](http://data.nemoarchive.org/biccn/grant/huang/macosko/transcriptome/sncell/raw)
	
### Intermediate analysis and code for main figure			
panel a:	https://github.com/mukamel-lab/BICCN-Mouse-MOp/tree/master/flagship_fig2a		
panel b:	dendrogram from companion paper (Bakken et al. 2020)		
panel c:	http://data.nemoarchive.org/brain/biccn/lab/lein/2020_M1_study_analysis/Transcriptomics/flagship/dendrogram_barplot
panels d, e:	http://data.nemoarchive.org/brain/biccn/lab/lein/2020_M1_study_analysis/Transcriptomics/flagship/dendrogram_heatmap
panels f, g:	from companion paper (Bakken et al. 2020)		
panel h:	http://data.nemoarchive.org/biccn/lab/lein/2020_M1_study_analysis/Transcriptomics/flagship/cross_species_heatmap/GABAergic_avg_CP100K_expr.csv.gz		
panel i:	Custom UCSC browser of all M1 tracks	https://genome.ucsc.edu/s/sarojas/hg38-mop-dense	

#### Analysis and code for extended or supplementary data figures			
panel j:	Browser https://brainome.ucsd.edu/annoj/BICCN_MOp/		
Extended Data Figure 1:	http://data.nemoarchive.org/brain/biccn/lab/lein/2020_M1_study_analysis/Transcriptomics/flagship/cluster_overlap_plots		

