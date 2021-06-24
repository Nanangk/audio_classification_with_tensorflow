# Audio Classification with TensorFlow
We are going to create a deep learning model and train it to learn to classify **audio files**. Audio classification usually does not get the same kind of attention as image classification with deep learning - this could be because **audio processing** that is typically used in such scenarios is not as straight forward as image data. In this project, we will look at one such processing to convert **raw audio into spectrograms** before using them in a convolutional neural network.

## Dataset
This project uses the **gtzan_music_speech** dataset from **tensorFlow dataset**

The dataset was collected for the purposes of music/speech discrimination. The dataset consists of 120 tracks, each 30 seconds long. Each class (music/speech) has 60 examples. The tracks are all 22050Hz Mono 16-bit audio files in .wav format.

**Homepage:**  [http://marsyas.info/index.html](http://marsyas.info/index.html)

**Source code:** [tfds.audio.gtzan_music_speech.GTZANMusicSpeech](https://github.com/tensorflow/datasets/tree/master/tensorflow_datasets/audio/gtzan_music_speech/gtzan_music_speech.py)

**Versions:**

1.0.0 (default): No release notes.

**Download size:** 283.29 MiB

**Dataset size:** 424.64 MiB

**Auto-cached ([documentation](https://www.tensorflow.org/datasets/performances#auto-caching):** No

[Click Here](https://www.tensorflow.org/datasets/catalog/gtzan_music_speech) for more information about the dataset

## Library
- [TensorFlow](https://www.tensorflow.org/)
- [IPython](https://ipython.org/)
- [Matplotlib](https://matplotlib.org/)
- [Taqadum](https://tqdm.github.io/)


