# 😄 Facial Expression Recognition

Facial Expression Recognition (FER) is a deep learning project that identifies human emotions from facial images. It leverages convolutional neural networks (CNNs) to detect expressions such as happy, sad, angry, surprised, and more.

---

## 📌 Key Features

- 🎯 Accurate classification of 7 facial expressions  
- 🧠 CNN-based deep learning model using TensorFlow/Keras  
- 📊 Training history and performance visualization  
- 🖼️ Preprocessing pipeline for FER2013 dataset  

---

## 📁 Dataset

We use the [FER-2013 dataset](https://www.kaggle.com/datasets/msambare/fer2013) from Kaggle:

- 35,887 grayscale facial images (48x48 pixels)  
- Labeled with 7 emotions:
  - 😠 Angry  
  - 🤢 Disgust  
  - 😨 Fear  
  - 😄 Happy  
  - 😢 Sad  
  - 😲 Surprise  
  - 😐 Neutral

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:** TensorFlow, Keras, NumPy, Pandas, Matplotlib, Seaborn  

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/aniketkc123/EE708_Term_Project.git
cd ee708
```
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Download the dataset
Download fer2013.csv from Kaggle and place it in the project directory.

4. Train the model
```bash
python train.py
```
📈 Model Performance
Achieved high accuracy on the validation set

Plotted training vs validation loss and accuracy

Displayed confusion matrix to analyze class-wise accuracy

🤖 Future Improvements
Apply transfer learning using pre-trained models like ResNet or EfficientNet

Build a mobile version using TensorFlow Lite

🙋‍♂️ Contributing
Contributions are welcome. Feel free to fork this repo, improve it, and make a pull request.
