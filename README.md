Certainly! Here's a revised version of the given sentence:

---

## Machine Translation with Transformers using PyTorch

*Aim:* To translate English to French using Transformers implemented with PyTorch.

We utilized the Opus Books dataset from Hugging Face.

To download the dataset from Hugging Face, use the following code:

python
from datasets import load_dataset

dataset = load_dataset("opus_books")


You can find the tokenization and preprocessing weights in the "Weights" folder, named as follows:

eng_tokens
frn_tokens
english_preprocessing
french_preprocessing
