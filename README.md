# HU_CISC699_FInal_Applied_PROJECT

This is the source code for my CISC 699 Final Applied Project under Prof. Abrar Qureshi in Harrisburg University of SCience and Technology titled "MUSICON , a music player emulator" supported by MySQL DB in the back end.  The main goal of this project is to create music player emulator that have basic functionalities to enable users to play music and digital audio files. This product is capable of a feature that allows users to create a playlist using a database to store, update, insert, delete information on the created playlists. The MusicOn emulator application must be able to play a song, create and display a playlist, pause, and resume a long song, and change the song, play the previous or next song. This application can play songs in multiple modes namely normal, loop, shuffle. This system can perform the features standalone as well as dependent on other features. 
The product in this project is a Music Player Simulator which can operate based on the user’s input and supported by a MySQL/Postgres SQL Database.

Project Proposal : 

MUSICON project is a software artifact, allowing users to play, pause, resume, and skip audio files as they wish. MUSICON starts with the display of its functions via an infinite loop for the user's comfort and usability. The major functionalities cover letting users check their permissions supported by the backend MySQL database. It allows users to create their own account and super users provide relevant access and the features available will be decided based upon the permissions. Superusers are responsible for any sort of maintenance related to DB w.r.t adding, deleting, and updating users and songs as and when items are available to be put in DB. MUSICON allows users to group the songs of their liking and place them under one category named playlist. Each user can create 1 or many playlists. Users are allowed to play audio files in any order which can be the sequential, random, or looped way. These modes are applicable to single audio files or multiple audio files via creating a playlist. It can mine the DB present in the backend to well assist users with their choice made from the existing menu options. It is an interactive music player emulator that requests user interaction at each, and every choice made. MUSICON is well supported by a tightly connected, fully relational database in the back end.

Here is the menu of the application based on user input: 

------------------------------ MUSICON CATEGORIES MENU ------------------------------
0.  Muiscon Category Options Menu
1.  Music
2.  Podcasts
3.  FM Radio
4.  Exit from Musicon
-------------------------------------------------------------------------------------
------------------------------ MUSIC MENU ------------------------------
0.  Music Options Menu
1.  Add a new song to library
2.  Delete a song from library
3.  Show songs in library
4.  Search by song name or artist
5.  Play a song present in Library
6.  Create a playlist
7.  Show all playlists
8.  Add songs to the playlist
9.  Play songs in playlist
10. Show recently played songs
11. Music mix of the songs
12. Return to Categories Menu
13. Exit from Musicon
------------------------------------------------------------------------

------------------------------ PODCAST MENU ----------------------------
0.  Podcast Options Menu
1.  Add a new Podcast to library
2.  Delete a Podcast from library
3.  Show Available Podcasts in library
4.  Search by Podcast name or Podcaster
5.  Search by Podcast Category
6.  Play a Podcast present in library
7.  Return to Categories Menu
8.  Exit from Musicon
-----------------------------------------------------------------------

------------------------------ FM RADIO MENU --------------------------
0.  FM Radio Options Menu
1.  Add a new FM station to library
2.  Delete an FM station from library
3.  Show Available FM Stations in library
4.  Search FM Station by Frequency
5.  Search FM Station by Category
6.  Search FM Station by Location
7.  Play an FM Station present in Library
8.  Return to Categories Menu
9.  Exit from Musicon
----------------------------------------------------------------------

This is coded in Python programming language using Jupyter notebook and is capable of running standalone with the support of Pygame, Pandas, Tkinter, VLC , pymysql. Please drop me a comment or email me at prful.munugoti@gmail.com for any questions.
