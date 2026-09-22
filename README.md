# Pet Face Classification

Academic computer-vision project exploring image classification with transfer learning using a pretrained ResNet50 model.

> **Project type:** Academic / learning project

## Approach

```text
Pet images
   ↓
Resize / preprocessing / augmentation
   ↓
ResNet50 pretrained on ImageNet
   ↓
Frozen convolutional base
   ↓
Custom classification layers
   ↓
Pet-face class prediction
```

The notebook uses a 224×224×3 input and `preprocess_input`, followed by training/validation monitoring and test-set prediction.

## Techniques

- TensorFlow / Keras
- ResNet50 transfer learning
- Image preprocessing
- Data augmentation
- Frozen pretrained feature extractor
- Dropout
- Categorical cross-entropy
- Adam optimizer
- Training/validation loss and accuracy plots

## Repository contents

```text
Pet_Face-Classification/
├── README.md
├── requirements.txt
└── pet_face_classification.ipynb
```

The repository is intended to preserve the academic notebook workflow. Dataset files and trained weights are not included unless explicitly added later.

## Status

This is coursework/learning work, not a claim of production-grade computer-vision engineering.

## Requirements

Install the packages listed in `requirements.txt`.

## Author

**Shaik Muneeruddin**
