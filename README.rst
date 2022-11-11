**Coqui STT** (🐸STT) is a fast, open-source, multi-platform, deep-learning toolkit for training and deploying speech-to-text models. 🐸STT is battle tested in both production and research 🚀

--------------
For Fabiennes model:
To run the model, click on Fabs_version_train_your_first_coqui_STT_model.ipynb
To run the original model, go to the folder "Notebooks" and choose the following: Train your first 🐸 STT model
In both cases the model can be opened by clicking "Open in Colab"

INSTRUCTIONS:
Using the Colab, every block can be run without adding or removing something.
First some necessary stuff will be downloaded using pip.
Then the data is being downloaded and formatted into something usable. This can take some time since it has some iterations to do.
Then you will be able to check if the data is how it is supposed to be. (To be certain you can look at how it should be on the original model, however only one sentence was used)
This is followed by setting the right configurations for the model.
Before testing the model, there is a training. The quality of the training depends on the amount of epochs. However, more epochs means more training time. Default is set at epoch = 100, which takes about an hour to train.
The last step is to test the model, in which the sentences from the audio's are being learned.

In the Colab file the instructions given are the ones with the original model, so not my own. These instructions are clear and give a good explanation of what is supposed to be done.

The original data only used one sentence to train the model. In my version 100 sentences are used. The dataset in which these sentences can be find is retrieved from HuggingFace and consist of validated English Common Voice data. Pulled from the data are the audio (.wav) and the sentences. To change the model from single sentence to multiple sentences many iteration processes where added for the downloading stage.

The model learns, using the transcribed sentences, what is said in the audio files. It will give an overview of the name of the audio file, the sentence corresponding, and what the model understood the audio to say. Making use of more epoch makes the understanding of the model better. It makes some mistakes, but this could be due to the different voices used in the audio. Other than that is works as expected.
---------------
