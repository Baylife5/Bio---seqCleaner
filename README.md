# Bio---seqCleaner
In this exercise, you will create a program to “clean up” a sequence of DNA by removing ambiguous bases (denoted by “N”) output from a sequencer. Your task is to create a Python program called seqCleaner that:

* asks for and collects a sequence of DNA using input()

* removes the ambiguous parts of the sequence, outputs the “cleaned” sequence, replacing the ambiguous parts with a count in {}’s. For example, if I enter the * * * 

* sequence of DNA “AaNNNNNNGTC” (without quotes), the program will output: AA{6}GTC
