# Introduction

## Business Driver
Business have image data (robot cameras, security cameras, employee devices) that could be leveraged to improve processes. This project covers the key skills needed to build a machine learning tool to create business value from those images. The use cases for object recognition run from self-driving cars to self-checkout stores to robot picking in automation lines.

## Project Details
The project for this internship is to develop a functioning object recognition model trained on a specific set of images that you will gather. We will work with you to pick a specific use-case for object detection, gather and label images, use transfer learning on a pre-trained neural network, and present a functioning demonstration of their model. You may work in teams on the image labeling part of this project if you so choose.

## Getting Set up

* Install Anaconda [from here](https://www.anaconda.com/products/individual) - use the "Just me" installation option.
* Install Visual Studio Code (really useful for text editing) [from here](https://code.visualstudio.com/download)
* Run Anaconda command line (start menu option: `Anaconda3 (64-bit)`, `Anaconda3 Prompt (Anaconda3)`)
> We will be using the command line quite a bit during this internship. If you do not have much experience with using the command line, here are a couple of introductions and tutorials: [here](https://www.makeuseof.com/tag/a-beginners-guide-to-the-windows-command-line/) or [here](https://www.computerhope.com/issues/chusedos.htm)
* Create new environment: `conda create --name internship python=3.8` (documentation [here]
> You also need to get used to reading documentation about the tools you are using. It helps to learn what is possible and to understand what it is we are doing. The documentation for conda environments is found [here](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html).
* Activate new environment: `conda activate internship`
* Install tensorflow: `pip install tensorflow` 
> Here is another set of documentation about [pip](https://realpython.com/what-is-pip/).
* Set up the Jupyter notebook server: `conda install jupyter`
* Set up other dependencies: 
    * `pip install matplotlib scipy tensorflow_hub labelimg selenium seaborn`
* Start jupyter notebook server `jupyter notebook`
* Create a new folder `internship` from your `C:\Users\username\` folder
* Create new notebook (new menu option, choose Python 3) and call it `Week1`

Every time you return to working on this project, you will need to follow these steps:
1. Run Anaconda command line (start menu option: `Anaconda3 (64-bit)`, `Anaconda3 Prompt (Anaconda3)`) tool
2. Activate your project environment: `conda activate internship`
3. Start jupyter notebook server `jupyter notebook`

From the Jupyter notebook server page, navigate to your `internship` folder and open the notebook where you left off.