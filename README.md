# Pattern-Sense-Classifying-Fabric-Pattern-using-Deep-Learning
This project classifies fabric patterns such as floral, striped, checked, plain, and geometric using a Convolutional Neural Network (CNN) and provides a web interface for prediction using Flask.

📁 Project Structure
├── app.py
├── Data.py
├── TrainCNN.py
├── requirements.txt
├── fabric_pattern_model.h5  (generated after training)
├── templates/
│   ├── index.html
│   └── result.html

⚙️ Setup Instructions
1. Clone or Download the Project
Download or clone the repository and navigate into it.
2. Create a Virtual Environment
python -m venv venv
venv\Scripts\activate
3. Install Dependencies
pip install -r requirements.txt

📊 Dataset Preparation
Ensure your dataset is located at the following path:

D:\projectfabric\Fabric\Clothing Pattern Classification Dataset (MD-Fashion-2)_Samples"


Or update the `data_dir` path in `Data.py` to reflect your actual dataset location.

---
## 🧠 Model Training

1. Run the data preprocessing script:
```bash
python Data.py


