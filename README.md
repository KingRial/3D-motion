3D-motion
==================================================

3D-motion is an experimental study to see if a 3D background could be used inside a home automation supervisor built with a web UI.

The purpose of this experiment is to see 3D components ( the background ) living together with plain HTML components ( the lights which, sometimes, change color ).

The navigation can be made using a mouse or [Leap Motion]( https://www.leapmotion.com/ ).

With the advent of virtual and enhanced reality, this demo could became a nice piece of code to play with and fuel new ideas.

P.S. Take a look at Leap Motion, it can become an interesting interface; especially for virtual reality!

How does it work ?
==================================================
It's pretty easy to use and it's all thanks to the [THREE](http://threejs.org/) library.
The javascript code:
- builds two types of render engines: one for the 3D WebGL and the other for CSS effects.
- creates two scenes in which the render will build the actors
- adds a camera and the controls linked to the mouse and link it to both scenes
- adds the lights ( or you will see just a place dark space ;) ) inside both scenes
- loads the 3D model and adds it to the WebGL scene
- adds html DOM objects to the CSS scene ( using common HTML click events too! )
- create a loop which will render the scenes updating the content if neededby the engines

Changelog
----------------------------
#v0.0.1
- Added to GiTHub


How to see everything in action
----------------------------
Just open index.html on your browser ( the content must be web served )

License
-------
[GNU3](http://www.gnu.org/licenses/gpl-3.0.html)
