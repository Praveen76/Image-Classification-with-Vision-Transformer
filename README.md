# Image-Classification-with-Vision-Transformer


This repository demonstrates the implementation of the Vision Transformer (ViT) model for image classification, using the CIFAR-100 dataset. The ViT model applies the Transformer architecture, typically used for natural language processing, to image classification by treating images as sequences of patches and using self-attention mechanisms.

## Learning Objectives

By the end of this experiment, you will:
- Understand the Vision Transformer (ViT) model architecture.
- Learn how to create sequences of image patches to feed into the ViT model.
- Perform image classification using the ViT model on the CIFAR-100 dataset.

## Introduction

The Vision Transformer (ViT) model, created by Alexey Dosovitskiy and others, represents a novel approach to image classification. This model adapts the Transformer architecture for use with images by dividing them into patches and processing these patches with self-attention mechanisms. This repository provides a Jupyter Notebook that demonstrates the implementation of ViT on the CIFAR-100 dataset.

### Requirements

- TensorFlow 2.4 or higher
- TensorFlow Addons

You can install the required packages using pip:
```bash
pip install -U tensorflow-addons
```

## Data Description

**CIFAR-100 Dataset:**
- **Training Images**: 50,000 images (500 per class)
- **Testing Images**: 10,000 images (100 per class)
- **Image Size**: 32x32 color images
- **Number of Classes**: 100 fine-grained classes grouped into 20 superclasses.

Each image is labeled with both a "fine" label (specific class) and a "coarse" label (superclass), providing a rich dataset for hierarchical image classification.

## Files

- `ImageClassification_with_VisionTransformer.ipynb`: A Jupyter Notebook containing all the code and documentation necessary to understand and implement the Vision Transformer model for image classification.

## How to Use

1. **Clone the Repository:**
```bash
git clone https://github.com/Praveen76/Image-Classification-with-Vision-Transformer.git
cd Image-Classification-with-Vision-Transformer
```

2. **Open the Jupyter Notebook:**
   - Run Jupyter Notebook in your environment:
   ```bash
   jupyter notebook
   ```
   - Open the `ImageClassification_with_VisionTransformer.ipynb` file to view and run the steps outlined.

3. **Follow the Notebook Instructions:**
   - The notebook is designed to guide you through loading the dataset, preparing the data, configuring the ViT model, and training the model for image classification.

## Contributing

Contributions are welcome! For major changes, please open an issue first to discuss what you would like to change. Ensure to update tests as appropriate.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE.md) file for details.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have suggestions or improvements.


## License

This project is licensed under the [MIT License](LICENSE).

# Issues:
If you encounter any issues or have suggestions for improvement, please open an issue in the Issues section of this repository.

---
# Contact:
The code has been tested on Windows system. It should work well on other distributions but has not yet been tested. In case of any issue with installation or otherwise, please contact me on [Linkedin](https://www.linkedin.com/in/praveen-kumar-anwla-49169266/)

Happy coding!!

---
## **About Me**:
I’m a seasoned Data Scientist and founder of [TowardsMachineLearning.Org](https://towardsmachinelearning.org/). I've worked on various Machine Learning, NLP, and cutting-edge deep learning frameworks to solve numerous business problems.

