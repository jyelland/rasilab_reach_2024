# Documentation
The CRISPR data you were given
    - gq_mageck.gene_summary.tsv 
    - cb_mageck.gene_summary.tsv 
The output (csv file) of the GO analysis (before you did anything to it)
    - gq_go_output.csv
    - cb_go_output.csv
The final GO analysis table
    - gq_filtered_df_2.csv
    - cb_nmd_go_table.csv
The code (jupyter notebook) that generated that final table
    - gq_filtered_df_2.ipynb
    - gq_pandas_go_analysis.ipynb
    - cb_nmd_go_table.ipynb
# Objective
- RNA metabolism is influenced by various factors, including processes like splicing and nonsense-mediated decay (NMD). Assessing the impact of these factors is crucial. In the context of CRISPR screens, direct measurement of RNA levels becomes important. RNA sequencing provides a quantitative approach to evaluate RNA molecules, offering insights into the effects of gene perturbations on transcriptional regulation, key genes, and pathways. The ReLic screening strategy, focused on splicing and NMD, holds promise in identifying functional consequences resulting from CRISPR-mediated gene modifications. Such investigations contribute to a deeper understanding of the impact of RNA-related processes on gene function.
- **GQ** - What are the factos that affects RNA metabolism specifically spilicing?
## Research
- **What is CRISPR Screening?**
    - CRISPR screening is a technique used to identify and understand the function of specific genes in an organism. It involves using CRISPR-Cas9, a powerful gene editing tool, to systematically target and modify different genes within a cell or organism. By observing the resulting changes in cellular behavior or characteristics, researchers can gain insights into the roles and importance of different genes in various biological processes.
- **ReLiC Screening** (Notes from Presentation)
    - CiBER-seq is a powerful tool for studying gene expression and identifying gene pathways related to protein synthesis. It utilizes a barcode system to measure the effects of gene changes, revealing varying impacts on cells. By integrating CRISPR interference and barcoded expression reporters, it allows measurement of gene expression and understand how different genetic changes influence gene interactions. CiBER-seq uncovers the connections between genes and their roles in biological processes. 
    - Splicing ReLiC: As learned in started Biology classes, the relation between DNA and RNA is known as the central dogma of molecular biology where DNA makes mRNA makes protein through a strategic process. The focus of this process includes a complex and regulated step that includes transcription, pre mRNA splicing, editing, degradation, polyadenylation, etc. known as RNA metabolism. Splicing plays a vital role in which the cutting of introns, noncoding, for exons, coding, to covalently connect for the exons to exit the nucleus and be expressed. The exons acts as a random barcode that is counted by a deep screening to find the effect of sgRNA on reporter mRNA levels. Pooled CRISPR screens are widely used for forward genetic screening in human cells; however, the disrupted RNA metabolism does not manifest with growth and viability defects. For instance, the presence of a mutation can change a phenotype completely or not change it at all. FACS-based CRISPR screening uses protein level readouts for mRNA phenotypes; however, RNA molecules may not alter protein levels. RNA molecules can undergo modifications with specific proteins and the production can be independently performed.
    - **Insert Figures**
- **MaGeCK**
    - Model-based Analysis of Genome-wide CRISPR/Cas9 Knockout: a method used to prioritize single guide RNA, genes, and specific pathways in CRISPR screenings. This method is commonly used in comparison to other methods, for it identifies positive and negatively selected genes under robust and extreme conditions, noting which genes survived and which genes didn't. Though the use and integration of public data sets knocked out data sets are easily identifiable. 
    - Pandas is a powerful Python library that specilizaes in data manipulation and analysis was used to focus on the genetic screening data analysis. Pandas is also used to manage tabular data, which helped with analyizing which column to use for the input on GOrilla.
    - Utilizing pandas, I compared the variables from MaGeCK and visualized the data as a graph. Through this analysis, I identified the most suitable column for GOrilla.
- **GO(Gene Ontology)rilla**
    - GOrilla is a web-based application that performs gene ontology (GO) enrichment analysis on ranked gene lists, without the need for explicit target and background sets. GOrilla provides efficient and rigorous statistical analysis, taking threshold multiple testing into account without the need for simulations. The results are presented in a hierarchical structure, offering a clear visualization of the relationships between enriched GO terms. GOrilla is a valuable addition to the existing repertoire of GO enrichment tools, offering unique features, fast running time, and effective graphical representation.
## GOrilla - Input Data
- In GOrilla, the input includes the organism expressed as Homo sapiens and a single ranked list of Gene IDs (sgRNA) based on the variable positive selection ranking (pos|rank). The positive selection ranking pertains to the specific targeting of genes involved in increasing introns.
    - **Single-guide RNA (sgRNA)** is a molecule used in the CRISPR-Cas9 gene editing system. It is a synthetic RNA sequence that consists of a targeting sequence complementary to a specific DNA sequence of interest and a scaffold sequence that binds to the Cas9 enzyme. The sgRNA guides the Cas9 enzyme to the desired DNA target site, enabling precise gene editing or modification.
    - **Insert Data Set**
- The data was given to   it was generated (e.g. a custom CRISPR screen designed by our lab (aka RELIC screen) using the intron-retention/splicing reporter)
- **Results** - https://cbl-gorilla.cs.technion.ac.il/GOrilla/zctdtiao/GOResults.html 
## Output
- https://www.science.org/doi/10.1126/science.abb9662 - Figure 1F
- Specficed the signficant gene IDs within the positive selection ranking
- From table, I filtered out the FDR (q-value), False Discovery Rate, (q<0.05)
    - Researchers used the False Discovery Rate (FDR) control method to identify significant genes from the vast gene expression dataset, ensuring that only a small proportion of the reported associations were likely to be false positives.
- Split the Enrichment column to get the "enrichment" number by itself 
- Rounded the "enrichment" number to see if the frequency of numbers were significant to the research
    - Created a histogram to view the enrichment
- With viewing the table, q-value is more significant to the objective. Highlighting on the table is sufficent to show that the lowest q-values are for splicing and RNA processing and NMD. 
    - Made a finialized table showing GO term, description, q-value, enrichment, number of genes in that GO term 
## Conclusion
## References
- https://sourceforge.net/p/mageck/wiki/Home/#gene_summary_txt
- https://innovativegenomics.org/education/digital-resources/what-is-crispr/ 
- https://www.yourgenome.org/facts/what-is-crispr-cas9/
- https://www.khanacademy.org/college-careers-more/bjc/2015-challenge/2015-life-science/v/bjc-crispr-cas-9
- https://link.springer.com/article/10.1186/s13059-015-0843-6 
- https://www.science.org/doi/10.1126/science.abb9662
- https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-10-48#Sec5

<img src="path_to_image_file", width=500px>
