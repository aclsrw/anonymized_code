# assignment_2

* Pre-Run

pip install -r requirements.txt

* Commands to train embeddings

bash get_wikis.sh

bash get_fasttext.sh

bash train_fasttext.sh

then, back to scripts => train_all.sh

* Commands to Train + Evaluate (e.g. a language pair might be: en-aztr):

cd scripts

bash build_vocab.sh en-az

bash train.sh en-az

bash decode.sh en-az

* Reference BLEU Scores:

az-en: 3.0

aztr-en (az with tr): 7.1

be-en: 5.4

beru-en (be with ru): 11.6

gl-en: 16.5

glpt-en (gl with pt): 22.0
