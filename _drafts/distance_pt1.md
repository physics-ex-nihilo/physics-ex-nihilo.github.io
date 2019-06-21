---
layout: post
title: distance.
excerpt: How do we identify, quantify, and measure space?
author: r.m.
---

In this discussion, I will address three different aspects regarding _distance_. 

First is the practical aspect. What does 'distance' mean? How do we identify, quantify, and measure space?

Second is the mechanical aspect. How do we create the _tools_ to measure distance? You may trust that a ruler is straight, but how can you be sure?

Finally is the mathematical aspect. Why do we measure distances in straight lines, as opposed to some other curve? Is there anything that makes a line mathematically special?

Before we begin the discussion, it's important to establish what are assumptions are. Namely:

> I'm assuming a _basic_ understanding of time. That is, you should understand words like "before", "after", "now", "later", "then", etc.

> Related to this, I assume that we can recognize _changes_ in our environment. We can see when something is different from how it was before, and characterize what that difference is.

This is not an exhaustive list of the assumptions I use, but I think these are the most important. With that settled, let's take a look at the practical methods for analyzing distance.

----
****

## Practical Methods

***Near and far***

Suppose I place a rock on the table in front of you. You close your eyes, and when you open them again, something is different. What is it?

[before and after image of a rock on a table. A person sits on the right side of the table. In the after image, the rock is further from the person seated there.]

Our human senses tell us that most of the objects in the room are unchanged. The chairs and the table are the same, as is the fridge in the corner. The walls have not changed color, nor have any new doors or windows appeared. No, if something has changed, it is the rock.

Yet that's not exactly correct either. The rock _itself_, as an object, looks much the same. It has not grown in size; its texture and shape appear just as they did before. As far as you can perceive, every single object in the room is identical to what it was before you closed your eyes.

_And yet something is different_.

What do we call this new property? One idea is to use _near_ vs. _far_. Before, the rock was near; now it is far. This seems simple enough. However, this concept has problems.

***Different observers***

Suppose you want to teach someone else these ideas. You could sit them in a room and play the same game with them. Maybe you could play the game multiple times, with different objects in different settings. That way you can be sure that they have the same notion that you do.

Then one day, you and your friend find yourselves in a situation something like this:

[image of a rock between two people. It is closer to the person on the left than the person on the right].

One person says that the rock is near, the other person says that the rock is far. This demonstrates that the question of near vs. far is _subjective_ - it depends on the observer. Subjective notions are still _true_, but can we do better? Is there a way to describe the change in a way so that all observers agree?

We can approach the _objective_ version of near and far by closely examining cases where the two observers disagree. Consider the folowing situation:

[image of, from left to right, a person, a tree, a bird, a rock, and another person]

Now we discover something interesting. For the person on the left, while the bird is far, the rock is _more far_, and the tree is _less far_. Similarly, the person on the right might describe the rock as _near_, the bird as _less near_, and the tree as _even less near_.

That is to say, near/far are properties with _magnitude_. If someone says "the rock is far", you can ask "how far?". This idea will come up again and again: if you can _compare_ the property of one thing to the property of another thing, saying one is less and one is more, than you can _measure_ that property. You can attach a number to it.

So how do we measure this farness? Or, better asked, how do we _invent_ the measurement for farness?

***Measuring farness***

Here is one idea. Suppose you stretch a rope taut in between me and one of the objects, then cut the rope off at the end points. Repeat this for me and every object, then do the same thing between you and every object. We might end up with ropes like this:

[image of six ropes representing the distance between the two observers and the various objects, labeled appropriately]

In case it's not clear, we've _immediately_ solved the apparent disagreement by measuring things this way. The trick is that each rope is stretched between _two_ points: the observer, and the object.

Let's think back to the original example: you're sitting in room with a rock in front of you. You close your eyes, and when you open them the rock is farther. _You_ didn't change, nor did anything else in the room. Since the rock is the only thing that changed, we concluded that "farness" is a property of the rock _alone_.

And yet, if we want an _objective_, _measurable_ version of farness, it must rely on a start point and an end point! It is a property of _two_ things, not just one.

This is a point we will return to later, because even if it _seems_ simple and obvious, it's surprisingly subtle and will lead to unintuitive consequences.

For now, let's focus on the new, objective version of farness. We'll call this property _distance_. It depends on a start point and an end point; if you move either one, the distance changes. Finally, distances can be compared by stretching a rope in between the two points for each distances, and comparing the ropes to each other. A longer rope means the distance is bigger; a shorter rope means the distance is smaller.

Can we be more precise in this measurement? Is it possible to get an exact _number_ for the distance between two points?  Unfortunately, the best that we can do is get a _relative_ number of the distance.

Imagine you have a length of rope representing some distance. You lay the rope out straight on the floor. Then, take a short, straight stick and line it against the rope, starting at one end. Continuing this process, you can see how many lengths of stick are equal the to the length of the rope.

[image of a rope stretched out straight, and markings showing stick-lengths along the rope. At the far right end of the rope is the stick.]

The number that we get out of this depends on the size of the stick that we start with - it's not an _absolute_ number. In order for two observers measuring the rope to get the same number, they have to use the same stick, or at least sticks of the same length. This "reference length" is totally arbitrary. There's no special instruction I could give to guarantee that you and I end up with the same standard, apart from comparing them directly.

There is one case where the choice of reference doesn't matter. Suppose you and I are comparing two lengths of rope, representing distances between two pairs of start and end points. Perhaps when you go to measure the ropes, you get results of 4 stick-lengths for the first one and 12 stick-lengths for the second one. On the other hand, using a different reference, I get 3 stick-lengths for the first rope and 9 stick-lengths for the second.

Although the numbers we get for the two ropes disagree, the _ratio_ of lengths between the two ropes _will_ agree, so long as you and I are measuring the same ropes. You obtained a ratio of 4:12, and I obtained a ratio of 3:9. Mathematically, these are the same. We both agree the the second rope is three times the length of the first. This is another way of demonstrating that distance measurements must be made _relative_ to other distances. There is no such thing as an absolute unit of length.

***Summary***

Let's collect our results. We have discovered a physical property called _distance_, which is specified between two points. Distances have _magnitdue_: they can be large, or small. We can compare distances by stretching a rope in between the two points of consideration, then cutting the rope at the ends. If we want a specific number for the distance, we can compare the rope to some reference length, and count how many reference lengths it takes to equal the length of the rope. (Moving forward, whenver I need to refer to a specific distance, I will go ahead and use the internationally agreed-upon standard of length, the _meter_.)

One more point I want to emphasize is that I don't think it's possible to _define_ distance just in terms of words. Throughout this section I've had to refer to things like "move" and "length", assuming that you understand what they mean. If you _didn't know_ what distance or length or motion were at _all_, it's hard to see how I could describe them to you. The best way I can think of to teach someone what distance is would be to _show_ them, for example by playing the game described in the beginning of this post. For that to work, one person has to already have the concept in mind.

However, once we recognize and agree upon what distance _means_, we can build upon it to make more concepts. This is part of what we'll do in future posts. For now, let's move to a closer look at the tools required for analyzing distances.

----
****

## Mechanical Methods

***The straightedge***

To measure distances with _any_ sort of tool, you need a straight line. One way to make a straight line is to use something that's straight to begin with. But how do you know that something is straight to begin with, if you don't have anything to compare it to?

You could use your eyes. This might sound like a lousy and inaccurate method, but it's possible to get decent results in this way. As a first estimate, you can pick up any stick that looks approximately straight. Despite your first glance, the stick may still curve left or right. How do you tell? If you hold the stick up to your eye and look right down the length, you should be able to see if there's some curvature. Rolling the stick in your hands, you can check the overall straightness of it.

It's not perfect, but with practice you could use a chisel to shave off the curved bits of the wood until the stick is straight to within visual accuracy.  Let's call this tool - a thin, straight object made out of some durable material - a _straightedge_.

***The plumb line***

Making the straightedge from sight does require that I _know_ what straightness is. If you can't tell what a straight line is, it's unreasonable to ask you to make one. So here's one method, which I used in the practical section above: take a piece of string or rope, and pull it tight. That shape is a straight line.

One issue might arise if your rope is heavy, or stretched over a long distance: the rope will sag under its own weight, acquiring a curve. However, we can avoid this problem by attaching a weight to one end of the rope and letting it hang vertically.

To get the best idea of straightness, the rope should be as thin as possible.  Otherwise, the thickness of the rope allows for too much uncertainty in the length. So, ideally we would use a thin thread. This tool is known as a _plumb line_. Provided that you have the materials available, you can thus teach anyone what a straight line is.

***Comparing standards***

How do we _compare_ standards of straightness? If you and I have both made straightedges, is there a way to tell who's is straighter? We could lay the straightedges right next to each other, and see if there are any gaps or deviations between the two. But that alone wouldn't tell us _which_ one is straighter than the other.

We could use a plumb line to measure the accuracy of the straightedge. But in practice this is cumbersome. The thread is flexible, and therefore doesn't hold the shape of the straight line. If you nudge or bump against it, it starts swinging, which also makes comparison difficult.

In using the plumb line as a reference, we're acknowledging that the plumb line will be _more_ accurate than a straightedge made by sight. Yet how do we _know for sure_ that it is?

The key here is _consistency_. If I were to make a dozen plumb lines, all using identical materials, there would be very little deviation in the straight lines they made (although, to be fair, _comparing_ plumb lines to each other would be difficult, for the same reason that comparing plumb lines to straightedges is difficult). On the other hand, if I make a dozen straightedges, I'd expect there to be more _variation_. Placing each straightedge right next to every other, some of them would probably have gaps between them.

This is good way to _measure_ how perfectly my straightedges are made. Suppose you and I each make a dozen straightedges. I compare all my straightedges to each other, and find that the average gap between them is half a centimeter (0.05m). However, when you compare all of your sraightedges to each other, you find the average gap between them is only a millimeter (0.01m). Thus, we conclude that your straightedges are more accurate than mine.

[image of two pairs of straightedges placed right next to each other. The pair on the left has larger gaps than the pair on the right.]

The assumption behind this is that each of our mistakes will be _random_ on average. Neither of us will make exactly the same straightedge twice. However, if I'm clumsier at using the chisel and worse at spotting a straight line, my mistakes are spread over a wider range, and thus the average gap between my straightedges is wider.

//NEEDS EDITING As long as both of us are _reasonably_ close to a straight line in the first place (perhaps checked by a rough comparison to the plumb line), then we don't need a perfect measuring tool to check the straightedges. The gaps between straightedges should be small enough that measuring them isn't greatly affected by the straightness of the ruler used. //NEEDS EDITING

