# -Implementation-of-Image-Super-Resolution-Algorithm-Based-On-Mixed-Deep-Convolutional-Networks
This project presents an image super-resolution (SR) model based on a mixed deep convolutional network. The model reconstructs high-resolution images from low-resolution inputs using learnable upsampling, convolutional feature extraction, encoder–decoder denoising, and dilated convolutions for multi-scale detail enhancement.

This project folder contains the code and outputs for the image super-resolution (SR) model based on mixed deep convolutional networks.

Run Inference in Python

Open a terminal or command prompt

Navigate to this folder:
D:\SuperResolutionProject

Make sure trained model weights are in code/weights/

Run inference on Set5:
python code/evaluate.py --dataset Set5

Run inference on Set14:
python code/evaluate.py --dataset Set14

Outputs (SR images and metrics) will be saved in the outputs/ folder

Install Dependencies

Install required Python packages (once):
pip install -r requirements.txt

Requires Python 3.8+ and PyTorch

GPU recommended for faster processing

Folder Structure

IPCV Project Github/ : Python scripts for model inference, dataset handling, and evaluation

outputs/ : Super-resolved images and evaluation metrics (PSNR, SSIM)

requirements.txt : Python dependencies



Notes

Datasets (Set5, Set14) are not included; download separately

Ensure model weights are placed in the correct folder

