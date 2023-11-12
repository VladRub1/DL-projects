# Machine Translation

This project presents a custom implementation of deep models for 
**machine translation** from English to Russian.

The training used a [dataset](./data.txt) of hotel and apartment 
descriptions in both English and Russian.

[Here](./NeuralMachineTranslation-eng-rus-RubanovVladislav.ipynb) you can find code with:
* data analysis
* custom implementation of NLP models based on **RNN** and **transformer** architectures
* model training
* examples of model outputs, metrics
* instructions (in the last section) on **downloading and using the best trained model** 
  from HuggingFace Hub.

The file [vocab.py](./vocab.py) contains code for transforming (tokenizing) textual data.
