File Details:
________________________________________________________

Useful files:

c3d.pickle: 	C3D model weights file(Pretrained on Sports1M dataset). It was downloaded as is.

eval_shot_predictions.py: 	Calculate the TIoU metric.

get_localizations.py: 	Used to create localized segments.

Video_Dataset.py: 	Subclassing Dataset class

utils.py: 	some utility functions that are used throughout the project

________________________________________________________

The following files are for reference purpose only:

model_gru.py: 	Model of GRU RNN defined here

model_c3d.py: 	c3d defined and may be loaded with pretrained wts (in c3d.pickle)

extract_c3dFeats_par.py: 	To extract c3d FC7 layers features from the dataset and dump to disk.

sequence_rnn.py: 	main file for training RNN on features and creating predictions json file.

finetune_c3d.py: 	main file for finetuning a pretrained C3D model and dump weights to disk.


________________________________________________________

Folders:

sample_labels_shots: dataset labels (in json format)

c3d_feats_16: FC7 layers features extracted using extract_c3dFeats.py file (using pretrained C3D model)

