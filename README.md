# microlab-cnn
Reproducible CNN framework for microorganism image classification with AlexNet and DenseNet-121, assessing the impact of compression, scaling, and augmentation using the DIBaS dataset.

---

## 🚀 Usage
You can run the experiments directly in Google Colab:

1. Open the desired notebook from the `notebooks/` folder.  
2. Mount Google Drive and set your dataset path.  
3. Follow the notebook cells to:
   - Convert TIFF images to JPG/PNG  
   - Create augmented datasets  
   - Train CNN models  
   - Save results and plots  

---

## ⚙️ Dependencies
- Python 3.10+  
- TensorFlow 2.x  
- Keras  
- PyTorch (utility functions only)  
- OpenCV, Pillow, NumPy, Pandas, Matplotlib  
- Google Colab environment (recommended)

---

## 📦 License
This project is released under the **MIT License**.  
You are free to use, modify, and distribute it with proper attribution.

---

## 🧾 Citation
If you use this repository or its methods in your research, please cite:

> Boukouvalas, D.T. *et al.* (2025). *Impact of Image Quality and Data Augmentation on CNN Performance for Microorganism Classification.*  
> GitHub repository: [https://github.com/dtbouk-droid/microlab-cnn](https://github.com/dtbouk-droid/microlab-cnn)

---

## 🧰 Notes
- The code and image preparation steps mirror those used in the original study.  
- Pretrained models were **not** used; all CNNs were trained from scratch.  
- Hardware: Google Colab Pro (A100 40 GB / Tesla P100 16 GB).  
- All hyperparameters and training logs are available in the notebooks.

---

📧 For questions or collaborations, contact: **[dtbouk@uni9.edu.br]**
