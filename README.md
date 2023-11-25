# Stable Diffusion Regularization Image Dataset
Pre-rendered regularization images of man and women on Stable Diffusion 1.5, 2.1 and SDXL checkpoints

## What are Regularization Images?

Regularization images are images that are used as part of a regularization process to improve the stability and performance of deep learning models.

>By creating regularization images, you're essentially defining a "class" of what you're trying to invert. For example, if you're trying to invert a new airplane, you might want to create a bunch of airplane images for regularization. This is so that your training doesn't drift into another class, let's say "car" or "bike". This can even help against going towards a "toy plane" if you are using real references and not interpretations.
>[source](https://www.reddit.com/r/StableDiffusion/comments/xu1ill/comment/iqu81m7/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)


## About the images:

All images were generated with Stable Diffusion 1.5, 2.1, and SDXL 1.0 checkpoint.
For each class (man and woman), a total of 5000 images were generated.

## Class of images:
- woman
- man


## How the images are generated:

All images were generated using only the base Stable Diffusion checkpoints (1.5, 2.1 and SDXL), with simple prompts such as `photo of a woman`, `a woman` or simply `woman`.

## Other related projects:

- https://github.com/tobecwb/stable-diffusion-face-dataset
- https://github.com/tobecwb/facial-features-yolo8x-seg
- https://github.com/tobecwb/stable-diffusion-regularization-images