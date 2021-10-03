## EATD-Corpus
The EATD-Corpus is a dataset consist of audio and text files of 162 volunteers who received counseling.


### How to use

Training set contains data from 83 volunteers (19 depressed and 64 non-depressed).

Validation set contains data from 79 volunteers (11 depressed and 68 non-depressed).

Each folder contains depression data for one volunteer.

- {positive/negative/neutral}.wav: Raw audio in wav
- {positive/negative/neutral}_out.wav: Preprocessed audio. Preprocessing operations include denoising and de-muting
- {positive/negative/neutral}.txt: Audio translation
- label.txt: Raw SDS score
- new_label.txt: SDS score multiplying 1.25


