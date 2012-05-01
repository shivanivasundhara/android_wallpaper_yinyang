Introduction
============

Project for generating Yin Yang -symbol as an Android Livepaper plus making it dynamical using
OpenGL ES 2.0 shaders for rendering it on screen. There are some somewhat 'uglyish'
hacks involved, e.g renderer is implemented directly into GLSurfaceView, which
isn't the best option if similarly named methods are introduced to base class
one day.

Beyond this, screensaver should comply with regular expectations one could have for
them. Application icon and screensaver thumbnail image are the same ones for
size reasons. Not to forget while making rendering as dynamic as possible - it comes along
with the good news as file size tends to drop significantly.

That said, hope you enjoy this tiny Yin Yang live wallpaper for Android devices.

Compiled application can be downloaded from Google Play store;
http://play.google.com/store/apps/details?id=fi.harism.wallpaper.yinyang

The source code is released under Apache 2.0 and can be used in commercial or
personal projects. See LICENSE for more information. See NOTICE for any exceptions,
there is a clause about application icon and wallpaper thumbnail image used in
the wallpaper. Besides these exceptions, let it be as-is implementation or -
maybe more preferably - as an example for implementing your own effects.
