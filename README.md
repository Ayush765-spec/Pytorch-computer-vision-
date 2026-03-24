# Pytorch-computer-vision-
# PyTorch Computer Vision Models

This project demonstrates a step-by-step approach to building and improving computer vision models using PyTorch, focusing on the FashionMNIST dataset. The notebook walks through the process of data loading, visualization, model building, training, evaluation, and gradual model improvements.

## Dataset
- **FashionMNIST**: A dataset of 28x28 grayscale images of 10 fashion categories, with 60,000 training and 10,000 test samples.

## Project Structure
- **03_pytorch_computer_vision.ipynb**: The main Jupyter notebook containing all code, explanations, and results.

## Workflow Overview
1. **Data Loading & Visualization**
	- Loads FashionMNIST using `torchvision.datasets`.
	- Visualizes samples and explores data structure.
2. **Data Preparation**
	- Uses `DataLoader` to batch and shuffle data for efficient training/testing.
3. **Model 0: Baseline (Linear Model)**
	- A simple neural network with two `nn.Linear` layers and a `nn.Flatten` layer.
	- Serves as a baseline for comparison.
4. **Model 1: Adding Non-Linearity**
	- Introduces a `ReLU` activation between linear layers.
	- Uses device-agnostic code for CPU/GPU compatibility.
	- Slight improvement, but still limited by model capacity.
5. **Model 2: Convolutional Neural Network (CNN)**
	- Adds convolutional (`nn.Conv2d`) and pooling (`nn.MaxPool2d`) layers.
	- Significantly improves performance by capturing spatial features.
	- Trains and evaluates using modular functions for reusability.
6. **Evaluation & Visualization**
	- Compares model performance using accuracy and loss.
	- Visualizes predictions and confusion matrix for detailed analysis.

## Gradual Model Improvements
- **Baseline Model**: Starts with a simple linear classifier to establish a reference point.
- **Non-Linearity**: Adds activation functions to enable the model to learn more complex patterns.
- **CNN**: Incorporates convolutional and pooling layers, which are essential for image data, leading to a substantial boost in accuracy and generalization.
- **Evaluation**: Each model is evaluated on test data, and results are compared using plots and confusion matrices.

## How to Run
1. Install dependencies (see notebook for pip commands).
2. Run the notebook cells sequentially to reproduce results and visualizations.

## Key Libraries Used
- `torch`, `torchvision`, `matplotlib`, `pandas`, `numpy`, `torchmetrics`, `mlxtend`

## Results
- The project demonstrates how model architecture improvements (from linear to CNN) lead to better performance on image classification tasks.
- Visualizations and metrics provide insights into model strengths and weaknesses.

---

For more details, see the notebook: `03_pytorch_computer_vision.ipynb`.







These are the proofs of works where the model gets trained gradually and finally gives accurate predictions to the results as seen tested and run in goggle colab 
<img width="1041" height="637" alt="Screenshot 2026-03-24 231905" src="https://github.com/user-attachments/assets/d8d24a57-888a-4add-9264-c03a1c7c43f1" />
<img width="1067" height="763" alt="Screenshot 2026-03-24 231858" src="https://github.com/user-attachments/assets/82b374fa-10d6-4470-9ae2-a1565961b8d2" />
<img width="733" height="413" alt="Screenshot 2026-03-24 231818" src="https://github.com/user-attachments/assets/8b1f86cc-a442-4cd6-a21e-1661b3dfd465" />
<img width="1777" height="143" alt="Screenshot 2026-03-24 231650" src="https://github.com/user-attachments/assets/bca941bd-1c6c-4ea2-b4af-a8112b16b778" />
<img width="1416" height="670" alt="Screenshot 2026-03-24 231621" src="https://github.com/user-attachments/assets/bfaece3b-cad1-49a9-bdc2-5e36c37c3c3f" />
<img width="596" height="594" alt="Screenshot 2026-03-24 231413" src="https://github.com/user-attachments/assets/e2f2b582-b433-4c2c-948e-f494a19f82e1" />
<img width="1010" height="581" alt="Screenshot 2026-03-24 231403" src="https://github.com/user-attachments/assets/10c258e1-155a-4ea8-99c7-786b96565213" />
<img width="777" height="659" alt="Screenshot 2026-03-24 231349" src="https://github.com/user-attachments/assets/4d7e310c-ae5e-4869-afa5-f6f809336c28" />




