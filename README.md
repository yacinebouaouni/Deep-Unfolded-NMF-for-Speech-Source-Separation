# Deep-Unfolded-NMF-for-Speech-Source-Separation

This project is an implementation of the paper "Deep Recurrent NMF for Speech Separation by Unfolding Iterative Thresholding" of the authors : Scott Wisdom, Thomas Powers, James Pitton and Les Atlas. The original paper code has two major constraints :

* It was develloped using both Python and uses API calls to Matlab.
* The code is highly dependent on the private dataset CHiME2.

In this project we propose a full implementation in Python 3 (No Matlab) and can be used with simple datasets (e.g. wav files)
