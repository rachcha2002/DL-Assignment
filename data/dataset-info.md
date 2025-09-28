# EuroSAT Dataset

## Dataset Overview
**EuroSAT** is a land use and land cover classification dataset based on Sentinel-2 satellite images covering 13 spectral bands and consisting of 10 classes with a total of 27,000 labeled and geo-referenced images.

## Dataset Details
- **Name**: EuroSAT
- **Source**: [HuggingFace Datasets](https://huggingface.co/datasets/blanchon/EuroSAT_RGB)
- **Total Images**: 27,000
- **Image Format**: RGB (3 channels)
- **Image Resolution**: 64x64 pixels
- **File Format**: JPEG

## Classes (10 total)
1. **AnnualCrop** - Annually harvested crops
2. **Forest** - Forest areas
3. **HerbaceousVegetation** - Herbaceous vegetation
4. **Highway** - Highway infrastructure
5. **Industrial** - Industrial areas
6. **Pasture** - Pasture lands
7. **PermanentCrop** - Permanently cultivated crops
8. **Residential** - Residential areas
9. **River** - River bodies
10. **SeaLake** - Sea and lake water bodies

## Data Split
- **Training**: 80% (21,600 images)
- **Testing**: 20% (5,400 images)
- **Split Method**: Stratified random split to maintain class distribution

## Storage Information
- **Location**: No local storage - downloaded at runtime
- **Download Method**: Automatic download via HuggingFace datasets library
- **Runtime Storage**: Temporary storage in Colab environment during execution
- **Persistent Storage**: Google Drive for model checkpoints and results

## Usage
The dataset is automatically downloaded and processed during notebook execution. No manual download required.

## Citation
If using this dataset, please cite:
```
Helber, P., Bischke, B., Dengel, A., & Borth, D. (2019). 
EuroSAT: A novel dataset and deep learning benchmark for land use and land cover classification. 
IEEE Journal of Selected Topics in Applied Earth Observations and Remote Sensing, 12(7), 2217-2226.
```

## License
The dataset is available under the MIT License.