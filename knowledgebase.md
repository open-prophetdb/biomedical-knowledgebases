### PrimeKG: A Knowledge Graph for Precision Medicine.

PrimeKG integrates 20 high-quality resources to describe 17,080 diseases with 4,050,249 relationships representing ten major biological scales, including disease-associated protein perturbations, biological processes and pathways, anatomical and phenotypic scales, and the entire range of approved drugs with their therapeutic action, considerably expanding previous efforts in disease-rooted knowledge graphs. PrimeKG contains an abundance of 'indications', 'contradictions', and 'off-label use' drug-disease edges that lack in other knowledge graphs and can support AI analyses of how drugs affect disease-associated networks.

- [Paper](https://www.nature.com/articles/s41597-023-01960-3)

- [Code](https://github.com/mims-harvard/PrimeKG)

- [Data](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/IXA7BM)

- [Website](https://zitniklab.hms.harvard.edu/projects/PrimeKG/)

### BindingDB

BindingDB is a public, web-accessible database of measured binding affinities, focusing chiefly on the interactions of proteins considered to be candidate drug-targets with ligands that are small, drug-like molecules. BindingDB supports medicinal chemistry and drug discovery via literature awareness and development of structure-activity relations (SAR and QSAR); validation of computational chemistry and molecular modeling approaches such as docking, scoring and free energy methods; chemical biology and chemical genomics; and basic studies of the physical chemistry of molecular recognition. BindingDB also includes a small collection of host-guest binding data of interest to chemists studying supramolecular systems.

The data collection derives from a variety of measurement techniques, including enzyme inhibition and kinetics, isothermal titration calorimetry, NMR, and radioligand and competition assays. BindingDB includes data extracted from the literature and patents by the BindingDB project, selected PubChem confirmatory BioAssays, and ChEMBL entries for which a well defined protein target ("TARGET_TYPE='PROTEIN'") is provided. Data extracted by BindingDB typically includes more details regarding experimental conditions, etc. BindingDB currently contains about 2,781,729 binding data for 9,173 proteins and over 1,190,936 drug-like molecules.

- [Paper](https://pubmed.ncbi.nlm.nih.gov/26481362/)
- [Website](https://www.bindingdb.org/rwd/bind/index.jsp)
- [Dataset](https://www.bindingdb.org/rwd/bind/chemsearch/marvin/Download.jsp)


### PreMedKB: an integrated precision medicine knowledgebase for interpreting relationships between diseases, genes, variants and drugs

Precision Medicine Knowledgebase (PreMedKB) integrate the four fundamental components of precision medicine: diseases, genes, variants and drugs. PreMedKB allows for search of comprehensive information within each of the four components, the relationships between any two or more components, and importantly, the interpretation of the clinical meanings of a patient's genetic variants. PreMedKB is an efficient and user-friendly tool to assist researchers, clinicians or patients in interpreting a patient's genetic profile in terms of discovering potential pathogenic variants, recommending therapeutic regimens, designing panels for genetic testing kits, and matching patients for clinical trials.

### DGIdb: The Drug Gene Interation Database

The Drug-Gene Interaction Database (DGIdb, www.dgidb.org) is a web resource that provides information on drug-gene interactions and druggable genes from publications, databases, and other web-based sources. Drug, gene, and interaction data are normalized and merged into conceptual groups. The information contained in this resource is available to users through a straightforward search interface, an application programming interface (API), and TSV data downloads. 
DGIdb contains over 10,000 genes and 15,000 drugs involved in over 50,000 drug-gene interactions or belonging to one of 43 potentially druggable gene categories. 

- [Paper](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7778926/)
- [Website](https://beta.dgidb.org/)
- [Data](https://beta.dgidb.org/downloads)


### DISNET: A framework for extracting phenotypic disease information from public sources

Within the global endeavour of improving population health, one major challenge is the identification and integration of medical knowledge spread through several information sources. The creation of a comprehensive dataset of diseases and their clinical manifestations based on information from public sources is an interesting approach that allows one not only to complement and merge medical knowledge but also to increase it and thereby to interconnect existing data and analyse and relate diseases to each other. 

The DISNET database integrates phenotypic and genetic-biological characteristics of diseases and information on drugs from several sources curated by experts and unstructured textual sources. For phenotypic characteristics, information is retrieved from Wikipedia, PubMed and MayoClinic and more are being added; for biological characteristics, information is retrieved from DisGeNet to obtain gene and protein data, WikiPathways to obtain metabolic pathways data and IntAct to obtain protein interaction data; and for drug information, PharmGKB is used, among others.

- [Paper](https://peerj.com/articles/8580/)

- [Website](http://disnet.ctb.upm.es/)

- [Data](https://disnet.ctb.upm.es/about/database)


### FORUM: building a Knowledge Graph from public databases and scientific literature to extract associations between chemicals and diseases

Metabolomics studies aim at reporting a metabolic signature (list of metabolites) related to a particular experimental condition. These signatures are instrumental in the identification of biomarkers or classification of individuals, however their biological and physiological interpretation remains a challenge. 

FORUM is an open knowledge network aiming at supporting metabolomics results interpretation in biomedical sciences and automated reasoning. Containing more than 8 billion statements, it federate data from several life-science resources such as PubMed, ChEBI and PubChem. Leveraging the bridges in this linked dataset, we automatically extract associations between compound and biomedical concepts, using literature metadata enrichment.

- [Paper](https://academic.oup.com/nar/article/49/D1/D605/5910787)

- [Code](https://github.com/eMetaboHUB/Forum-DiseasesChem)

- [Website](https://forum-webapp.semantic-metabolomics.fr/)


### Full-DTIs-LC-Benchmark

A benchmark dataset containing Drug-Target Interation (DTI) data of Lung Cancer (LC). This dataset avoided information that is only generated automatically, through text mining, and focused on most trustworthy sources, namely DrugBank, KEGG, DGIdb and TTD data. The union of DrugBank, KEGG, DGIdb and TTD provided 44,169 positive drug-gene interactions in total, with 1931 of those related on one side (drug) or the other (gene) to Lung Cancer (LC). As for the negative drug-gene pairs, there are 627,971 pairs, for which no interaction is reported in any of the above databases.

- [Paper](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-023-05373-2)
- [Code](https://github.com/fotais/drug-gene-interactions/tree/main)
- [Data](https://github.com/fotais/drug-gene-interactions/blob/main/Full-DTIs-LC-Benchmark.csv)


### gutMDisorder: a comprehensive database for dysbiosis of gut microbiota in phenotypes and interventions

Gut microbiota plays a significant role in maintaining host health, and conversely, disorders potentially lead to dysbiosis, an imbalance in the composition of the gut microbial community. Intervention approaches, such as medications, diets, and several others, also alter the gut microbiota in either a beneficial or harmful direction.

A comprehensive resource for associations between gut microbes and phenotypes or interventions in Human and Mouse, derived from manual literature extraction and raw data reprocessing.

- [Paper](https://academic.oup.com/nar/article/51/D1/D717/6754909)

- [Website](http://bio-annotation.cn/gutMDisorder/)

- [Data](http://bio-annotation.cn/gutMDisorder/resource.dhtml)


### gutMGene: a comprehensive database for target genes of gut microbes and microbial metabolites

Metagenomic sequencing of fecal samples has identified 3.3×106 non-redundant microbial genes from up to 1,500 different species. One of the contributions of gut microbiota to host biology is the circulating pool of bacterially derived small-molecule metabolites. It has been estimated that 10% of metabolites found in mammalian blood are derived from the gut microbiota, where they can produce systemic effects on the host through activating or inhibiting gene expression. Currently, detailed information on target genes of gut microbes and microbial metabolites is scattered in literatures and no online repository is available for collecting these data.

Here, gutMGene team manually extracted microbe-metabolite, microbe-target, and metabolite-target relationships in Human and Mouse from almost 400 publications. All of these relationships were experimentally validated in vivo or in vitro and measured by RT-qPCR, high performance liquid chromatography, 16S rRNA sequence, and so on.

- [Paper](https://academic.oup.com/nar/article/50/D1/D795/6368055)

- [Website](http://bio-annotation.cn/gutmgene/home.dhtml)

- [Data](http://bio-annotation.cn/gutmgene/resource.dhtml)


### Human Symptoms Disease Network (HSDN)

Use large-scale medical bibliographic records and the related Medical Subject Headings (MeSH) metadata from PubMed, to generate a symptom-based network of human diseases (Human Symptoms Disease Network, HSDN), where the link weight between two diseases quantifies the similarity of their respective symptoms. By integrating disease–gene association and protein–protein interaction (PPI) data, we investigate the correlations between the symptom similarity of diseases and their degree of shared genes or PPIs.

- [Paper](https://www.nature.com/articles/ncomms5212)

- [Code](https://github.com/dhimmel/hsdn)

- [Data](https://www.nature.com/articles/ncomms5212#MOESM1042)


### MetSigDis: a manually curated resource for the metabolic signatures of diseases

MetSigDis, a manually curated resource, aims to provide a comprehensive resource of metabolite alterations in various diseases. MetSigDis provides a search engine to query metabolic signatures and diseases along with relationships among them. Furthermore, to help users interactively analyze associations among diseases in metabolite level online, MetSigDis provides a network visualization tool to show associations among diseases and metabolites.↳

The current version of MetSigDis documents 6,849 curated relationships between 2,420 metabolites and 129 diseases across 8 species involving Homo sapiens, Rat, Mouse, Drosophila melanogaster, Triatomine, Mice, Pig, and Mus musculus. Each entry in the MetSigDis contains detailed information on a relationship between metabolite and disease, including metabolite ID, metabolite name, disease ID, disease name, species, metabolomics analytical platforms, tissue, metabolite alteration, and literature reference.

- [Paper](https://academic.oup.com/bib/article/20/1/203/4091292)

- [Website](http://bio-annotation.cn/MetSigDis/)

- [Data](http://bio-annotation.cn/MetSigDis/download)


### OAHG: An integrated resource for annotating human genes with multi-level ontologies

In recent years, diverse products of genes in transcriptional level were well investigated, such as protein-coding gene (PCG), miRNA, lncRNA, circRNA, and so on. Their roles that vary from molecule to phenotype in human body attracted much attention these years. Now the annotation of genes’ roles using normalized terminologies is urgent for quantitative analyses. To this end, multiple manually curated databases were established about the annotation of an individual type of roles for an individual type of gene, such as miRNA-disease annotation (HMDD), lncRNA-disease annotation (LncRNADisease), circRNA-disease annotation (CircRNA2Disease), GOA, and so on. Although GeneRIF documented multiple roles of genes in the ‘functional description’ section, these roles were not normalized to ontologies. In summary, there is no online repository for annotating biological roles of genes comprehensively using ontogoies except for Ontogene.

Updated version at: [OntoGene: a resource for annotating human genes at transcriptional level with ontologies](http://bio-annotation.cn/OntoGene/)

- [Paper](https://www.nature.com/articles/srep34820)

- [Website](http://bio-annotation.cn/Ontogene/Home.jsp)

- [Data](http://bio-annotation.cn/Ontogene/Download.jsp)


### Orphanet Data

Orphanet is a unique resource, gathering and improving knowledge on rare diseases so as to improve the diagnosis, care and treatment of patients with rare diseases. Orphanet aims to provide high-quality information on rare diseases, and ensure equal access to knowledge for all stakeholders. Orphanet also maintains the Orphanet rare disease nomenclature (ORPHAcode), essential in improving the visibility of rare diseases in health and research information systems.

Orphanet was established in France by the INSERM (French National Institute for Health and Medical Research) in 1997.This initiative became a European endeavour from 2000, supported by grants from the European Commission: Orphanet has gradually grown to a Consortium of 40 countries, within Europe and across the globe.

- [Website](https://www.orphadata.com/)


### PharmKG: a dedicated knowledge graph benchmark for bomedical data mining

Biomedical knowledge graphs (KGs), which can help with the understanding of complex biological systems and pathologies, have begun to play a critical role in medical practice and research. However, challenges remain in their embedding and use due to their complex nature and the specific demands of their construction. Existing studies often suffer from problems such as sparse and noisy datasets, insufficient modeling methods and non-uniform evaluation metrics. In this work, we established a comprehensive KG system for the biomedical field in an attempt to bridge the gap. Here, we introduced PharmKG, a multi-relational, attributed biomedical KG, composed of more than 500 000 individual interconnections between genes, drugs and diseases, with 29 relation types over a vocabulary of ~8000 disambiguated entities. Each entity in PharmKG is attached with heterogeneous, domain-specific information obtained from multi-omics data, i.e. gene expression, chemical structure and disease word embedding, while preserving the semantic and biomedical features. For baselines, we offered nine state-of-the-art KG embedding (KGE) approaches and a new biological, intuitive, graph neural network-based KGE method that uses a combination of both global network structure and heterogeneous domain features. Based on the proposed benchmark, we conducted extensive experiments to assess these KGE models using multiple evaluation metrics. Finally, we discussed our observations across various downstream biological tasks and provide insights and guidelines for how to use a KG in biomedicine. We hope that the unprecedented quality and diversity of PharmKG will lead to advances in biomedical KG construction, embedding and application.

- [Paper](https://academic.oup.com/bib/article/22/4/bbaa344/6042240)

- [Code](https://github.com/MindRank-Biotech/PharmKG)

- [Website](http://www.tcmip.cn/Syndrome/front/#/)

- [Dataset](https://zenodo.org/record/4077338)


### PreMedKB: an integrated precision medicine knowledgebase for interpreting relationships between diseases, genes, variants and drugs
Precision Medicine Knowledgebase (PreMedKB) integrate the four fundamental components of precision medicine: diseases, genes, variants and drugs. PreMedKB allows for search of comprehensive information within each of the four components, the relationships between any two or more components, and importantly, the interpretation of the clinical meanings of a patient's genetic variants. PreMedKB is an efficient and user-friendly tool to assist researchers, clinicians or patients in interpreting a patient's genetic profile in terms of discovering potential pathogenic variants, recommending therapeutic regimens, designing panels for genetic testing kits, and matching patients for clinical trials.

- [Paper](https://pubmed.ncbi.nlm.nih.gov/30407536/)


### SMPDB: The Small Molecule Pathway Database

SMPDB (The Small Molecule Pathway Database) is an interactive, visual database containing more than 30 000 small molecule pathways found in humans only. The majority of these pathways are not found in any other pathway database. SMPDB is designed specifically to support pathway elucidation and pathway discovery in metabolomics, transcriptomics, proteomics and systems biology. It is able to do so, in part, by providing exquisitely detailed, fully searchable, hyperlinked diagrams of human metabolic pathways, metabolic disease pathways, metabolite signaling pathways and drug-action pathways. All SMPDB pathways include information on the relevant organs, subcellular compartments, protein_complex cofactors, protein_complex locations, metabolite locations, chemical structures and protein_complex quaternary structures. Each small molecule is hyperlinked to detailed descriptions contained in the HMDB or DrugBank and each protein_complex or enzyme complex is hyperlinked to UniProt. All SMPDB pathways are accompanied with detailed descriptions and references, providing an overview of the pathway, condition or processes depicted in each diagram. The database is easily browsed and supports full text, sequence and chemical structure searching. Users may query SMPDB with lists of metabolite names, drug names, genes/protein_complex names, SwissProt IDs, GenBank IDs, Affymetrix IDs or Agilent microarray IDs. These queries will produce lists of matching pathways and highlight the matching molecules on each of the pathway diagrams. Gene, metabolite and protein_complex concentration data can also be visualized through SMPDB's mapping interface. All of SMPDB's images, image maps, descriptions and tables are downloadable.

- [Paper](http://www.ncbi.nlm.nih.gov/pubmed/24203708)

- [Website](http://smpdb.ca/)

- [Data](http://smpdb.ca/downloads)

### LitCovid: A literature hub for tracking up-to-date scientific information about the 2019 novel Coronavirus.

LitCovid is the most comprehensive resource on the subject, providing a central access to 374,577 (and growing ) relevant articles in PubMed. The articles are updated daily and are further categorized by different research topics (e.g. transmission) and geographic locations.

- [Website](https://www.ncbi.nlm.nih.gov/research/coronavirus/)

- [Paper](https://academic.oup.com/nar/article/49/D1/D1534/5964074)

### Thera-SAbDab: Therapeutic Structural Antibody Database

The Therapeutic Structural Antibody Database (Thera-SAbDab) is a database of immunotherapeutic variable domain sequences and their corresponding structural representatives in SAbDab (which harvests data from the PDB). It updates structural mappings alongside SAbDab on a weekly basis. It detects not only exact sequence matches to known structures, but also close sequence matches (divided into two categories: 95-98% seqID, or 99% seqID).

- [Website](https://opig.stats.ox.ac.uk/webapps/sabdab-sabpred/sabdab)

- [Paper](https://academic.oup.com/nar/article/50/D1/D1368/6431822)

### UmabsDB: The Umabs Antibody Therapies Database

The Umabs Antibody Therapies Database is launched and run by Umabs Therapeutics. All indexed antibody entries are collected from open sources. We are a team of antibody scientists who aim to provide the best and most updated data to the antibody research community. A well-curated database provides a comprehensive scope of the field. Furthermore, data of good quality is the infrastructure for AI-based antibody therapy development. In the future, we will upload research data of 1) discovery, 2) development and 3) NGS sequencing data from open sources and research activities of trusted collaborative organisations.

- [Website](https://umabs.com/)

### SoFDA: an integrated web platform from syndrome ontology to network-based evaluation of disease–syndrome–formula associations for precision medicine

SoFDA is the first available collections of traditional Chinese medicine (TCM) syndrome ontology, the syndrome classification tool and the related-feature associations with disease and prescriptions for investigating the pathological links and therapeutic mechanisms. It contains the detailed information of 310 TCM syndromes recorded in the monograph of "Chinese Medicine Diagnostics" and 9 novel syndromes of COVID-19, as well as 8045 diseases and 1359 TCM prescriptions used for the corresponding syndromes. Considering the lack of classification information for most TCM syndromes affecting diagnostic efficacy in the daily clinical settings, SoFDA offers a novel prediction tool for syndrome classification, based on symptoms and the related target genes, the enriched gene ontology items, pathways, network modules and network density, with a simple operation and a satisfying performance. More importantly, it evaluates the association levels of syndrome-syndrome, syndrome-disease, syndrome-formula and syndrome-disease-formula, via calculating the symptom-, target gene-, the enriched gene ontology item-, pathway- and network module-based similarities and the network density, and further utilizes a variety of visualization types, such as heatmap, multi-level network and upsetview, to illustrate the association calculation results. In summary, SoFDA is of great significance to elucidate the biological basis of TCM syndromes and to facilitate functional and mechanistic studies of TCM syndrome differentiation and treatment.

- [Paper](https://www.sciencedirect.com/science/article/pii/S2095927322001037)

- [Website](http://www.tcmip.cn/Syndrome/front/#/)


### SymMap: an integrative database of traditional Chinese medicine enhanced by symptom mapping

The pharmaceutical industry has heavily emphasized phenotypic drug discovery (PDD), which relies primarily on knowledge about phenotype changes associated with diseases. Traditional Chinese medicine (TCM) provides a massive amount of information on natural products and the clinical symptoms they are used to treat, which are the observable disease phenotypes that are crucial for clinical diagnosis and treatment. Curating knowledge of TCM symptoms and their relationships to herbs and diseases will provide both candidate leads and screening directions for evidence-based PDD programs. 

SymMap is an integrative database of traditional Chinese medicine enhanced by symptom mapping. It contains 1717 TCM symptoms and related them to 499 herbs and 961 symptoms used in modern medicine based on a committee of 17 leading experts practicing TCM, 5235 diseases associated with these symptoms, 19 595 herbal constituents (ingredients) and 4302 target genes, and built a large heterogeneous network containing all of these components. Thus, SymMap integrates TCM with modern medicine in common aspects at both the phenotypic and molecular levels.

- [Paper](https://academic.oup.com/nar/article/47/D1/D1110/5150228)

- [Website](http://www.symmap.org/)


### TTD: Therapeutic Target Database

TTD is a database providing information about the known and explored therapeutic protein and nucleic acid targets, the targeted disease, pathway information and the corresponding drugs directed at each of these targets.
As for 2022, TTD contains 3,578 targets and 38,760 drugs.

- [Paper](https://academic.oup.com/nar/article/50/D1/D1398/6413598)

- [Website](https://db.idrblab.net/ttd/)

- [Data](https://db.idrblab.net/ttd/full-data-download)


### Stanford Biomedical Network Dataset Collection

BioSNAP, short for "Biomedical Snapshots," is a collection of large-scale biomedical datasets and computational tools. It's part of the SNAP (Stanford Network Analysis Project) initiative, which aims to develop and provide resources to facilitate research in network analysis and complex system modeling.

- [Website](https://snap.stanford.edu/biodata/index.html)

### SIDER

SIDER contains information on marketed medicines and their recorded adverse drug reactions. The information is extracted from public documents and package inserts. The available information include side effect frequency, drug and side effect classifications as well as links to further information, for example drug–target relations.

- [Website](http://sideeffects.embl.de/)

### STITCH

The STITCH database (Search Tool for Interactions of Chemicals) is a resource for exploring interactions between proteins and chemicals, including drugs, in various biological systems. It's designed to integrate information about interactions from multiple sources and make it accessible for researchers and scientists.

- [Website](http://stitch.embl.de/cgi/download.pl)

### MetaCyc

MetaCyc is a curated database of experimentally elucidated metabolic pathways from all domains of life. MetaCyc contains pathways involved in both primary and secondary metabolism, as well as associated metabolites, reactions, enzymes, and genes. The goal of MetaCyc is to catalog the universe of metabolism by storing a representative sample of each experimentally elucidated pathway.MetaCyc currently contains 3,153 pathways, 19,020 reactions and 19,372 metabolites.

- [Website](https://metacyc.org/)

### NSides

nSIDES is the home for the drug side effect and drug interaction resources made available from the Tatonetti Lab. Below you will find descriptions of each of the resources with links to download the data and access the code.

- [Website](https://nsides.io/)
