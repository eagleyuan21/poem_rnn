# Poems RNN

## Done by Haley Matuszak and Eagle Yuan


### Setting up the environment

Make sure to have python version 3.9 and jupyter notebook installed. Once this is ready, run the following pip command to install necessary packages used to train and generate poems.
```
pip install -r requirements.txt
```

### Running the code

train.ipynb:

To train our model, simply run the train.ipynb notebook sequentially. Note that without a GPU, this can take a few hours. We recommend you use our pretrained model if you do not have access to a strong GPU and there is no need for training.

generate.ipynb: 

You can simply run the generate notebook to begin generation of poems. The parameters to modify the rhyme scheme and starter words are in the sixth code block. When running for the first time, be sure to run all blocks. When running afterwards, you only have to run from the sixth block and onwards.