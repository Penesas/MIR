# MIR
Project

In this project, I study the music genre classification.

The main code file is in FinalProject.ipynb.
I used keras(tensor flow) to train the data from GTZAN which provides a great data site for music analysis.
GTZAN data set could be downloaded from here:  
http://marsyasweb.appspot.com/download/data_sets/

The original data set was using “.au” audio file, I used footbar2000 to transform them to “.wav”

The packages that required for this project were used for this course. 

I found some sound processing python code that would help me to process the data that I download from GTZAN.
audiofile_read.py
rp_extract.py
wavio.py

The result is ok compare to what have existed online. 

Something else may work:
The human reaction for a music genre is mostly base on the instruments. 
So to improve the accuraccy, one way is to extract instrument frame out of spectrum.
For example, I can replace the low requency mel frame to drum play, so '1' for 1 beat, 0 for else. Ignoring the contiune vibration sound, this might clear out the interferes and increase the accuracy.


Cite: https://github.com/tuwien-musicir/DL_MIR_Tutorial by Thomas Lidy
