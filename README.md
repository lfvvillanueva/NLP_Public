# Natural Language Processing: Comprehensive Study Guide

## Master's Program in Applied Artificial Intelligence – ITESM

![NLP](https://img.shields.io/badge/Natural%20Language%20Processing-Active-brightgreen)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-In%20Progress-yellow)

---

## Overview

This repository documents the comprehensive study journey through a **Natural Language Processing (NLP)** course as part of the Master's Program in Applied Artificial Intelligence at Instituto Tecnológico y de Estudios Superiores de Monterrey (ITESM). The repository contains weekly study guides, implementations, exercises, and practical applications of core NLP concepts and techniques.

The primary objective is to develop a profound understanding of the theoretical foundations and practical applications of natural language processing, from foundational text preprocessing methodologies to advanced neural architectures capable of capturing complex linguistic phenomena.

---

## General Learning Objectives

Upon successful completion of this Master's course, you will be able to:

- **Analyze** raw textual data and apply comprehensive preprocessing, tokenization, and normalization techniques aligned with computational and linguistic requirements
- **Construct** numerical representations of text using classical (DTM, TF-IDF) and modern (embeddings) approaches to capture semantic relationships
- **Design** and implement neural network architectures (RNN, LSTM) for sequence processing and temporal dependency modeling
- **Develop** and fine-tune transformer-based models (BERT, GPT) for diverse NLP tasks with state-of-the-art performance
- **Engineer** Retrieval-Augmented Generation (RAG) systems integrating large language models with external knowledge sources
- **Evaluate** model performance rigorously using classical metrics (Precision, Recall, F1-score) and modern benchmarks (BLEU, ROUGE, GLUE, SuperGLUE)
- **Identify** and mitigate ethical risks, including bias, toxicity, fairness issues, and hallucinations in language models
- **Deploy** production-grade NLP applications with considerations for efficiency, scalability, and responsible AI practices

---

## Course Structure

### **Module 1: Linguistic Corpus and Text Processing**

**Specific Learning Objectives:**

- 1.1 Describe the evolution of written language analysis
- 1.2 Apply tokenization techniques to segment texts into linguistic units that facilitate computational processing
- 1.3 Utilize regular expressions to identify and extract relevant patterns within texts
- 1.4 Construct matrix representations of documents using Document-Term Matrix (DTM) and TF-IDF to transform text into numerical information
- 1.5 Analyze textual information using structured representations for processing

**Topics Covered:**

- 1.1 Historical background and evolution of NLP
- 1.2 Language structure and linguistic foundations
- 1.3 Linguistic corpus (text corpus) construction and management
- 1.4 Tokenization and normalization techniques (stemming, lemmatization)
- 1.5 Regular expressions (regex) for pattern matching and extraction
- 1.6 Bag-of-words model and its applications
- 1.7 Document-Term Matrix representation
- 1.8 TF-IDF weighting and relevance scoring

**Key Concepts:** Text preprocessing pipelines, corpus normalization, linguistic segmentation, numerical text representation

**Practical Skills:** Regex pattern design, corpus construction, text cleaning, matrix representations, exploratory text analysis

---

### **Module 2: Embedded Representations and Neural Networks**

**Specific Learning Objectives:**

- 2.1 Explain the concept of embedded representations and their importance for modeling semantic relationships between words
- 2.2 Apply embedded vector models, such as Word2Vec, to represent words in vector spaces that capture semantic similarities
- 2.3 Analyze the functioning of Recurrent Neural Networks (RNN) for text sequence processing
- 2.4 Implement models based on LSTM architectures to capture long-term dependencies in NLP tasks

**Topics Covered:**

- 2.1 Vectorization: meaning as vector representation
- 2.2 One-Hot Encoding approach and its limitations
- 2.3 Embedded vectors: word-to-vector transformations
- 2.4 Recurrent Neural Network (RNN) fundamentals and applications
- 2.5 Long Short-Term Memory (LSTM) and GRU architectures for sequence modeling

**Key Concepts:** Distributional semantics, vector spaces, semantic similarity, sequential dependencies, vanishing gradient problem, long-term memory retention

**Practical Skills:** Word embedding generation, RNN/LSTM implementation, sequence processing, embedding visualization and evaluation

---

### **Module 3: Transformers**

**Specific Learning Objectives:**

- 3.1 Explain the functioning of Encoder-Decoder architectures and their utility in sequence modeling tasks
- 3.2 Analyze the attention mechanism and the paradigm shift in language models
- 3.3 Understand the Transformer architecture and its impact on modern NLP model development
- 3.4 Apply bidirectional pre-trained models such as BERT in diverse NLP tasks
- 3.5 Apply unidirectional pre-trained models such as GPT for text generation tasks
- 3.6 Evaluate language model performance using classical, modern metrics and benchmarks (Precision, Recall, F1-score, BLEU, ROUGE, GLUE, SuperGLUE)

**Topics Covered:**

- 3.1 Attention mechanism and self-attention foundations
- 3.2 Encoder-Decoder architectures and sequence-to-sequence modeling
- 3.3 Transformer architecture: multi-head attention, positional encodings, layer normalization
- 3.4 Pre-trained language models and transfer learning paradigm
- 3.5 BERT family: bidirectional representations and fine-tuning strategies
- 3.6 Classification and Named Entity Recognition (NER) with transformers
- 3.7 Sampling strategies for text generation (greedy, beam search, top-k, nucleus sampling)
- 3.8 Evaluation metrics and performance benchmarking
- 3.9 Hallucinations in language models: understanding and mitigation

**Key Concepts:** Self-attention mechanisms, positional information, transformer scalability, contextual representations, pre-training objectives, evaluation frameworks, generative artifacts

**Practical Skills:** Transformer implementation, attention visualization, model fine-tuning, evaluation metric computation, benchmark performance analysis, hallucination detection

---

### **Module 4: State-of-the-Art Models**

**Specific Learning Objectives:**

- 4.1 Understand the general functioning of Large Language Models (LLMs) and their application to real-world problems using pre-trained models
- 4.2 Design and implement Retrieval-Augmented Generation (RAG) systems using embedded vectors and vector databases to integrate quantized LLMs with external knowledge sources
- 4.3 Utilize vector databases to store and retrieve embedded document representations within RAG systems
- 4.4 Analyze ethical, social, and security risks associated with language model usage in different real-world contexts

**Topics Covered:**

- 4.1 Large Language Models (LLMs): architecture, scaling laws, and practical applications
- 4.2 Fine-tuning approaches: full fine-tuning, parameter-efficient methods (LoRA, BitFit, adapters)
- 4.3 Efficiency and real-world applications: model quantization, distillation, and optimization
- 4.4 Vector databases: architecture, similarity search, and scalable retrieval
- 4.5 Retrieval-Augmented Generation (RAG): integration patterns, knowledge source management
- 4.6 Ethical implications of LLMs: fairness, transparency, accountability
- 4.7 Bias detection and toxicity mitigation in language models

**Key Concepts:** Model scaling, parameter efficiency, knowledge integration, vector similarity, ethical AI, responsible deployment, safety considerations

**Practical Skills:** LLM fine-tuning and adaptation, RAG system design, vector database management, bias and fairness evaluation, ethical assessment frameworks, production deployment

---

## Repository Structure

```
NLP_Public/
├── README.md                                              # This file
├── Module_01_Corpus_and_Text_Processing/
│   ├── NLP_Week_1_Regex_Tokenization_Review.ipynb
│   ├── notebooks/
│   │   ├── text_preprocessing.ipynb
│   │   ├── tokenization_normalization.ipynb
│   │   ├── regex_patterns.ipynb
│   │   ├── document_term_matrix.ipynb
│   │   └── tfidf_analysis.ipynb
│   ├── exercises/
│   └── resources/
├── Module_02_Embeddings_and_Neural_Networks/
│   ├── notebooks/
│   │   ├── word_embeddings_fundamentals.ipynb
│   │   ├── word2vec_implementation.ipynb
│   │   ├── rnn_basics.ipynb
│   │   └── lstm_architecture.ipynb
│   ├── exercises/
│   └── resources/
├── Module_03_Transformers/
│   ├── notebooks/
│   │   ├── attention_mechanism.ipynb
│   │   ├── encoder_decoder_architecture.ipynb
│   │   ├── transformer_architecture.ipynb
│   │   ├── bert_applications.ipynb
│   │   ├── gpt_text_generation.ipynb
│   │   ├── evaluation_metrics.ipynb
│   │   ├── sampling_strategies.ipynb
│   │   └── hallucinations_analysis.ipynb
│   ├── exercises/
│   └── resources/
├── Module_04_StateOfTheArt_Models/
│   ├── notebooks/
│   │   ├── large_language_models.ipynb
│   │   ├── fine_tuning_strategies.ipynb
│   │   ├── model_efficiency.ipynb
│   │   ├── vector_databases.ipynb
│   │   ├── rag_systems.ipynb
│   │   ├── ethical_considerations.ipynb
│   │   └── bias_toxicity_mitigation.ipynb
│   ├── exercises/
│   └── resources/
├── utils/
│   ├── preprocessing.py
│   ├── evaluation.py
│   ├── visualization.py
│   └── rag_utilities.py
├── datasets/
│   ├── README.md
│   └── data_sources.md
├── requirements.txt
└── LICENSE
```

---

## Prerequisites

### Academic & Conceptual Background

- **Linear Algebra:** Matrix operations, eigenvalues, vector spaces, tensor operations
- **Calculus:** Differentiation, gradients, chain rule, optimization methods
- **Probability & Statistics:** Probability distributions, Bayes' theorem, hypothesis testing, inference
- **Machine Learning Fundamentals:** Supervised learning, classification, regression, evaluation metrics
- **Neural Networks Basics:** Forward propagation, backpropagation, activation functions, loss functions

### Technical Requirements

- **Python 3.8+** with proficiency in:
  - Object-oriented programming (classes, inheritance, polymorphism)
  - Functional programming paradigms
  - List comprehensions and generator expressions
  - Context managers and decorators

- **Essential Libraries:**
  - **NumPy:** Numerical computing and array operations
  - **Pandas:** Data manipulation and analysis
  - **Scikit-learn:** Classical ML algorithms and evaluation
  - **PyTorch:** Deep learning framework (primary for this course)
  - **Transformers (HuggingFace):** Pre-trained models and utilities
  - **NLTK & spaCy:** NLP tools and linguistics

- **Development Tools:**
  - Git for version control
  - Jupyter Notebook/Lab for interactive development
  - Terminal/command-line proficiency
  - Text editor or IDE (VS Code, PyCharm, etc.)

### Hardware Recommendations

- **Recommended:** GPU with CUDA support (NVIDIA) or Metal (Apple Silicon)
  - Minimum 4GB VRAM for most exercises
  - 8GB+ VRAM for transformer fine-tuning
- **Fallback:** CPU-only computation supported but significantly slower
- **Storage:** Minimum 10GB free space for datasets and model weights

---

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/lfvvillanueva/NLP_Public.git
cd NLP_Public
```

### 2. Create Virtual Environment

```bash
python -m venv nlp_env
source nlp_env/bin/activate  # On Windows: nlp_env\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Verify Installation

```bash
python -c "import torch; import transformers; print('Setup successful!')"
```

---

## Key Technologies & Libraries

| Technology                 | Purpose                      | Version |
| -------------------------- | ---------------------------- | ------- |
| Python                     | Primary programming language | 3.8+    |
| PyTorch                    | Deep learning framework      | 2.0+    |
| Transformers (HuggingFace) | Pre-trained models           | 4.30+   |
| NumPy                      | Numerical computing          | 1.24+   |
| Pandas                     | Data manipulation            | 2.0+    |
| Scikit-learn               | ML utilities                 | 1.3+    |
| NLTK                       | NLP toolkit                  | 3.8+    |
| Matplotlib/Seaborn         | Data visualization           | Latest  |

---

## How to Use This Repository

1. **Sequential Learning:** Progress through Modules 1-4 in order, building foundational knowledge progressively
2. **Hands-On Practice:** Complete all notebook implementations and replicate code examples
3. **Concept Mastery:** Review the specific learning objectives for each module to ensure comprehension
4. **Exercise Completion:** Work through all exercises systematically, testing your understanding
5. **Integration:** Apply knowledge from previous modules in subsequent modules
6. **Documentation:** Maintain detailed notes on concepts, implementations, and challenges

### Running a Notebook

```bash
jupyter lab Module_01_Corpus_and_Text_Processing/notebooks/text_preprocessing.ipynb
```

### Module Progression

- **Module 1** provides essential foundations for all subsequent work
- **Module 2** builds on Module 1 to introduce learned representations
- **Module 3** synthesizes Modules 1-2 within modern transformer architectures
- **Module 4** applies all previous knowledge to state-of-the-art systems

---

## Practical Projects & Applications

### Module 1: Text Processing Pipeline

- Build a complete corpus preprocessing pipeline
- Implement regex patterns for domain-specific extraction
- Compare DTM vs. TF-IDF representations
- Analyze corpus statistics and distributions

### Module 2: Word Embeddings & Sequence Modeling

- Generate word embeddings using Word2Vec
- Implement sentiment analysis using LSTM
- Compare different embedding approaches
- Analyze semantic relationships in embedding space

### Module 3: Transformer Fine-Tuning

- Fine-tune BERT for text classification tasks
- Implement GPT-based text generation
- Evaluate models using GLUE benchmarks
- Analyze attention patterns and model behavior
- Identify and document hallucinations

### Module 4: Retrieval-Augmented Generation System

- Design a RAG pipeline with external knowledge integration
- Implement vector database operations
- Fine-tune an LLM for specific domains
- Conduct comprehensive ethical and bias assessment
- Deploy as a functional system with API interface

---

---

## Learning Resources

### Essential Textbooks & References

- **"Speech and Language Processing"** by Jurafsky & Martin (3rd Edition)
  - Primary reference for Modules 1-2
  - Available at: https://web.stanford.edu/~jurafsky/slp3/

- **"Deep Learning"** by Goodfellow, Bengio, and Courville
  - Essential for understanding neural network foundations
- **"Attention Is All You Need"** (Vaswani et al., 2017)
  - Foundational paper for Module 3
  - Available at: https://arxiv.org/abs/1706.03762

- **"BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding"** (Devlin et al., 2018)
  - Key reference for Module 3 BERT implementations
- **"Language Models are Unsupervised Multitask Learners"** (Radford et al., 2019)
  - GPT-2 foundations for Module 4

### Online Courses & Documentation

- **HuggingFace Course:** https://huggingface.co/course
  - Practical implementations and model access
- **Stanford CS224N:** NLP with Deep Learning
  - Lecture videos and materials
- **Papers with Code (NLP Section):** https://paperswithcode.com/area/natural-language-processing
  - Implementation references and benchmarks
- **ArXiv:** https://arxiv.org/
  - Latest research papers and preprints

### Practical Tools & Libraries

- **Transformers Library (HuggingFace):** Model implementations and utilities
- **NLTK:** Classical NLP tools for Module 1
- **spaCy:** Advanced NLP pipeline and linguistic annotations
- **PyTorch:** Deep learning framework for Modules 2-4
- **Scikit-learn:** ML utilities for baseline models and evaluation
- **Weights & Biases:** Experiment tracking and visualization

### Vector Databases (Module 4)

- **Pinecone:** Managed vector database service
- **Weaviate:** Open-source vector search
- **FAISS (Facebook AI Similarity Search):** Efficient similarity search library
- **Milvus:** Open-source vector database platform

### Evaluation & Benchmarking

- **GLUE & SuperGLUE Benchmarks:** https://gluebenchmark.com/
- **Papers with Code Leaderboards:** Track state-of-the-art performance

---

## Best Practices & Standards

### Code Quality

- Follow PEP 8 style guidelines rigorously
- Implement comprehensive docstrings (NumPy/Google style)
- Use type hints for enhanced code clarity
- Maintain consistent naming conventions

### Reproducibility

- Pin all package versions in `requirements.txt`
- Set random seeds for all stochastic processes
- Document data preprocessing steps meticulously
- Include hardware specifications in reports

### Documentation

- Create README files for each week's content
- Comment complex algorithmic logic thoroughly
- Include output examples in notebook markdown cells
- Provide mathematical notation for theoretical concepts

---

## Assessment & Evaluation

### Module-Specific Assessment

**Module 1: Linguistic Corpus and Text Processing**

- Practical exercises: Text preprocessing pipelines and corpus construction
- Assessment: Implementation of complete preprocessing workflows
- Deliverables: Cleaned corpus and performance analysis

**Module 2: Embedded Representations and Neural Networks**

- Practical exercises: Embedding generation and RNN/LSTM implementation
- Assessment: Model performance on sequence tasks
- Deliverables: Trained embeddings and sequence models

**Module 3: Transformers**

- Practical exercises: Fine-tuning models, attention analysis, evaluation metrics
- Assessment: Benchmark performance on standard NLP tasks (GLUE, SuperGLUE)
- Deliverables: Fine-tuned models and comprehensive evaluation reports

**Module 4: State-of-the-Art Models**

- Practical exercises: RAG system development, model fine-tuning, ethical analysis
- Assessment: Production-ready system implementation
- Deliverables: Complete RAG pipeline with ethical assessment

### Overall Evaluation Criteria

- **Conceptual Understanding:** Mastery of theoretical foundations for each module (25%)
- **Implementation Skills:** Code quality, correctness, and efficiency (25%)
- **Practical Applications:** Real-world problem solving and analysis (25%)
- **Documentation and Presentation:** Clear communication of methods and results (15%)
- **Ethical Responsibility:** Consideration of bias, fairness, and safety implications (10%)

---

## Ethical Considerations

This course emphasizes responsible AI development:

- **Bias Evaluation:** Assess models for demographic and representational biases
- **Fairness:** Consider impact on marginalized communities
- **Transparency:** Document model limitations and decision boundaries
- **Privacy:** Handle sensitive textual data with appropriate safeguards
- **Environmental Impact:** Consider computational costs and carbon footprint

---

## Contributing & Feedback

This repository is maintained as a personal learning artifact. For suggestions or corrections:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add detailed explanation'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request with comprehensive description

---

## Contact & Support

- **Institution:** Instituto Tecnológico y de Estudios Superiores de Monterrey (ITESM)
- **Program:** Master's in Applied Artificial Intelligence
- **Author:** Luis Fernando Villanueva
- **Repository:** https://github.com/lfvvillanueva/NLP_Public

For questions or clarifications regarding course content, consult:

- Course instructor and teaching assistants
- Institutional learning management system
- Peer study groups and collaborative forums

---

## License

This repository is licensed under the **MIT License**. See the LICENSE file for detailed terms and conditions. Educational use is encouraged; commercial applications require explicit attribution and compliance with institutional policies.

---

## Acknowledgments

- ITESM faculty and instructors for comprehensive pedagogical guidance
- Open-source community for exceptional tools and infrastructure:
  - PyTorch and the Facebook AI Research team
  - HuggingFace for Transformers library and model hub
  - Scikit-learn contributors
  - NLTK and spaCy development teams
- Authors of foundational papers and textbooks referenced throughout
- Peer learners and colleagues for collaborative discussions and feedback
- Original dataset contributors and curators

---

## Program Information: ITESM Master's in Applied Artificial Intelligence

This course is part of the **Maestría en Inteligencia Artificial Aplicada** (Master's Program in Applied Artificial Intelligence) at Instituto Tecnológico y de Estudios Superiores de Monterrey (ITESM).

### Institution Details

- **University:** Instituto Tecnológico y de Estudios Superiores de Monterrey (ITESM)
- **Program:** Maestría en Inteligencia Artificial Aplicada
- **Level:** Postgraduate (Master's degree)
- **Language of Instruction:** Spanish
- **Course Language:** English (C2 level required)
- **Accreditation:** ITESM and recognized international standards

### Program Focus Areas

The Master's program integrates core concepts across:

- Machine Learning and Deep Learning
- Natural Language Processing
- Computer Vision
- Reinforcement Learning
- Applied AI Systems and Deployment

### Academic Excellence Standards

This repository adheres to:

- ITESM academic integrity policies
- Industry-standard NLP practices and methodologies
- Ethical AI development guidelines
- Rigorous evaluation frameworks
- Reproducibility and transparency standards

---

**Last Updated:** May 2026  
**Course Status:** In Progress (Module 1 - 4)  
**Maintained by:** Luis Fernando Villanueva

---

## Quick Module Reference

| Module | Focus                                       | Key Technologies                    | Deliverables                           |
| ------ | ------------------------------------------- | ----------------------------------- | -------------------------------------- |
| **1**  | Text preprocessing and corpus construction  | Regex, Tokenization, DTM, TF-IDF    | Cleaned corpus, preprocessing pipeline |
| **2**  | Learned representations and sequence models | Word2Vec, RNN, LSTM                 | Trained embeddings, working models     |
| **3**  | Transformer architectures and fine-tuning   | BERT, GPT, Attention, Transformers  | Fine-tuned models, evaluation metrics  |
| **4**  | LLMs and RAG systems                        | LLMs, RAG, Vector databases, Ethics | Production system, ethical assessment  |

---

> **Note:** This repository serves as a comprehensive study artifact for postgraduate-level Natural Language Processing education within the Master's Program in Applied Artificial Intelligence at ITESM. It synthesizes theoretical knowledge with practical implementation, emphasizing both depth of understanding and pragmatic application of cutting-edge techniques in the field of NLP.
