# AR Tag Detection and Tracking
There are two aspects to using an AR Tag, namely detection and tracking, both of which will be implemented in this project. The detection stage will involve finding the AR Tag from a given image sequence while the tracking stage will involve keeping the tag in “view” throughout the sequence and performing image processing operations based on the tag’s orientation and position (a.k.a. the pose).

## DataSet Download
The dataset can be downloaded from here : 
https://drive.google.com/open?id=1ij1_lzTf1-zFl5kzlxROlHquEemW4o3h

Place the `Input Sequences` and `Reference Images` in the same folder as the code.

## How to run code
1. Unzip the folder which has the code and input sequences
2 . Each of the following code parts asks you to select the input sequence you would like to run the code with.
3. Run `python ./part_1.py` for AR Tag detection (1)
4. Run `python ./part_2.1.py` for Superimposing Lena image on AR Tag (2)
5. Run `python ./part_2.2.py` for Placing virtual cube on AR Tag (3)

## Results

  <p align="center">
  <img src="https://github.com/ramaprashanth/perception-for-autonomous-robots/blob/master/AR%20Tag%20Tracking/result_1.png">
  </p>

  <p align="center">
  <img src="https://github.com/ramaprashanth/perception-for-autonomous-robots/blob/master/AR%20Tag%20Tracking/result_2.png">
  </p>
