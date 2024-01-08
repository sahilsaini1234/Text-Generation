# Text Generator with Keras Model Trained on BBC News Data

## Overview

Welcome to the Text Generator powered by a Keras model trained on the BBC News dataset. This Jupyter Notebook provides a step-by-step guide on loading the trained model and generating text. Follow the instructions below to get started.

## Getting Started

1. **Clone the Repository:**
   - Clone this repository to your local machine.

    ```bash
    git clone <https://github.com/sahilsaini1234/Text-Generation.git>
    ```

2. **Install Dependencies:**
   - Install the required dependencies by running the following command:

    ```bash
    pip install -r requirements.txt
    ```

3. **Open and Run the Notebook:**
   - Open the `Text_Generator_final.ipynb` Jupyter Notebook using your preferred environment.
   - Execute each cell sequentially to load the model and generate text.

## Usage

1. **Load the Model:**
   - Use the provided code to load the trained Keras model.

    ```python
    # Example code to load the model
    from keras.models import load_model

    model = load_model("path/to/your/model.h5")
    ```

2. **Generate Text:**
   - Follow the instructions in the notebook to generate text using the loaded model.

3. **Experiment and Customize:**
   - Feel free to experiment with different prompts and parameters to customize the generated text according to your preferences.

## Model Details

- **Architecture:** The text generator is built using the Keras library with a deep neural network architecture.
- **Training Data:** The model is trained on a curated dataset comprising articles from various categories covered by BBC News.
- Data Link: https://www.kaggle.com/datasets/hgultekin/bbcnewsarchive/data

## Acknowledgments

We would like to express our gratitude to the BBC for providing the rich dataset that made this project possible. Additionally, we appreciate the contributions of the Keras and TensorFlow communities for their invaluable support.

## Feedback

Your feedback is important to us! If you encounter any issues, have suggestions for improvement, or would like to contribute, please feel free to open an issue or submit a pull request on GitHub.

Happy text generating!
