# Image Super-Resolution

## 🚀 Project Overview
I developed a deep learning-based super-resolution algorithm to upscale low-resolution **strong lensing images** using high-resolution samples as ground truths. Implemented using **PyTorch/Keras**, I explored multiple models to achieve the best results.

### 📂 Dataset Description
The dataset consists of simulated **strong lensing images** at multiple resolutions:
- 🔹 **High-Resolution (HR) images**
- 🔹 **Low-Resolution (LR) images**

Dataset sample: ![Dataset Sample](https://raw.githubusercontent.com/ktdjiren/--SuperResolution/main/sample_images.png)

---
## 🏆 Implemented Models
To tackle this problem, I trained and evaluated **three** different deep learning models:
1. **Super-Resolution CNN (SRCNN)** – A pioneering deep learning model for super-resolution.
2. **Residual Channel Attention Network (RCAN)** – Uses residual learning & attention mechanisms to enhance details.
3. **Diffusion Model** – A generative model that iteratively refines images for ultra-sharp quality.
---
## 📊 Model Performance Comparison
Here's how each model stacked up based on key performance metrics:

| Model                              | Average PSNR (dB) | Average SSIM | Average MSE |
|------------------------------------|-------------------|-------------|-------------|
| **Super-Resolution CNN**           | 42.11          | 0.9730      | 0.005002      |
| **Residual Channel Attention Network (RCAN)** | 41.77 | 0.9681      | 0.005295      |
| **Diffusion Model**                 | 41.78976270            | 0.97712056      | 0.00006671      |

Output Images:
  ![ Output](https://github.com/ktdjiren/--SuperResolution/blob/main/Task%20III.A/result_RCAN_SR.png)
---
## ⚡ How to Run the Code
Clone this repository:
```bash
   git clone https://github.com/ktdjiren/--SuperResolution.git
```

---
## 💡 Discussion & Observations
- **Super-Resolution CNN (SRCNN):** Simple yet effective for basic upscaling.
- **RCAN:** Delivers sharper images with its attention-based architecture.
- **Diffusion Model:** Achieves stunning results but is computationally intensive.

👉**Insights & Conclusion**  
- **SRCNN** achieved the highest **PSNR (42.11 dB)** but slightly lower **SSIM (0.9730)**, indicating good pixel-wise accuracy but fewer fine details.  
- **RCAN** used attention mechanisms for sharper images but had slightly lower metrics than SRCNN.  
- **Diffusion Model** had the highest **SSIM (0.9771)** and lowest **MSE**, producing the most visually accurate images but at a higher computational cost.  

👉 **Diffusion Model** offers the best perceptual quality, while **SRCNN** is more efficient with strong numerical accuracy.

---
## 📬 Contact
For queries, suggestions, or collaborations, feel free to reach out!  
📧 Email: [rawatamanamanaman1234@gmail.com]  
🔗 GitHub: [https://github.com/ktdjiren]

