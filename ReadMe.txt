Pitch Detection Algorithm

YIN_algorithm.go - Reads a mono 16 bits wav  file and detects the main pitch of the
                   audio, and the probability of it being correct.
                   With this information you can detect the note that is played.
The frequency detection algorithm is based on YIN algorithm more specifically
a port to the Go ( GoLang ) programming language of the C implementation 
on https://github.com/ashokfernandez/Yin-Pitch-Tracking/blob/master/Yin.c

Author:  Joao Nuno Carvalho
Email:   joaonunocarv@gmail.com
Date:    2017.12.9
License: MIT OpenSource License

Example of output:

Sample rate:  44100
Seconds: 0 - Main Frequency: 984.417082 - Probability: 0.999044
Seconds: 2 - Main Frequency: 990.320629 - Probability: 0.997262
Seconds: 4 - Main Frequency: 989.257290 - Probability: 0.997597
Seconds: 6 - Main Frequency: 988.253456 - Probability: 0.997996
Seconds: 8 - Main Frequency: 991.866481 - Probability: 0.997232
Seconds: 10 - Main Frequency: 991.771215 - Probability: 0.997156
Seconds: 12 - Main Frequency: 991.162099 - Probability: 0.996812
................................................................
................................................................
................................................................
Seconds: 46 - Main Frequency: 987.661482 - Probability: 0.998325
Seconds: 48 - Main Frequency: 987.597377 - Probability: 0.998335
Seconds: 50 - Main Frequency: 988.092516 - Probability: 0.998054
Seconds: 52 - Main Frequency: 986.479938 - Probability: 0.998543
Seconds: 54 - Main Frequency: 984.867540 - Probability: 0.999011
Seconds: 56 - Main Frequency: 985.571353 - Probability: 0.998717
