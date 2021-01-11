# Fine-tuning-Bert-for-word-replacement

The task aims at fine-tuning BERT model on Europarl monolingual documents [available at http://www.statmt.org/europarl/] and written in english. After fine tuning the fine tuned model is saved and used for word replacement task in a sentence such that after replacing the word with a new word the context of the sentence remain same. It has been taken care that the stem of the original word and replaced word are not same.

The code is written in google colab and the notebook is well commented to explain each process.

The fine tuned model is available under 'fine-tuned-model/checkpoint-300000' folder and the corresponding pickle files for whole dataset [with one row as one sentence] and tokenized dataset are also available in the repository along with colab notebook.
