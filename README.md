# English-to-Urdu Machine Translation

A compact Transformer-based machine translation project for translating English sentences into Urdu using TensorFlow, Keras, and Keras Hub.

## Project Structure

- `machine_translation.ipynb` - data preparation, model training, and inference
- `Dataset/english-corpus.txt` - English source sentences
- `Dataset/urdu-corpus.txt` - corresponding Urdu translations

## Getting Started

Install the required packages:

```bash
pip install numpy pandas matplotlib tensorflow keras keras-hub kagglehub
```

Open and run `machine_translation.ipynb` from the project directory. The notebook cleans and pairs the corpus, creates training/validation/test splits, trains the Transformer model, and provides a `translate()` function for inference.

## Example

```python
translate("I wish you would trust me")
```

The model is intended for educational experimentation with sequence-to-sequence translation.
