---
layout: post
title: ROS Meets Precision Agriculture at Blue River Technology
date: 2014-06-05 16:48:00
author: Brian Gerkey
categories: blog
---

![Blueriver lettuce thinner](/images/blog_images/blueriver-1.jpg)

If you were to design the worst possible environment for software engineering, the cramped jump seat of a John Deere tractor would be a contender.
The sound and vibration of the engine makes conversation and concentration difficult. If the sun isn't making it impossible to see the monitor, the blowing dust is.

This is a common scenario at Blue River Technology because the company is in the agriculture business.
[Blue River](http://www.bluerivert.com/) combines computer vision and robotics to deliver precision thinning to lettuce growers.

![Blueriver lettuce thinner](/images/blog_images/blueriver-2.jpg)

Blue River has been using ROS since late 2012.
According to Willy Pell, Blue River's Sr. Systems Engineer:

"We love ROS because it makes it easy to find and correct errors in the worst possible circumstances. Any time something is wrong we know within a few dozen lines of code where the problem is presenting itself. It allows us to build systems <a href="http://en.wikipedia.org/wiki/Unix_philosophy">The UNIX Way</a>.  In other words, we make simple, open source programs that communicate well with other programs."

Blue River makes machines called lettuce thinners.
Lettuce growers plant too many seeds because only 80% of seeds actually turn into plants.
Since a lettuce head needs 10 inches on either side to get the resources it needs, growers must then thin the field of excess lettuce.
Blue River's machine is pulled behind a tractor and takes pictures of the plant seedlings.
It identifies the ones to keep and the ones to kill and toggles a sprayer to render its verdict.
There is finality to this machine.
If it messes up it doesn't just waste time, it impacts the grower's yield.

Added Pell, "ROS has been a fantastic tool for us. I love how you can gut one node and not have it affect the rest of the system. I love how you can break the system apart and test subcomponents. Being able to confidently refactor, test and debug large parts of the system allows us to evolve extremely quickly."

![Blueriver lettuce thinner](/images/blog_images/blueriver-3.jpg)

It never ceases to amaze and delight us when we learn of new and innovative uses of ROS.
Just recently, <a href="blog/ros...launch!.html">ROS celebrated a celestial milestone</a> when it arrived at the International Space Station as part of Robonaut 2.
While Blue River's solution is certainly more terrestrial it is no less innovative and impactful.
Being able to deliver a precision agricultural solution to farmers means higher yield and fewer chemicals.

Because of the permissive open source license of ROS, we aren't always aware of who is using ROS and for what purposes.
In this case, we are very grateful to the team at Blue River for sharing their story with us.

If you are using ROS and have a story to share, please drop us a line at <a href="mailto:info@osrfoundation.org">info@osrfoundation.org</a>.
