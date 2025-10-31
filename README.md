# 🧬 Graduate Course: Transcriptomics — From Quantification to Interpretation

**Duration:** 5 days × 6 hours/day  
**Audience:** MSc and PhD students with general molecular biology background  
**Focus:** Conceptual and bioinformatic understanding of transcriptomic technologies, their data types, and applications  
**Format:** Morning theory (≈3h) + Afternoon case-based discussion (≈3h)  
**Class:** From 5 to 20 graduate students

## **Day 1 — Introduction to Transcriptomics & Quantitative RNA Methods**

### **Learning Goals**
- Understand what transcriptomics studies and where it fits among omics disciplines.  
- Trace the historical evolution of RNA quantification up to qPCR.  
- Interpret key qPCR metrics and limitations.  
- Understand course structure, expectations, and discussion format.

### **Afternoon #1 (Concepts)**
...

### **Afternoon #2 (Case Scenario)**  
- Research for ~1h for a qPCR experiment in any research study.
- Make a two slides presentation (5 minutes or less) in our colective google presentations.
- Answer these questions:
  - What was the biological question?
  - How many genes were quantified?
  - What reference genes were used for normalization?

## **Day 2 — Microarrays: The First Genome-Wide View**

### **Learning Goals**
- Understand how hybridization-based methods enabled transcriptome-scale quantification.  
- Interpret microarray data structure, normalization, and biases.  
- Evaluate experimental design and reproducibility.

### **Morning (Concepts)**
1. **Principles of microarray technology**  
   - Probes, hybridization, fluorescence detection.
   - One-color vs two-color systems
2. **Normalization methods (RMA, quantile)**  
3. **Statistical analysis concepts**
   - Fold-change, p-value, multiple testing.  
   - Differential expression and others.

### **Afternoon (Case Scenario)**  
- Research for ~1h for a microarray experiment in any research study. Make a two slides presentation (5 minutes or less) in our colective google presentations:
- Answer these questions:
  - Probe platform used? One or two color method?
  - Normalization method used? Which statistical method?
  - How many differentially expressed genes were found?


## **Day 3 — RNA-seq: The Short-Read Revolution**

### **Learning Goals**
- Understand how next-generation sequencing enabled unbiased transcriptome profiling.  
- Grasp conceptual steps in RNA-seq data processing (not coding).  
- Recognize differences between alignment, pseudoalignment, and quantification.  
- Interpret normalization, differential expression, and enrichment logic.

### **Morning (Concepts)**
1. **RNA-seq workflow overview**  
   - Library prep, sequencing, and read mapping principles.  
2. **Data formats and meaning**  
   - FASTQ, BAM, count matrices.  
3. **Core analysis logic**  
   - Quality assessment → alignment → quantification → normalization → DE analysis.  
4. **Experimental design**  
   - Replication, depth, batch control.  
5. **Biological interpretation**  
   - PCA, volcano plots, enrichment (conceptual level).

### **Afternoon (Case Scenario)**  
**Case:** *Differential expression in a disease model using RNA-seq.*  
- Review methods and results from a real paper (e.g., neurodegeneration or infection model).  
- Identify analysis pipeline choices and potential pitfalls.  
- Debate normalization methods and statistical thresholds.  
- **Present:** Our proposed analysis pipeline for this question, and what conclusions we’d trust.

**Wrap-up reflection:**  
> What do we gain from moving from probe signals to sequence counts?

## **Day 4 — Long-Read Transcriptomics**

### **Learning Goals**
- Understand how long-read sequencing (PacBio, Nanopore) reveals transcript isoforms.  
- Compare long-read vs short-read data in accuracy, length, and resolution.  
- Recognize typical analytical goals: isoform discovery, splicing, fusion detection.  
- Discuss hybrid methods combining technologies.

### **Morning (Concepts)**
1. **Overview of long-read technologies**  
   - PacBio SMRT and Nanopore sequencing.  
2. **Advantages for isoform-level resolution**  
3. **Typical computational strategies**  
   - Alignment and isoform quantification.  
4. **Error rates and correction strategies**  
   - Hybrid sequencing (short + long reads).  
5. **Applications**  
   - Alternative splicing, transcript novelty, structural RNA features.

**Discussion prompt:**  
> What biological discoveries require full-length transcript information?

### **Afternoon (Case Scenario)**  
**Case:** *Discovery of new isoforms in neuronal differentiation.*  
- Review a study using long-read sequencing to characterize splicing.  
- Identify how the authors validated isoforms and what short-read data missed.  
- Discuss trade-offs: cost, throughput, and error correction.  
- **Present:** How we’d integrate long-read data into a hybrid transcriptomics study.

**Wrap-up reflection:**  
> Long reads reveal complexity — but what challenges remain for analyzing them?

## **Day 5 — Single-Cell and Spatial Transcriptomics**

### **Learning Goals**
- Understand single-cell RNA-seq (scRNA-seq) and spatial transcriptomics principles.  
- Recognize data structures (cell barcodes, UMIs, spatial coordinates).  
- Grasp conceptual steps in clustering, marker identification, and trajectory analysis.  
- Appreciate integration between scRNA-seq, bulk, and spatial data.

### **Morning (Concepts)**
1. **Why move to single-cell resolution?**  
2. **Overview of scRNA-seq methods**  
   - Droplet-based and plate-based systems.  
3. **Key computational concepts**  
   - Normalization, dimensionality reduction, clustering.  
4. **Spatial transcriptomics technologies**  
   - Visium, MERFISH, Slide-seq.

**Discussion prompt:**  
> How does single-cell data change the kinds of biological questions we can ask?

### **Afternoon (Case Scenario)**  
**Case:** *Mapping tumor microenvironment heterogeneity with scRNA-seq + spatial transcriptomics.*  
- Review a modern paper combining both modalities.  
- Identify strengths and limits of each approach.  
- Propose an experimental and analytical workflow for a related question.  
- **Present:** Our study design to explore cellular diversity and spatial context.

**Wrap-up reflection:**  
> Across all technologies, how have transcriptomics methods changed what we can know about gene expression?

## **Final Synthesis Activity (End of Day 5 or Take-Home)**

- **Group exercise:** Each team receives a biological research question (e.g., drug response, development, disease).  
- **Task:** Choose the appropriate transcriptomic approach(es) and outline how they’d design, analyze, and interpret the study.  
- **Presentation:** 10-minute talk per group followed by guided discussion.
