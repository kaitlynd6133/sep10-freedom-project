# Entry 5
##### 4/20

## Content
For this project we continued on tinkering on our tool and learning about Aframe to become more familar with it. I visited the [Aframe](https://aframe.io/docs/1.7.0/introduction/) Website and watched videos on Aframe on [Youtube](https://www.youtube.com/playlist?list=PLWkWuhMLkR7D_VSEMkj45NIgF8i2dlUce) to learn about Aframe. I also learned more about Aframe on these [slides](https://docs.google.com/presentation/d/1C8xDyvXzVgtX3G8UdXVNEn2PWVnsLF0sPu4QMRCL7xY/edit?slide=id.g849c2abd37_0_0#slide=id.g849c2abd37_0_0) I learned how to position and rotate primitives better as well as changing the material of primitives, dimension attributes, and using the animation component.
#### My Cat Model
 With these knowledge I added things like whiskers, nose, a body, for my previous cat model and also made the cat wave on one side of its arm using animation. I used another cone to create its nose, the four cylinder for the whiskers, another bigger sized cones for its torso, two medium sized cones for its arms and another two spheres for the legs.

 **Example :**

 ```
<a-cone position="-.02 1.5 -4" radius-bottom="0.05" height="0.1" rotation= "190 0 0"  color="black"></a-cone>

<a-cylinder color="black" position="0.7 1.8 -4" rotation= "0 0 -70" height="0.6" radius="0.01"></a-cylinder>
<a-cylinder color="black" position="0.7 1.6 -4" rotation= "0 0 -100" height="0.6" radius="0.01"></a-cylinder>
<a-cylinder color="black" position="-0.7 1.8 -4" rotation= "0 0 70" height="0.6" radius="0.01"></a-cylinder>
<a-cylinder color="black" position="-0.7 1.6 -4" rotation= "0 0 100" height="0.6" radius="0.01"></a-cylinder>

<a-cone color="pink" position= "0 0.2 -5" radius-bottom="1.2" height= "1.5" radius-top="0.5"></a-cone>

<a-sphere position="-0.5 -0.8 -5" radius="0.5"  scale="0.8 1 1" color="pink"></a-sphere>
<a-sphere position="0.5 -0.8 -5"  scale="0.8 1 1" radius="0.5" color="pink"></a-sphere>

<a-cone color="#ED7794" position= "0 0.2 -5" radius-bottom="1.2" height= "1.5" radius-top="0.5"></a-cone>

  <a-cone position="-1 0.15 -5" rotation="0 0 110" radius-bottom="0.3" height="0.9" color="pink"></a-cone>

  <a-cone position="1 0.4 -5" rotation="0 0 -90" radius-bottom="0.3" height="0.9" color="pink" animation="property: rotation; to: 0 0 -50; dir: alternate; dur: 500; loop: true">
  </a-cone>

    </a-scene>

 ```
I added more shapes to my cat and adjusted the positioning, rotation, and radius. For the rotation I learned that `x rotation` is tilting sideways, `y rotation` is spinning, and `z rotation` is tilting fowards/backwards. I learned that adding the `radius` attributes defines the sizes of curved components. For instance, changing the `radius-bottom`to 0.01 on the cone for the nose is going to turn it into a cone.
#### Animation
Now for the animation part, I learned that the `property; rotation` part is to select what I want to animate. The `0 0 -50` is the target vaule. The cone starts at `rotation= "0 0 -90` to `0 0 -50`.  The `dir altnerane;` is to make the animation repeat going back and forth. The cone starts tiled -90 which is backwards to -50 forwards. The `dur` is the duration. Its going 500 milliseconds. Lastly, the `loop;true` is to run the animation forever.

## Skills
Skills that I gained from learning my tool is learning on my own, debugging, embracing failure.
#### How to Learn
I had to learn how to learn on my own for this project. I learned how to create 3d models using code and animate. I went to youtube and watch Aframe lessons and took down notes. I went on the Aframe website to learn about animation on my own to figure out how to make my cat model wave. I also searched up on google things that the website dosen't teach me.
#### Debugging
When tinkering with the aframe animation, i went through multiple errors so I had to learn how to debug them. For example, when I was trying to animate the cone the animation would just stop and not have the back and forth effect. So, I decided to ask chatgpt to explain to me what was wrong with my code. And then I soon figured out that I was missing the dir alternate to make it go back and forth.

#### Embracing Failure
I had to keep on making mistakes on the code in order to learn how to get the shapes where I wanted it to be. For example, when adujusting the positioning I would try different vaules and reload the preview to see where the shapes would end up. Theough trial and error, I gradually understood how each change affected the final result. 

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
