# SER_MLP
 
Speech Emotion Recognition System using MLP (Multilayer Perception)

Dependencies: librosa, soundfile, numpy, sklearn, pyaudio

Corpus: RAVDESS

Train (Features): mfcc, chroma, mel

Parameter setting: alpha=0.01, batch_size=256, epsilon=1e-08, hidden_layer_sizes=(300,), learning_rate='adaptive', max_iter=500

Result: Accuracy: 48.3%

*MEMO: This is very simple-tutorial code to learn fundamental ideas about how to establish a MLP model
*MEMO: The files (corpus) was pro-processed so that they have lowered sample rates (than original files)
