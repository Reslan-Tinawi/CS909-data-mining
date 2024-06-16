# CS909 - Assignment 2

This is the code for the second assignment for the [CS909 Data Mining](https://warwick.ac.uk/fac/sci/dcs/teaching/modules/cs909/) module.

The assignment focuses on predicting protien levels (regression) form biological tissue images. Different traditional regression models are experimented: multi-layer perceptron, Support Vector Regression. In addition, deep neural network are tested.

The challenge in this problem is finding good and representative features that can be utilized for the prediction task. For traditional machine learning models, PCA on different channels of the tissue images are tested along with [GLCM Texture Features](https://scikit-image.org/docs/stable/auto_examples/features_detection/plot_glcm.html). For deep learning models, CNNs are utilized on the raw images. In addition, pre-trained models like `ResNet50` are utilized for fine-tuning a CNN model.

## Installation

To set up the project, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/Reslan-Tinawi/CS909-data-mining.git
   cd CS909-data-mining\assignment-2
   ```

2. Create a virtual environment:

   ```bash
   python -m venv cs909-assignment-2-venv
   ```

3. Activate the virtual environment:

   On Windows:

   ```bash
   cs909-assignment-2-venv\Scripts\activate
   ```

   On macOS/Linux:

   ```bash
   source cs909-assignment-2-venv/bin/activate
   ```

4. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

5. Start JupyterLab:

   ```bash
   jupyter lab
   ```
