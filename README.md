# End to end Image Captioning system

## Flickr Caption Generator 
This project aims to generate captions for images from the Flickr 8k dataset using a deep learning model. The model leverages the InceptionV3 architecture for image feature extraction and a Bidirectional LSTM for caption generation.

## Project Structure

- **`flickr_caption_generator.ipynb`**: Code for the project, from data loading and preprocessing to model training and evaluation.
- **`data/`**: Directory containing the Flickr 8k dataset, including images and corresponding captions.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/themartiangirl/flickr-caption-generator.git
   cd flickr-caption-generator

2. Create and activate a virtual environment:
    ```bash 
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`

3. Install the required packages:
    ```bash
    pip install -r requirements.txt

4. Download and unzip the Flickr 8k dataset:
    ```bash
    wget https://storage.googleapis.com/TBDBESTIEDATA
    unzip TBDBESTIEDATA.zip -d data

## Model Architecture
- ** InceptionV3 pre-trained on ImageNet.
- ** Bidirectional LSTM network with an embedding layer and a dense layer with a softmax activation for word prediction.
- ** The performance is evaluated using BLEU scores.

## References
- ** Szegedy, C., et al. "Rethinking the Inception Architecture for Computer Vision." CVPR, 2016.
- ** Keras documentation on InceptionV3

## License 
- ** This project is licensed under the GNU General Public License (GPL).
