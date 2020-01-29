# Mainstream NER Datasets and Brief Description

### [ReCoNLL](https://github.com/pfliu-nlp/Named-Entity-Recognition-NER-Papers/tree/master/ner_dataset/ReCoNLL)
ReCoNLL is revised on CoNLL-2003. We manually fixed errors with the instruction of the measure ECR (entity coverage ratio) proposed by the [work](http://pfliu.com/InterpretNER/rethink-ner.pdf). Specifically, we corrected 65 sentences in the test set and 14 sentences in the training set. 

### [PLONER](https://github.com/pfliu-nlp/Named-Entity-Recognition-NER-Papers/tree/master/ner_dataset/PLONER)
PLONER (Person, Location, Organization NER) is purposed to evaluate the cross-domain generalization. We pick the samples which contain at least one of three entity type (Person, Location, Organization) from representative datasets, such as WNUT16, CoNLL03, OntoNotes 5.0. 

### [CoNLL2003](https://github.com/pfliu-nlp/Named-Entity-Recognition-NER-Papers/tree/master/ner_dataset/CoNLL2003)
CoNLL2003 is  one of the most widely used NER data set. More about the datasets can be found in this paper: [Introduction to the CoNLL-2003 Shared Task: Language-Independent Named Entity Recognition](https://www.aclweb.org/anthology/W03-0419.pdf).

### [OntoNotes 5.0](https://catalog.ldc.upenn.edu/LDC2013T19)
The corpus type of OntoNotes 5.0 includes newswire (News), broadcast news (BN), broadcast conversation (BC), telephone conversation (Tele) and web data (Web) in English. For more detailed description about the data set, please refer to the document: [OntoNotes Release 5.0](https://catalog.ldc.upenn.edu/docs/LDC2013T19/OntoNotes-Release-5.0.pdf) .

### [Wnut16](https://github.com/pfliu-nlp/Named-Entity-Recognition-NER-Papers/tree/master/ner_dataset/Wnut16)
A shared task on named entity recognition in Twitter.  For more information about the data set, please refer to the paper: [Results of the WNUT16 Named Entity Recognition Shared Task](https://www.aclweb.org/anthology/W16-3919.pdf).

### [CoNLL++](https://github.com/pfliu-nlp/Named-Entity-Recognition-NER-Papers/tree/master/ner_dataset/CoNLL++)
CoNLL++ views ner (CoNLL03) as a task to train with noisy annotations and test with gold-standard annotations. We corrected 186 sentences in the test set. For more information about the data set, please refer to the paper: [CrossWeigh: Training Named Entity Tagger from Imperfect Annotations](https://www.aclweb.org/anthology/D19-1519.pdf).


### [Multi-lingual]
* [Finnish](https://github.com/pfliu-nlp/Named-Entity-Recognition-NER-Papers/tree/master/ner_dataset/multilingual/fi) The dataset is refined by this [paper](https://arxiv.org/pdf/1911.09812.pdf).
* [Arabic](https://github.com/pfliu-nlp/Named-Entity-Recognition-NER-Papers/tree/master/ner_dataset/multilingual/ar) The dataset is refined by this [paper](https://arxiv.org/pdf/1911.09812.pdf).