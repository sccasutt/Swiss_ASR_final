Bachelor Thesis Code and Results

Thesis Title:
"The impact of simple data augmentation techniques on Swiss German automatic speech recognition (ASR)."

From the management summary:

Utilizing an iterative process, it will be shown that data augmentation for Swiss German ASR can extend a dataset in a helpful manner, making a model more effective and accurate when transcribing Swiss German spoken audio to Swiss German text. 
It is also shown that adding different kinds of augmentations have different effects and that chaining different augmentations have marginal benefits. 
Although adding augmentations to a dataset can be beneficial, it is no substitute for effectively adding more data to the training of a Swiss-German ASR model.

For full replication of the experiments: 

Docker Image: paperspace/nb-pytorch:22.02-py3
Original Data: https://projects.mtc.ethz.ch/swiss-voice-data-collection

The results folder contains all automatically transcribed Swiss German results obtained

The training data folder contains all CSVs used to train a Wav2Vec2 model (https://github.com/facebookresearch/fairseq/blob/main/examples/wav2vec) for Swiss German ASR. 
