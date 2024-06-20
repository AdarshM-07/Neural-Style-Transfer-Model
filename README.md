# Neural Style Transfer Project

## Project Overview
Neural Style Transfer (NST) is a revolutionary technique in digital art and image processing, leveraging deep learning to blend the content of one image with the style of another. This project addresses challenges such as content integrity, high-resolution images, and real-time processing. The key objectives are to develop a robust NST model, ensure content preservation, capture artistic styles effectively, and produce visually appealing results.

## Installation Instructions
Follow these steps to set up the environment and run the project:

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/AdarshM-07/Neural-Style-Transfer-Model.git
   cd Neural-Style-Transfer-Model
2. **Create a Virtual Environment:**
   ```sh
   python -m venv neural_style_transfer  #     Creates the virtual environment folder
   source neural_style_transfer/bin/activate  # Activate the virtual environment (Linux/macOS)
   # OR
   neural_style_transfer\Scripts\activate.bat  # Activate on Windows`
3. **Install Dependencies:**
   ```sh
   pip install -r requirements.txt
4. **Run the Jupyter Notebook:**
   ```sh
   jupyter notebook Neural_Style_transfer.ipynb

## Usage

Examples of how to use the code:

1. **Basic Usage**:
Open the Neural_Style_transfer.ipynb notebook in Jupyter and follow the instructions within each cell to run the Neural Style Transfer.

2. **Custom Parameters**:
You can fine-tune the parameters in the respective cells of the notebook to achieve different results.

3. **Experiment with Different Images**:
Modify the paths to the content and style images in the notebook to explore various artistic outputs.

## Dependencies
List of all required libraries and dependencies:

- numpy==1.23.5
- tensorflow==2.10.0
- opencv-python==4.6.0.66
- matplotlib==3.6.2

To install all dependencies, use the provided `requirements.txt` file:
```sh
pip install -r requirements.txt
