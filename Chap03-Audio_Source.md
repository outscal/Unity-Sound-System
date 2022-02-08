# Audio Source

The audio source is the primary component that you will attach to a GameObject to make it play sound. This is the component that is responsible for playing the sound. In common development practice, it's generally a good idea to make an empty gameObject to act as the Audio Source and make it a child when you're dealing with large, complex structures, so you have a clear idea of where the Audio Source is.
To add the Audio Source component, select one GameObject, and go to the Inspector tab. Click on Add Component and search for Audio Source.
The Audio Source component has quite a few properties which we can tinker around with. This includes its pitch, panning, spatial blending (We'll get to that later), and if you open the 3D Sound Settings, you will find options for adding Doppler Effects and volume rolloffs.
The more interesting part here is the AudioClip slot which is where the sound effect to be played goes. An Audio Clip is a sound file that is loaded into an AudioSource. It can be any standard audio file such as .wav, .mp3, and so on. An Audio Clip is a component within itself. Audio source will playback the Audio Clip when triggered through the mixer, through code or by default, when it awakes.

![Audio_source](https://user-images.githubusercontent.com/44625252/152986666-b1100971-9cfe-436c-9754-54dbf92e24ff.png)

There are a lot of settings that you can tinker with to observe various ways of applying these sounds. For example, the “Play On Awake” option when un-ticked (ticked by default), will stop the sound from playing on awaking or at the start of the scene itself.

---
<aside>

> 💡 🚀 **[Join Discord Server](https://discord.gg/J5zDscnzms) → Get your doubts solved by experts instantly**
</aside>

![discord_png](https://user-images.githubusercontent.com/44625252/152948137-97167a02-bba1-47b9-b33c-fb2ac41f11fc.png)

---
