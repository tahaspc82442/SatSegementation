# GNR602 Image Processing Simulation Project

[![Hugging Face Spaces](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue)](https://huggingface.co/spaces/tahaspc/gnr602)

**Version:** 1.0.0
**Last Updated:** May 1, 2025

## Overview

This project provides an interactive web application built with Streamlit for demonstrating image processing simulations. Users can easily upload an image, configure processing parameters such as thresholds, and execute a simulation to visualize the results in real-time.

This tool is designed for educational purposes, experimentation, or as a basic framework for more complex image analysis tasks.

## Features

* **Image Upload:** Supports common image formats (e.g., JPG, PNG, BMP) for user convenience.
* **Interactive Threshold Selection:** Allows users to dynamically adjust threshold values using sliders or numerical inputs.
* **Simulation Execution:** A simple button click triggers the image processing pipeline based on the selected image and parameters.
* **Result Visualization:** Displays the original and processed images side-by-side or in a sequence for easy comparison.
* **Web-Based Interface:** Accessible via any modern web browser thanks to Streamlit.
* **Online Demo Available:** Try it instantly on Hugging Face Spaces.

## Online Demo

A live version of this application is hosted on Hugging Face Spaces. You can try it out directly without any local installation:

[**>> Try the GNR602 Image Simulation on Hugging Face Spaces <<**](https://huggingface.co/spaces/tahaspc/gnr602)

## Local Setup and Installation

To run this application on your local machine, please follow these steps:

### Prerequisites

Ensure you have the following software installed:

* [Python](https://www.python.org/downloads/) (Version 3.7 or newer is recommended)
* [pip](https://pip.pypa.io/en/stable/installation/) (Python package installer, usually comes with Python)
* [Git](https://git-scm.com/downloads/) (For cloning the repository)

### Step 1: Clone the Repository

Open your terminal or command prompt and clone the project repository:

```bash
git clone [https://github.com/tahaspc82442/SatSegementation](https://github.com/tahaspc82442/SatSegementation)
Navigate into the newly created project directory:cd SatSegementation
Step 2: Set Up a Virtual Environment (Recommended)Using a virtual environment prevents package conflicts with other projects.# Create a virtual environment named 'venv'
python -m venv venv

# Activate the virtual environment:
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate
Step 3: Install DependenciesInstall all the required Python libraries using pip. You can install them directly:pip install opencv-contrib-python streamlit numpy pandas matplotlib
Alternatively, if you create a requirements.txt file in the root of your project with the following content:# requirements.txt
opencv-contrib-python
streamlit
numpy
pandas
matplotlib
You can install all dependencies with a single command:pip install -r requirements.txt
Step 4: Run the Streamlit ApplicationOnce the dependencies are installed and your virtual environment (if used) is active, start the application:streamlit run app.py
This command will typically open the application automatically in your default web browser. If not, the terminal output will provide a local URL (usually http://localhost:8501) that you can open manually.How to Use the ApplicationLaunch: Start the application locally using the streamlit run app.py command or access the Online Demo.Upload Image: Use the file uploader widget (often in the sidebar) to select an image file from your computer.Adjust Thresholds: Use the interactive sliders or input boxes provided to set the desired threshold values for the image processing algorithm.Run Simulation: Click the button labelled "Run Simulation" (or similar) to process the image with the current settings.Analyze Results: The application will display the output, which might be the processed image, numerical data, or plots, allowing you to see the effect of the chosen thresholds.Core DependenciesThis project relies heavily on the following libraries:Streamlit: The core framework for building the interactive web application UI.OpenCV (opencv-contrib-python): Provides the essential computer vision and image processing functions. (contrib version includes extra modules).NumPy: Fundamental package for scientific computing, especially for handling image arrays efficiently.Pandas: Useful for data handling and manipulation, potentially used if your simulation involves tabular data.Matplotlib: Used for generating plots or potentially displaying images within the Streamlit app.ContributingContributions are welcome! If you'd like to contribute, please follow these steps:Fork the repository.Create a new branch (git checkout -b feature/YourFeatureName).Make your changes and commit them (git commit -m 'Add some feature').Push to the branch (git push origin feature/YourFeatureName).Open a Pull Request.Please ensure your code adheres to standard Python style guides (like PEP 8) and includes documentation where necessary.(Optional: Add more specific contribution guidelines if needed)LicenseThis project is licensed under the MIT License. Feel free to use, modify, and distribute the code as per the license terms.(Note: If you choose a different license, update this section and add the corresponding license file, e.g., LICENSE.txt, to your repository.)ContactIf you have any questions, suggestions, or issues, feel free to:Open an issue on the GitHub repository: https://github.com/tahaspc82442/SatSegementation/issues
