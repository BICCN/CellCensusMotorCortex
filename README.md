
 


# *A Multimodal Cell Census and Atlas of the Mammalian Primary Motor Cortex*
<img src="https://user-images.githubusercontent.com/39201252/115451895-99c59900-a1d2-11eb-801e-7c1578e91545.png" height=70/>

 
**Resources for "A Multimodal Cell Census and Atlas of the Mammalian Primary Motor Cortex", *Nature*, August XX, 2021**

## Abstract
We report the generation of a multimodal cell census and atlas of the mammalian primary motor cortex (MOp or M1) as the initial product of the BRAIN Initiative Cell Census Network (BICCN). This was achieved by coordinated large-scale analyses of single-cell transcriptomes, chromatin accessibility, DNA methylomes, spatially resolved single-cell transcriptomes, morphological and electrophysiological properties, and cellular resolution input-output mapping, integrated through cross-modal computational analysis. The study reveals a unified molecular genetic landscape of cortical cell types that congruently integrates their transcriptome, open chromatin and DNA methylation maps. Second, cross-species analysis achieves a unified taxonomy of transcriptomic types and their hierarchical organization that are conserved from mouse to marmoset and human. Third, cross-modal analysis provides compelling evidence for the epigenomic, transcriptomic, and gene regulatory basis of neuronal phenotypes such as their physiological and anatomical properties, demonstrating the biological validity and genomic underpinning of neuron types and subtypes. Fourth, in situ single-cell transcriptomics provides a spatially-resolved cell type atlas of the motor cortex. Fifth, integrated transcriptomic, epigenomic and anatomical analyses reveal the correspondence between neural circuits and transcriptomic cell types. We further present an extensive genetic toolset for targeting and fate mapping glutamatergic projection neuron types toward linking their developmental trajectory to their circuit function. This page provides a guide to access accessing data and tools associated with this work 


## Resources


#### Brain Cell Data Center (BCDC)
www.biccn.org

#### International Neuroscience Initiatives
[IBI](https://ibi.dimensions.ai/)

#### Neuroscience Multi-omic Data Archive (NeMO) 
[Primary transcriptomics and epigenomics data in this study](https://assets.nemoarchive.org/dat-ch1nqb7)

#### Atlas of Cis-elements gene regulatory elements 
[CATlas](http://catlas.org/mousebrain/)

#### LIGER - integrating multiple single cell datasets 
[LIGER](https://github.com/welch-lab/liger)

#### Neuromorpho - Inventory of digital reconstructed neurons
[Neuromorpho](www.neuromorpho.org)

#### MetaNeighbor - Characterizing cell type replicability

[MetaNeighbor](https://nam12.safelinks.protection.outlook.com/?url=https%3A%2F%2Fgithub.com%2Fgillislab%2FMetaNeighbor-Protocol&amp;data=04%7C01%7C%7Cfe6189e9c6fa4888d1a508d9042e44cf%7C32669cd6737f4b398bddd6951120d3fc%7C0%7C0%7C637545419050652251%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&amp;sdata=XOsmVXMpGnmATEcM3u1BN97V%2Bpw%2BffTwCnrVpx3WmFg%3D&amp;reserved=0)



## Main Figures
Data and supporting codes related to analyses in figures.

1. [Figure 1: Summary of experimental and computational approaches taken and as well as community resources generated by BICCN.](#figure-1-summary-of-experimental-and-computational-approaches-taken-and-as-well-as-community-resources-generated-by-BICCN)

2. [Figure 2: MOp consensus cell type taxonomy.](#figure-2-mop-consensus-cell-type-taxonomy)
3. [Figure 3: In situ cell type identification spatial mapping and projection mapping of individual cells in the MOp by MERFISH.] (#MERFISH)

4. [Figure 4: Correspondence between transcriptomic and morpho-electrical properties of mouse MOp neurons by Patch-seq, and cross-species comparison of L5 ET neurons.](#figure-4-Correspondence-between-transcriptomic-and-morpho-electrical-properties-of-mouse-MOp-neurons-by-Patch-seq-and-cross-species-comparison-of-L5-ET-neurons) 

5. [Figure 5: Epi-Retro-Seq links molecular cell types with distal projection targets.](#figure-5-Epi-Retro-Seq-links-molecular-cell-types-with-distal-projection-targets) 

6. [Figure 6: Genetic tools for targeting cortical glutamatergic projection neuron types.](#figure-6-Genetic-tools-for-targeting-cortical-glutamatergic-projection-neuron-types)

7. [Figure 7: Global wiring diagram and anatomical characterization of MOp-ul neuron types.](#figure-7-Global-wiring-diagram-and-anatomical-characterization-of-MOp-ul-neuron-types) 

8. [Figure 8: Existence of L4 excitatory neurons in MOp.](#figure-8-Existence-of-L4-excitatory-neurons-in-MOp) 

9. [Figure 9: Two distinct L5 ET projection neuron types in MOp.](#figure-9-Two-distinct-L5-ET-projection-neuron-types-in-MOp)

10. [Figure 10: An integrated multimodal census and atlas of cell types in the primary motor cortex of mouse, marmoset and human.](#figure-10-An-integrated-multimodal-census-and-atlas-of-cell-types-in-the-primary-motor-cortex-of-mouse-marmoset-and-human)

 

### *Figure 1: Summary of experimental and computational approaches taken and as well as community resources generated by BICCN*

References for main technqiues 

#### Single cell mRNA sequencing
[Tasic et al, 2018](https://www.nature.com/articles/s41586-018-0654-5/)

[Yao et al, 2020](https://www.biorxiv.org/content/10.1101/2020.03.31.016972v2)

#### Single nucleus mRNA sequencing

[Bakken et al, 2020](https://www.biorxiv.org/content/10.1101/2020.03.31.016972v1)

[Hodge et al, 2019](https://www.nature.com/articles/s41586-019-1506-7)





### *Figure 2: MOp consensus cell type taxonomy*

#### High-resolution primary data			
[Panel 2a](http://data.nemoarchive.org/publication_release/MOp_MiniAtlas_2020/)

Panels 2b-2g: 
- [10x V3 macaque](http://data.nemoarchive.org/biccn/lab/lein/lein/transcriptomic/sncell/raw/)
- [10x V3 human (10X159-1 through 10x160-8)](http://data.nemoarchive.org/biccn/lab/linnarsson/transcriptome/sncell/10X/raw/10X159-1/)
- [10x V3 marmoset (bi005_m1, bi006_m1)](http://data.nemoarchive.org/biccn/lab/feng/transcriptome/sncell/raw/)
- [10x V3 mouse Broad data (files with prefix pBICCNsMMrMOp)](http://data.nemoarchive.org/biccn/grant/huang/macosko/transcriptome/sncell/raw)
	
#### Analysis and code for main figure			
[Panel 2a](https://github.com/mukamel-lab/BICCN-Mouse-MOp/tree/master/flagship_fig2a)	

Panel 2b:	Dendrogram reproduced from companion paper (Bakken et al. 2020)		

[Panel 2c](http://data.nemoarchive.org/brain/biccn/lab/lein/2020_M1_study_analysis/Transcriptomics/flagship/dendrogram_barplot)

[Panels 2d, 2e](http://data.nemoarchive.org/brain/biccn/lab/lein/2020_M1_study_analysis/Transcriptomics/flagship/dendrogram_heatmap)

Panels 2f, 2g:	Reproduced from companion paper (Bakken et al. 2020)

[Panel 2h](http://data.nemoarchive.org/biccn/lab/lein/2020_M1_study_analysis/Transcriptomics/flagship/cross_species_heatmap/GABAergic_avg_CP100K_expr.csv.gz)

[Panel 2i: Custom UCSC browser of all M1 tracks](https://genome.ucsc.edu/s/sarojas/hg38-mop-dense)	

#### Extended or supplementary data figures			
[Panel 2j: Browser](https://brainome.ucsd.edu/annoj/BICCN_MOp/)		

[Extended Data Figure 1](http://data.nemoarchive.org/brain/biccn/lab/lein/2020_M1_study_analysis/Transcriptomics/flagship/cluster_overlap_plots)		



### *MERFISH* 

#### High-resolution primary data	
[MERFISH raw data and processed data](https://download.brainimagelibrary.org/02/26/02265ddb0dae51de/)


#### Analysis and code for main figure	
[MERFISH data processing pipeline](https://github.com/ZhuangLab/MERlin)

[Panel 3b](https://github.com/ZhuangLab/BICCN_MOp_2021/tree/main/flagship)

### *Figure 4: Correspondence between transcriptomic and morpho-electrical properties of mouse MOp neurons by Patch-seq, and cross-species comparison of L5 ET neurons*

#### High-resolution primary data								

Panel a:
- [Patch-seq mouse transcriptomic data in FASTQ format](http://data.nemoarchive.org/biccn/grant/zeng/tolias/)
- [Biccn/grant/zeng/zeng/transcriptome](http://data.nemoarchive.org/biccn/grant/zeng/zeng/)					

Panels b-g:	
- [Morphological reconstructions in SWC format](https://download.brainimagelibrary.org/3a/88/3a88a7687ab66069/)					
- [Electrophysiological traces in NWB format](https://dandiarchive.org/dandiset/000008/)					
								

Panel h:	 	
- [10x V3 macaque](http://data.nemoarchive.org/biccn/lab/lein/lein/transcriptomic/sncell/raw/)					
- [10x V3 human (10X159-1 through 10x160-8)](http://data.nemoarchive.org/biccn/lab/linnarsson/transcriptome/sncell/10X/raw/10X159-1/)
- [10x V3 marmoset (bi005_m1, bi006_m1)](http://data.nemoarchive.org/biccn/lab/feng/transcriptome/sncell/raw/)					
- [10x V3 mouse Broad data (files with prefix pBICCNsMMrMOp)](http://data.nemoarchive.org/biccn/grant/huang/macosko/transcriptome/sncell/raw)					
Panels i-k:
- [Electrophophysiology in NWB format](https://dandiarchive.org/dandiset/000043/draft)					
- [Morphological reconstructions in SWC format](https://download.brainimagelibrary.org/79/1d/791d4ad4b5663855/)					

														
								
#### Analysis and code for main figure			

Panel h:	
- [10x 4 species integration](http://data.nemoarchive.org/biccn/lab/lein/2020_M1_study_analysis/Transcriptomics/cross_species_integration/sample.combined_exc_4_species_integration.RDS)
- [Code](http://data.nemoarchive.org/brain/biccn/lab/lein/2020_M1_study_analysis/Transcriptomics/flagship/projecting_patch_seq_onto_umap)
 
Panels a-g:	
- [Code](https://github.com/berenslab/mini-atlas/blob/master/code/flagship-figure.ipynb)						


### *Figure 5: Epi-Retro-Seq links molecular cell types with distal projection targets*

#### High-resolution primary data									

[Epi-Retro-Seq raw data](http://data.nemoarchive.org/biccn/grant/cemba/cemba/epigenome/sncell/mCseq_retro/mouse/)	

[Gene Expression Omnibus data](https://www-ncbi-nlm-nih-gov.ezproxy.u-pec.fr/geo/query/acc.cgi?acc=GSE150170)					
									
#### Analysis and code for main figure				
[Code](https://github.com/zhoujt1994/BICCN2020Flagship.git)				


### *Figure 6: Genetic tools for targeting cortical glutamatergic projection neuron types*

#### High-resolution primary data					
					
Panel c					
Label in Fig	Full Descriptive ID	Induction date 	Harvest date 	Tamoxifen dose 	Originating Lab
Lhx2	Lhx2-CreER; Ai14	E12.5	E13.5	2 mg/kg body weight	Huang
Lhx2	Lhx2-CreER; Ai14	E12.5	P30	100 mg/kg body weight	Huang
Fezf2	Fezf2-CreER; Ai14	E12.5	E13.5	2 mg/kg body weight	Huang
Fezf2	Fezf2-CreER; Ai14	E12.5	P30	2 mg/kg body weight	Huang
					
Panels d-k					
Label in Fig	Full Descriptive ID	experiment id	Originating Lab	Link to Brain Architecture viewer	BIL link
PlxnD1	PlxnD1-CreER;LSL-Flp	180722	Huang	http://brainarchitecture.org/viewer4/mouse/map/8401F	https://download.brainimagelibrary.org/84/aa/84aa97d12a6c17ba/180722_WG_PlxnD1lslFlpCFA1female_processed/
PlxnD1	PlxnD1-CreER;LSL-Flp	180730	Huang	http://brainarchitecture.org/viewer4/mouse/map/28819F	https://download.brainimagelibrary.org/e9/2a/e92aa2dc0e14ad4d/180730_WG010_PlxnD1_CFA_female_processed/
Fezf2	Fezf2-CreER;LSL-Flp	180830	Huang	http://brainarchitecture.org/viewer4/mouse/map/28827F	https://download.brainimagelibrary.org/db/b8/dbb827c84942c557/180830_JH_WG_Fezf2LSLflp_CFA_female/
Fezf2	Fezf2-CreER;LSL-Flp	190903	Huang	http://brainarchitecture.org/viewer4/mouse/map/28917F	https://download.brainimagelibrary.org/2b/6e/2b6e48dc425d16db/190903_JH_WG0006_Fezf2LSLflp_MOp_CFA_female_processed/
Tle4	Tle4-CreER;LSL-Flp	180605	Huang	http://brainarchitecture.org/viewer4/mouse/map/28814F	https://download.brainimagelibrary.org/84/aa/84aa97d12a6c17ba/180605_WG_Tle4lslFlpRPCFA_female_processed/
Tle4	Tle4-CreER;LSL-Flp	180816	Huang	http://brainarchitecture.org/viewer4/mouse/map/8421F	https://download.brainimagelibrary.org/c8/1f/c81fe306a97b33e8/180816_JH_WG_Tle4LSLFlpNPCfa_female/
Foxp2	Foxp2-Cre	190915	Huang	http://braincircuits.org/viewer4/mouse/map/29158F	this is undergoing validation
Foxp2	Foxp2-Cre	191209	Huang	http://braincircuits.org/viewer4/mouse/map/29159F	https://download.brainimagelibrary.org/81/bc/81bcaddee6e8ac06/191209_JH_KM_FoxP2-ires-cre_CFA_male2_processed/
					
Panel j					
Label in Fig	Full Descriptive ID	experiment id	Originating Lab	Link to Brain Architecture viewer	BIL link
PlxnD1-Tbr2	Tbr2-CreER;PlxnD1-Flp;dtTA TM E17.5	GK01	Huang	TBD	TBD
PlxnD1-Tbr2	Tbr2-CreER;PlxnD1-Flp;dtTA TM E17.5	GK02	Huang	TBD	TBD
PlxnD1-Tbr2	Tbr2-CreER;PlxnD1-Flp;dtTA TM E17.5	GK03	Huang	TBD	TBD
PlxnD1-Tbr2	Tbr2-CreER;PlxnD1-Flp;dtTA TM E17.5	GK04	Huang	TBD	TBD
PlxnD1-Tbr2	Tbr2-CreER;PlxnD1-Flp;dtTA TM E17.5	GK05	Huang	TBD	TBD
PlxnD1-Tbr2	Tbr2-CreER;PlxnD1-Flp;dtTA TM E13.5	GK11	Huang	TBD	TBD
PlxnD1-Tbr2	Tbr2-CreER;PlxnD1-Flp;dtTA TM E13.5	GK12	Huang	TBD	TBD
PlxnD1-Tbr2	Tbr2-CreER;PlxnD1-Flp;dtTA TM E13.5	GK13	Huang	TBD	TBD
PlxnD1-Tbr2	Tbr2-CreER;PlxnD1-Flp;dtTA TM E13.5	GK14	Huang	TBD	TBD
PlxnD1-Tbr2	Tbr2-CreER;PlxnD1-Flp;dtTA TM E13.5	GK15	Huang	TBD	TBD
					


### *Figure 7: Global wiring diagram and anatomical characterization of MOp-ul neuron types*
panel a	Hongwei 			
				
panel b	Pavel			
				
panel c	Julie			
Label in Fig	Full Descriptive ID	experiment id	Originating Lab	Link to registered swc (single cells) or 25 um grid file (tracer)
Rabies	Tlx3-660759241	660759241	Allen	http://download.alleninstitute.org/publications/cellular_anatomy_of_the_mouse_primary_motor_cortex/Viral_Tracer_Data_in_MOp_25_um_nrrd/
AAV	C57BL/6J-127084296	127084296	Allen	http://download.alleninstitute.org/publications/cellular_anatomy_of_the_mouse_primary_motor_cortex/Viral_Tracer_Data_in_MOp_25_um_nrrd/
Cux2 L2/3/4 IT	Cux2-IRES-Cre-947242021	947242021	Allen	http://download.alleninstitute.org/publications/cellular_anatomy_of_the_mouse_primary_motor_cortex/Viral_Tracer_Data_in_MOp_25_um_nrrd/
Nr5a1 L4 IT	Nr5a1-Cre-882407664	882407664	Allen	http://download.alleninstitute.org/publications/cellular_anatomy_of_the_mouse_primary_motor_cortex/Viral_Tracer_Data_in_MOp_25_um_nrrd/
Tlx3 L5 IT	Tlx3-Cre_PL56-880719308	880719308	Allen	http://download.alleninstitute.org/publications/cellular_anatomy_of_the_mouse_primary_motor_cortex/Viral_Tracer_Data_in_MOp_25_um_nrrd/
Rbp4 L5 IT+ET	Rbp4-Cre_KL100-948130129	948130129	Allen	http://download.alleninstitute.org/publications/cellular_anatomy_of_the_mouse_primary_motor_cortex/Viral_Tracer_Data_in_MOp_25_um_nrrd/
Sim1 L5 ET	Sim1-Cre_KJ18-297711339	297711339	Allen	http://download.alleninstitute.org/publications/cellular_anatomy_of_the_mouse_primary_motor_cortex/Viral_Tracer_Data_in_MOp_25_um_nrrd/
Ntsr1 L6 CT	Ntsr1-Cre_GN220-159651060	159651060	Allen	http://download.alleninstitute.org/publications/cellular_anatomy_of_the_mouse_primary_motor_cortex/Viral_Tracer_Data_in_MOp_25_um_nrrd/
IT projections	L2/3_Cux2-CreERT2-18453_3456_x24161_y6646	18453_3456_x24161_y6646	Allen	http://download.alleninstitute.org/publications/cellular_anatomy_of_the_mouse_primary_motor_cortex/Single_Cell_Reconstructions_in_MOp/
IT projections	L4_Cux2-CreERT2-18864_3338_x3396_y21865	18864_3338_x3396_y21865	Allen	http://download.alleninstitute.org/publications/cellular_anatomy_of_the_mouse_primary_motor_cortex/Single_Cell_Reconstructions_in_MOp/
IT projections	L5_AA0271 [A]	AA0271 [A]	MouseLight	http://ml-neuronbrowser.janelia.org/
ET projections	L5_+MY+TH_Fezf2-CreERT2-182725_3762_x5563_y19178	182725_3762_x5563_y19178	Allen	http://download.alleninstitute.org/publications/cellular_anatomy_of_the_mouse_primary_motor_cortex/Single_Cell_Reconstructions_in_MOp/
ET projections	L5_no MY_Fezf2-CreERT2_182725_4080_x6576_y11407	182725_4080_x6576_y11407	Allen	http://download.alleninstitute.org/publications/cellular_anatomy_of_the_mouse_primary_motor_cortex/Single_Cell_Reconstructions_in_MOp/
CT projections	L6_AA0649 [A]	AA0649 [A]	MouseLight	http://ml-neuronbrowser.janelia.org/
CT projections	L6_AA0898 [A]	AA0898 [A]	MouseLight	http://ml-neuronbrowser.janelia.org/
				
panel d	Hongwei 			
				
Panels d-i				
Label in Fig	Full Descriptive ID	experiment id	Originating Lab	Link to Brain Architecture viewer
PlxnD1	PlxnD1-CreER;LSL-Flp	180722	Huang	http://brainarchitecture.org/viewer4/mouse/map/8401F
PlxnD1	PlxnD1-CreER;LSL-Flp	180730	Huang	http://brainarchitecture.org/viewer4/mouse/map/28819F
Tle4	Tle4-CreER;LSL-Flp	180605	Huang	http://brainarchitecture.org/viewer4/mouse/map/28814F
Tle4	Tle4-CreER;LSL-Flp	180816	Huang	http://brainarchitecture.org/viewer4/mouse/map/8421F
				
#### Analysis and code for main figure				
panel c	https://github.com/AllenInstitute/MOp_anatomy_rendering	code to reproduce rendering of registered data in 3D		
				
				


### *Figure 8: Existence of L4 excitatory neurons in MOp*
								
					
#### Analysis and code for main figure					
[Panels 8a,c,e](https://github.com/mukamel-lab/BICCN-Mouse-MOp/tree/master/flagship_fig8)

[Panel 8b](https://brainome.ucsd.edu/annoj/BICCN_MOp/)				
					
					
### *Figure 9: Two distinct L5 ET projection neuron types in MOp*
					
#### Analysis and code for main figure						 				
[Panel 9d](https://brainome.ucsd.edu/annoj/BICCN_MOp/)	

[Panel 9e](https://github.com/zhoujt1994/BICCN2020Flagship.git)				
					
					

### *Figure 10: An integrated multimodal census and atlas of cell types in the primary motor cortex of mouse, marmoset and human*

						
			
#### Analysis and code for main figure			
[snATAC-seq Utilites](https://github.com/yal054/snATACutils)			
			
					
			
#### Extended or supplementary data figures			
[snATAC-seq Utilites](https://github.com/yal054/snATACutils)	

[Extended data figure 3](https://github.com/lhqing/flagship_tf_figure) 		
