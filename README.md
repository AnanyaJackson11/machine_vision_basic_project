# machine_vision_basic_project
#🧪 Glucose Visualization and Prediction via Deep Learning

This project transforms glucose measurement data into visual representations and applies deep learning to predict glucose levels from blood images. It also explores synthetic image generation using GANs to enrich the dataset.

## Project Workflow

### Step 1: Dataset Loading
- Loads a CSV file containing glucose voltages.
- Uses Pandas for preprocessing.

### Step 2: Visual Encoding of Glucose Data
- Converts each voltage entry into a grayscale "blood vessel" pattern.
- Visuals are generated using:
  - NumPy (random vessel patterns)
  - SciPy's `gaussian_filter` (for smoothing)
  - OpenCV (for saving and displaying images)

### Step 3: Model Training (Planned/Partial)
- Builds a **CNN** to predict glucose voltage from synthetic blood images.
- Considers training a **CycleGAN** to generate realistic blood images from non-visual data.

 Technologies Used

- Python
- Pandas, NumPy
- OpenCV
- SciPy
- TensorFlow/Keras (for CNNs)
- Possibly PyTorch (for CycleGAN)


## Key Idea

> Turn medical voltage readings into images that can be visually analyzed and predicted using deep learning. This creates a hybrid between numeric and visual machine learning.

## 🚀 Future Work

- Improve realism of generated images.
- Train and validate CNNs more robustly.
- Finalize CycleGAN training for medical-style data generation.
- Generate a custom data set for better understanding and evaluation

---

##  How to Run

1. Place your `data.csv` in the working directory.
2. Run the notebook `mv_project.ipynb`.
3. Visuals will be saved in the `blood_visualizations` folder.




