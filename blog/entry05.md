# Entry 5: Learning My Tool (AFrame)
##### 4/26/26

## AFrame Introduction

For my Freedom Project, I am using AFrame as my main coding tool. AFrame is a web-based coding tool that allows its users to create 3D and virtual reality scenes using HTML code. I ultimately decided to chose AFrame as my tool because my project is based on veterinary technology and I want bring my original ideas, like my **HoloVet scanner**, to life in a 3D environment. I also wanted to wanted to challange myself by learning something new, since I have never worked with 3D coding before as it is out of my comfort zone and I always perosnally believed it was a very rigorous thing to do.

## What I learned/ Where I learned it (Resources)

I mainly learned AFrame by using the <a href="https://aframe.io/"> official website </a> and some <a href="https://www.youtube.com/watch?v=jhEfT9YjLcU&t=147s"> YouTube videos </a>, although many videos were outdated. From this, I learned how 3D shapes are created using geometry, where each shape has its own properties like width, height, and radius.

I also learned that coding in A-Frame requires a lot of precision. Even small mistakes can cause the code not to work. For example, positions use three values (x, y, z) separated by spaces, not commas. For example:

* x = left/right
* y = up/down
* z = forward/backward
 
```html

position="0 1.5 -3" ✅

position="0,1.5,-3" ❌

```

At first, this was very confusing for me because I was used to seperating numbers with commas, so my code would not work even if it looked correct. The computer cannot guess what you mean, so you have to clearly define everything in the code. For example, even flat shapes like circles need extra properties to be fully visible. AFrame involves math, especially when working with dimensions and positioning. While the math I used was mostly basic, it still plays an important role in creating accurate 3D objects. Overall, I learned that AFrame is creative and fun but also requires patience and attention to detail.

### Experimenting

I experimented with shapes, backgrounds, positioning, and very simple animations. For example, I created a purple rotating box using this code:

```html

<a-box color="purple"
animation="property:
rotation; to: 0 360 0; dur;
5000; loop: true">
</a-box>

```


## Textures / Materials

I also explored how to change how objects look using the material component, such as adding color:

```html

<a-entity
 geometry="primitive: box"material="color: red"></a-entity>

```

This helped me understand that 3D design is not just about shape, but also a lot about appearance. However, many of the material properties were confusing, and I did not fully understand all of them yet.

## All of the skills I developed

* Persistance 
* Attention to detail
* Problem Solving

## Next Steps 

To be honest, I found A-Frame very difficult. I had to work independently, and most resources were hard to follow. I learn better visually, so the lack of clear tutorials in YouTube made it more challenging. Even though I struggled, I still learned through trial and error and understood how important details are in coding. And for that Im very much proud of myself. Next, I want to keep practicing with simpler and visual examples and representations. It would also be very cool if Aframe themselves would make videos for tutorials so users like me can better understand AFrame and start applying it to their own projects.

