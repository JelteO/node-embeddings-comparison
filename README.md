# Node Embeddings Comparison: Node2Vec, GraphSAGE, and GAT

This repository contains the code and experiments for our research paper:

**"A Comparative Study of Node2Vec, GraphSAGE, and GAT in Network Science"**  
by **Jelte Oldenhof** and **Burak Ağaçhan**, LIACS, Leiden University.

---

## Overview

We compare three popular embedding techniques—**Node2Vec**, **GraphSAGE**, and **Graph Attention Networks (GAT)**—for tasks such as **node classification** and **link prediction** on various datasets.

---

## 📂 Datasets

Please download the following `.mat` files and organize them in the `Datasets/` directory as shown below before running the experiments:

Datasets/
├── BlogCatalog/
│   └── blogcatalog.mat
├── PPI/
│   └── PPI.mat
└── Wikipedia/
└── POS.mat


1. **Wikipedia Co-occurrence Graph**  
   - **File**: `POS.mat`  
   - **Folder**: `Datasets/Wikipedia/`  
   - **Description**: A word co-occurrence network where nodes represent words and edges represent co-occurrences within a context window.  
   - **Download Link**: [Wikipedia Dataset](https://github.com/allenhaozhu/REFINE/tree/main/data)

2. **Protein-Protein Interaction (PPI) Network**  
   - **File**: `PPI.mat`  
   - **Folder**: `Datasets/PPI/`  
   - **Description**: A biological network where nodes represent proteins and edges represent interactions between them.  
   - **Download Link**: [PPI Dataset](http://thebiogrid.org/download.php)

3. **BlogCatalog Social Network**  
   - **File**: `blogcatalog.mat`  
   - **Folder**: `Datasets/BlogCatalog/`  
   - **Description**: A social network graph where nodes represent bloggers and edges represent interactions.  
   - **Download Link**: [BlogCatalog Dataset](https://datasets.syr.edu/datasets/BlogCatalog3.html)

---

**Instructions**:  
- Create the following subfolders within the `Datasets/` directory: `BlogCatalog/`, `PPI/`, and `Wikipedia/`.  
- Place the respective `.mat` files in their corresponding subfolders as shown above.  


## Citation

If you use this code, please cite our paper:

```bibtex
@inproceedings{oldenhof2024comparative,
  title={A Comparative Study of Node2Vec, GraphSAGE, and GAT in Network Science},
  author={Jelte Oldenhof and Burak Ağaçhan},
  year={2024},
  booktitle={Social Network Analysis for Computer Scientists Course 2024}
}
```

## Contact

Feel free to reach out for questions or collaboration:

- **Jelte Oldenhof**: [LinkedIn](https://www.linkedin.com/in/jelte-oldenhof/)
- **Burak Ağaçhan**: [LinkedIn](https://www.linkedin.com/in/cihatburak/)

Let’s collaborate and turn data into impactful solutions!