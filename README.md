# How to generate music using deep learning: a simple approach

This project is the first step of a bigger project: creating music with different instrument and including the timing using neural network.

To begin with, some parts of this project are inspired of the Sigurður Skúli’s work on his project: https://github.com/Skuldur/Classical-Piano-Composer.

In this version, only one instrument is allowed and the time (the time between two notes or chords and the duration of each note/chord) is not generated by the neural network but manually implemented.

The goal of this project is to show how we can apply NLP techniques to music. I hope it will also help people starting with text/music generation and don't know how and where to start. In this idea, I will describe all step and try to use the simplest solution and premade function/class.

This project is mainly based on two libraries: Pytorch for the neural network and music21 for data preprocessing.

We will use music from a the videogame licence Final Fantasy: those songs are "simple" and all use one instrument: the piano. We will also provide another dataset with classic music from Bach, Beethoven and Tchaikovsky.

Finally, I will add more features to this model later (like the time and more than one instrument) when I will have decent results.

Thanks for reading!