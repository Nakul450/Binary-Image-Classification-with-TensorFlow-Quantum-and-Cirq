# Binary-Image-Classification-with-TensorFlow-Quantum-and-Cirq
This project demonstrates a hybrid quantum-classical neural network designed using TensorFlow Quantum (TFQ) and Cirq. The model is trained to classify images from the Fashion MNIST dataset using quantum circuits as feature extractors.


# ✨ Project Highlights
✅ Implements Quantum Data Encoding using qubit rotations

🧩 Uses entangling gates (XX, ZZ, CZ, CNOT) to extract high-dimensional features

🧠 Combines classical neural networks with quantum layers for hybrid learning

🎯 Trained on Fashion MNIST with competitive accuracy

📈 Includes performance tracking and accuracy comparison with classical baselines


# 🚀 How It Works
Data Preprocessing: Classical Fashion MNIST images are downsampled and encoded onto quantum circuits using rotation gates.

Quantum Circuit Layer: Qubits are rotated and entangled using trainable gates (e.g., RY, RZ, CZ, CNOT).

Measurement & Readout: The circuit measures the readout qubit in the Z-basis to generate features.

Hybrid Model: Quantum features are passed to a classical dense layer for classification.

Training: The whole model is trained end-to-end using backpropagation with TensorFlow.


# 🛠️ Technologies Used
TensorFlow Quantum

Cirq

Python 3.9+

NumPy, SymPy, Matplotlib
