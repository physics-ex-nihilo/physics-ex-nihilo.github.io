---
layout: post
title: distance, part 1.
excerpt: How do we identify, quantify, and measure space?
author: r.m.
---

The first physical concept for us will be _distance_. In the next three posts, I'd like to cover three lessons on this topic: _practical_ methods, _mechanical_ methods, and _mathematical_ methods. Here in part one, we'll discuss the practical: What does 'distance' mean? How do we identify, quantify, and measure space?

Before we begin the discussion, I'll assume three prerequisites:

> - A _basic_ understanding of time. That is, you should understand words like "before", "after", "now", "later", "then", etc.

> - Related to this, I assume that we can recognize _changes_ in our environment. We can see when something is different from how it was before, and characterize what that difference is.

> - Finally, we'll rely on an intuitive understanding of magnitude. To at least a rough degree, we can distinguish big things from small things.

This is not an exhaustive list of the assumptions I'm making, but I think these are important ones to keep in mind. With that settled, let's take a look at the first steps in analyzing distance.

----
****

## Practical Methods

***Near and far***

Suppose I place a rock on the table in front of you. You close your eyes, and when you open them again, something is different. What is it?

{% include image.html
  url="/assets/images/distance_pt1/image1.png"
  max-width="60%"
  alt="Before the change occurs..."
%}

{% include image.html
  url="/assets/images/distance_pt1/image2.png"
  max-width="60%"
  alt="...and after."
%}

Our human senses tell us that most of the objects in the room are unchanged. The chairs and the table are the same, as is the fridge in the corner. The walls have not changed color, nor have any new doors or windows appeared. No, if something has changed, it is the rock.

Yet that's not exactly correct either. The rock _itself_, as an object, looks much the same. It has not grown in size; its texture and shape appear just as they did before. As far as you can perceive, every single object in the room is identical to what it was before you closed your eyes.

_And yet something is different_.

What do we call this new property? One idea is to use _near_ vs. _far_. Before, the rock was near; now it is far. This seems simple enough. However, the concept has problems.

***Different observers***

Suppose you want to teach someone else these ideas. You could sit them in a room and play the same game with them. Maybe you could play the game multiple times, with different objects in different settings. That way you can be sure that they have the same notion of near and far that you do.

Then one day, you and your friend find yourselves in a situation something like this:

  {% include image.html
    url="/assets/images/distance_pt1/image3.png"
    max-width="100%"
    alt="Two observers."
  %}

One person says that the rock is near, the other person says that the rock is far. This demonstrates that the question of near vs. far is _subjective_ - it depends on the observer. Is there a way to resolve this conflict?

The problem lies in thinking of farness as something that only depends on _one_ object. In fact, I've already given the answer away: farness depends on the _observer_ as well as the object being observed.

If we think about it, this seems strange. We concluded in the "what's different" game that whatever changed had something to do with the _rock_, not with the observer or anything else in the room. So it should only be a property of one thing, right?  And yet, if we want an _objective_ version of farness, it must rely on two things!

This is important enough that it bears repeating: _farness is a property of two things, not one_. We will return to this point later, because even if it _seems_ simple and obvious, it's surprisingly subtle and will lead to unintuitive consequences.

For now, to avoid confusion, let's come up with a new term. Whenever the observer is _implied_, we'll stick with _farness_. Otherwise, we'll make clear exactly what two things we want the relationship between, and we'll call that relationship _distance_.

We may now return to the above image and apply our new concept.  The objective statement describing this situation is that the distance between Red and the rock is _smaller than_ the distance between Blue and the rock.

This comparison is the first hint at how to _measure_ distance.

***Measuring distance***

Let's add more objects into the picture:

  {% include image.html
    url="/assets/images/distance_pt1/image4.png"
    max-width="100%"
    alt="A person, a tree, a bird, and a rock."
  %}

Using our intuitive grasp of magnitudes, we would say that while the distance from Blue to the bird is large, the distance to the rock is _larger_, and the distance to the tree is _smaller_. That is to say, distance is a  property with _magnitude_.

This idea will come up again and again: if you can _compare_ the property of one thing to the property of another thing, saying one is less and one is more, then you can _measure_ that property. You can attach a number to it.

So how do we measure this farness? One idea is to stretch a rope taut in between the observer and one of the objects, then cut the rope off at the end points. For example, you might do this for Blue and the rock.

  {% include image.html
    url="/assets/images/distance_pt1/image5.png"
    max-width="100%"
    alt="A rope measuring how far the rock is."
  %}

When we perform this ritual with the rope, we can see that the distance from the observer to the rock is the same as the distance from one end of the rope to the other. Let's call "the distance from one end of the rope to the other" the _length_ of the rope. So, the length of the rope is the same as the distance we want to measure.

Now repeat this process for the tree and the bird. We'll end up with three ropes, which we can compare to each other:

  {% include image.html
    url="/assets/images/distance_pt1/image6.png"
    max-width="100%"
    alt="A comparison between three ropes."
  %}

Earlier, we mentioned that the distance from Blue to the tree is smallest, the distance to the rock is largest, and the bird is somewhere in between. Looking at the ropes, we have the same relationship: the least amount of rope is used for the tree, the most amount for the rock, and a middling amount of rope for the bird. This is true no matter _who_ is looking at the ropes; therefore, we have an objective measurement.

***Numerical distance***

Can we be more precise in our measurement? Is it possible to get an exact _number_ for the distance between two points?  Unfortunately, the best that we can do is get a _relative_ number.

Imagine you have a length of rope representing some distance. You lay the rope out straight on the floor. Then, take a short, straight stick and line it up with the rope, starting at one end. Continuing this process, you can see how many lengths of stick are equal the to the length of the rope.

  {% include image.html
    url="/assets/images/distance_pt1/image7.png"
    max-width="100%"
    alt="The length of the rope is roughly equal to the length of four sticks."
  %}

The number that we get depends on the length of the stick that we start with - it's not an _absolute_ number. In order for two observers measuring the rope to get the same number, they have to use the same stick, or at least sticks of the same length.

This "reference length" is totally arbitrary; the only way to guarantee that you use the same reference I do is by showing you that reference in person. The _metre_ was actually once defined this way: it was simply a [bar of metal](https://en.wikipedia.org/wiki/Metre#International_prototype_metre_bar) that one organization distributed copies of.

There is no such thing as absolute length; you can only ever measure the _ratio_ of one length to another length.

***Summary***

Let's collect our results.

>We have discovered a physical property called _distance_, which is specified between _two points_.

>Distances have _magnitdue_: they can be large, or small. We can compare distances by stretching a rope in between the two points of consideration, then cutting the rope at the ends.

>If we want a specific number for the distance, we can compare the rope to some reference length, and count how many reference lengths it takes to equal the length of the rope. (Moving forward, whenever I need to refer to a specific distance, I will go ahead and use the internationally agreed-upon metre.)

Once we recognize and agree upon what distance _means_, we can build upon it to make more concepts. This is part of what we'll do in future posts. But before we get to that, it's worth taking a closer look at the tools for measuring distance. The next post will do exactly that.
