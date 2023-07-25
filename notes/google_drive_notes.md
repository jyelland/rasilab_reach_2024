# https://docs.google.com/document/d/1pm8s1GsDygkZAIZ5U-h7Nw7eMhKVGkSIK1jx5_jSpuk/edit

# Poster
https://docs.google.com/presentation/d/1sT4stqd8UFZODSqZkhSpsRSWgU-tb4m1ny7c7_8JvKY/edit#slide=id.gda83f6c2f8_0_0 

What is Crispr Screening: CRISPR screening is a technique used to identify and understand the function of specific genes in an organism. It involves using CRISPR-Cas9, a powerful gene editing tool, to systematically target and modify different genes within a cell or organism. By observing the resulting changes in cellular behavior or characteristics, researchers can gain insights into the roles and importance of different genes in various biological processes.

Objective/Question:
RNA metabolism is influenced by various factors, including processes like splicing and nonsense-mediated decay (NMD). Assessing the impact of these factors is crucial. In the context of CRISPR screens, direct measurement of RNA levels becomes important. RNA sequencing provides a quantitative approach to evaluate RNA molecules, offering insights into the effects of gene perturbations on transcriptional regulation, key genes, and pathways. The ReLic screening strategy, focused on splicing and NMD, holds promise in identifying functional consequences resulting from CRISPR-mediated gene modifications. Such investigations contribute to a deeper understanding of the impact of RNA-related processes on gene function.

Software used: 
MAGeCK (Model-based Analysis of Genome-wide CRISPR/Cas9 Knockout): a method used to prioritize single guide RNA, genes, and specific pathways in CRISPR screenings. This method is commonly used in comparison to other methods, for it identifies positive and negatively selected genes under robust and extreme conditions, noting which genes survived and which genes didn't. Though the use and integration of public data sets knocked out data sets are easily identifiable. 
GOrilla: GOrilla is a web-based application that performs gene ontology (GO) enrichment analysis on ranked gene lists, without the need for explicit target and background sets. It utilizes a flexible threshold statistical approach called mHG, enabling the identification of significantly enriched GO terms at the top of a ranked gene list. GOrilla provides efficient and rigorous statistical analysis, taking threshold multiple testing into account without the need for simulations. The results are presented in a hierarchical structure, offering a clear visualization of the relationships between enriched GO terms. GOrilla is a valuable addition to the existing repertoire of GO enrichment tools, offering unique features, fast running time, and effective graphical representation.

CB Background: 

NMD ReLiC: The analysis of NMD (nonsense-mediated mRNA decay) insertion and deletion events in CRISPR data screening yields valuable insights into the functional consequences and potential regulatory effects of gene modifications within the nonsense-mediated decay pathway. This is a strategy used to assess the functional consequences of gene perturbations on the nonsense-mediated decay (NMD) pathway. By combining CRISPR-mediated gene modifications with NMD reporters, NMD ReLiC allows for the identification and characterization of genetic variants that impact NMD activity, revealing the regulation and consequences of NMD in various biological processes. The NMD pathway serves as a quality control mechanism that degrades mRNA molecules containing premature termination codons (PTCs) resulting from nonsense mutations or frameshift mutations involving additions or deletions of bases. NMD has been implicated in human phenotypes, exerting either beneficial or detrimental effects on disease outcomes. This study investigates the impact of NMD insertion and deletion events on disease pathogenesis and other relevant outcomes.

GQ Background:

Splicing ReLiC: As learned in started Biology classes, the relation between DNA and RNA is known as the central dogma of molecular biology where DNA makes mRNA makes protein through a strategic process. The focus of this process includes a complex and regulated step that includes transcription, pre mRNA splicing, editing, degradation, polyadenylation, etc. known as RNA metabolism. Splicing plays a vital role in which the cutting of introns, noncoding, for exons, coding, to covalently connect for the exons to exit the nucleus and be expressed. The exons acts as a random barcode that is counted by a deep screening to find the effect of sgRNA on reporter mRNA levels. Pooled CRISPR screens are widely used for forward genetic screening in human cells; however, the disrupted RNA metabolism does not manifest with growth and viability defects. For instance, the presence of a mutation can change a phenotype completely or not change it at all. FACS-based CRISPR screening uses protein level readouts for mRNA phenotypes; however, RNA molecules may not alter protein levels. RNA molecules can undergo modifications with specific proteins and the production can be independently performed.

Key: 
Id: Gene Id number used to identify each gene in the data set.
Num: The number of targeting sgRNAs for each gene refers to the quantity of specific guide RNA sequences that can be designed to target a particular gene. This number indicates the potential versatility and flexibility of targeting options for genetic manipulation or gene editing purposes, allowing for more precise and efficient gene targeting and modifications. 
Neg|score: The RRA (Relative Rank Abundance) low value of a gene in negative selection suggests that the gene is less abundant or less prevalent in a given context or condition compared to wildtype genes. This indicates a potential association with negative selection, where the gene is under evolutionary pressure or experiencing reduced fitness during intron insertion and deletion.
Neg|p-value: The raw p-value (using permutation) of this gene in negative selection refers to the statistical significance of the observed association between the gene and negative selection based on a specific permutation test. It provides a measure of the likelihood that the observed results occurred by chance alone, with a lower raw p-value indicating a stronger indication of the gene's involvement in negative selection.
Neg|fdr: false discovery rate (FDR) for a gene in the context of negative selection. It represents the proportion of genes classified as being under negative selection that is expected to be false discoveries or false positives, or possible replicates, providing an estimation of the likelihood that the observed association is due to chance. 
Neg|rank: This represents the rank of a gene in relation to negative selection, indicating its relative position or abundance compared to other genes in the context of negative selection. 
Neg|goodsgrna: It refers to the number of "good" single-guide RNA (sgRNA) sequences available for targeting the gene in the context of negative selection, suggesting the potential versatility and options for genetic manipulation or gene editing.
Neg|lfc: The Neg|lfc stands for "log fold change" in the context of negative selection, indicating the magnitude of change in gene expression or another relevant metric between the negative selection condition and a  reference condition.
Pos|score: This represents the score or a numerical value assigned to a gene in the context of positive selection, indicating its potential significance or relevance in positive selection.
Pos|p-value: It refers to the p-value (probability value) associated with a gene in the context of positive selection, representing the statistical significance of the observed association between the gene and positive selection.
Pos|fdr: The Pos|fdr stands for false discovery rate in the context of positive selection, representing the proportion of genes classified as being under positive selection that are expected to be false discoveries or false positives.
Pos|rank: This indicates the rank of a gene in relation to positive selection, representing its relative position or abundance compared to other genes in the context of positive selection.
Pos|goodsgrna: It refers to the number of "good" single-guide RNA (sgRNA) sequences available for targeting the gene in the context of positive selection, indicating the potential versatility and options for genetic manipulation or gene editing.
Single-guide RNA (sgRNA) is a molecule used in the CRISPR-Cas9 gene editing system. It is a synthetic RNA sequence that consists of a targeting sequence complementary to a specific DNA sequence of interest and a scaffold sequence that binds to the Cas9 enzyme. The sgRNA guides the Cas9 enzyme to the desired DNA target site, enabling precise gene editing or modification.
Pos|lfc: "log fold change" in the context of positive selection, indicating the magnitude of change in gene expression or another relevant metric between the positive selection condition and a reference condition.

Clinical impact: CRISPR screening has a significant clinical impact as it enables the identification of potential therapeutic targets and the understanding of disease mechanisms. By systematically modifying and studying genes, CRISPR screening helps uncover genes involved in diseases, allowing for the development of targeted therapies. It also aids in identifying drug resistance mechanisms, predicting drug responses, and advancing personalized medicine approaches. Ultimately, CRISPR screening contributes to accelerating the discovery and development of novel treatments and improving patient outcomes.

Oral Health Connection: CRISPR technology has the potential to make a significant impact on oral health in several ways:

1. Targeted Gene Therapy: Scientists are exploring the use of CRISPR for targeted gene therapy in oral health conditions. This means they can potentially use CRISPR to treat genetic disorders that affect oral health, such as problems with tooth enamel or dentin development.

2. Dental Disease Research: CRISPR allows researchers to make precise changes to genes in laboratory models, like animals or cell cultures. By doing so, they can study the genetic factors involved in dental diseases such as tooth decay, gum disease, and oral cancers. This research can lead to a better understanding of these conditions and the development of new treatments.

3. Bacterial Modification: CRISPR can be used to modify harmful bacteria in the mouth that contribute to tooth decay or gum diseases. Researchers are investigating ways to use CRISPR to target and disrupt the genes of these bacteria, potentially making them less harmful and reducing oral health problems.

4. Salivary Diagnostics: CRISPR-based techniques can be used to create advanced diagnostic tools for oral diseases. By leveraging CRISPR's gene-editing abilities, scientists can design tests that detect specific genetic markers in saliva. This enables early detection of oral conditions and diseases, improving the chances of successful treatment.

Future Directions: 

References: 

CiBER-seq dissects genetic networks by quantitative CRISPRi profiling of expression phenotypes | Science
Research Techniques Made Simple: CRISPR Genetic Screens - PMC (nih.gov)
MAGeCK enables robust identification of essential genes from genome-scale CRISPR/Cas9 knockout screens (harvard.edu)
Table of Contents (gsea-msigdb.org)
(PDF) APPLICATIONS OF CRISPR TECHNOLOGY IN DENTISTRY: A REVIEW (researchgate.net)
https://link.springer.com/article/10.1186/s13059-015-0843-6 

Work for 7/13- create graph, and research impact on oral health

GOrilla puts in a given ID but it has to be in a certain order. What is that order? Find out through pandas and use the MAGeCK tool to understand which would be best.
pos,rank would be the best because its a ranking of the certain gene in positive selection
The ID genes (sgRNA) are targeted to get genes involved in the rise of introns/NMD (positive selection) which are supposed to be cut out of the mature mRNA.

GQ – Understanding the Relationship of the MAGeCK Variable Relationships
Directly proportional:
neg | score vs neg | p-value

neg | score vs neg | rank

pos | score vs pos | p-value

pos | score vs pos | rank

Interesting:
neg | score vs neg | lfc

pos | score vs neg | lfc

neg | score vs pos | rank

Christine Data- create graphs and interpret

Jul 25, 2023
# Methodology:
The study involved the receipt and analysis of CRISPR data obtained from a custom CRISPR screening conducted by the Rasi Lab, commonly known as relic screening. The screening methodology utilized intron retention/slicing reporters and nonsense-mediated decay (NMD) to identify specific gene targets associated with increased intron retention and NMD. The data input for the analysis in GOrilla comprised Homo sapiens as the organism and a single ranked list of Gene IDs (sgRNA) based on the variable positive selection ranking (pos|rank), which is tailored to target genes involved in intron retention and NMD.
The data was then processed using Python (pandas), and the analysis focused on determining the most significant results for Gene Ontology (GO) analysis using GoRilla. A diagram with color-coded p-values representing various biological processes and a table presenting GO terms, their descriptions, P-values, FDR values, enrichment scores, and associated genes were provided. To filter out potentially false associations, the False Discovery Rate (FDR) control method was applied, specifically targeting significant genes within the positive selection ranking with a q-value of less than 0.05. Histograms were then created based on neg l score, num, and neg I p-value, to visualize data. 
Furthermore, to gain a better understanding of the enrichment values and their significance, the "enrichment" column was isolated and rounded, and a histogram was generated to visualize the frequency distribution of enrichment values. Upon reviewing the table, it became evident that the q-value played a more crucial role in achieving the research objectives. The lowest q-values were associated with splicing, RNA processing, and NMD screening, which were highlighted in the table, along with the corresponding GO term, description, q-value, enrichment, and the number of genes falling within each GO term.
# Objective: 
The project involves the design of customized CRISPR screens to discern the key factors implicated in Nonsense-Mediated Decay (NMD) and splicing processes, with a focus on assessing the effectiveness of the screens in targeting the intended biological processes. The primary objective of CRISPR screens is to discover novel factors associated with these biological processes and gain a comprehensive understanding of the functionality of specific genes or genetic elements within the organism's genome. To achieve this, Go analysis is employed to delineate a roadmap of specific factors influencing the targeted biological processes.