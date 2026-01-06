Project Overview
This project converts a text prompt into a short video using Stable Diffusion.
A base image is first generated from text, and then subsequent frames are
created using image-to-image diffusion to maintain scene consistency.
All generated frames are finally compiled into a video using OpenCV.


Setup Instructions
bash
pip install diffusers transformers accelerate torch torchvision
pip install opencv-python pillow


System Requirements
Python 3.9+
CUDA-enabled GPU
Minimum 6GB VRAM recommended


How to Run the Project
python text_to_video.py


Example Prompt
A cinematic sunset over mountains with moving clouds


Output
Video Duration: ~6 seconds
FPS: 4
Resolution: 512x512
Output File:
