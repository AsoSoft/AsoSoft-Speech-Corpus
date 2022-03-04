# AsoSoft Speech Corpus
This dataset is a subset of the AsoSoft Speech Corpus that can be used for spoken language processing tasks in Central Kurdish such as speech recognition, speaker recognition, gender identification, and phonetic analysis. This subset includes 45 speakers, each of them has uttered 72 (same) sentences; the first 70 sentences of the AsoSoft Speech Corpus (i.e., sentence 1 to sentence 70) and the last two sentences (i.e., sentence 699 and sentence 700). Each of the last two sentences covers all Central Kurdish phonemes. The original version of the dataset contains 700 sentences for each speaker. The sentences are manually designed to represent the phonetic characteristics of the Central Kurdish. The recording date of this dataset is during the year 2016. 

The information of the speakers is given in the following table. As shown, various information such as microphone type, noise level, gender (this label can be used for gender identification tasks), age, dialect/city (this label may be used for the phonetic analysis of the various dialects of Kurdish and also dialect identification task), education and the length (total and average), are given. 

In the dataset, for each wave file (.wav, recorded in 22.05 kHz, 16bit, mono), two other files are given, one for writing transcription (.wrd) and another for the phonetic transcription (.phn). The file name format is as bellow:  
`SpeakerID(3digits) + Gender(Femal/Male) + RecordingDevice(Laptop/PC/Mobile) + Mic(USB/Philips/Jack/Laptop) + SentenceID(3digits)`

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
