# CIFAR10-CNN-Design-and-Evaluation

This project explores the design, training, and evaluation of deep Convolutional Neural Networks (CNNs) for image classification on the CIFAR-10 dataset. Several experiments were conducted to compare different network architectures, training strategies, and layer configurations.

## 📌 Dataset
- CIFAR-10 image dataset consisting of 60,000 32x32 color images in 10 classes.
- 15% of the dataset was reserved for test evaluation.

## 🧠 Tasks and Experiments

### 1. CNN Architecture Design
- A deep CNN was designed and trained for classifying CIFAR-10 images.
- The network architecture (number of layers, kernel sizes, and filter counts) is described in detail in the code.
- Performance was compared with the best Dense (fully connected) network designed in a previous phase.

### 2. Training Time and Accuracy Comparison
- Training duration was recorded.
- Accuracy on the test set was reported and compared with the previous Dense model.

### 3. Learning Rate Scheduling
- Two learning rate schedules were compared:
  - **Exponential decay**
  - **OneCycle policy**
- Both were evaluated over 50 epochs.

### 4. Pooling Layer Effect
- The impact of including or removing pooling layers in the CNN was evaluated.
- Training time, accuracy, and loss were plotted for both setups.

### 5. Stride Experimentation in Pooling
- The effect of different stride values (2 and 4) in pooling layers was studied.
- Accuracy and loss were visualized over 50 epochs for each stride configuration.

### 6. Transfer Learning
- A pre-trained powerful CNN model was used (e.g., Xception, EfficientNetB0).
- Two setups were tested:
  - Entire network frozen (only classification head was trained).
  - One inner layer unfrozen and trained.
- Accuracy and loss were plotted for both scenarios.

## 🔧 Tools & Frameworks
- Python, TensorFlow/Keras
- Matplotlib for visualization
- GPU training enabled

## 📊 Results
- Graphs and charts showing the comparison of training time, accuracy, and loss across all experiments.

## 🧑‍💻 Author
This project was completed as part of a deep learning course assignment.

---

Feel free to fork, clone, or build upon this for similar evaluation tasks or experiments.
