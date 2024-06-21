Kinect Interactive Nature Experience – README
- Kinect Interactive Nature Experience: https://youtu.be/_bP4hAyujCM
- Github link: https://github.com/marcelloferrand/KinectInteractiveNatureExperience
- Video documentation: https://youtu.be/ixXaq-CI5lU
- Interactive audio demonstration: https://youtu.be/Mm0eWptT7h4


This project consists of an audio reactive experience, which allows users to use Kinect to manipulate and perform an audio-visual representation of “nature”.
This was achieved using TouchDesigner and Ableton, utilising the TDAbleton built-in component which connects the two programs.
I started by working on the visuals, attempting to achieve interesting patterns and textures that resembled elements of nature like water, ripples and leaves. This was the most challenging and time-consuming part of the project, as it was my first time using TouchDesigner and creating audio reactive visuals. This was achieved using “Noise TOPs”, feedback loops and experimentation. I then made sure that the colour of the patterns were coherent and relevant to the theme that I was trying to achieve by modulating the “Levels TOP” to assign a green and blue colour palette. 
After I was satisfied with the visuals, I started to test audio reactivity to see what parameters worked best to modulate to get my desired result.
For this I focused on the audio features and delved into the world of Kinect, TouchDesigner and TDAbleton. To accomplish this, I analysed the Kinect data and extracted the X and Y axis of each hand to control different parameters and to control different variables such as:
-	Left hand on the X axis: Fine tune of pad to change tone and make sound evolving
-	Left hand on the Y axis: Octave of clicker synth to create “cricket” sound
-	Right hand on the X axis: Amount of reverb on the master channel
-	Right hand on the Y axis: Low pass filter on the master channel

After recording the audio, I imported it in TouchDesigner and used the “audioAnalysis” component to perform FFT on the audio and extract certain frequencies to modulate the visualisation and make it react to certain elements of the sound.
Finally, I ensured that all the elements corresponded with one another, and that the audio visualisation was cohesive with the experience of being in nature, but in a digital environment. I am highly satisfied with the outcome of the project, as it enabled me to not only to enhance my understanding of TouchDesigner and its compatibility with Ableton, but also build an immersive application that can be versatile in its implementation.
