## DINOInspect: Transformer-Based Bakery Item Visual Clustering

### Project Description
DINOInspect is a computer vision side project that demonstrates unsupervised clustering and exploratory analysis of bakery products (bread, cake, and related items) using self-supervised Vision Transformer features.

This project uses **DINOv2**, a state-of-the-art visual representation model, to extract embeddings from images of bakery products. The embeddings are then clustered with k-means to discover visual groupings, assess labeling quality, and explore feature space structure in a real manufacturing context.

### Key Features
- Uses DINOv2 (Vision Transformer) for deep visual embedding extraction.

- Crops individual bakery items from COCO-annotated images.

- Clusters items using k-means.

- Visualizes clusters in 2D using t-SNE.

- Computes and reports cluster purity using ground-truth labels.

- Demonstrates practical applications of self-supervised learning in food production, inspection, and quality control.
