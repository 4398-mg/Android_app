# Captonse Android App

Wimbo is a neural network based music generation platform that is encapsulated by client applications for various platforms. Our music generation allows users to tailor generated music to their tastes by enabling them to set the song's genre, tempo, and length. The underlying engine for song generation is constructed through the use of recurrent neural networks and spanning datasets. Users however never interact directly with the neural network, they instead interact with the generation engine through a front-end Web page. Based on a song’s parameters to generate the song, the neural network based song generator engine outputs a song in MIDI format. To generate music, we train models through genre-wise datasets and the utilization of recurrent neural network. The generation of the music from the neural network is based around continuous predictions on what note will occur based on previous notes. This process is performed sequentially alongside our trained models in order to produce coherent music.


The features of this App are:

        - Log in using Gmail
        - Generate new songs and add them to your history
        - Edit song titles
        - Delete songs
        - Download Music sheets
        - Download Songs
        - Play any song from your history

Instructions for how to build, install, and configure the entire project on your target device:

        - Android Studio 
 
                - compileSdkVersion 27
		
                - minSdkVersion 21

                - targetSdkVersion 27




