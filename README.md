# **Face Recognition Using Hand-Crafted Features**  

## **Description**  
This project implements face recognition using traditional feature extraction techniques and machine learning models. Instead of deep learning, it leverages **Local Binary Patterns (LBP)**, **Gabor filters**, and **Gray-Level Co-occurrence Matrix (GLCM)** to extract facial features. The extracted features are then used to train classifiers like **SVM, KNN, and Random Forest** to recognize faces effectively.  

## **Techniques Used**  
- **Local Binary Patterns (LBP)** – Captures texture patterns by comparing pixel intensities. [MDN Docs](https://en.wikipedia.org/wiki/Local_binary_patterns)  
- **Gabor Filters** – Extracts edge and texture information. [MDN Docs](https://en.wikipedia.org/wiki/Gabor_filter)  
- **Gray-Level Co-occurrence Matrix (GLCM)** – Analyzes texture by computing spatial relationships between pixel intensities.  
- **Principal Component Analysis (PCA)** – Reduces feature dimensions while preserving variance. [MDN Docs](https://en.wikipedia.org/wiki/Principal_component_analysis)  
- **Support Vector Machine (SVM)** – Classifies faces by finding an optimal hyperplane.  

## **Libraries & Dependencies**  
- **[OpenCV](https://opencv.org/)** – Image processing and feature extraction  
- **[scikit-learn](https://scikit-learn.org/)** – Machine learning models  
- **[NumPy](https://numpy.org/)** – Numerical operations  
- **[Matplotlib](https://matplotlib.org/)** – Visualization  

## **Installation & Setup**  
### **Prerequisites**  # **Face Recognition Using Hand-Crafted Features**  

## **Description**  
This project implements face recognition using traditional feature extraction techniques and machine learning models. Instead of deep learning, it leverages **Local Binary Patterns (LBP)**, **Gabor filters**, and **Gray-Level Co-occurrence Matrix (GLCM)** to extract facial features. The extracted features are then used to train classifiers like **SVM, KNN, and Random Forest** to recognize faces effectively.  

## **Techniques Used**  
- **Local Binary Patterns (LBP)** – Captures texture patterns by comparing pixel intensities. [MDN Docs](https://en.wikipedia.org/wiki/Local_binary_patterns)  
- **Gabor Filters** – Extracts edge and texture information. [MDN Docs](https://en.wikipedia.org/wiki/Gabor_filter)  
- **Gray-Level Co-occurrence Matrix (GLCM)** – Analyzes texture by computing spatial relationships between pixel intensities.  
- **Principal Component Analysis (PCA)** – Reduces feature dimensions while preserving variance. [MDN Docs](https://en.wikipedia.org/wiki/Principal_component_analysis)  
- **Support Vector Machine (SVM)** – Classifies faces by finding an optimal hyperplane.  

## **Libraries & Dependencies**  
- **[OpenCV](https://opencv.org/)** – Image processing and feature extraction  
- **[scikit-learn](https://scikit-learn.org/)** – Machine learning models  
- **[NumPy](https://numpy.org/)** – Numerical operations  
- **[Matplotlib](https://matplotlib.org/)** – Visualization  

## **Installation & Setup**  
### **Prerequisites**  
Ensure you have Python **3.7+** installed. Install required dependencies using:  
```bash  
pip install -r requirements.txt  
```  

### **Running the Project**  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-repo-link.git  
   cd Face-Recognition-Handcrafted-Features  
   ```  

2. Navigate to the project directory and activate the virtual environment (optional but recommended):  
   ```bash  
   python -m venv venv  
   source venv/bin/activate  # On macOS/Linux  
   venv\Scripts\activate     # On Windows  
   ```  

3. Run Jupyter Notebook:  
   ```bash  
   jupyter notebook  
   ```  

4. Open `notebooks/feature_extraction.ipynb` to extract features and train models.  

## **Project Structure**  
```plaintext  
/  
│── data/               # Face dataset (Yale Face Database)  
│── models/             # Trained machine learning models  
│── notebooks/          # Jupyter notebooks for feature extraction and training  
│── src/                # Core Python scripts for feature extraction and classification  
│── README.md           # Project documentation  
│── requirements.txt    # Dependencies list  
```  

## **Results**  
- The **best-performing model** achieved **[XX]% accuracy** using **[Feature Extraction Method]**.  
- Traditional feature extraction methods successfully recognized faces without deep learning.  


Ensure you have Python **3.7+** installed. Install required dependencies using:  
```bash  
pip install -r requirements.txt  
```  

### **Running the Project**  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-repo-link.git  
   cd Face-Recognition-Handcrafted-Features  
   ```  

2. Navigate to the project directory and activate the virtual environment (optional but recommended):  
   ```bash  
   python -m venv venv  
   source venv/bin/activate  # On macOS/Linux  
   venv\Scripts\activate     # On Windows  # **Face Recognition Using Hand-Crafted Features**  

## **Description**  
This project implements face recognition using traditional feature extraction techniques and machine learning models. Instead of deep learning, it leverages **Local Binary Patterns (LBP)**, **Gabor filters**, and **Gray-Level Co-occurrence Matrix (GLCM)** to extract facial features. The extracted features are then used to train classifiers like **SVM, KNN, and Random Forest** to recognize faces effectively.  

## **Techniques Used**  
- **Local Binary Patterns (LBP)** – Captures texture patterns by comparing pixel intensities. [MDN Docs](https://en.wikipedia.org/wiki/Local_binary_patterns)  
- **Gabor Filters** – Extracts edge and texture information. [MDN Docs](https://en.wikipedia.org/wiki/Gabor_filter)  
- **Gray-Level Co-occurrence Matrix (GLCM)** – Analyzes texture by computing spatial relationships between pixel intensities.  
- **Principal Component Analysis (PCA)** – Reduces feature dimensions while preserving variance. [MDN Docs](https://en.wikipedia.org/wiki/Principal_component_analysis)  
- **Support Vector Machine (SVM)** – Classifies faces by finding an optimal hyperplane.  

## **Libraries & Dependencies**  
- **[OpenCV](https://opencv.org/)** – Image processing and feature extraction  
- **[scikit-learn](https://scikit-learn.org/)** – Machine learning models  
- **[NumPy](https://numpy.org/)** – Numerical operations  
- **[Matplotlib](https://matplotlib.org/)** – Visualization  

## **Installation & Setup**  
### **Prerequisites**  
Ensure you have Python **3.7+** installed. Install required dependencies using:  
```bash  
pip install -r requirements.txt  
```  

### **Running the Project**  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-repo-link.git  
   cd Face-Recognition-Handcrafted-Features  
   ```  

2. Navigate to the project directory and activate the virtual environment (optional but recommended):  
   ```bash  
   python -m venv venv  
   source venv/bin/activate  # On macOS/Linux  
   venv\Scripts\activate     # On Windows  
   ```  

3. Run Jupyter Notebook:  
   ```bash  
   jupyter notebook  
   ```  

4. Open `notebooks/feature_extraction.ipynb` to extract features and train models.  

## **Project Structure**  
```plaintext  
/  
│── data/               # Face dataset (Yale Face Database)  
│── models/             # Trained machine learning models  
│── notebooks/          # Jupyter notebooks for feature extraction and training  
│── src/                # Core Python scripts for feature extraction and classification  
│── README.md           # Project documentation  
│── requirements.txt    # Dependencies list  
```  

## **Results**  
- The **best-performing model** achieved **[XX]% accuracy** using **[Feature Extraction Method]**.  
- Traditional feature extraction methods successfully recognized faces without deep learning.  


   ```  

3. Run Jupyter Notebook:  
   ```bash  
   jupyter notebook  
   ```  

4. Open `notebooks/feature_extraction.ipynb` to extract features and train models.  

## **Project Structure**  
```plaintext  
/  
│── data/               # Face dataset (Yale Face Database)  
│── models/             # Trained machine learning models  
│── notebooks/          # Jupyter notebooks for feature extraction and training  
│── src/                # Core Python scripts for feature extraction and classification  
│── README.md           # Project documentation  
│── requirements.txt    # Dependencies list  
```  

## **Results**  
- The **best-performing model** achieved **[83]% accuracy** using **[Feature Extraction Method]**.  
- Traditional feature extraction methods successfully recognized faces without deep learning.  

