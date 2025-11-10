#  AutoSpecNER: A Dataset and Benchmark for Named Entity Recognition of Vehicle Specifications

**Authors:** Jordan Lee, **Abdirahman Abdullahi**, Filippos Ventirozos  
**Status:** Under Review – *LREC 2025 (Main Track)*  
**Paper:** [“AutoSpecNER: A Dataset and Benchmark for Named Entity Recognition of Vehicle Specifications”](#)  
**Institution(s):** [University / Lab names]  

---

## Overview

**AutoSpecNER** is a collaborative research project submitted to *LREC 2025*, introducing a new expert-annotated dataset and benchmark for **fine-grained Named Entity Recognition (NER)** in the **automotive domain**.

The work investigates how NLP models extract detailed vehicle specifications from **real and AI-generated car listings**, supporting advancements in automotive knowledge bases, hallucination detection, and structured data extraction from unstructured text.

---

## My Contribution

As a **co-author**, I contributed to:
- Developing and testing the **annotation processing scripts**  
- Conducting **inter-observer variability** analysis to assess annotation consistency  
- Supporting **evaluation and experimental review** of model benchmarking  
- Reviewing and editing sections of the final manuscript  

All dataset assets, trained models, and annotation files are maintained by the **lead author** and are **not included** in this repository prior to official publication.

---

## Research Summary

- **Dataset:** 659 real and AI-generated vehicle adverts (Autotrader-sourced)  
- **Entities:** 11,000+ labeled mentions across 15 specification-related categories  
- **Inter-Annotator F1:** 91.5%  
- **Benchmarking:**  
  - Rules-based baselines  
  - Transformer encoders (BERT, RoBERTa, DeBERTa-v3)  
  - Large Language Models (GPT-5, Gemini, Mistral, LLaMA-3)  
- **Best Model:** DeBERTa-v3 (F1 = 90.1%)

---

##  Repository Structure

```text
.
├── README.md                  # this file
└── AutoSpecNER_paper.pdf      # preprint under review (LREC 2025)

