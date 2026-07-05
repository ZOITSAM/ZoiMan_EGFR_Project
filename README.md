# ZoiMan_EGFR_Project
Title (specific, not generic)
• Research Question (what are you answering?)
• Background (why does EGFR matter? What's known? What's the gap?)
• Hypothesis (if applicable, what do you expect to find?)
• Methods (which databases, in what order, why)
• Expected Output (what will you deliver? Figures, tables, findings)
• Timeline (which days for which steps)

PROPOSAL:
Title: Structural and Functional Analysis of EGFR Mutation Hotspots in Non-Small Cell Lung Cancer Using Bioinformatics Databases 

Research Question: Which aminoacid positions in the EGFR are most frequently mutated in non-small lung cancer (NSCLC) and why are these positions considered mutation hotspots?

Background: NSCLC is the most common type of lung cancer occuring n both smokers and non-smokers but smoking remains the greatest risk factor. But EGFR-mutant NSCL is more common in people who are non- or light-smokers, women, East Asian and also in patients with the subtype NSCLS of adenocarcinoma. 

Under normal circusmances EGFR encodes a receptor tyrosine kinase that regulates important cellular process including cell growth , proliferation, differentiation and survival, and its a activation is tightly controlled by ligand binding. However, mutations within the EGFR gene can lead to extra receptor activation , resulting in uncontrolled cell proliferation and tumor development. 

Several EGFR mutations have been identified as clinically significant . Among the most common are exon 19 deletions and the L858R substitution within the tyrosine kinase domain. These mutations are known as mutation hotspots because they occur frequently in patients with NSCLC and are associtaed with sensitivity to EGFR tyrosine kinase inhibitors such as gefitinib and erlotinib. Other mutations include the T790M, may develop during treatment and contribute to acquired drug resistance. 

Even if these mutations are well documented, understanding why the mutations in specific locations contribute to disease development. Using multiple databases can provide more information between the relationship of sequence conservation, protein domains, 3D structure and disease associated variants. 

Hypothesis: That the most common EGFR mutation hotspots occur within highly conserved regions of the tyrosine kinase domain, since its essential fot normal receptor function. Mutations in these areas can potentially alter the EGFR structure and activity , leading to continuous signaling that causes uncontrolled proliferation of the cells ( aka tumour)

Methods: Firstly use UniProt to obtain normal human EGFR sequence, functional annotation and structural features information, to help understand normal biological roles and protein organisation. Next, use BLAST to compare the human EGFR protein sequence with homologous sequences from other species to identify highly conserved amino acids location and determine whether commonly mutated positions are evolutionarily conserved. After that use InterPro to identify within EGFR protein domains including extracellular domain, transmembrane region and tyrosine kinase domain. Then, ClinVar will be used to retrieve clinically significant EGFR variants associated with NSCLC , to map mutation hotspots to specific functional regions. Lastly, the Protein Data Bank (PDB) will be used to examine the 3D structure of EGFR. the mutations hotspots identified using ClinVar will be visualised in PDB within the protein structure and we will investigate hwo their location influences the protein stability, catalytic activity and receptor signalling. 

Expected Output:A table sumamarising the most common EGFR mutations and their clinical significance, a sequence alignment highlighting conserved a.a. residues, a diagram showing location of functional protein and annotated images of 3D EGFR structure displaying mutation hotspots. The final report will explain how sequence conservation, domain organisation and protein structure contribute to the development of NSCLC and why certain a.a positions are particularly susceptible to disease-causeong mutations

Timeline: The project will use in Day 1 - sequence retrieval and evolutionary analysis ( Tool; UniProt and BLAST). Day 2- examine gene information and genomic context ( e.g. chromosome position and gene features= Genomic + gene info - ENSEMBL , NCBI Gene*) . Day 3- investigate EGFR expression and biological function ( Tool: expression databases such as UniProt functional annotation and related gene expression resources) . Day 4- analyse protein domains and 3D structure (Tool: InterPro and PDB). Day 5- integrate all findings , interpret the mutation hotspots and prepare the final report and Github repository. 

*
 Ensembl
Use for:
Chromosome location of EGFR (7p11.2)
Exon/intron structure
Transcript variants
Gene diagrams
Why it’s important:
 This is your main “gene map” tool.

NCBI Gene
Use for:
Gene summary (EGFR function overview)
Genomic context
Links to ClinVar, PubMed, protein data
Why it’s important:
 It connects gene → disease → literature.


