# Pedestrian Classification Project

This project implements a pedestrian classification system using the **INRIA Person Dataset**. It extracts HOG features from images and trains multiple machine learning models to classify whether an image contains a pedestrian or not. The pipeline includes feature extraction, training, validation, and testing with visualizations.

---

## 📥 Download the Dataset

The dataset is already cropped and ready to use.
👉 **[Download the INRIA Cropped Dataset](https://drive.google.com/file/d/1t8-AUQRYJb0LqGnp6ebRB7NJ-iI78mWL/view?usp=sharing)**

After downloading, place the extracted `INRIAPerson` folder in the project root under "pedestrian_classification" folder.

---

## 🧠 How to Run

1. Install the required libraries:

```bash
pip install numpy pandas opencv-python scikit-image scikit-learn matplotlib seaborn joblib
```

2. Open the notebook or Python script in VS Code or Jupyter.

3. Run all cells from top to bottom.

The script will automatically:

* Load training and validation images
* Extract features
* Train multiple models
* Evaluate performance
* Save models and results
* Test on unseen test images
* Visualize predictions

---

## 📂 Output

After running, you will find:

* **Models/** — trained classifier files
* **Results/** — comparison tables and summaries
And visualized output after every cell

---

## 📌 Notes

* Test images are used **only at the final stage**.
* Validation results help compare models and detect overfitting.
* Visualization includes confusion matrices and prediction collages.

---

## 👤 Author

Yousif Hisham

---
