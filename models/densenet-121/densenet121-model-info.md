# DenseNet-121 Model

## Model Specifications

- **Architecture:** DenseNet-121
- **Pretrained on:** ImageNet
- **Total Parameters:** 7.6M
- **Dataset Split:** 80% Training / 20% Testing

## Performance

- **Accuracy:** TBD% (EuroSAT dataset)
- **Training Status:** In Progress/Completed
- **Training Epochs:** 35

## Model File

- **Saved Location:** Google Drive (too large for GitHub)
- **Download Link:** [DenseNet-121 Weights](https://drive.google.com/file/d/1VsgdHVt8kFw2WLxvnSb14tXa3MkVO5HA/view?usp=sharing)
- **File Size:** 88MB

## Model Architecture Details

- **Backbone:** DenseNet-121 with ImageNet pretraining
- **Classifier Head:** Custom 3-layer classifier with dropout and batch normalization
- **Input Size:** 224×224×3 (RGB images)
- **Output Classes:** 10 (EuroSAT land use categories)

## Training Configuration

- **Optimizer:** AdamW with weight decay
- **Learning Rate:** 0.0008 (optimized for DenseNet)
- **Loss Function:** CrossEntropyLoss with label smoothing
- **Data Augmentation:** Horizontal/vertical flips, rotation, color jitter

## Usage

This model is trained for satellite image classification on the EuroSAT dataset and can be used for land use and land cover classification tasks.
