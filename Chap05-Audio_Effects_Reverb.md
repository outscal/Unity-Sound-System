# Audio Effects

Applying Audio effects can change the tone of your game and push it towards realism. The effect components can be added to the object with the Audio Listener or Audio Source. Ordering the components in case of multiple effects would be an important part to manage as otherwise that can lead to undesirable effects. The below is a very good example of using 2 types of Audio effects, the Audio Listener has been modified by an Audio Low Pass Filter and then an Audio Chorus filter.

![Audio_Effects](https://user-images.githubusercontent.com/44625252/152987570-166f4a83-35dc-4e58-8e69-b67fa02c1edb.png)

The ordering can be changes anytime by opening the context menu in the inspector and selecting the Move up/Move Down commands. Of course, it is also possible to untick/tick the active states of the components, and the changes can also be applied by running a script at specific conditions. This needs to be carefully as some of these effects are also CPU intensive.

Can you think of an audio effect that can be used to show a gun blast?

![Gun Effects!](https://media.giphy.com/media/8TzpRpIxG4qvA0KLzR/giphy.gif)

# Audio Reverb Zone

Reverb zones are used for distorting the audio clip depending on where the audio listener is located inside the reverb zone. A very good example is when you are entering an underground tunnel, for example, where the sound needs to gradually change from a point where there is no ambient effect to a place where there is one.

![Audio_Reverb](https://user-images.githubusercontent.com/44625252/152987706-85586e1e-1473-4328-9b88-6a05dc18419d.png)

Audio reverb filter can also be used that comes with a set of reverb presets already defined, as shown below:

![Reverb_Preset](https://user-images.githubusercontent.com/44625252/152987746-e5eab7d4-ab29-406b-b163-5f0fdbdff9bf.png)

Think of some scenarios where Reverb can be used in a game.

![Reverb!](https://media.giphy.com/media/GLjbMKJdoob60/giphy.gif)

See you in the next one!
