AsoSoft Speech Corpus
=====================

## Speech Recognition for Kurdish

AsoSoft is the first company to work in the field of Speech Recognition for the Kurdish language. We develop Speech Recognition, Speaker Recognition, and Speech Command software and tools for the Kurdish language through Artificial Intelligence and Signal Processing. Kurdish language speech data and its related resources like tags are of most important language resources which are required for NLP research and applications such as automatic speech recognition, speaker recognition, etc. In this project, speech data for the Kurdish language (Central Kurdish) was designed and collected so that it could be used in automatic speech recognition, speaker recognition, phonology research, dialect analysis, etc. So far, approximately 30 hours of speech have been recorded and transcribed in order to produce this corpus.

A subset of the AsoSoft speech corpus for research and non-commercial use is available for downloaded. This subset of the AsoSoft Speech Corpus can be used for spoken language processing tasks in Central Kurdish such as speech recognition, speaker recognition, gender identification, and phonetic analysis. This subset includes 45 speakers, each of them has uttered 72 (same) sentences; the first 70 sentences of the AsoSoft Speech Corpus (i.e., sentence 1 to sentence 70) and the last two sentences (i.e., sentence 699 and sentence 700). Each of the last two sentences covers all Central Kurdish phonemes. The original version of the dataset contains 700 sentences for each speaker. The sentences are manually designed to represent the phonetic characteristics of the Central Kurdish. The recording date of this dataset is during the year 2016.

## Metadata

The information of the speakers is given in a table which contains:

*   Microphone type: _USB/Philips/Jack/Laptop_
*   Noise level
*   Gender (this label can be used for gender identification tasks): _Femal/Male_
*   Dialect/city (this label may be used for the phonetic analysis of the various dialects of Kurdish and also dialect identification task)
*   Age
*   Education
*   Length (total and average)

## Files

In the dataset, for each recording three files are given:

*   **.wav**: wave file recorded in 22.05 kHz, 16bit, mono
*   **.wrd**: transcription in Kurdish alphabet
*   **.phn**: phonetic transcription in ASCII format

The file name format is as bellow:  
SpeakerID(_3digits_) + Gender + RecordingDevice(_Laptop/PC/Mobile_) + Mic + SentenceID(_3digits_)  
For example `001MLU001`:  
SpeakerID=001, Gender=Male, RecordingDevice=Laptop, Mic=USB, and SentenceID=001



##  Cite
If you are using this corpus, please cite the following reference:
~~~
@article{veisi2021Jira,
  title={Jira: a Kurdish Speech Recognition System Designing and Building Speech Corpus and Pronunciation Lexicon},
  author={Veisi, Hadi and Hosseini, Hawre and MohammadAmini, Mohammad and  Fathy, Wirya and Mahmudi, Aso},
  journal={arXiv preprint arXiv:2102.07412},
  year={2021}
}
~~~
