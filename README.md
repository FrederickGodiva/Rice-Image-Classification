<h1 align="center">Image Classification</h1>

---

# Table of Contents

- [Overview](#overview)
- [Data Source](#data-source)
- [Project Structure](#project-structure)
- [Tech Stack](#tech-stack)
- [Usage](#usage)

# Overview

This project is about training a machine learning model and making it ready to use on web, mobile, and server platforms. It includes tools for training, tuning, and exporting the model in different formats for easy deployment.

# Data Source

Dataset used in this project is taken from [kaggle](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset)

# Project Structure

```tree
├── model.keras                 # saved trained model
├── model.tflite                # trained model in tflite
├── notebook.ipynb              # model training notebook
├── README.md                   # documentation for this project
├── requirements.txt            # dependencies used in the project
├── saved_model                 # tensorflow savedmodel directory
|  ├── assets
|  ├── fingerprint.pb
|  ├── saved_model.pb
|  └── variables
├── tfjs_model                  # model converted to tensorflow.js format
|  ├── group1-shard1of1.bin
|  └── model.json
├── tuner_directory             # directory containing hyperparameter configurations
```

# Tech Stack

<a href="https://www.python.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=python"/></a>
<a href="https://jupyter.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=jupyter"/></a>
<a href="https://scikit-learn.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=scikitlearn"/></a>
<a href="https://numpy.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=numpy"/></a>
<a href="https://matplotlib.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=matplotlib"/></a>
<a href="https://seaborn.pydata.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=seaborn"/></a>
<a href="https://www.tensorflow.org/"><img src="https://go-skill-icons.vercel.app/api/icons?i=tensorflow"/></a>

# Usage

1. Clone this repository

   ```bash
   git clone https://github.com/FrederickGodiva/Rice-Image-Classification.git
   ```

2. Install Python Virtual Environment Library

   ```bash
   pip install virtualenv
   ```

3. Create Python Virtual Environment

   Linux / Mac:

   ```bash
   python3 -m virtualenv venv
   ```

   Windows:

   ```bash
   python -m virtualenv venv
   ```

4. Activate the Environment

   Linux / Mac:

   ```bash
   source venv/bin/activate
   ```

   Windows:

   ```bash
   venv/Scripts/activate
   ```

5. Install all the requirements

   ```bash
   pip install -r requirements.txt
   ```

6. Open each notebook and run each cell code

7. Exit the Virtual Environment

   ```bash
   deactivate
   ```

---

Copyright &copy; 2025 - Frederick Godiva
