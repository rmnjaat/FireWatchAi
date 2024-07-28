```markdown
This is  Fire detecting model trained by me and shared my step by step process below

# 🚒 Continuous Fire Detection Project

This project uses a YOLO model to detect fire continuously in images. Follow the steps below to set up and run the project.

## 🚀 Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. **Launch Google Colab**
   - Go to [Google Colab](https://colab.research.google.com).
   - Upload `yolo8_on_fire.ipynb`.
   - ⚙️ **Set Runtime Type**: Switch to **GPU** for faster performance.

3. **Get the Dataset**
   - Visit the [Continuous Fire Dataset](https://universe.roboflow.com/-jwzpw/continuous_fire).
   - dowanload dataswet in yolov8 formate and dowanload as code  copy the secret key .

4. **Add Your Secret Key**
   - 🔑 Locate where the secret key is required and insert yours.

## 🔧 Code Overview & Customization

- The notebook is set up for training and testing fire detection.
- **Customization Tips**:
  - 🛠️ Change the `epochs` in the training configuration for desired accuracy.

## 📈 Training the Model

5. **Run Training and Save Best Weights**
   - Execute the training cells in Colab.
   - Download the best weights from:
     ```
     /content/runs/detect/train/best.pt
     ```

6. **Update Model Weights**
   - Replace `best.pt` with your `best.pt` file.
   - Because my best.pt is on 20 epochs , may cause irrerugal results 

## 🧪 Testing the Model

7. **Install Dependencies**
   ```bash
   pip install torch==2.0.1 torchvision==0.15.2 ultralytics==8.0.121
   ```
   > **Note**: Use these specific versions to avoid errors.

8. **Upload Test Images**
   - Add your own test images.
   - Run `mail.py` and adjust the `source` parameter to match your image paths.
   - you can put source as 0  and show = true to for a cam as input.

## 📝 Notes

- Keep the file names and structure unchanged for smooth execution.
- The instructions assume familiarity with Colab and Python scripting.

---

Feel free to explore, experiment, and enjoy creating a robust fire detection system! 🔥
```

Let me know if there's anything else you'd like to add or change!
