# Elastic Deep Autoencoder for Text Embedding Clustering by an Improved Graph Regularization
In this code, a deep autoencoder with an adapted elastic loss for text embedding clustering (EDA-TEC) is proposed. The elastic loss is a combination of the Frobenius norm and , L2,1 -norm to consider both types of noises. Additionally, to maintain the high-dimensional data geometric structure, a modified graph regularization term based on the weighted cosine similarity measure is used. EDA-TEC also improves clustering results by considering the sparsity regularization of the manifold representation data. In this jointly end-to-end deep learning model, better representation and data clustering results are achieved with high accuracy on common datasets compared to existing methods.

## Citation

If you find this implementation or code useful in your work, please consider citing our paper:

```bibtex
@article{DaneshfarSoleymanbaigiNafisiYamini2023,
  title = {Elastic Deep Autoencoder for Text Embedding Clustering by an Improved Graph Regularization},
  author = {Fatemeh Daneshfar, Sayvan Soleymanbaigi, Ali Nafisi, Pedram Yamini},
  journal = {Expert Systems with Applications},
  year = {2023},
  pages = {121780},
  url = {https://www.sciencedirect.com/science/article/abs/pii/S0957417423022820},
}
