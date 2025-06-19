# 📦 ModelSet AST Dataset

This repository contains the processed version of the ModelSet dataset, where **5,432 Ecore models** and **3,085 XMI (UML) models**—filtered for English language and appropriate structural content—have been transformed into a structured **JSON Abstract Syntax Tree (AST)** using a predefined, unified schema. All AST elements follow consistent naming conventions: **classes use PascalCase**, while **attributes and methods use camelCase**.


- 🔗 [Original Dataset Website](https://modelset.github.io/)
- 💻 [ModelSet GitHub Repository](https://github.com/modelset/modelset-dataset)

The original ModelSet comprises:
- **5,460 Ecore models** collected from GitHub
- **5,120 UML models** retrieved from GenMyModel repositories

---

## 📐 Dataset Description

Each AST representation faithfully captures the **structure and semantics** of the original model. This format is designed to support a variety of downstream tasks, including:

- Model understanding and analysis  
- Automatic classification  
- Model-to-model transformation  
- Machine learning and pattern extraction  

In addition, each entry includes rich metadata labels:
- `category` — application domain  
- `purpose` — intended use  
- `notation` — modeling language  
- `tool` — modeling environment used  

---

## 📁 Repository Structure

- `data/` — JSON AST files for each model  
- `schema/` — Definition of the unified JSON schema  
- `scripts/` — Tools used for processing and transformation  

---

## 📄 License and Citation

If you use this resource in your work, please cite the original ModelSet dataset and this repository accordingly.

---

Feel free to open an issue or pull request if you'd like to contribute or need help using the dataset.
