# BE-BLC-for-English-NER-task-Bert-ELMO-OntoNotes
BE-BLC: BERT-ELMO-Based Deep Neural Network Architecture
for English Named Entity Recognition Task
# Requirements
OS: Linux  
Python version: 3.7.7  
AllenNLP version: 0.9.0  
PyTorch version: 1.4.0  
# Dataset
OntoNotes 5.0 from LDC (thru email)  
CoNLL-formatted OntoNotes 5.0 scripts from http://conll.cemantix.org/2012/data.html  
# Run
allennlp train "path\To\the\Json\File" -s "path\Where\To\save\the\outputted\model"
# Test
allennlp evaluate "/path/to/model.tar.gz" "path/to/test/data/conll-2012/v9/data/test/data/english/"
# If you used this model please cite us as :
>@article{affi2021blc, title={BE-BLC: BERT-ELMO-Based Deep Neural Network Architecture for English Named Entity Recognition Task}, author={Affi, Manel and Latiri, Chiraz}, journal={Procedia Computer Science}, volume={192}, pages={168--181}, year={2021}, publisher={Elsevier} }
