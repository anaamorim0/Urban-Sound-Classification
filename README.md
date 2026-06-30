# Urban Sound Classification

Project for the **Machine Learning II** course (2025/2026), part of the 3rd year, 1st semester of the Computer Science Bachelor's degree.

The goal of this project is to classify urban sounds (e.g. sirens, car horns, dog barks, street music, among others) using Deep Learning techniques, comparing different neural network architectures.

## Description

This repository explores the task of automatic urban sound classification, going through the typical Deep Learning pipeline applied to audio: from data collection and pre-processing, to feature extraction, model training, and comparative performance evaluation.

## Repository structure

| File | Description |
|---|---|
| `Download&Pre-processing.ipynb` | Downloads the dataset and pre-processes the audio files (cleaning, normalization, and preparing the data for training). |
| `RNN_Training&Evaluation.ipynb` | Training and evaluation of an RNN (Recurrent Neural Network) model. |
| `CRNN_Training&Evaluation.ipynb` | Training and evaluation of a CRNN (Convolutional Recurrent Neural Network) model. |
| `CNN_Improved.ipynb` | Improved/optimized version of the CNN model. |
| `CRNN_Improved.ipynb` | Improved/optimized version of the CRNN model. |
| `Classificacao-de-Sons-Urbanos-com-Deep-Learning.pdf` | Final project report, with a detailed description of the methodology, experiments, and results. |
| `Project_Assignment.pdf` | Project assignment provided by the course. |

## Models explored

- **CNN** (Convolutional Neural Network)
- **RNN** (Recurrent Neural Network)
- **CRNN** (Convolutional Recurrent Neural Network)

Each architecture was trained and evaluated independently, with iterative versions reflecting optimizations over the initial versions.

## How to run

1. Clone the repository:
   ```bash
   git clone https://github.com/anaamorim0/Urban-Sound-Classification.git
   cd Urban-Sound-Classification
   ```

2. Install the required dependencies (using a virtual environment is recommended):
   ```bash
   pip install numpy pandas librosa tensorflow scikit-learn matplotlib jupyter
   ```

3. Open the notebooks with Jupyter:
   ```bash
   jupyter notebook
   ```

4. Start by running the `Download&Pre-processing.ipynb` notebook to obtain and prepare the data, then run the training notebooks for the desired models.

> **Note:** the notebooks assume the use of the [UrbanSound8K](https://urbansounddataset.weebly.com/urbansound8k.html) dataset, which must be downloaded separately (it is not included in the repository due to its size).

## Results

Detailed results, performance metrics, and architecture comparisons can be found in the final report: [`Classificacao-de-Sons-Urbanos-com-Deep-Learning.pdf`](./Classificacao-de-Sons-Urbanos-com-Deep-Learning.pdf).

## Technologies

- Python
- Jupyter Notebook
- TensorFlow / Keras
- Librosa (audio processing)
- NumPy / Pandas
- Scikit-learn
- Matplotlib
