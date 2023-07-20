# DeepNLP-models-MindSpore

The Reproduction of Open Source Code Based on DSKSD

- If you're interested in DeepNLP, I strongly recommend you to work with this awesome lecture.

  * <a href="http://web.stanford.edu/class/cs224n/syllabus.html">cs-224n-slides</a>
  * <a href="https://www.youtube.com/watch?v=OQQ-W_63UgQ&list=PL3FW7Lu3i5Jsnh1rnUwq_TcylNr7EkRe6">cs-224n-videos</a>

This material is not perfect but will help your study and research:) Please feel free to pull requests!!

<hr>

## Contents

| Model      | Links   |
| ------------- |:-------------:| 
| 01. <strong>Skip-gram-Naive-Softmax</strong> | [<a href="https://github.com/mindspore-courses/DeepNLP-models-MindSpore/blob/main/notebooks/01.Skip-gram-Naive-Softmax.ipynb">notebook</a> / data / <a href="https://arxiv.org/abs/1301.3781">paper</a>] |
| 02. <strong>Skip-gram-Negative-Sampling</strong> | [<a href="https://github.com/mindspore-courses/DeepNLP-models-MindSpore/blob/main/notebooks/02.Skip-gram-Negative-Sampling.ipynb">notebook</a> / data / <a href="http://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf">paper</a>] |
| 03. <strong>GloVe</strong> | [<a href="https://github.com/mindspore-courses/DeepNLP-models-MindSpore/blob/main/notebooks/03.GloVe.ipynb">notebook</a> / data / <a href="https://nlp.stanford.edu/pubs/glove.pdf">paper</a>] |
| 04. <strong>Window-Classifier-for-NER</strong> | [<a href="https://github.com/mindspore-courses/DeepNLP-models-MindSpore/blob/main/notebooks/04.Window-Classifier-for-NER.ipynb">notebook</a> / data / paper] |
| 05. <strong>Neural-Dependancy-Parser</strong> | [<a href="https://github.com/mindspore-courses/DeepNLP-models-MindSpore/blob/main/notebooks/05.Neural-Dependancy-Parser.ipynb">notebook</a> / <a href="https://github.com/rguthrie3/DeepDependencyParsingProblemSet/tree/master/data">data</a> / <a href="http://cs.stanford.edu/people/danqi/papers/emnlp2014.pdf">paper</a>] |
| 06. <strong>RNN-Language-Model</strong> | [<a href="https://github.com/mindspore-courses/DeepNLP-models-MindSpore/blob/main/notebooks/06.RNN-Language-Model.ipynb">notebook</a> / <a href="https://github.com/tomsercu/lstm/tree/master/data">data</a> / <a href="https://arxiv.org/pdf/1504.00941.pdf">paper</a>] |
| 07. <strong>Neural-Machine-Translation-with-Attention</strong> | [<a href="https://github.com/mindspore-courses/DeepNLP-models-MindSpore/blob/main/notebooks/07.Neural-Machine-Translation-with-Attention.ipynb">notebook</a> / <a href="http://www.manythings.org/anki/">data</a> / <a href="https://arxiv.org/pdf/1409.0473.pdf">paper</a>] |
| 08. <strong>CNN-for-Text-Classification</strong> | [<a href="https://github.com/mindspore-courses/DeepNLP-models-MindSpore/blob/main/notebooks/08.CNN-for-Text-Classification.ipynb">notebook</a> / <a href="http://cogcomp.org/Data/QA/QC">data</a> / <a href="http://www.aclweb.org/anthology/D14-1181">paper</a>] |
| 09. <strong>Recursive-NN-for-Sentiment-Classification</strong> | [<a href="https://github.com/mindspore-courses/DeepNLP-models-MindSpore/blob/main/notebooks/09.Recursive-NN-for-Sentiment-Classification.ipynb">notebook</a> / <a href="https://nlp.stanford.edu/sentiment/index.html">data</a> / <a href="https://nlp.stanford.edu/~socherr/EMNLP2013_RNTN.pdf">paper</a>] |
| 10. <strong>Dynamic-Memory-Network-for-Question-Answering</strong> | [<a href="https://github.com/mindspore-courses/DeepNLP-models-MindSpore/blob/main/notebooks/10.Dynamic-Memory-Network-for-Question-Answering.ipynb">notebook</a> / <a href="https://research.fb.com/downloads/babi/">data</a> / <a href="https://arxiv.org/abs/1506.07285">paper</a>] |


## Requirements

- Python 3.7
- MindSpore 2.1
- nltk 3.2.2
- gensim 2.2.0
- sklearn_crfsuite


## Getting started

`git clone https://github.com/mindspore-courses/DeepNLP-models-MindSpore.git`

### prepare dataset

````
cd script
chmod u+x prepare_dataset.sh
./prepare_dataset.sh
````

### docker env
ubuntu 16.04 python 3.5.2 with various of ML/DL packages including tensorflow, sklearn, MindSpore

`docker pull dsksd/deepstudy:0.2`

````
pip3 install docker-compose
cd script
docker-compose up -d
````

### cloud setting

`not yet`

## Author

Sungdong Kim / <a href="https://github.com/FLoutione">@FLoutione</a>