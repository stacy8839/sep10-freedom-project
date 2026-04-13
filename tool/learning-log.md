# Tool Learning Log

## My Tool is [A-Frame](https://aframe.io/): **X**

---

### 03/30/26
* Started experimenting with A-Frame to understand how 3D scenes are created using HTML-like tags.

* Looked at how objects like <a-box>, <a-sphere>, and <a-plane> work.
Added a sky background using <a-sky> to make the scene feel like a world instead of empty space.

* I also Tested object positioning like the following:

x = left/right
y = up/down
z = forward/backward

* For example ➜

position= "0 1.5 -3" this places the object slightly above the ground and in front of you

* Some Questions I have!

Can objects change color when the user clicks them?
Can I make objects move when a key on the keyboard is pressed?

* Next Steps
Try adding textures or images to objects to make them more visually appealing!

### 04/13/26:
Cool things I learned while exploring and tinkering with my tool Aframe!

#### The Instant 360-degree!
You can create a full 360-degree photo viewer with just one line of code!

The code:

<a-scene>
  <a-sky src="your-360-image.jpg"></a-sky>
</a-scene>


#### Annimated Interactions!
You can add complex animations without Javascript! This can be done by just adding the animation component to any HTML tag.

For example:

<a-box color="purple"
       animation="property: rotation; to: 0 360 0; dur: 5000; loop: true">
</a-box>


* Some Questions I have!

*  Can I hover over objects in Aframe, if so which component can I use?

*  I commonly overhear "painting in 3D" in Aframe, what does that mean?

*  How do users create fully immersive VR and AR experiences directly in the browser using HTML?


* The Next Steps I will take!

I will try importing 3D models and images into the scene.


<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
