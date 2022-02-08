# Audio Listener

This is a component that's automatically attached to the main camera every time you create a scene. It doesn't have any properties, since its only job is to act as the point of perception. Leaving the Audio Listener as is, is recommended.
Audio Listener is the component that is automatically attached to the main camera every time you create a scene.
This component listens to all audio playing in the scene and transfers it to the system's speaker. It acts as the ears of the game. Only one AudioListener should be in a scene for it to function properly. Imagine making a video and consider this to be a microphone that receives the input from any given Audio sources in the scene, think how multiple microphones may cause unexpected effect in your video. Same effect would be observed in Unity.

![Audio_listerner](https://user-images.githubusercontent.com/44625252/152986435-b82ee526-5883-4c7f-9beb-814dc8cd6c48.png)

You can either attach the Audio listener to the Camera or the main Player GameObject depending on the needs of your game. Think of what suits the gameplay better. Reverberation would also be applied to all audible sounds in the scene if the listener is within the boundaries of a reverb zone. You can also add different audio effects to the listener which will in turn be applied to all audible objects in the scene.

---
<aside>

> 💡 🚀 **[Join Discord Server](https://discord.gg/J5zDscnzms) → Get your doubts solved by experts instantly**
</aside>

![discord_png](https://user-images.githubusercontent.com/44625252/152948137-97167a02-bba1-47b9-b33c-fb2ac41f11fc.png)

---
