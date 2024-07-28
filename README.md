# FireWatchAi
Sure! Here’s the `README.md` in markdown format:

# Fire Detection with YOLOv8

This repository contains code for detecting fire using the YOLOv8 model. Follow the steps below to set up and run the project.

## Steps to Set Up and Run

### 1. Download or Clone the Repository
Clone the repository using the command:
```bash
git clone https://github.com/yourusername/your-repo-name.git
```
Or download the ZIP file and extract it.

### 2. Upload the Jupyter Notebook to Google Colab
Upload the `yolo8_on_fire.ipynb` file to [Google Colab](https://colab.research.google.com/).
- Set the runtime type to GPU by navigating to `Runtime > Change runtime type` and selecting `GPU`.

### 3. Download Dataset from Roboflow
Download the fire detection dataset from Roboflow:
- Visit [this link](https://universe.roboflow.com/-jwzpw/continuous_fire).
- Follow the instructions to download the dataset in YOLO format.

### 4. Paste Your API Key
Insert your Roboflow API key into the code where needed.

### 5. Understanding the Code
The uploaded notebook contains code for:
- Loading and preparing the dataset.
- Training the YOLOv8 model on the fire dataset.
- Adjusting parameters such as the number of epochs for training.

#### Important Changes:
- **Epochs:** Modify the number of training epochs to improve model performance.

### 6. Download the Best Model
Once training is complete, download the best model:
- Path: `runs/detect/train/best.pt`

### 7. Replace the Existing Model
Replace the existing `best.pt` file in the repository with your trained model.

### 8. Test the Model
- Upload test images to the repository or your Colab environment.
- Run the `mail.py` script, modifying the `source` parameter to point to your test images.

## Conclusion
This project allows you to customize and train a fire detection model using YOLOv8. Feel free to experiment with different parameters and datasets for improved results.


Feel free to customize the placeholders and make any additional changes!
