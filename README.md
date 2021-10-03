## EATD-Corpus
The EATD-Corpus is a dataset consist of audio and text files of 162 volunteers who received counseling.


### Download
The EATD-Corpus can be downloaded at https://pan.baidu.com/s/1dIZBRZxLaFjLEsis47b7ag with extraction code 2022.


### How to use

There are 162 folders in the dataset. Each folder contains depression data for one volunteer.

- {positive/negative/neutral}.wav: Raw audio in wav
- {positive/negative/neutral}.mp3: Raw audio in mp3
- {positive/negative/neutral}_out.wav: Preprocessed audio. Preprocessing operations include denoising and de-muting
- {positive/negative/neutral}.txt: Audio translation
- {positive/negative/neutral}_seg.txt: Audio translation with word segmentation
- {positive/negative/neutral}_out.csv: Audio features extracted with COVAREP toolkits
- label.txt: Raw SDS score
- new_label.txt: SDS score multiplying 1.25
