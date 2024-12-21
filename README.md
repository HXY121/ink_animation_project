# Ink Animation Style Transfer Project

## Project Overview

This project implements deep learning-based ink animation style transfer. By combining traditional Chinese ink painting art with modern deep learning methods, it successfully transforms ordinary images into ink painting styles, and further applies these methods to animation rendering. The technique is based on **CycleGAN** (Generative Adversarial Networks) for image style transfer, and post-processing techniques enhance the visual effects of ink painting. The methods in this project can be extended to fields such as animation, gaming, and virtual reality, offering broad application potential.

## Project Structure

ink_animation_project/ ├── data/ │ ├── input_images/ # Raw input images │ └── output_images/ # Style-transferred output images ├── models/ │ └── cycle_gan.py # CycleGAN model implementation ├── preprocess.py # Image preprocessing script ├── style_transfer.py # Style transfer script ├── postprocess.py # Post-processing script ├── README.md # Project documentation ├── requirements.txt # Required dependencies └── LICENSE # License file # ink_animation_project
