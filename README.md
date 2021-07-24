# Neural Machine Translation for German-English on the Multi30K dataset

Multi30K is a dataset to stimulate multilingual multimodal research for English-German. It is based on the Flickr30k dataset, which contains 31,014 images sourced from online photo-sharing websites. Each image is paired with five English descriptions, which were collected from Amazon Mechanical Turk. The dataset contains 145,000 training, 5,070 development, and 5,000 test descriptions. The Multi30K dataset extends the Flickr30K dataset with translated and independent German sentences.

The baseline score is a Seq2Seq model with LSTM. Three approaches are then implemented to improve the translation quality:
* Learning rate decay
* Using CNN as encoder
* Using pre-trained word embedding

Translation quality is evaluated by BLEU score.

This notebook is based on the assignment from the course "Deep Learning in Applications" at Harbour.Space University.