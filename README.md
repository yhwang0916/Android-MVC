Model View Controller for Android
==================================


(C) 2010-2013, Gaurav Vaish<br/>
http://www.m10v.com

All code is available under Apache Public License v2.0


----------------------------------------------------------------

The key components are:
* Controller: Represented by an android.app.Application inherited class
* Model: Any data objects, business entities
* View: The Activities.

The updates to the models are done by execution of commands
(represented by ICommand implementations).

The commands in turn provide how should the updated models
by viewed (a deviation from normal MVC implementation where
navigation is separated out).

Will be looking at implementing the last part (decoupled navigation)
in, may be, a branch or a fork ;)

----------------------------------------------------------------

