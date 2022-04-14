## rumor-detection

### Install

pip install tensorflow==1.13

some code is from https://github.com/TeamLab/text-capsule-network, and thanks them.

pip install Keras==2.2.4


### Requirement
Python 3.5

TensorFlow  1.13

Keras  2.2.4

### DataSet

Twitter DataSet: https://figshare.com/articles/PHEME_dataset_of_rumours_and_non-rumours/4010619

### Usage
1. Download Twitter DataSet and extract, set the DataSet path to the `data_file_path` in `config.py`.

2. Download glove word vectors: http://nlp.stanford.edu/data/glove.840B.300d.zip, and set the `w2v_file_path` in `config.py`.

3. Run `python main.py`.

## Early Rumour Detection (Torch)
If there are problems with the codes, you can try the newly uploaded torch codes by Menglong Lu.
