# minbert Assignment
This is an exercise in developing a minimalist version of BERT.

In this assignment, you will implement some important components of the BERT model to better understanding its architecture. 
You will then perform sentence classification on ``sst`` dataset and ``cfimdb`` dataset with the BERT model.

## Assignment Details

### Important Notes
* There is a detailed description of the code structure in [structure.md](./structure.md), including a description of which parts you will need to implement.  
* You are NOT allowed to import the `transformers` library to implement BERT.  

## Reference accuracies: 

Pretraining for SST:
Dev Accuracy: 0.391 (0.007)
Test Accuracy: 0.403 (0.008)

Mean reference accuracies over 10 random seeds with their standard deviation shown in brackets.

Finetuning for SST:
Dev Accuracy: 0.515 (0.004)
Test Accuracy: 0.526 (0.008)

Finetuning for CFIMDB:
Dev Accuracy: 0.966 (0.007)
Test Accuracy: -

### Academic Integrity
All assignments must be done individually and we will be running plagiarism detection
on your code. If we confirm that any code was plagiarized from that of other students
in the class, you will be subject to strict measure according to the university's academic integrity
policy.

### Acknowledgement
Parts of the code are from the [`transformers`](https://github.com/huggingface/transformers) library ([Apache License 2.0](./LICENSE)).

Original authors: Shuyan Zhou, Zhengbao Jiang, Ritam Dutt, Brendon Boldt, Aditya Veerubhotla, and Graham Neubig, for Carnegie Mellon University's CS11-711 Advanced NLP class.  
Adapted by Zining Zhu for University of Toronto's CSC401/2511 Natural Languages Computing.  