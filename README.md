# ForestClassifier-ImageDL

This repository contains an end-to-end pipeline for image classification using a custom Convolutional Neural Network (CNN) and transfer learning. The project includes dataset preprocessing, model training, embedding visualization, and evaluation using state-of-the-art techniques.

## Overview

### Features
- **Custom CNN Model**: A tailored convolutional architecture built from scratch to classify images effectively.
- **Transfer Learning**: Leveraged a pretrained ResNet model as a backbone, fine-tuned with custom linear layers for enhanced performance.
- **Embedding Visualization**: High-dimensional embeddings projected into 2D using t-SNE and UMAP for exploratory data analysis.
- **Logging and Monitoring**: Training and validation metrics tracked with TensorBoard.

## Jupyter Notebook

The project is fully implemented and documented in a Jupyter Notebook. The notebook includes:
- Data preprocessing and augmentation.
- Implementation and training of both custom CNN and transfer learning models.
- Generation and visualization of embeddings using t-SNE and UMAP.
- Performance evaluation with metrics and visual plots.

To explore the project, open the notebook `image_classification.ipynb`.

## Results

### Model Performance
- **Custom CNN**:
  - Training Accuracy: 94.21%
  - Validation Accuracy: 91.12%
  - Test Accuracy: 91.05%
- **Transfer Learning**:
  - Training Accuracy: 100%
  - Validation Accuracy: 100%
  - Test Accuracy: 100%

### Embedding Visualization
The t-SNE and UMAP plots reveal clear clusters corresponding to the target classes, demonstrating the model's ability to learn meaningful feature representations.

## Key Takeaways

- Custom CNNs are powerful for image classification when designed appropriately for the dataset.
- Transfer learning with pretrained models like ResNet improves performance significantly, especially on smaller datasets.
- Visualization techniques like t-SNE and UMAP are invaluable for understanding learned representations.

## Future Work

- Experiment with different backbone models for transfer learning.
- Implement more data augmentation techniques for improved generalization.
- Deploy the trained model as a web application for real-time classification.

## License

This project is licensed under the [GNU General Public License v3.0](LICENSE).

---

Contributions are welcome! Feel free to fork the repository and submit pull requests for enhancements or bug fixes.
