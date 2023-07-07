# Presention on ReLiC (RNA-linked CRISPR screening) screening
- **slide 1**: mRNA transfer info genes to protein
    - central dogma of biology
- **slide 2**: RNA metabolism is complex and involes thousands of RNA binding proteins (RBPs)
    - Splicing = cutting of introns for exons to covalently connect that turn in mature mRNA
        - Exons exits nucleus to be expressed
    - Initiation to Elongation to Termination to Processing 
        - Splicing (Alternative Splicing)
        - 5' Cap (Prevents against degradation)
        - 3' Poly A Tail (Prevents against degradation)
        - After 5' Cap and 3' Poly A tail is connected to sequence ready to leave cell and go into the cytoplasm
    - Polydenylation : process adding Poly A tail 
        - leads to noncoding RNAs decay
- **slide 3** mRNA metabolism pathways have primarily been charcterized in yeast
    - identify RBP networks that regulate pathways in human cells
- **slide 4** pooled CRISPR screens are widely used for forward genetic screening in huma cells
    - limitation Disrupt RNA metabolism doesn't manifest with growth and viabilty defects
        - harmful vs. not harmful mutations
            - Substituion, Insertion, Deletion, Frameshift -- can change gene's phenotype however no change can occur, slient mutation
- **slide 8** how can mRNA barcode-linked CRISPR screening be implemented in human cells 
    - mRNA barcode linked CRISPR screening experiements in human cells
    1. create guide RNA (gRNA) library 
        - guide CAS-9 to genomic location
    2. synthesize gRNA and barcode library 
        - barcode that serves as a molecular identifier
    3. introduce gRNA and barcode library in target human cells 
    4. expose cells to drug to see what survives
    5. Extract mRNA and barcode info 
    - Overall... requires expertise in molecular biology, gene editing teqnique, and bioinformatics
- **last slide** ReLiC screens
    - attB 
    - mCherry/Puro = control reporter
    - N20 = random barcode 1
    - hU6/mU6 = sgRNA CRISPR library
    - Reporter = Reporter of intrest
    - N20 = random baracode 2
- **last slide pt.2** second application of ReLiC screening strategy: factors involving splicing (**project objective**)
    - Reporter - Incorrectly splicing (intron present) or Correctly splicing (just exon present)
    - Project: run raw read counts through Mageck software
        - Reporter, N20 (Barcode 2) - "treatment"
        - mCherry, N20 (Barcode 1) - "control"
    