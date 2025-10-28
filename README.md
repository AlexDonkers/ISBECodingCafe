# 🧠 LLMs meet Knowledge Graphs: Exploring RDF graphs using Neuro-Symbolic AI

**TU/e Built Environment Coding Cafe**

**Alex Donkers**


Quick links
   → [Gemini API key](https://aistudio.google.com/app/api-keys)
   → [Notebook](https://colab.research.google.com/drive/1_Z2fGH9IzpnvosbnmclMQuU0T9b3oy0q)



This repository contains all materials for the **"Neuro-Symbolic GraphRAG"** workshop — a hands-on introduction to combining **RDF knowledge graphs**, **ontologies**, and **Large Language Models (LLMs)** for reasoning over structured data.

Participants will learn how to go from **raw regulation text** to a **queryable, explainable knowledge system**, powered by **FireBIM ontologies** and **Gemini 2.0**.

---

## 🎯 Learning Goals

By the end of this workshop, you will be able to:
- Load and explore RDF data in Python.
- Understand and query ontologies with SPARQL.
- Use LLMs to classify text and enrich knowledge graphs.
- Translate natural language questions into SPARQL queries.
- Build a neuro-symbolic **GraphRAG pipeline** that connects LLM reasoning to symbolic RDF structures.

---

## 🧩 Workshop Modules

| Module | Topic | Description |
|--------|-------|-------------|
| **1. GraphDB & RDF Exploration** | *Understanding graphs* | Explore RDF data using `rdflib` and visualize it interactively with PyVis. |
| **2. RDF & OWL Ontologies** | *Reasoning over structure* | Load both the instance graph and the FireBIM Regulation Ontology (FRO) to understand how semantics and relationships are defined. |
| **3. Large Language Models (LLMs)** | *Neural meets symbolic* | Use **Gemini 2.0 Flash** to classify regulation texts into high-level themes and enrich the RDF graph with semantic triples. |
| **4. GraphRAG & Natural Language Querying** | *Neuro-symbolic reasoning* | Generate SPARQL queries from plain English questions and summarize results using an LLM. |

---

## 🧱 Dataset

We use a small curated dataset of **digital building regulations** in Turtle (`.ttl`) format:
- `fro.ttl` – The **FireBIM Regulation Ontology**, defining classes and relationships.
- `DutchFireRegulations.ttl` – Instance data containing building regulation clauses.

---

## 🚀 Getting Started

1. **Generate a Gemini API key**
   → [Google AI Studio](https://aistudio.google.com/app/api-keys)

3. **Open the notebook in Google Colab**  
   → [Notebook](https://colab.research.google.com/drive/1_Z2fGH9IzpnvosbnmclMQuU0T9b3oy0q)

4. **Run all cells sequentially**  
   Each module builds on the previous one — make sure you complete them in order.

5. **Follow along the presentation (20 min)**  
   The slides summarize the theory and connect to each notebook exercise.

---

## 🧠 Mini Challenges

Each notebook includes *hands-on challenges* such as:
- Writing SPARQL queries to explore predicates and classes.
- Linking clauses to ontology concepts.
- Using Gemini to classify rules by topic.
- Translating natural language to SPARQL queries.
- Summarizing query results with Gemini.

Try them all to deepen your understanding!

---

## 🧩 Tech Stack

- 🧮 **RDF / SPARQL:** `rdflib`
- 🔍 **Visualization:** `networkx`, `pyvis`
- 🤖 **LLMs:** `Gemini 2.0 Flash API`
- 🧱 **Ontology:** FireBIM FRO and FBO
- 📓 **Environment:** Google Colab (no local GraphDB required)

---

## 🧠 About the Approach

This workshop demonstrates **neuro-symbolic AI** — combining:
- **Symbolic reasoning:** via RDF, OWL, and SPARQL  
- **Neural reasoning:** via Gemini’s natural language understanding  

Together, they enable **GraphRAG** (Graph Retrieval-Augmented Generation):  
> Natural language → LLM → SPARQL → Graph → Reasoned answer.

---

## 🧑‍🏫 Author

**Alex Donkers**  
Built as part of the *FireBIM* research initiative on digital building regulations.  
📧 [Personal research page](https://research.tue.nl/nl/persons/alex-ja-donkers/)  
🌐 [LinkedIn](https://www.linkedin.com/in/alexdonkers/)

---

## 📜 License

Reuse of the material in this library is limited, and can only happen after personal agreement from the author.

---

### ⭐ If you use or adapt this workshop
Please cite it or link back to the GitHub repository to support open, explainable AI for the built environment.
