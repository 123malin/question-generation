# question-generation

A survey of the papers related to generating the questions:

* Machine Comprehension by Text-to-Text Neural Question Generation [[paper]](https://arxiv.org/pdf/1705.02012.pdf) 

    Asking questions is a good way to examine and improve our knowledge. Based on the standard MC(machine comprehension) task and models for question answering(QA), this paper proposes a recurrent neural model that generates natural-language questions from documents. With document and answer(that i think is key word, or key phrase) as inputs, it can generate natural-language questions. The dataset used to train the model and experiment with is [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/), a large-scale, human-generated corpus of (document, question, answer)triples. Baseline model is Seq2Seq, built on the encoder-decoder architecture with attention and pointer-softmax outlined in [Bahdannau](https://arxiv.org/pdf/1409.0473.pdf) [PPT](http://www.iclr.cc/lib/exe/fetch.php?media=iclr2015:bahdanau-iclr2015.pdf). 

* Question Generation via Overgenerating Transformations and Ranking [[paper]](https://www.lti.cs.cmu.edu/sites/default/files/cmulti09013.pdf)

* Text2Test: Question Generator Utilizing Information Abstraction Techniques and Question Generation Methods for Narrative and Declarative Text [[paper]](http://www.dlsu.edu.ph/research/centers/adric/nlp/_archive/8th-NNLRS/8nnlprs-29.pdf)
* Automatic Factual Question Generation from Text [[paper]](http://www.cs.cmu.edu/~ark/mheilman/questions/papers/heilman-question-generation-dissertation.pdf)

* Neural Question Generation from Text: A Preliminary Study [paper](https://arxiv.org/abs/1704.01792)
* Question Generation for Question Answering [paper](http://www.aclweb.org/anthology/D17-1091)
* Learning to Ask: Neural Question Generation for Reading Comprehension [paper](https://arxiv.org/pdf/1705.00106.pdf)
