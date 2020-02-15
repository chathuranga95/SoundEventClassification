# Sound Event Classification
Classify daily life events using audio data. 

## Segmented Sound Event Classification
Steps to follow
- Find the guide and explaination on [this](https://medium.com/@chathuranga.15/sound-event-classification-using-machine-learning-8768092beafc) medium article.
- Find the dataset [here].(https://drive.google.com/drive/folders/1tPk7fjftHhHK7vF7iX5XhRi34dz3seh2?usp=sharing)
- Use [STFT_feature_extractor.ipynb](https://github.com/chathuranga95/SoundEventClassification/blob/master/STFT_feature_extractor.ipynb "STFT_feature_extractor.ipynb") for extract STFT features and save the features. (This will create a new directory 'stft_257_1')
- Use [sound_event_classifier.ipynb](https://github.com/chathuranga95/SoundEventClassification/blob/master/sound_event_classifier.ipynb "sound_event_classifier.ipynb") for training the machine learning model and testing. The features should be generated first by the above step.
- You may use a different train, validation and test splitting scheme by changing the code.

## Continuous Sound Event Classification

Classify a sequence of sound events on a recorded audio clip. Find the guide and explaination on [this](https://medium.com/@chathuranga.15/real-time-sound-event-classification-83e892cf187e) medium article.
