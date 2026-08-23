# 🧬 Bioinformatics × AI Workshop

### Introduction to Bioinformatics, Computational Biology, CADD & AI for Biology

> **Connecting Biology, Data Science, & AI**

A comprehensive, hands-on workshop designed primarily for **Computer Science, Data Science, and AI/ML students** to build a practical bridge between biological problems and modern computational intelligence.

This workshop introduces the biological foundations required to work with biological data, then progressively connects them to **Data Science, Machine Learning, Deep Learning, Generative AI, Foundation Models, and Computer-Aided Drug Design (CADD).**

Special thanks to the **ProgramMatrix** 3 Zero Club Committee, School of Computing and Informatics, Albukhary International University, for their support in organizing this workshop.

<img width="1024" height="1280" alt="WhatsApp Image 2026-08-23 at 8 08 02 PM" src="https://github.com/user-attachments/assets/b596e129-92cf-403b-9c99-388927231650" />



---

## 🎯 Workshop Vision

Biology is rapidly becoming one of the world's largest data-generating fields.

Genomic sequences, gene-expression matrices, protein structures, medical images, molecular graphs, clinical records, and biomedical literature can all be transformed into computational problems.

This workshop asks a simple question:

> **What happens when we point modern AI at biological problems?**

The goal is to help participants move from:

**Biological Question → Biological Data → Computational Representation → ML/DL Model → Interpretation → Biological Validation**

---

# 📚 Workshop Structure

The workshop is organized into two sessions.

## 🟢 Day 1 — Bioinformatics & Computational Biology

### Introduction to Biology for CS Students

- Cell, nucleus, gene, genome, protein, mutation
- DNA, RNA, and proteins
- Central Dogma of Molecular Biology
- Genes, genomes, and genetic variation
- Sources of biological data

### Bioinformatics

- What is Bioinformatics?
- Why Bioinformatics emerged
- Biological data types
- DNA / RNA / Protein sequences
- FASTA and FASTQ
- Biological databases
- NCBI
- GenBank
- UniProt
- PDB
- Ensembl
- KEGG

### Sequence Analysis

- Sequence alignment
- Pairwise alignment
- Needleman–Wunsch
- Smith–Waterman
- Multiple Sequence Alignment
- BLAST
- Genome analysis
- Variant calling
- Genome annotation
- Comparative genomics

### Omics & Structural Biology

- Transcriptomics
- RNA-seq
- Gene-expression analysis
- Proteomics
- Mass spectrometry
- Protein structure
- Primary, secondary, tertiary & quaternary structure
- Structural bioinformatics

### Computational Biology

- What is Computational Biology?
- Bioinformatics vs Computational Biology
- Mathematical modeling
- Differential equations
- Markov chains / HMMs
- Bayesian statistics
- Graph theory
- Biological networks
- Gene Regulatory Networks
- Protein–Protein Interaction Networks
- Metabolic Networks
- Signaling Networks
- Molecular Dynamics
- ML surrogate models

### Biology × Data Science

- Biological data as structured data
- Data preprocessing
- Feature engineering
- Exploratory Data Analysis
- Statistical analysis
- Hypothesis testing
- Multiple-testing correction
- PCA
- t-SNE
- UMAP
- Clustering
- Classification
- Regression
- Biological visualization

### Machine Learning for Biology

- Why ML is needed in biology
- Traditional vs ML-based Bioinformatics
- Biological feature engineering
- Classical ML pipelines
- Model evaluation
- Interpretability
- Biological validation

Day 1 establishes the foundation for understanding how biological measurements become computational and machine-learning problems.

---

# 🔵 Day 2 — Deep Learning, Modern AI & CADD

## Deep Learning for Biological Data

- Representation Learning
- CNNs for biological sequences and images
- RNNs / LSTMs for sequences
- Transformers for biological sequences
- Protein Language Models
- Learned protein embeddings
- Protein function prediction
- Protein structure prediction
- AlphaFold
- Computer Vision for Histopathology
- Medical & biological image analysis
- Multimodal Deep Learning

Modern biological AI topics include sequence models, protein representation learning, AlphaFold-style structure prediction, histopathology analysis, and multimodal learning.

---

## 🤖 Modern AI for Biology

### Generative AI

- Generative models for biology
- Protein sequence generation
- Molecular generation
- Structural generation
- Diffusion models
- Variational Autoencoders
- Autoregressive generation

### Biomedical LLMs

- General-purpose LLMs
- Domain-specific biomedical LLMs
- BioGPT
- Med-PaLM
- Biomedical NLP
- Named Entity Recognition
- Relation Extraction
- Literature Mining
- Clinical Text Understanding

### Retrieval-Augmented Generation

- Scientific question answering
- Retrieval
- Embeddings
- Context augmentation
- Evidence-grounded generation
- Citation-aware biomedical RAG

### Knowledge Graphs + LLMs

- Biomedical knowledge graphs
- Genes
- Proteins
- Diseases
- Drugs
- Pathways
- Graph-based reasoning
- Drug repurposing
- Hypothesis generation

---

# 💊 Computer-Aided Drug Design (CADD)

The workshop introduces how computational methods can transform drug discovery from traditional trial-and-error workflows toward data-driven and structure-guided approaches.

Topics include:

- What is Drug Design?
- Rational Drug Design
- What is CADD?
- Molecular Docking
- Molecular Modeling
- Target Identification
- Virtual Screening
- Molecular Property Prediction
- Binding Affinity Prediction
- Toxicity Prediction
- Molecular Graphs
- Graph Neural Networks
- Protein Design
- De Novo Protein Design
- Generative Models for Drug Discovery

### AI-driven Drug Discovery Pipeline

```text
Target Identification
        ↓
Virtual Screening
        ↓
Property Prediction
        ↓
Hit Identification
        ↓
Molecular Optimization
        ↓
Preclinical Validation
        ↓
Clinical Trials
```

---

# 🧪 Case Studies

The workshop connects concepts to realistic biological AI problems.

### 01 — DNA Sequence → ML Classification

Predict whether a DNA sequence contains a promoter using sequence representations and ML/DL models.

**Example pipeline:**

```text
DNA Sequence
     ↓
k-mer / One-Hot Encoding
     ↓
Preprocessing
     ↓
Random Forest / 1D-CNN
     ↓
Evaluation
     ↓
Motif Interpretation
```

---

### 02 — Gene Expression → Clustering → Discovery

Use single-cell RNA-seq data to discover previously uncharacterized cell populations.

```text
Gene × Cell Matrix
        ↓
Normalization
        ↓
Variable Gene Selection
        ↓
PCA
        ↓
UMAP
        ↓
Clustering
        ↓
Cell-Type Annotation
```

---

### 03 — Histopathology → Cancer Classification

Use deep learning to classify tumor regions from histopathology images.

```text
Whole-Slide Image
        ↓
Patch Extraction
        ↓
Stain Normalization
        ↓
CNN / Vision Transformer
        ↓
Cancer Classification
        ↓
Interpretability
        ↓
Pathologist Validation
```

---

### 04 — Protein Sequence → Function Prediction

Use pretrained protein language models to predict the function of proteins with unknown roles.

```text
Protein Sequence
        ↓
Tokenization
        ↓
Protein Language Model
        ↓
Embeddings
        ↓
Fine-Tuning
        ↓
Function Prediction
```

---

### 05 — Molecule → Drug Property Prediction

Represent molecules as graphs and use Graph Neural Networks to predict molecular properties.

```text
Molecular Structure
        ↓
Atoms + Bonds
        ↓
Molecular Graph
        ↓
GNN
        ↓
Property Prediction
        ↓
Virtual Screening
```

The case-study framework covers sequence classification, single-cell clustering, histopathology classification, protein-function prediction, and molecular property prediction.

---

### 06 — Biomedical Literature → LLM + RAG

Build an evidence-grounded biomedical research assistant.

```text
Research Question
        ↓
Document Retrieval
        ↓
Text Chunking
        ↓
Embeddings
        ↓
Retriever
        ↓
LLM
        ↓
Evidence-Grounded Answer
        ↓
Source Citations
```

The workshop emphasizes faithfulness, citation accuracy, and expert validation rather than treating an LLM response as automatically reliable.

---

# 🛠️ Computational Ecosystem

The workshop introduces a practical Python-centered ecosystem for computational biology.

| Category | Tools / Technologies |
|---|---|
| Programming | Python |
| Biological Computing | Biopython |
| Numerical Computing | NumPy |
| Data Analysis | Pandas |
| Classical ML | Scikit-learn |
| Deep Learning | PyTorch |
| Deep Learning | TensorFlow / Keras |
| Molecular AI | RDKit |
| Transformers | Hugging Face Transformers |
| Bio Foundation Models | ESM, DNABERT, ChemBERTa |
| Bioinformatics Platform | Galaxy |
| Biological Databases | NCBI, UniProt, PDB |
| Molecular Benchmarks | MoleculeNet |
| Genomic Data | GEO, TCGA |
| Dataset Practice | Kaggle |

The workshop specifically introduces Biopython, NumPy, Pandas, Scikit-learn, PyTorch/TensorFlow, RDKit, Hugging Face Transformers, Galaxy, biological APIs, and public datasets. 
---

# 🧠 Learning Roadmap

The recommended progression after the workshop is:

```text
01
Learn Biology Fundamentals
        ↓
02
Learn Biopython + Biological Data
        ↓
03
Reproduce a Classic Bioinformatics Pipeline
        ↓
04
Apply Classical Machine Learning
        ↓
05
Learn Deep Learning for Biological Data
        ↓
06
Use Pretrained Foundation Models
        ↓
07
Fine-Tune ESM / DNABERT / ChemBERTa
        ↓
08
Explore Generative AI + RAG
        ↓
09
Build an End-to-End AI-for-Biology Project
```

This progression follows the workshop's proposed roadmap from biological fundamentals and Biopython through classic pipelines, pretrained models, and original projects.

---

# 📊 Biological Data → AI Model Mapping

One of the key ideas of this workshop is learning to **match the biological modality with the appropriate computational architecture**.

| Biological Data | Example Problem | Suitable Models |
|---|---|---|
| DNA / RNA Sequence | Promoter prediction | RF, CNN, Transformer |
| Protein Sequence | Function prediction | ESM, Transformer |
| Protein Structure | Structure prediction | Geometric DL |
| Gene Expression | Cell clustering | PCA, UMAP, GNN |
| Histopathology | Cancer classification | CNN, ViT |
| Molecules | Property prediction | GNN |
| Biomedical Text | Literature mining | LLM, RAG |
| Knowledge Graph | Drug repurposing | GNN + LLM |
| Multimodal Data | Integrated prediction | Multimodal DL |

---

# 🔬 Important Principle

> **A biological prediction is a hypothesis until it is validated biologically.**

High-performing models alone are not sufficient.

A reliable AI-for-biology workflow should consider:

- Data quality
- Biological relevance
- Data leakage
- Reproducibility
- Model interpretability
- External validation
- Experimental / wet-lab validation

The workshop explicitly highlights challenges including small sample sizes, noise and batch effects, label scarcity, heterogeneity, interpretability, data leakage, and reproducibility.

---

# 🎓 Who Is This Workshop For?

This workshop is especially suitable for:

- Computer Science students
- Data Science students
- AI / ML students
- Software Engineers interested in AI for Science
- Researchers entering Bioinformatics
- Computational Biology beginners
- Biomedical AI enthusiasts
- Students interested in Drug Discovery
- Anyone interested in AI × Biology

### Prerequisites

Basic knowledge of:

- Python
- Machine Learning fundamentals
- Data Science concepts

No advanced biology background is required.

The workshop intentionally introduces core biological concepts from a CS perspective before moving toward computational modeling and AI.

---

# 📖 Recommended Resources

### Biological Databases

- **NCBI** — Genomic sequences, PubMed, genome resources
- **UniProt** — Protein sequences and annotations
- **RCSB PDB** — 3D biomolecular structures
- **Ensembl** — Genome annotation and visualization
- **KEGG** — Biological pathways

### Datasets & Benchmarks

- **TCGA** — Cancer genomics
- **GEO** — Gene expression datasets
- **MoleculeNet** — Molecular ML benchmarks
- **Kaggle** — Biological ML datasets and competitions

These resources are introduced as part of the workshop's practical ecosystem.

---

# 📚 Selected References

The workshop draws on foundational and modern work in AI and computational biology, including:

1. Jumper et al. — **Highly accurate protein structure prediction with AlphaFold** — *Nature*, 2021.
2. Lin et al. — **Evolutionary-scale prediction of atomic-level protein structure with a language model** — *Science*, 2023.
3. Vaswani et al. — **Attention Is All You Need** — NeurIPS, 2017.
4. Ji et al. — **DNABERT: Pre-trained Bidirectional Encoder Representations from Transformers Model for DNA-language in Genome** — *Bioinformatics*, 2021.
5. Litjens et al. — **A Survey on Deep Learning in Medical Image Analysis** — *Medical Image Analysis*, 2017.
6. Gilmer et al. — **Neural Message Passing for Quantum Chemistry**.

The complete reference list is included in the workshop slides.

---

# 🌱 From Workshop to Research

The workshop is designed not only to introduce tools, but to help participants identify **research problems at the intersection of Biology and AI**.

Potential directions include:

- AI for Genomics
- Protein Language Models
- Protein Structure Prediction
- Drug Discovery
- Molecular Property Prediction
- Graph Neural Networks for Biology
- Biomedical NLP
- Biomedical RAG
- Multimodal Biomedical AI
- Computational Pathology
- Generative Protein Design
- AI-driven Systems Biology

---

# 💡 Final Takeaway

The central idea of this workshop can be summarized as:

```text
BIOLOGY
   ↓
BIOLOGICAL DATA
   ↓
BIOINFORMATICS
   ↓
COMPUTATIONAL BIOLOGY
   ↓
DATA SCIENCE
   ↓
MACHINE LEARNING
   ↓
DEEP LEARNING
   ↓
GENERATIVE / FOUNDATION AI
   ↓
BIOLOGICAL DISCOVERY
```

Modern biology is increasingly becoming a computational science.

The opportunity for the next generation of **CS + AI researchers** is to learn how to translate biological questions into computational problems — and then build intelligent systems that can help answer them.

> **Biology gives us the questions.  
> Data gives us the evidence.  
> AI gives us new ways to explore the possibilities.**

---

# 👨‍🏫 Instructor

<img width="1755" height="1241" alt="S M Asiful Islam Saky_page-0001" src="https://github.com/user-attachments/assets/d847a249-fa21-40a4-934e-39f196ad0e69" />


### S M Asiful Islam Saky

**Doctoral Researcher**  
Universiti Tunku Abdul Rahman (UTAR), Malaysia

🔗 GitHub: https://github.com/saky-semicolon  
🔗 LinkedIn: https://www.linkedin.com/in/saky-semicolon/

---

## ⭐ If This Workshop Helps You

If you find these materials useful:

- ⭐ Star this repository
- 📢 Share it with someone interested in AI + Biology
- 💡 Build your own AI-for-Biology project

**Let's build the next generation of AI-powered biological discovery. 🧬🤖**
