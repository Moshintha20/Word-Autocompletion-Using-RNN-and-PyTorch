# Word Autocompletion Using Recurrent Neural Network and PyTorch

## Project Overview
This project implements a **Recurrent Neural Network (RNN)** for word autocompletion. The model is designed to suggest possible completions for partially typed words, similar to what is used in modern applications like email or text messaging. For example, given the input "univ", the model might suggest completions such as "university" or "universal".

![image](https://github.com/user-attachments/assets/ae3a49b0-a35b-4f5a-b655-1b3bfa6741ee)


The project is implemented using **PyTorch** and is trained on a dataset of 10,000 common English words. This list serves as the vocabulary for the model.

## Features
- Predicts autocompletion for words based on 3-4 starting letters.
- Trained on a dataset of 10,000 common English words.
- RNN-based model implemented using PyTorch.
- Provides multiple potential word completions.

## Dataset
The dataset used in this project is a simple text file (`wordlist.txt`) containing 10,000 common English words, which acts as the vocabulary for the autocompletion model.

## Installation

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd Recurrent-Neural-Network-Word-Autocomplete
   ```

2. Install the required Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the main Python script to train the model and get predictions:
   ```bash
   python main.py
   ```

2. Input a string of 3-4 letters, and the model will output the most likely word completions based on the trained data.

## Model Architecture
- The model uses a **Recurrent Neural Network (RNN)** to predict word completions.
- **PyTorch** is used as the deep learning framework.
- Training involves processing sequences of letters from the wordlist to allow the model to understand the structure of common English words.

## Example
Given the input "comp", the model might output:
- "complete"
- "computer"
- "company"

## Results
The RNN model successfully predicts meaningful word completions based on partial input. While it may not always be perfect, the model provides multiple plausible completions.

## Future Improvements
- Use a larger and more diverse vocabulary for training.
- Experiment with more advanced RNN architectures, such as LSTMs or GRUs.
- Optimize the model for faster predictions.

<!--
## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
-->
