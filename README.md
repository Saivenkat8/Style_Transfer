# Style_Transfer
## Prerequisites
Ensure you have the following dependencies installed:

Python (>= 3.6)

PyTorch (latest version recommended)

NumPy

Matplotlib

Pillow (PIL)

## Setup
## Clone the Repository:

```bash
git clone https://github.com/your-username/style-transfer.git
cd style-transfer
```

## Install Dependencies:

```bash
pip install -r requirements.txt
```
This command will install the required Python packages.

Download VGG19 Model:

```bash
wget https://download.pytorch.org/models/vgg19-dcbb9e9d.pth -P models/
```

This downloads the VGG19 model pre-trained weights.


## Open the Jupyter Notebook:

```bash
jupyter notebook style_transfer_notebook.ipynb
```
This will open the Jupyter Notebook in your default web browser.

## Execute the Cells:

Run each cell in the notebook sequentially by pressing Shift + Enter.
Make sure to modify the paths of the input images (base_image_path and style_reference_image_path) according to your file system.
Review the Results:

The notebook will display the generated images and print relevant information during the training process.
Experiment with different hyperparameters and model configurations as needed.
Customization
Feel free to customize the notebook for your specific use case. You can modify the style transfer model architecture, adjust hyperparameters, or use different pre-trained models for feature extraction.

## Additional Notes
Ensure that your system has a compatible GPU if you want to leverage GPU acceleration. PyTorch will automatically use the GPU if available.
Refer to the PyTorch installation guide for detailed instructions on installing PyTorch based on your platform.
Enjoy experimenting with neural style transfer! If you encounter any issues, refer to the official documentation of the libraries or reach out to the community for assistance.
