# Video Doorbell, Lab 7

*A lab report by Vini Tripathii*

### Current suffering from Murphy's Law: My code for the required portion is done and I was working on the creative part of the assignment when my raspberry pi appears to have fried (it is not responding). I borrowed Fei's raspberry pi but it is not responding either. Currently working on trying to get a raspberry pi so I can finish and take video.

### In This Report

1. Upload a video of your version of the camera lab to your lab Github repository
1. As usual, update your class Hub repository to add your [forked IDD-Fa18-Lab7](/FAR-Lab/IDD-Fa18-Lab7) repository.
1. Answer the questions in-line below on your README.md.

## Part A. HelloYou from the Raspberry Pi

**a. Link to a video of your HelloYou sketch running.** 
https://drive.google.com/file/d/1jbSwtCZGpogygwU5vNl4CIiYhqvLwrnn/view?usp=sharing

## Part B. Web Camera

**a. Compare `helloYou/server.js` and `IDD-Fa18-Lab7/pictureServer.js`. What elements had to be added or changed to enable the web camera? (Hint: It might be good to know that there is a UNIX command called `diff` that compares files.)**

The node-webcam librarry was added to enable the web camera. In addition, a webcam instance with default parameters was created. The
takePicture function was then linked to the button "Take a picture" on the web page. 
**b. Include a video of your working video doorbell**
https://drive.google.com/file/d/1ZpCR7GdJqNdGZzebPKUrW_bGK91yqFGG/view?usp=sharing

## Part C. Make it your own
https://drive.google.com/file/d/1b5Fb5-n3sKQH9k25wN2vqZOiGtnmFGUP/view?usp=sharing
I add an auidble timer (3 quarter notes played in succession, last not light pitch) as a warning for when the photo is being taken. I used the delay attribute of the webcamera to stall the photo process to synchronize with the notes.
Note: The volume is very soft in the video 
