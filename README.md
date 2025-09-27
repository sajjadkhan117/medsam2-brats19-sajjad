# Inference and Evaluation of MedSAM-2 on Brain Tumor Segmentation (BRATS 2019)

## Overview

This project evaluates the **MedSAM-2** architecture for brain tumor segmentation using the BRATS 2019 dataset. MedSAM-2 is an advanced deep learning model based on the Segment Anything Model (SAM), specifically adapted for medical image segmentation tasks.

## Project Details

- **Author:** Sajjad Khan
- **Dataset:** BRATS 2019 (Brain Tumor Segmentation Challenge)
- **Model:** MedSAM-2 (Segment Anything Model for Medical Images)
- **Task:** 3D Brain Tumor Segmentation from MRI Scans
- **Evaluation Metric:** Dice Score

## Technologies Used

- **Deep Learning Framework:** PyTorch
- **Development Environment:** Google Colab
- **Programming Language:** Python
- **Data Processing:** NumPy, Matplotlib, PIL, nibabel
- **Model Architecture:** MedSAM-2
- **Dataset:** BRATS 2019 (HGG and LGG patients)

## Project Structure
├── notebooks/
│ └── MedSAM2_BRATS19_Inference.ipynb # Main inference notebook
├── data/
│ └── brats2019/ # BRATS 2019 dataset
├── checkpoints/
│ └── MedSAM2_latest.pt # Pretrained model weights
└── README.md

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sajjadkhan117/medsam2-brats19-sajjad.git
   cd medsam2-brats19-sajjad
   ```

2. Install dependencies:
   ```bash
   pip install torch torchvision torchaudio
   pip install nibabel matplotlib pillow numpy
   ```

3. Download the BRATS 2019 dataset and place it in the `data/` directory.

4. Download the MedSAM-2 pretrained weights and place them in the `checkpoints/` directory.

## Usage

1. Open the main notebook: `MedSAM2_BRATS19_Inference.ipynb`
2. Follow the step-by-step instructions in the notebook.
3. Run the inference code to evaluate MedSAM-2 on your dataset.

## Results

- **Average Dice Score:** [Your result here]
- **Dataset:** BRATS 2019 HGG patients
- **Model Performance:** [Brief analysis of strengths and limitations]

## Key Features

- **Batch Inference:** Process multiple patients and slices efficiently
- **Visualization:** Compare ground truth masks with MedSAM-2 predictions
- **Evaluation:** Comprehensive Dice score analysis
- **Scalability:** Easy to extend to other medical imaging datasets

## References

- [MedSAM-2 GitHub Repository](https://github.com/bowang-lab/MedSAM2)
- [BRATS 2019 Dataset](https://www.kaggle.com/datasets/awsaf49/brats-2019-data)
- [Segment Anything Model (SAM)](https://github.com/facebookresearch/segment-anything)

## License

This project is for educational and research purposes.

## Contact

- **Author:** Sajjad Khan
- **GitHub:** [@sajjadkhan117](https://github.com/sajjadkhan117)

---

## Acknowledgments

Special thanks to the MedSAM-2 team and the BRATS 2019 organizers for providing the dataset and model.
