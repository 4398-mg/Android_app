Wimbo is a neural network based music generation platform that is encapsulated by client applications for various platforms. Our music generation allows users to tailor generated music to their tastes by enabling them to set the song's genre, tempo, and length. The underlying engine for song generation is constructed through the use of recurrent neural networks and spanning datasets. Users however never interact directly with the neural network, they instead interact with the generation engine through a front-end Web page. Based on a song’s parameters to generate the song, the neural network based song generator engine outputs a song in MIDI format. To generate music, we train models through genre-wise datasets and the utilization of recurrent neural network. The generation of the music from the neural network is based around continuous predictions on what note will occur based on previous notes. This process is performed sequentially alongside our trained models in order to produce coherent music.

Feature list:
	1. Google Login
	2. Parameter selectors "Genre", "Tempo", "Duration" and Generate button
	3. Music Player to play the generated song
	4. Music Playlist contain all the generated songs 
	5. Download, Delete, Rename, Musicsheet buttons with functionalities
Instructions for how to build, install, and configure the entire project on your target device:
	1. Need Android Studio 
	2. Configuration:  
		compileSdkVersion 27
		defaultConfig {
			applicationId "edu.temple.musicgen"
			minSdkVersion 21
			targetSdkVersion 27
			versionCode 1
			versionName "1.0"
			testInstrumentationRunner "android.support.test.runner.AndroidJUnitRunner"
			}
