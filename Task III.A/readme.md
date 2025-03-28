# Image Super-resolution

## Project Overview
I developed a deep learning-based super-resolution algorithm to upscale low-resolution strong lensing images using high-resolution samples as ground truths. The project was implemented using **PyTorch/Keras**, and I explored multiple models to achieve the best results.

### Dataset Description
The dataset consists of simulated strong lensing images at multiple resolutions:
- **High-Resolution (HR) images**
- **Low-Resolution (LR) images**

Dataset sample: ![Dataset Sample]https://raw.githubusercontent.com/ktdjiren/--SuperResolution/main/Task%20III.A/sample_images.png
---
## Implemented Models

To tackle this problem, I trained and evaluated three different deep learning models:
1. **Super-Resolution CNN (SRCNN)**
2. **Residual Channel Attention Network (RCAN)**
3. **Diffusion Model**

## Model Performance Comparison
Below is a comparison of the models based on their performance metrics:

| Model                     | Average PSNR (dB) | Average SSIM | Average MSE |
|---------------------------|-------------------|-------------|-------------|
| Super-Resolution CNN      | XX.XX            | X.XXXX      | X.XXXX      |
| Residual Channel Attention Network (RCAN) | XX.XX      | X.XXXX      | X.XXXX      |
| Diffusion Model           | XX.XX            | X.XXXX      | X.XXXX      |

(Note: Replace `XX.XX` and `X.XXXX` with actual results obtained from the experiments.)

---
### Steps to Run the Code
 Clone this repository:
   ```bash
   git clone https://github.com/your-repo/image-super-resolution.git
   ```

   ```

---
## Discussion
- **Super-Resolution CNN (SRCNN):** A basic CNN-based architecture that enhances image resolution.
- **RCAN:** Utilizes residual learning and channel attention mechanisms to improve performance.
- **Diffusion Model:** A generative approach that iteratively refines the image to produce high-quality results.

Based on the results, **[my observations here, e.g., which model performed best and why]**.

---
## Contact
For any queries or contributions, feel free to reach out:
📧 Email: [your.email@example.com]  
🔗 GitHub: [your-github-link]


