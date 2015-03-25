
---

# This project has moved to [GitHub](http://genzeb.github.io/flip) at http://genzeb.github.io/flip #

---

If you've liked it before, please head on over to [GitHub](http://genzeb.github.io/flip) and like it there too.

---


## Flip 3D View Animation and Transition ##
### Create awesome looking 3D view transition in your android applications ###

The view transition animations in Android are very limited. One particular omission is the 3D flip transition that is common in iOS. This project contains a animation subclass that allows for a 3D flip animation and a library that takes a `ViewAnimator` (such as `ViewFlipper`) and animates a flip transition b/n its subviews (left-to-right or right-to-left).

The key missing ingredient from most flip animation is the zoom effect. Without it, simple flips on the y-axis appear very much 2D and lose their distinctive 3D feel.

Take a look at [this video](http://youtu.be/52mXHqX9f3Y) to see how this looks.

There are also a number of other animations in the `AnimationFactory` class. Enjoy.

<a href='http://www.youtube.com/watch?feature=player_embedded&v=52mXHqX9f3Y' target='_blank'><img src='http://img.youtube.com/vi/52mXHqX9f3Y/0.jpg' width='425' height=344 /></a>

## How to Install ##
Get a copy of the source [here](https://code.google.com/p/android-3d-flip-view-transition/source/checkout). Copy-paste the /src/com folder to your project's source folder. Use the flip transition in any of your `ViewAnimator` (such as `ViewFipper`) by doing:
```
AnimationFactory.flipTransition(viewFlipper, FlipDirection.LEFT_RIGHT);
```

It's that easy!

If you want to create a `FlipAnimation` and use it some other way, you may do so by the constructor or the `AnimationFactory.flipAnimation` method.

## Disclaimer ##

You may use, modify, etc. this code. However, give credit per the license agreement.