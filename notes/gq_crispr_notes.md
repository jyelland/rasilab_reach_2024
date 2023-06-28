---
title: Notes on Markdown and CRISPR
author: Grace Quarterman
date: 2023-06-27
---

# Markdown
- Markdown is a markup language to add formatting elelments to tex documents.
- To make a heading "#"
- To make a subheading "##"
- Easy for creating websites, taking notes, and produce print-ready documents
    - can also good for book writing, presentaions, email messages, and collaboration
- Dilinger - is a Markdown editor like VSCode
- Markdown file (.md or .markdown) converts to the application then HTML then renderend output
- "flavors" - variants of Markdown
    - analogy of US Eglish vs London English. Same language different dialect.
## Markdown Tutorial
- Italics _text_
- Bold **text**
- Heading "#", More "#" smaller the heading
- Link "[Name of Link](Link)"
- Images "! [Alternative Name](Link)c
- Blockquotes " >"Quote" "
- List 
    * Item 1
        * Sub Item
    * Item 2
- List
    1. Item 1
    2. Item 2

# What is CRISPR-Cas9?
## Jennifer Doudna's Ted Talk
- Doudna purpose of creating CRISPR was to invent technology for **editing genomes**
- Changes to genetic cells to cure genetic dieases
- Cas9 is a specific protein that cuts the DNA to change specific infected part on DNA
- Stands for Clustered Regularly Interspaced Short Palindromic Repeats 
- Allows the cell to keep track of infection..."genetic vaccination card"
- **Trigger** cells to repair breaks in DNA at the points near or at the mutation
- Still some complications due to unintened effects but when it happend Doudna believs that it will benefit human health in years to come
- Enhancement for genetic change... "designer humans"
## YourGenome
- Edits parts of the genome by removing, adding, or alterniting section of DNA
- CRISPR is benefical because it is a simple and precise way of genetic manipulation
- Cas9 (enzyme) acts as a "molecular scissor"
- gRNA (guide RNA) guides the enzyme to the right part of the mutated genome
- Makes a cut across both strands
- Process of CRISPR
1. gRNA binds to trageted site
2. Cas9 enzyme binds to gRNA
3. Cas9 cuts
4. Cut is repaired introducing new mutation
- CRISPR recognises and defends aganist virus next time it attacks
- Problem: potential for gRNA to bind somewhere else on sequence rather than the targeted spot which could introdue a mutation to a wrong location
## Khan Academy
- Genetic Engerineering
- Each of the sequences are called spacers, special proteins will find and squash it
- crRNA replaces mutated RNA and tracRNA combines with crRNA because of Cas9 
- Zinc Finger Nucleases and Talens are more complicatd and takes more time than CRISPR
- CRISPR can only edit DNA next to PAM (prodce baser adjacent motifs) sequences 

# CRISPR Genetic Screens
## What is CRISPR screening?
- A single experiemtal approach to screen a population of muatnt cells to discover genes involved relating to a specfic phenotyope
- In lamens terms, the screeing is used to find the genetic sequence that influences the phentoype in the entre genome that has many genetic sequences.
    - "Targeted assesement of specfic gene set."
- **CRISPER-ko screen (CRISPER Knockout)**
    - Gene "knockout" by identifyin genomic regions
    - **Traditionally targets protein-coding genes**
        - Used to study enhancers (including rid of skin dieases)
    - Targets (location of genes), Models (whats is used to find the sequence), Assay (how is being assested to be screened), Analysis(measuring and outcome)
    - Changes in sgRNA - sign of CRISPR-ko screens
    - Can identify novel role for genes contribution to phenotypes
        - It is important to review screen hits using atl knockdown method like RNAi or complementary functional experiement
- **sgRNA (SureGuide RNA)** - Nuclease System to allow system to genome edit
    - Increase sgRNA per target improves the sensitivity of a CRISPR-ko screen
    - Negative controls of sgRNA: are nontargeting, assess neutral variations in screen
    - Positive controls of sgRNA: are targeting, find ssental genes like ribosomal/proteasomal subunits
        - Should not be ignored by CRISPR-ko and should serve as a confidence booster for the screen 
- Designing the screen to study bases off the set of genes (size, complexity, and cost)
- Focusing on a certian sequence of elements by transcription factors, kineases, or RNA binding proteins causing it too be more direct and managable screening strategy
- Choice of preferred delivery method of CRISPR should be evaluted for the type of cell b/c it can cause undesirable effects
- **How is Cas9 introduced to cells?**
    - Creation of variablity in Cas9 protien expression among cells
    - Establish cell lines expressing Cas9 like ATCC
- Most CRISPR screens combne with assays that exert selective stresst on cell fitness.
    - Lower fitness decreass abundance
- CRISPR screens on cell engernieering can trigger desirable phenotype
- To measure changes in sgRNA abundance, it is amplified from genomic DNA isolation before and after screen
- A postive screen hit for a gene will result in many independent sgRNA abundances