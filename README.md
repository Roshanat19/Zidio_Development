# Speech Recognition and Digit Recognition Projects  

This repository contains two machine learning projects developed using VS Code:  

1. **Speech Recognition**: A model that recognizes and transcribes speech into text.  
2. **Digit Recognition**: A model that classifies handwritten digits based on image input.  

Both projects are provided as Jupyter Notebooks (`.ipynb` files) and can be run within VS Code. Follow the steps below to set up and run each project.

---

## Prerequisites  

Ensure you have the following installed on your system:  

- **VS Code**  
- **Python Extension** for VS Code  
- **Jupyter Extension** for VS Code  

### Required Python Packages  

For both projects, you will need:  

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`  

Additionally:  

- For **Speech Recognition**:  
  - `librosa` (for audio processing)  
  - `speechrecognition`  
  - `pyaudio` (optional, for real-time recognition)  

- For **Digit Recognition**:  
  - `tensorflow` (for deep learning model training)  
  - `keras`  

### Installing Dependencies  
Run the following command in the VS Code terminal to install all packages:  
```bash  
pip install pandas numpy matplotlib seaborn scikit-learn librosa speechrecognition pyaudio tensorflow keras  
```

---

## Project 1: Speech Recognition  

### Dataset Description  
The dataset includes:  

- **Audio Samples**: Various speech files.  
- **Transcriptions**: Textual representation of spoken words.  

### Running the Code  

1. Open the `Speech_Recognition.ipynb` file in VS Code.  
2. Run each cell sequentially to load, preprocess, and build the speech recognition model.  
3. The code includes steps for audio feature extraction and model training.  

---

## Project 2: Digit Recognition  

### Dataset Description  
This project uses the **MNIST** dataset, which contains:  

- **Images**: 28x28 grayscale images of handwritten digits (0-9).  
- **Labels**: Corresponding digit labels for each image.  

### Running the Code  

1. Open the `Digit_Recognition.ipynb` file in VS Code.  
2. Run each cell to preprocess the data, train a deep learning model, and evaluate its performance.  
3. The project utilizes a convolutional neural network (CNN) for image classification.  

---

## Getting Started  

1. **Clone the repository** or download the files:  
   ```bash  
   git clone <GitHub Repository Link>  
   ```  
2. Open the project folder in VS Code.  
3. Launch the Jupyter Notebook files (`Speech_Recognition.ipynb` and `Digit_Recognition.ipynb`).  
