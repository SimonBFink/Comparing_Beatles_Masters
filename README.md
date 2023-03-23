COMPARING BEATLES' MASTERS

My final project for Spring 2023 Code Louisville, Data Analysis with Python

PROJECT TITLE: 

Comparing Beatles' Masters, 2009 and 2015

PROJECT DESCRIPTION:

The aim of this project is to use the tools of python to compare different versions of the same song that the Beatles have released in the Digital Streaming era. 

In the last two decades, the Beatles have re-released their classic albums and singles several times digitally. Often times, the new release features new "mastering". What is mastering? To quite iZotope software's page:

    Mastering is the final polish that turns a finished mix into a release that’s ready for listeners to experience on all devices—from tiny iPhone speakers to massive dance club sound systems.

The Beatles have always been famous for using cutting edge technology in their recordings, and these recent releases are no exception. The new masters are made from the original audio by some of the leading audio professionals working today.

In this project we'll be focusing on two versions of "Strawberry Fields Forever." One is from 2009 and the other is from 2015. Both use the same original audio recorded in 1967. 

One well known trend in audio mastering is that things get progressively louder and louder. Louder tends to sound "better" and more ear-catching (at least on initial listen), so there has long been a temptation to produce louder and louder masters. This has been true at least since the 1960's, if not before. New digital audio technology gives audio engineers even more tools to make the music louder. 

This project will compare the loudness of the two versions of "Strawberry Fields Forever" by looking at the amplitude of the audio files. 

There is also an Addendum at the end of the project that explores the famous "splice point" of the song. The original mix of the song combinbined two different recordings of it played in different keys and tempos. Here I explore whether we can see evidence of the difference between the two recordings using a spectrogram. 

THE DATA
The data we'll import includes two .wav audio files. 

PACKAGES NEEDED:
pandas
matplotlib
numPy
ipynb
pydub
librosas

PROJECT FEATURES
1. Imported data from a .wav files.
2. Manipulated data: cleaned it up and made it usable.
3. Analyzed aspects of the data including song length, lenghth of silence before and after music, and the mean amplitude of each version.
4. Visualized the data in 2 plots with matplotlib.
5. Interpreted the data in the Jupiter Notebook file.

INSTRUCTIONS:
1. Open the folder ("Final_Project").
2. Open the "ComparingAudio.ipynb" file as a Jupyter Notebook.
3. Press "Run All" if the code hasn't been run yet.
4. Read and scroll down to see the coding steps, visualization, and interpretation. 




