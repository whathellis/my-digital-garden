---
{"dg-publish":true,"permalink":"/05-notes/animation/animation-basics-in-14-minutes-6-big-ideas-for-beginners-note/","contentClasses":"daily Thursday page-light-yellow","noteIcon":"","created":"2025-01-21T01:20:17.000+10:00","updated":"2025-01-21T16:22:36.477+10:00"}
---

[[Animation Basics in 14 Minutes (6 Big ideas for beginners)\|Animation Basics in 14 Minutes (6 Big ideas for beginners)]]
### Ideas behind the animation
![Videoframe_20240720_070354_com.huawei.himovie.overseas.jpg](/img/user/99/Embeds/Videoframe_20240720_070354_com.huawei.himovie.overseas.jpg)
>  The most important question you can ask yourself while you're animating is
> > [!question] How does this motion feel?{ #f81db2}


#### 1. Speed
>  If we make things closer together they move more slowly and if we make them further apart they move more quickly

If I want to animate this  coin moving from one side of the piece of paper to the other i take a picture of it move it a little and then take another picture and then keep going until i get to the other side.

1. So if i ask myself [[05 Notes/Animation/Animation Basics in 14 Minutes (6 Big ideas for beginners).Note#^f81db2\|How does this motion feel?]] i'd probably describe it as jumpy or jittery
2. You can see that the coin moves a little bit more consistently across the screen, there's no more jumpiness at the moment. The coin moves across the screen in one second or 24 pictures.
	- This motion feel I'd say smooth or consistent but maybe a little unnatural. The coin starts moving suddenly and then stops moving suddenly.
3.  If we wanted to make a more natural feeling, the coin could start moving slowly, speed up in the middle and then slow down at the end. We start slow by having the coins closer together and then gradually get further and further apart and then we slow the coin down by making the spacing closer and closer, until we come to a stop.
	- For this next step i'm going to exaggerate the speeding up and slowing down a little.
4. We don't always have to start slow and finish slow either. Here's an example of how changing the acceleration can entirely change the way the motion feels.
#### 2. Acceleration and deceleration - easing
`````col
````col-md
flexGrow=1
===
![Videoframe_20240720_050953_com.huawei.himovie.overseas.jpg](/img/user/99/Embeds/Videoframe_20240720_050953_com.huawei.himovie.overseas.jpg)
````
````col-md
flexGrow=1
===

````
`````
> To make things slow down or speed up, we gradually get closer and closer together or further and further apart from each other.


<div class="transclusion internal-embed is-loaded"><a class="markdown-embed-link" href="/05-notes/animation/the-trickiest-animation-principle-simplified-note/#0532c1" aria-label="Open link"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="svg-icon lucide-link"><path d="M10 13a5 5 0 0 0 7.54.54l3-3a5 5 0 0 0-7.07-7.07l-1.72 1.71"></path><path d="M14 11a5 5 0 0 0-7.54-.54l-3 3a5 5 0 0 0 7.07 7.07l1.71-1.71"></path></svg></a><div class="markdown-embed">



Easing require some sort of force to be happening, and that force needs to bee greater than any of the other forces applied. 

</div></div>

These motions all feel quite different, but they have the exact same timing, they all take 24 frames to get from one side of the screen to the other. All of  the difference in the way that they feel comes from the amount of space we put between the frames.

#### 3. Squash and stretch
> Stretching out the frame where we're moving the fastest and then squash it where we change direction.

Using it can add a bit of life to your motion and also give the audience a sense of what your objects are made of.
`````col
````col-md
flexGrow=1
===
![Videoframe_20240720_051527_com.huawei.himovie.overseas.jpg](/img/user/99/Embeds/Videoframe_20240720_051527_com.huawei.himovie.overseas.jpg)
````
````col-md
flexGrow=1
===
![Videoframe_20240720_051827_com.huawei.himovie.overseas.jpg](/img/user/99/Embeds/Videoframe_20240720_051827_com.huawei.himovie.overseas.jpg)
````
`````
#### 4. Anticipation
Anticipation does two key things: 
- *Builds up energy*
- Gives the audience an indication that *something's about to happen*
`````col
````col-md
flexGrow=1
===
![Videoframe_20240720_052014_com.huawei.himovie.overseas.jpg](/img/user/99/Embeds/Videoframe_20240720_052014_com.huawei.himovie.overseas.jpg)
````
````col-md
flexGrow=1
===
![Videoframe_20240720_052033_com.huawei.himovie.overseas.jpg](/img/user/99/Embeds/Videoframe_20240720_052033_com.huawei.himovie.overseas.jpg)
````
````col-md
flexGrow=1
===
![Videoframe_20240720_052046_com.huawei.himovie.overseas.jpg](/img/user/99/Embeds/Videoframe_20240720_052046_com.huawei.himovie.overseas.jpg)
````
````col-md
flexGrow=1
===
![Videoframe_20240720_052058_com.huawei.himovie.overseas.jpg](/img/user/99/Embeds/Videoframe_20240720_052058_com.huawei.himovie.overseas.jpg)
````
`````
 I have a ball that moves quite suddenly and then slows down to make it feel more natural. I could add a little bit of [[05 Notes/Animation/Animation Basics in 14 Minutes (6 Big ideas for beginners).Note#3. Squash and stretch\|squash]] to anticipate the movement. This makes it feel like we're building up energy and releasing it all at once.
 
#### 5. Overshoot
Overshoot is like a mirror image to anticipation. 
> Imagine you have a really big movement go too far and then bounce back. 
`````col
````col-md
flexGrow=1
===
![Videoframe_20240720_052330_com.huawei.himovie.overseas.jpg](/img/user/99/Embeds/Videoframe_20240720_052330_com.huawei.himovie.overseas.jpg)
````
````col-md
flexGrow=1
===
![Videoframe_20240720_065645_com.huawei.himovie.overseas.jpg](/img/user/99/Embeds/Videoframe_20240720_065645_com.huawei.himovie.overseas.jpg)
````
`````
It helps add:
- *weight*
- *springiness*

#### 6. Arc
Things in nature don't usually follow a perfectly straight line, more often than not natural movements follow some sort of arc.
> Arcs tend to add flow to your motion.
`````col
````col-md
flexGrow=1
===
![Videoframe_20240720_065949_com.huawei.himovie.overseas.jpg](/img/user/99/Embeds/Videoframe_20240720_065949_com.huawei.himovie.overseas.jpg)
````
````col-md
flexGrow=1
===

````
`````
### How to use them together
If you're working on an animation, you can ask yourself [[05 Notes/Animation/Animation Basics in 14 Minutes (6 Big ideas for beginners).Note#^f81db2\|How does this motion feel?]] The answer could be anywhere from:
- It's great, I love it
- Could be better 
- This feels wrong
`````col
````col-md
flexGrow=1
===
![Videoframe_20240720_071002_com.huawei.himovie.overseas.jpg](/img/user/99/Embeds/Videoframe_20240720_071002_com.huawei.himovie.overseas.jpg)
````
````col-md
flexGrow=1
===
![Videoframe_20240720_071321_com.huawei.himovie.overseas.jpg](/img/user/99/Embeds/Videoframe_20240720_071321_com.huawei.himovie.overseas.jpg)
````
`````
If your answer is anything other than great, you can use these ideas to start asking questions that will help improve your animation:
- Does the speed feel right?
- Should we change the spacing to adjust the acceleration?
- Should we be using some squash or stretch?
- Maybe we need some anticipation?
- Are the arcs working well?
- Do we need some overshoot to help sell the weight?

###### Homework
1. Choose an animation medium it could be anything from a flipbook to a program  that you're learning 
2. Take one of the six ideas and create a short animation based on that 
	- one to two seconds long
3. Take a different idea maybe and create a second animation
	- once again one to two seconds long
4. Create a short animation that uses both of these ideas at the same time