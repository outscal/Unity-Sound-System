# Audio Listener

Here's a trick question - What do you use to listen for sounds?

Duh! your ears ofcourse. Imagine what would happen if humans didn't have ears. Hmm, probably we would have all been deaf to sounds. So, a listener is essentially something that your game needs so that sounds can be caught and heard by the player at the other end. I wish we could add ears to Unity, but there is something better ofcourse. You get a ear that is customizable according to needs of your game.

![](https://media.giphy.com/media/MWKEOz30XSS253y1od/giphy.gif)

This is a component that's automatically attached to the main camera every time you create a scene. It doesn't have any properties, since its only job is to act as the point of perception. Leaving the Audio Listener as is, is recommended.
Audio Listener is the component that is automatically attached to the main camera every time you create a scene.
This component listens to all audio playing in the scene and transfers it to the system's speaker. It acts as the ears of the game. Only one AudioListener should be in a scene for it to function properly. Imagine making a video and consider this to be a microphone that receives the input from any given Audio sources in the scene, think how multiple microphones may cause unexpected effect in your video. Same effect would be observed in Unity.

![](https://user-images.githubusercontent.com/44625252/152986435-b82ee526-5883-4c7f-9beb-814dc8cd6c48.png)

You can either attach the Audio listener to the Camera or the main Player GameObject depending on the needs of your game. Think of what suits the gameplay better. Reverberation would also be applied to all audible sounds in the scene if the listener is within the boundaries of a reverb zone. You can also add different audio effects to the listener which will in turn be applied to all audible objects in the scene.

Are you all ears? Head on to the Next!!!

![](https://media.giphy.com/media/xT9IgpxorXdkhoQle8/giphy.gif)
