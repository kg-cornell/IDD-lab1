# TuneMatcher (Updated the idea with second iteration)

TuneMatcher is a simple tool for prototyping interaction to detect whether the user has played the right tune. TuneMatcher takes the user played tune as an input and matches the sound of the tune with the orginal tune from the webserver. If the match is successful, it gives a green light and applause output. If the match is unsuccessful, it gives red light and laugh as output.

# Storyboard

Traditionally, a guitar learner would have to find a tutor to coach them to play guitar. However, best tutors are not always accessible. Moreover, tutors are expensive and not flexible with time.

<img src="/imgs/In-person Learning.png" alt="system diagram" width="720"/>

Guitar learners, who seek flexibility and convenience, resort to YouTube tutorials. However, YouTube tutorials are not personalized.

<img src="/imgs/Online Learning.png" alt="system diagram" width="720"/>

Introducing TuneMatcher! (Interation-1)

It not only shows you what notes to play at what point in time but also gives live feedback by matching the tunes that the guitar learner plays with the original tune.

<img src="/imgs/TuneMatcher Envi.png" alt="system diagram" width="1080"/>

TuneMatcher (Iteration-2)

The interaction with the laptop is now eliminated. A digital interface is mounted on the top of the fret board.

<img src="/imgs/Screen Shot 2022-09-11 at 8.49.19 AM.png" alt="system diagram" width="1080"/>


The user can now select the song that they want to play on the digital interface on the fret board. The display will start showing the user the notes/chords that they have to play, helping the user to play the right notes.

<img src="/imgs/Screen Shot 2022-09-11 at 8.48.20 AM.png" alt="system diagram" width="1080"/>

The display throws a green light each time the user play the right chord/note.

<img src="/imgs/Screen Shot 2022-09-11 at 8.48.06 AM.png" alt="system diagram" width="1080"/>

The display throws a red light each time the user play an incorrect chord/note. It also buzzes, vibrates and stops showing the next note/chord, indicating the the user has to redo the exercise.

<img src="/imgs/Screen Shot 2022-09-11 at 8.47.45 AM.png" alt="system diagram" width="1080"/>

When the user completes the song entirely and correctly, the display claps, along with throwing a green color.

<img src="/imgs/Screen Shot 2022-09-11 at 8.47.28 AM.png" alt="system diagram" width="1080"/>

# Act out the Interaction

Iteration-1: The interaction was enacted by using Tinkerbelle on laptop and phone. The phone was held by proxy guitar coach. The porxy coach turned the light green and played applause sound when the tune played on guitar was correct, and turned the light red and played laugh sound when the tune on the guitar was incorrect.

Iteration-2: The interaction was enacted by using Tinkerbelle on laptop and Apple Watch. The watch was mounted on the guitar as a ditital interface. The video recorder turned the light green and played applause sound when the tune played on guitar was correct, and turned the light red and played buzzer sound when the tune on the guitar was incorrect.

# Prototype

A prototype was created using Matchering 2.0 GitHub code. The code takes in 2 inputs - tune played by the guitar learner and original tune - and gives an output of whether the both the tunes match.

# Record the interaction (iteration-1)

[![Watch the video](https://github.com/kg-cornell/IDD-lab1/blob/42573797c90765f43768ca1146350e312c2ec560/imgs/Recording.png)](https://www.youtube.com/watch?v=QzDdfrWDlvg)

Iteration-2 (correct interaction)

[![Watch the video](https://github.com/kg-cornell/IDD-lab1/blob/42573797c90765f43768ca1146350e312c2ec560/imgs/Rec 2.png)](https://youtu.be/K20l5CO8HIo)


Iteration-2 (incorrect interaction)

[![Watch the video](https://github.com/kg-cornell/IDD-lab1/blob/42573797c90765f43768ca1146350e312c2ec560/imgs/Rec 3.png)](https://youtu.be/QhPgPFhYPPQ)
