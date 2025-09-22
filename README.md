# Atelopus-glyphus-immune-microbial-paper-
Microbial processing and analyses for Gratwick et al.

All associated data and scripts for the following manuscript in preparation:

## Prior infection by Batrachochytrium dendrobatidis in harlequin toads shifts their immune-microbial state and upon re-infection worsens disease outcomes. 

Brian Gratwicke, Owen G. Osborne, Arik Hartmann, Nicolette Ávila, Eric Baitchman, Gina DellaTogna, Yimairi Figuero, Jorge Guerrel, Estefany Illueca, Luke Linhoff, Joe D. Madison, Amy Ellison, Leon Grayfer, Roberto Ibáñez, Carly R. Muletz-Wolz

Abstract: 
Strategies to improve survival of wildlife impacted by emerging infectious disease are critically needed for species of conservation concern. Here, we investigated how prior infection by the skin fungal pathogen, Batrachochytrium dendrobatidis (Bd), affected subsequent disease outcomes in a highly susceptible and critically endangered frog, Atelopus glyphus. In parallel, we investigated how our experimental treatments affected the frogs’ skin microbiome and immune gene expression. 

## Data files:

1. Bacterial 16S:
>(1.1) **glyphus16s_feature_table_final.csv** is the complete feature table for use in phlyoseq object creation for 16s bacterial data

>(1.2) **glyphus16s_taxonomy_final.csv** is the complete 16s bacterial taxonomy for use in phlyoseq object creation.

>(1.3) **glyphus16s_meta_Final_anti2.csv** is the csv containing sample metadata, including relative abuance of anti-Bd micrbobes. Necessary for phlyoseq object creation.

>(1.4) **"glyphus_bray_PCOA_Bd_meta.csv"** Optional csv containing full meta data joined with 16s alpha and diversity metrics calculated from phyloseq. Code used to generate this file is included below.

2. Fungal ITS:
>(2.1) **glyphusITS_OTU_table_Clean.csv** is the complete feature table for use in phlyoseq object creation for fungal ITS data.

>(2.2) **glyphusITS_taxonomy_final** is the complete 16s bacterial taxonomy for use in phlyoseq object creation.

>(2.3) **glyphusITS_metadata2.txt** is the txt containing fungal IRS sample metadata. Necessary for phlyoseq object creation.

>(2.4) **"glyphusITS_treeNJ.rds"** Phylogenetic tree of ITS reads for phyloseq creation.

>(2.5) **""seqtabnochim.rds"** Sequence table of ITS reads with chimaeras removed, for phyloseq creation.

>(2.6) **""glyphus_ITS_diversity_bd.csv"** Optional csv containing full sample metdata with ITS alpha and beta diversity metrics calculated from phyloseq.

## Code for analyses and generating figures

>(3.1) **A_glyphus16s_analyses_figures.RMD** Complete and annotated R Markdown file for all bacterial 16s analyses and figures.

>(3.2) **A_glyphusITS_analyses_figures.RMD** Complete and annotated R Markdown file for all fungal ITS analyses and figures.




If you notice an error or have any further inquiries please feel free to reach out to me. 
 
