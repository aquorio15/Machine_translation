# Machine_translation
*Step 1: Preprocessing the data
  *Download the parallel corpus from Samanantar or Opus and extract them to a folder
  *Run DataPreprocessing.py inside Model folder(This will generate two new files after preprocessing)
  *Currently the preprocessing that is being carried out by the code are as follows:
  *Converting all the capital letters to small letters.
  *Removing non-printable characters.
  *Removing emojis.
  *Removing unknown characters (Heavily dataset dependent) 4.We will be using sentencepiece as the tokenizer
*Step 2: Training the model
  *Currently there are three models CNNSeq2Seq, Transformer model and RNN based LSTM network.
  *Just feed the data generated from step 1. into the model.
*Step 3: Inference
  *Run translate.py after changing the source and target file path also change the vocabularies file path
