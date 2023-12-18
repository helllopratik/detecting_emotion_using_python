# detecting_emotion_using_python
This repository will help detecting emotion from audio using python terminal
This program can be run in linux or windows terminal (CMD) using anaconda Prompt.
You need latest python and following pip files
##
import librosa  # Audio processing library
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import LabelEncoder
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score
from glob import glob
import joblib;
import librosa
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import LabelEncoder
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score
from glob import glob
##

<h>FOR TESTING THE LIVE EMOTION </h>
##
import tempfile
import librosa
import os
import pyaudio
import numpy as np
import speech_recognition as sr
from sklearn.tree import DecisionTreeClassifier
from sklearn.preprocessing import StandardScaler
import joblib;
##

This program was tested on win 11 using anaconda prompt.

To run this repository,
1) if .pkl file exists then open anaconda prompt and type
   *) python main.py
2) if .pkl file doesnt exist then you have to train data, for that run
   python test.py
3) again execute python main.py to test emotion.



If any error occur, please do report or mail me. Thanks.
any update or fix is accepted <3
