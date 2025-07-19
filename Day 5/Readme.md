
## 📝 **MNIST Digit Classification using ANN**

This FIle demonstrates how to perform handwritten digit classification on the **MNIST dataset** using an **Artificial Neural Network (ANN)** with simple **Forward Propagation**.

---

### 📂 **About the Dataset:**

* **MNIST** contains **60,000 training** and **10,000 testing images** of handwritten digits from **0 to 9**.
* Each image is **28x28 grayscale** (flattened into 784 input features for ANN).

---

### 🔧 **How Forward Propagation Works (Concept Brief):**

1. **Input Layer (784 neurons)**
   Each pixel of the 28x28 image is passed as input.

2. **Hidden Layers (Fully Connected Dense Layers)**

   * Each neuron applies:
     `Z = W * X + B`  (Weighted sum + bias)
   * Activation Function (e.g., **ReLU / Sigmoid**) transforms the output non-linearly.

3. **Output Layer (10 neurons)**

   * Represents **digits 0-9**.
   * Uses **Softmax** activation to convert outputs into probability scores.

4. **Prediction:**

   * The neuron with the **highest probability** is selected as the predicted digit.

---




### 💡 **Why Forward Propagation Works:**

Forward propagation allows the model to **transform raw pixel inputs through layers of weights** into meaningful probabilities that map to digits. Each layer extracts more abstract patterns like edges, curves, and eventually the shape of the number.

