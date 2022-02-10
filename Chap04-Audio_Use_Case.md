# Use Case for using audio in a Game

Enough theory, let's get ready to implement some sounds in our game!!!

![VideoSound!](https://media.giphy.com/media/xUPJPjTKii41WYbZHW/giphy.gif)

The example below if of a 2D platformer where the player sounds and game sounds have been demonstrated.

Steps to add an audio clip for a specific sounds in an organised manner using singleton script:

1. First step is to determine the audio clips that you will be needing for each scenario, the figure below shows an Audio folder in a unity project with different types of audio clips for different objects, environments and situations in the game

![Determining_audio](https://user-images.githubusercontent.com/44625252/152986892-cefdbbe8-3f5d-41b0-8e16-7ec7c1b2ddda.png)

2. Check if the audio listener is present with the required component in your game, in this case an empty object has been created which will hold all game background sounds

![Audio_Listener](https://user-images.githubusercontent.com/44625252/152986937-01c71adb-b526-4dbd-877e-970b20a7f008.png)

3. Create the Global SoundManager script (use any name as you see fit) for the static instance that we can then use globally to play the specific sounds for specific scenarios

![Sound_Manager_instance](https://user-images.githubusercontent.com/44625252/152986993-8696dfcb-f54f-4046-8095-686cf99180ff.png)

4. Create functions that can be called by other classes, in our case we have a list of enums that would hold sounds for each type of character

![Enum_sounds](https://user-images.githubusercontent.com/44625252/152987039-60c311d5-e290-45e0-86b3-36b95b0d6cfd.png)

5. To ease the process further, functions can be added as shown:

![functions_sounds](https://user-images.githubusercontent.com/44625252/152987081-92f8c773-bc94-4151-beba-fa3b9fae0924.png)

6. Finally, all we need is to call those functions at required situations, for example, the below code calls the PlayOnce function using the SoundManager Instance

![Key_sound](https://user-images.githubusercontent.com/44625252/152987129-bd76d303-5af7-4316-a869-04e0cfbbbea4.png)

Some useful inbuilt functions to play sound in unity are:

**Play()** – can be used to play any clip, will repeatedly play the clip provided

**PlayOneShot()** – will play the sounds only once when triggered

**PlayDelayed()** – can use a delay parameter to cause a delay for when the sound should be played from when it is triggered or called

**PlayScheduled()** – gives you a more accurate control over when the audio clip is played

Were you able to implement these concepts to add sounds to your game? Move ahead to learn few other audio features that Unity allows to implement.

![NextChapter!](https://media.giphy.com/media/xUPJPjTKii41WYbZHW/giphy.gif)
