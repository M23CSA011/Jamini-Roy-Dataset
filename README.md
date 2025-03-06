Here is the README file in Markdown code format that you can use:  

```markdown
# Jamini Roy Dataset Documentation

## Dataset Overview
This dataset comprises images related to the famous Indian artist Jamini Roy. It consists of original images alongside AI-generated images created using fine-tuned Stable Diffusion 3, combined with IPAdapter and ControlNet. The dataset is structured into different categories based on the generation method and noise levels.

### Dataset Repository
GitHub Repository: [Jamini Roy Dataset](https://github.com/M23CSA011/Jamini-Roy-Dataset)

## Data Structure
The dataset is organized into three main categories:

1. **0_real**: Contains the original 770 images of Jamini Roy paintings.
   - Directory: [0_real](https://github.com/M23CSA011/Jamini-Roy-Dataset/tree/master/0_real)

2. **ControlNet**: Images generated using a fine-tuned Stable Diffusion 3 model combined with IPAdapter and ControlNet.
   - Directory: [ControlNet](https://github.com/M23CSA011/Jamini-Roy-Dataset/tree/master/Controlnet)

3. **No_ControlNet**: Images generated using only a fine-tuned Stable Diffusion 3 model without ControlNet.
   - Directory: [No_ControlNet](https://github.com/M23CSA011/Jamini-Roy-Dataset/tree/master/No_ControlNet)

### Noise Levels in Generated Images
Both `ControlNet` and `No_ControlNet` categories contain images generated with varying levels of noise during the image generation process. Each noise category contains **770 images**.

The noise levels are structured as follows:
- **Noise_0.0** (1_fake)  
- **Noise_0.25** (1_fake)  
- **Noise_0.5** (1_fake)  
- **Noise_0.75** (1_fake)  

Each of these subdirectories contains 770 images corresponding to the specified noise level.

## File Naming Convention
Each image file follows a structured naming pattern:
```
Jamini_[ID].jpg
```
Where:
- `[ID]` is a unique identifier for the image

## Dataset Usage Instructions
### Downloading the Dataset
To download the dataset, use the following command:
```bash
git clone https://github.com/M23CSA011/Jamini-Roy-Dataset.git
```
Navigate to the dataset directory:
```bash
cd Jamini-Roy-Dataset
```

### Understanding Data Categories
- Use `0_real/` for original Jamini Roy images.
- Use `ControlNet/` for images generated with Stable Diffusion 3 + IPAdapter + ControlNet.
- Use `No_ControlNet/` for images generated with only Stable Diffusion 3.
- Explore noise variations (`Noise_0.0` to `Noise_0.75`) within `ControlNet/` and `No_ControlNet/`.

### Utilizing the Data for Research
- Compare original images with AI-generated images to analyze style transfer.
- Evaluate the impact of different noise levels on image generation quality.
- Train models to distinguish real vs. AI-generated images.

## Citation
If you use this dataset in your research, please cite:
```bibtex
@dataset{jamini_roy_dataset,
  author = {Kushal Agrawal},
  title = {Jamini Roy Dataset: Real and AI-Generated Images},
  year = {2025},
  publisher = {IEEE DataPort},
  url = {https://github.com/M23CSA011/Jamini-Roy-Dataset}
}
```
