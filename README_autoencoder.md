# 🧬 Gene Expression Classifier with Autoencoder

A deep learning project that simulates realistic gene expression data and classifies samples into disease categories using an autoencoder + classifier architecture.


🔄 Future Work: Expanding to Contrastive Autoencoders
To enhance the representation learning capability of this model, future iterations will explore contrastive autoencoders. While the current autoencoder effectively compresses gene expression data into a lower-dimensional space, contrastive learning introduces a powerful self-supervised signal that:

Encourages robust and discriminative embeddings,

Improves generalization under noise or batch effects,

Aligns latent space structure with biologically meaningful similarity (e.g., disease subtype proximity).

This is particularly relevant in gene expression analysis, where relationships between samples are subtle and high-dimensional. By integrating contrastive loss with reconstruction objectives, we aim to retain interpretability while learning semantically richer latent features useful for downstream tasks like classification or clustering.

...

Developed with ❤️ by [Allan Binu](https://github.com/Allan-Binu)
