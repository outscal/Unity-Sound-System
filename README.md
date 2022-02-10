# Introduction

After creating a game with the graphics and programming for the game logic, you will still be missing an important part of the game development which is sound. Sounds add realistic behaviour to the game, with a soothing effect – this can make the difference between a bad game and a good one. 

So, put on your headset and microphone and start building some awesome sounds for your game.

![Intro!](https://media.giphy.com/media/fYkWqB2Ay1VfuLaFU9/giphy-downsized-large.gif)

Most of the standard audio file formats are playable in unity which also has features for playing sounds in 3D space. You can play around with these settings and create different sounds in required moments in your game. Even Unity can also record audio from any available microphone on a user's machine for use during gameplay or storage and transmission.

The **Audio Manager** can be used to check and edit some of the settings for audio in the **scene**. To open it, goto **Edit > Project Settings > Audio**

![Audio](https://user-images.githubusercontent.com/44625252/152986137-740da521-9919-4153-ab2b-d3be8ab8599b.png)

Audio is quite an interesting concept to cover, not only in game design but when studying its nature in general. The way it's perceived depends on a lot of factors, which have to be taken into account when you're trying to control or use it.

Perception of audio generally involves the position of the source and how fast it's moving if it's moving at all (If you've studied Physics, you may be familiar with the Doppler Effect).

![Sound wave!](https://media.giphy.com/media/pv9vqIFuUD44TdnR73/giphy.gif)

In Unity, the positioning of a source of audio is important to characterize its source. For example, we need to make sure that a gameObject playing the sound of a waterfall matches with an actual waterfall gameObject, and that the player's perception of that sound feels real. Getting louder as the player gets closer, making sure the audio panning varies as the relative position of the waterfall changes with respect to the player, and so on.

Usually we have to deal with 2 main components related to Audio in Unity, which are:

1. Audio Listener
2. Audio Source

A closer look at these components in the next chapters will help understand the use cases for these and application in various scenarios. 

![MoveOnSB!](https://media.giphy.com/media/mgStALXN5ImLS/giphy.gif)

Let's see if you can beat SpongeBob in making sounds!!!
