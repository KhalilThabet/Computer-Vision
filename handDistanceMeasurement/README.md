## Hand's Distance Measurement

This program is an attempt to detect the distance from an object to the screen cam.

**Solution Explanation**
First, we imported the handDectector module from mediapipe ML solutions which allows us to apply landmarks on the hand. 

The next step is simple, we try to select 2 distance points that are equidistant in most cases (no risk of distorting the distance) and measure the center of our line.

<br>
    <kbd> <img src="https://google.github.io/mediapipe/images/mobile/hand_landmarks.png" /> </kbd>

<br>
And for the last steps we take samples of the distance between the cam and the center of our line and make lists of propotion of cm and hypothenus calculated by the formula of pytagore.