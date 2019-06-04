# Machine Translation Part

* Pre-Run

pip install -r requirements.txt

* Commands to get embeddings

bash get_fasttext.sh

* Commands to Train + Evaluate (e.g. a language pair might be: en-aztr):

cd scripts

bash build_vocab.sh en-az

bash train.sh en-az

bash decode.sh en-az

* Reference BLEU Scores:

az-en: 3.0

be-en: 5.4

gl-en: 16.5
