# Audio Mixer

Have you wondered what a DJ does? Yes, mixing different sounds to create an even better one. Exactly what an audio mixer is used for.

![](https://media.giphy.com/media/vybWlRniCXzZC/giphy.gif)

Unity provides an efficient tool that can be used to mix various audio sources, apply different effects and also perform mastering. Mastering is a form of audio post production, it can make the appearance of your game very appealing and soothing to hear. You can open the Audio Mixer from Window->Audio->Audio Mixer or Ctrl+8 which is the default hotkey.

![](https://user-images.githubusercontent.com/44625252/152988019-c4ddfd84-3846-4b63-bfaa-b079a0293f96.png)

You can give the name of your audio mixer in the first box. Basically, an audio mixer is an asset and you can have multiple mixers active at any time. There is always a Master group and then you can add different groups to define the structure of your mixer.

![](https://user-images.githubusercontent.com/44625252/152988071-485f3cbe-bb04-433b-9ff3-4bfc48833c6a.png)

You can also capture the settings of all the parameters in a group as a snapshot and hence, transitioning between multiple snapshots can provide your game with various themes.

![](https://user-images.githubusercontent.com/44625252/152988110-7e4eecdc-d322-40a9-ba4b-400c28ce5eb9.png)

The final option, Views allow you to disable the visibility of certain groups within a mixer and set this as a view. This also helps you to make transition between different views as required by your game.

# Microphone

Have you ever made a video? Or seen any youtuber recording with a mic in video? Of course, Unity also allows teh usage of microphone to record sounds.

![](https://media.giphy.com/media/eLjg1anm4bqkkX1DJE/giphy.gif)

The Microphone class can be used to record an Audio clip using a connected microphone. The device property can be used to get a list of all connected microphone devices:

```
//Get list of Microphone devices and print the names to the log
void Start()
{
  foreach (var device in Microphone.devices)
  {
    Debug.Log("Name: " + device);
  }
}

Other methods that can be used are

**End** – Stops recording

**GetDeviceCaps** – Get the frequency capabilities of a device

**GetPosition** – Get the position in samples of the recording

**IsRecording** – Check if the device is currently recording

**Start** – Start recording with device

Try to record some audio with your computer system's inbuilt microphone and Unity's microphone. Is there any difference?

![](https://media.giphy.com/media/TtFqXVtOQkomI/giphy.gif)

