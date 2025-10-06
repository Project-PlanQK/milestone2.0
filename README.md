# Milestone 2.0

This milestone focuses on the development and testing of a local framework for the PlanQK Assistant project. It includes scripts and notebooks for experimenting with the LlamaIndex framework and related tools.

## Contents

- **llamaindex_v3_2.py**: Python script for implementing and testing LlamaIndex functionalities.
- **llamaindex_v3_EBM2.py**: Extended version of the LlamaIndex script with additional features.
- **llamaindex.ipynb**: Jupyter notebook for interactive development and testing of LlamaIndex.
- **nomic.ipynb**: Jupyter notebook for exploring Nomic embeddings and their integration.
- **output/**: Directory containing output files, including processed PlanQK documentation in JSON format.
  - `docs.planqk.de_.json`
  - `docs.planqk.de_quickstart.html.json`
- **README.md**: Documentation for this milestone.

## Purpose

The goal of this milestone is to build and test a local framework for integrating LlamaIndex with PlanQK services. This includes:
- Creating and querying vector stores.
- Experimenting with embeddings and retrieval-augmented generation (RAG).
- Processing and indexing PlanQK documentation.

## Usage

1. **Run Python Scripts**:
   - Use `llamaindex_v3_2.py` or `llamaindex_v3_EBM2.py` to test LlamaIndex functionalities.
   - Ensure required dependencies are installed.

2. **Explore Notebooks**:
   - Open `llamaindex.ipynb` or `nomic.ipynb` in Jupyter Notebook for interactive testing.

3. **Process Documentation**:
   - Review processed PlanQK documentation in the `output/` directory.

## Notes

- Ensure Python 3.11+ is installed.
- Install dependencies as specified in the scripts or notebooks.
- Use the `.env` file to configure API keys for OpenAI and other services.

---
**Built for the PlanQK Assistant Project**
