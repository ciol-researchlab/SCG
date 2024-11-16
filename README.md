# Graph Neural Networks in Supply Chain Analytics and Optimization: Concepts, Perspectives, Dataset and Benchmarks
- Authors: Azmine Toushik Wasi, MD Shafikul Islam, Adipto Raihan Akib, and Mahathir Mohammad Bappy
- Affiliation: Shahjalal University of Science and Technology, Sylhet, Bangladesh; Louisiana State University, Louisiana, USA;
Computational Intelligence and Operations Laboratory, Sylhet, Bangladesh
- Dataset: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13652826.svg)](https://doi.org/10.5281/zenodo.13652826)

---

**Abstract:** Graph Neural Networks (GNNs) have recently gained traction in transportation, bioinformatics, language and image processing, but research on their application to supply chain management remains limited. Supply chains are inherently graph-like, making them ideal for GNN methodologies, which can optimize and solve complex problems. 
The barriers include a lack of proper conceptual foundations, familiarity with graph applications in SCM, and real-world benchmark datasets for GNN-based supply chain research. To address this, we discuss and connect supply chains with graph structures for effective GNN application, providing detailed formulations, examples, mathematical definitions, and task guidelines. Additionally, we present a multi-perspective real-world benchmark dataset from a leading FMCG company in Bangladesh, focusing on supply chain planning.
We discuss various supply chain tasks using GNNs and benchmark several state-of-the-art models on homogeneous and heterogeneous graphs across six supply chain analytics tasks. Our analysis shows that GNN-based models consistently outperform statistical ML and other deep learning models by around 10-30\% in regression, 10-30\% in classification and detection tasks, and 15-40\% in anomaly detection tasks on designated metrics.
With this work, we lay the groundwork for solving supply chain problems using GNNs, supported by conceptual discussions, methodological insights, and a comprehensive dataset.

---

The `raw` folder contains the raw datasets. Homogeneous and heterogeneous forms in `raw\homogeneous\` and `raw\heterogeneous\` respectively. Researchers have to choose both modality, and considerations (hoe they want to build the graph) first. The, develop the graphs and formulate problems accordingly.

---


![](./fig/WHAT-M.png)


---

For coding instructions, check `code\coding_directions.md`

---

## Citation:
```
@misc{wasi2024graphneuralnetworkssupply,
      title={Graph Neural Networks in Supply Chain Analytics and Optimization: Concepts, Perspectives, Dataset and Benchmarks}, 
      author={Azmine Toushik Wasi and MD Shafikul Islam and Adipto Raihan Akib and Mahathir Mohammad Bappy},
      year={2024},
      eprint={2411.08550},
      archivePrefix={arXiv},
      primaryClass={cs.LG},
      url={https://arxiv.org/abs/2411.08550}, 
}
```
and, 
```
@dataset{wasi_2024_13652826,
  author       = {Wasi, Azmine Toushik and
                  Islam, MD Shafikul and
                  Akib, Adipto Raihan and
                  Bappy, Mahathir Mohammad},
  title        = {{SCG Dataset from Graph Neural Networks in Supply 
                   Chain Analytics and Optimization: Concepts,
                   Perspectives, Dataset and Benchmarks}},
  month        = sep,
  year         = 2024,
  publisher    = {Zenodo},
  version      = 1,
  doi          = {10.5281/zenodo.13652826},
  url          = {https://doi.org/10.5281/zenodo.13652826}
}
```
