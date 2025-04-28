# Neural Style Transfer with VGG-19

This project implements Neural Style Transfer to generate artistic images by blending content and style features extracted using a pre-trained VGG-19 model.  
It is part of **Week 4 (Course 4: Convolutional Neural Networks)** from the **Deep Learning Specialization** by **Andrew Ng** on Coursera.

---

## Description

Neural Style Transfer (NST) applies the style of one image to the content of another using deep learning.  
This project includes:

- Using a pre-trained VGG-19 network to extract style and content representations
- Defining a cost function combining content cost and style cost
- Optimizing an input image to minimize the total cost
- Generating visually appealing artistic images

---

## Important Note

Due to file size limitations, the pre-trained model files in the `pretrained-model/` folder have been **removed** from this repository.

**To reproduce the results:**
- Download the VGG-19 pre-trained weights from the following link:  
  [VGG-19 TensorFlow weights](https://github.com/fchollet/deep-learning-models/releases/)  
- Specifically, download: `vgg19_weights_tf_dim_ordering_tf_kernels.h5`
- Place the downloaded file inside a `pretrained-model/` folder.

---

## Files and Folders Included

- `Art_Generation_with_Neural_Style_Transfer_v2.ipynb` — Main Jupyter notebook
- `nst_utils.py` — Helper functions for style transfer
- `public_tests.py` — Public test functions for assignment grading
- `images/` — Content and style images
- `output/` — Example outputs (optional)
- `LICENSE` — License file

---

## Key Concepts Covered

- Neural Style Transfer theory and implementation
- Style cost, content cost, and total cost computation
- Feature extraction using convolutional layers
- Optimization with gradient descent

---

## External Resources

- Pre-trained VGG-19 weights (TensorFlow format):  
  [https://github.com/fchollet/deep-learning-models/releases/](https://github.com/fchollet/deep-learning-models/releases/)

---

## Course Information

This project is part of:  
[Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning)  
Instructor: **Andrew Ng**  
Course 4: **Convolutional Neural Networks**  
Week 4: **Neural Style Transfer**

---

## License

This repository is created for educational and portfolio purposes only.  
It should not be used for direct assignment submission.

---
