# PestPlantDiseaseID-Taiwan
## Introduction

This project involves a Jupyter notebook for detecting plant diseases using a deep learning model. The notebook leverages a pre-trained Faster R-CNN model fine-tuned on a dataset of images of common plant diseases and pests in Taiwan. 

## Features

- **Data Preprocessing**: Steps to clean and prepare image datasets for training.
- **Model Training**: Fine-tuning a pre-trained Faster R-CNN model with custom datasets.
- **Disease Detection**: Real-time identification of pests and plant diseases from input images.
- **Evaluation**: Assess the model's performance and accuracy.

## Getting Started

### Prerequisites

Ensure you have the following installed:
- Python 3.8 or higher
- Jupyter Notebook
- Required Python libraries (listed in `requirements.txt`)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/plant_disease_detection.git
    ```

2. Navigate to the project directory:
    ```sh
    cd plant_disease_detection
    ```

3. Create and activate a virtual environment (optional but recommended):
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

4. Launch Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

5. Open the notebook `Plant_Disease_Detection.ipynb` and follow the instructions within.

### Notebook Structure

1. **Introduction**: Overview of the project and objectives.
2. **Data Preprocessing**: Steps to load and preprocess the dataset.
3. **Model Training**: Code to fine-tune the Faster R-CNN model.
4. **Disease Detection**: Using the trained model to detect diseases in new images.
5. **Evaluation**: Assessing the model's performance.

### Dataset

The dataset should be organized as follows:
```
data/
├── raw/
│   ├── aphid/
│   │   ├── image1.jpg
│   │   ├── image2.jpg
│   │   └── ...
│   ├── leafworm/
│   │   ├── image1.jpg
│   │   ├── image2.jpg
│   │   └── ...
│   └── ...
```

### Usage

1. **Data Preparation**:
    - Place your training images in the `data/raw` directory.
    - Follow the notebook steps to preprocess the data.

2. **Model Training**:
    - Run the cells in the notebook to train the model using the prepared dataset.

3. **Disease Detection**:
    - Use the notebook cells to detect diseases in new images.

### Results and Evaluation

- The notebook includes sections for evaluating the model's performance and visualizing the results.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the Taoyuan District Agricultural Research and Extension Station for providing the dataset.
- Inspired by various open-source projects and research papers on plant disease detection.
