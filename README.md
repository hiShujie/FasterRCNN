# 🚀 Fast R-CNN on PASCAL VOC 
​**​PyTorch Implementation of Fast R-CNN for Object Detection​**​  
>THU DA PRML 2023fall lecture project

---

<div align="center">
  <img src="assets/demo.gif" width="600" alt="Detection Demo">
  <br>
  <em>✨ Example detections on PASCAL VOC (mAP: 68.9%) ✨</em>
</div>

---

## 📦 Key Features  
- 🚄 ​**​3x Faster Training​**​ - Achieve 68.9% mAP on VOC07 test set in 4.5 hrs (single RTX 3090)
- 🧩 ​**​Modular Design​**​ - Plug-and-play ROI pooling & classifier modules
- 📂 ​**​VOC Ready​**​ - Auto-download & preprocess scripts for PASCAL VOC 2002012

---

## 🛠️ Installation  
### Requirements  
- 🐍 Python 3.8+  
- ⚡ PyTorch 2.0+  
- 💻 CUDA 11.8 (recommended)  
- 🧠 8GB+ VRAM (tested on RTX 3060/3090)  

### Quick Setup  
```bash
# Clone with SSD support submodule
git clone --recursive https://github.com/yourname/fastrcnn.git
cd fastrcnn

# Install dependencies (with auto CUDA detection)
pip install -r requirements.txt

# Download pre-trained backbone (ImageNet)
wget https://download.pytorch.org/models/resnet50-11ad3fa6.pth -O weights/resnet50.pth
