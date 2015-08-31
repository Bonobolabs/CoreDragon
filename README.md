SPDragNDrop
===========
Nevyn Bengtsson <nevyn.jpg@gmail.com>

SPDragNDrop is a Hackweek experiment written by me during the December 2012 Hackweek at Spotify. Since I really love the idea and would hate for the code+idea to just rot away, Spotify's letting me release the code under Apache 2.0 before my employment there ends.

Progress in Modern Times
------------------------

This project is many years old, but I'm resurrecting it in order to bring iPad split-screen cross-app drag and drop to the world! Progress:

* 20150831: [first cross-app drag and drop](https://lookback.io/watch/gFRLes3mS5CWRYqNN)

Background
----------

I've always loved multitouch. In addition, I love working spatially with windows and drag&drop. Neither concept has gained much traction on iPad, and not even exploring those concepts means missing out.

At Spotify, I got my windows by [copying Loren Brichter's stacked panes navigation](https://github.com/spotify/SPStackedNav). Finally, I had tactile, direct manipulation navigation. However, all contextual operations were still performed in modes. If you wanted to share a track with a friend, you'd go into the context menu mode for your track by long-pressing it, then the sharing mode by choosing an option in a table, then the friend selection mode... To me, it would be so much more natural to just grab the track, and drag it onto the icon representing my friend. Suddenly you'd be able to remove all these modes, and have direct manipulation of your objects.

I met my hero [Bret Victor](http://worrydream.com) at WWDC 2012, and we talked for a while about drag & drop on iPad, and he added a very important point I hadn't thought about for many years: with multitouch, you can pick something up with one hand, and navigate with the other. This concept had already blown my mind once back in 2005, when [TactaPad released a few amazing concept movies and then never showed themselves again](http://www.tactiva.com/tactadrawmovielarge.html).

So during Hackweek December 2012, I mocked up drag&drop inside the Spotify iPad app. It worked really well. You could pick up a track with your right hand, tap the tab bar with your left hand, navigate around the UI a bit either by tapping on items with your left hand or springloading with your right, and dropping your item when you were done.

<img src="https://dl.dropboxusercontent.com/u/6775/dragndrop.gif" width=400/>

Unfortunately, the idea never got any traction within the company and the branch died. That was over a year ago, and the code is now uncompileable. (Yes, when your build system breaks with every point update of Xcode, code really does rot.) Thus, the only screenshot I have is of the trivial demo app in this repo. Hopefully it is inspiring enough that you now feel the immediate need to use the code or the concept in your own app! Hooray!
