# disease-gene-bioinformatics

* **Name:** Ansag, Eugene Kim  
* **Assigned Gene:** SOD1 (Superoxide dismutase 1, soluble)  
* **Associated Disease:** Familial amyotrophic lateral sclerosis  

## Assigned Gene and Disease

* **Official Gene Symbol:** SOD1  
* **Full Gene Name:** Superoxide dismutase 1, soluble  
* **Associated Disease:** Familial amyotrophic lateral sclerosis (a genetic form of amyotrophic lateral sclerosis associated with pathogenic variants in SOD1).

## UCSC Gene Location

* **Chromosome:** Chromosome 21  
* **Genome Assembly Used:** GRCh38/hg38  
* **Genomic Coordinates in UCSC:** chr21:31,659,693-31,668,931  
* **DNA Strand:** Positive strand (+)  
* **Approximate Gene Size / Length:** 9,239 bp  

### Screenshot 1: Gene Location in UCSC
*Description: The UCSC Genome Browser displaying the SOD1 gene region on chromosome 21 with visible genomic coordinates and gene symbol.*  
* [View screenshot 1 (Gene Location)](screenshots/01_gene_location.png)

## Exons, Introns, and Transcripts

* **Number of Exons (in selected transcript):** 5 exons  
* **Multiple Transcripts/Isoforms:** Yes, multiple transcript models are visible in the UCSC Genome Browser.  
* **Definition of Exon vs. Intron:** Exons are regions of the gene that are retained in the mature RNA after splicing, whereas introns are intervening regions that are removed during RNA processing.  
* **Intron vs. Exon Length Observation:** The introns generally appear longer than the exons, creating relatively large gaps between the exon blocks.  

The selected GENCODE transcript is **ENST00000270142.11**, which contains 5 exons. The coding region is located at chr21:31,659,770-31,668,578, and the encoded SOD1 protein contains 154 amino acids.

### Screenshot 2: Gene Structure and Transcripts
*Description: Detailed view of the SOD1 gene structure showing exon boxes, intron connecting lines, and multiple transcript models.*  
* [View screenshot 2 (Gene Structure)](screenshots/02_gene_structure.png)

## Genome Browser Tracks

* **a. Gene annotation track used:** GENCODE and NCBI RefSeq  
* **b. ClinVar-related variant marks:** Yes, ClinVar-related variant marks are visible within and around the SOD1 gene region.  
* **c. Conservation variation:** Yes, certain regions exhibit noticeably stronger conservation signals than others across species.  
* **d. Conserved region location:** Conserved regions correspond predominantly to coding exons, although conservation can also occur in non-coding regions.  
* **e. Significance of conservation:** Strong sequence conservation across species suggests that a region has been maintained because it may have an important biological function. Highly conserved regions may therefore be less tolerant of sequence changes that could disrupt gene or protein function.  

### Screenshot 3: Browser Tracks (ClinVar and Conservation)
*Description: UCSC Genome Browser view displaying the SOD1 gene alongside ClinVar variant annotations and the 100 Vertebrates Basewise Conservation by PhyloP track.*  
* [View screenshot 3 (Browser Tracks)](screenshots/03_tracks.png)

## ClinVar Variant Selection

* **a. Gene:** SOD1  
* **b. Variant HGVS / Description:** NM_000454.5(SOD1):c.272A>C (p.Asp91Ala)  
* **c. rsID or ClinVar Variation ID/VCV accession:** ClinVar Variation ID: 14766; VCV000014766.81  
* **d. Chromosome and genomic position:** Chromosome 21; chr21:31,667,290 (GRCh38)  
* **e. Associated Condition / Disease:** Amyotrophic lateral sclerosis type 1 / SOD1-related disease  
* **f. Clinical Significance:** Conflicting classifications of pathogenicity  
* **g. Review Status:** Criteria provided, conflicting classifications  
* **h. ClinVar Record URL:** https://www.ncbi.nlm.nih.gov/clinvar/variation/14766/  

The selected variant is a single-nucleotide substitution that produces a missense change from **aspartic acid (Asp/D) to alanine (Ala/A) at amino acid position 91**, written as **p.Asp91Ala (D91A)**.

### Screenshot 4: ClinVar Variant Record
* [View Screenshot 4 (ClinVar Variant)](screenshots/04_clinvar_variant.png)

## Variant Mapping and Functional Context

* **a. Where is the variant located relative to your gene?** The variant is located at genomic coordinate **chr21:31,667,290**, within the SOD1 gene on chromosome 21.  
* **b. Is it in an exon, intron, UTR, splice region, or another region?** It is located inside a **coding exon**, corresponding to the coding region of the SOD1 transcript.  
* **c. Is it likely in a coding or non-coding region based on the displayed annotations?** Based on the GENCODE and RefSeq annotations, it is located in a **coding region** and produces the amino-acid substitution p.Asp91Ala.  
* **d. Based on its location and ClinVar information, briefly explain how the variant might affect the gene or gene product:** Because the variant changes one nucleotide within the coding sequence, it changes the encoded amino acid from aspartic acid to alanine at position 91 of the SOD1 protein. This missense substitution could alter the structural or functional properties of SOD1 and may contribute to abnormal protein function associated with SOD1-related disease.  
* **e. What additional evidence would be needed before concluding that the variant causes disease?** Additional evidence would include functional studies of the altered SOD1 protein, genetic segregation studies in affected families, population-frequency data, clinical evidence, and independent studies supporting the relationship between the variant and disease.  

### Screenshot 5: Variant Position in UCSC
* [View Screenshot 5 (Selected variant)](screenshots/05_variant_in_ucsc.png)

## Reflection Questions

* **1. What did UCSC show you about your gene that was not obvious from simply reading about the gene's function?**  
  The UCSC Genome Browser visually displayed the exact structural organization of the *SOD1* gene on chromosome 21. While functional descriptions explain the biological role of SOD1, the browser showed its physical exon-intron structure, transcript models, genomic coordinates, conservation patterns, and clinically reported variants.  

* **2. Why is knowing the exact genomic location of a disease-associated variant useful?**  
  Precise genomic coordinates allow a variant to be connected to a specific region of the SOD1 gene. This makes it possible to determine whether the variant occurs in an exon, intron, UTR, or other genomic region and to compare it with genome annotations and clinical databases.  

* **3. What is one limitation of predicting a variant's effect only from its genomic location?**  
  Genomic location provides structural context but does not directly demonstrate the functional effect of a variant. Experimental studies, clinical evidence, population data, and other genetic evidence are needed to determine whether a variant affects protein function or contributes to disease.  

* **4. What was the most interesting feature you observed about your assigned gene?**  
  It was interesting to see how the single-nucleotide substitution **c.272A>C** could be traced from its ClinVar record to an exact genomic position within the SOD1 gene. The variant produces the **p.Asp91Ala (D91A)** amino-acid change, allowing the genomic-level variant to be connected directly to a specific position in the SOD1 protein.  

## References and Links

* **NCBI ClinVar:** National Center for Biotechnology Information. ClinVar database entry for SOD1 variant c.272A>C (p.Asp91Ala), Variation ID: 14766. Available at: [ClinVar Record](https://www.ncbi.nlm.nih.gov/clinvar/variation/14766/)

* **UCSC Genome Browser:** Human (GRCh38/hg38) Assembly, UCSC Genomics Institute. SOD1 genomic region (chr21:31,659,693-31,668,931). Available at: [UCSC Genome Browser View](https://genome.ucsc.edu/cgi-bin/hgTracks?db=hg38&lastVirtModeType=default&lastVirtModeExtraState=&virtModeType=default&virtMode=0&nonVirtPosition=&position=chr21%3A31659693%2D31668931&hgsid=4173359369_3YBwcjAYFo5bQTPLFPFsoHaaREPx)
