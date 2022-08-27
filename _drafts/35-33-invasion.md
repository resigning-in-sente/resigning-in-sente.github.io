---
layout: post
title: 3-5 Approaches - The 3-3 Invasion
---

<link rel="stylesheet" type="text/css" href="/assets/css/besogo.css">
<link rel="stylesheet" type="text/css" href="/assets/css/board-wood.css">

<script src="/assets/js/besogo.js"></script>
<script src="/assets/js/editor.js"></script>
<script src="/assets/js/gameRoot.js"></script>
<script src="/assets/js/svgUtil.js"></script>
<script src="/assets/js/parseSgf.js"></script>
<script src="/assets/js/loadSgf.js"></script>
<script src="/assets/js/saveSgf.js"></script>
<script src="/assets/js/boardDisplay.js"></script>
<script src="/assets/js/coord.js"></script>
<script src="/assets/js/toolPanel.js"></script>
<script src="/assets/js/filePanel.js"></script>
<script src="/assets/js/controlPanel.js"></script>
<script src="/assets/js/namesPanel.js"></script>
<script src="/assets/js/commentPanel.js"></script>
<script src="/assets/js/treePanel.js"></script>

<body onload="besogo.autoInit()">

<section markdown="1">

### Approach with caution

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" orient="portrait" panels="control+tree" portratio="none" sgf="/assets/sgf/2022-07-29-sgf/01.sgf"></div>

<section markdown="1">

The 3-5 point is one of two relatively unorthodox initial corner moves that still sees frequent play (the other being the 4-5 point).
It is uncommon in SDK play but is encountered with greater frequency in dan play, and to some degree indicates a special strategy with a bias toward influence.
It is also commonly found in handicap games.

The 3-5 point, along with the 4-5 point, has a bit of a reputation as a trick play factory, being commonly used by stronger players to trick weaker players into suboptimal lines.
Timing an approach to a 3-5 point can be tricky, and once you do approach it is possible to end up in fairly complex variations.
Conversely, the complexity of the possible variations can make it tricky for weaker players to effectively employ the 3-5 point themselves.

In this article we will discuss some ways to handle a 3-5 point corner from the approaching side's perspective.
The focus will be on simple methods that avoid falling behind much (if at all) while limiting the number of possible complications.
We do not handle the defending side's perspective: anyone who plays the 3-5 point has no choice but to study the possible complications of the position.
The ability to simplify unconditionally rests solely with the approaching side in this opening.

### When in doubt, tenuki

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" orient="portrait" panels="control+tree" portratio="none" sgf="/assets/sgf/2022-07-29-sgf/02.sgf"></div>

<section markdown="1">

First, let's take a brief moment to understand the position.

The 3-5 point is biased toward influence, especially toward the side, compared to the more common 4-4, 3-4, and 3-3 points.
It has a tendency to be paired with the nearer of the two adjacent corners, because the 3-5 player (Black in the above example) is anticipating that the opponent will enter the 3-5 point and intends to press the invader from above, building influence toward the opposing side.
Conversely, it tends to not see as much use in diagonal fuseki (openings where both sides occupy diagonally opposite corners) because such games inherently tend to be more split it and prevent the formation of large moyos.

The first thing to note about responding to a 3-5 point is that in reality, there is no pressing need to respond at all.
In the above example, it is perfectly acceptable for White to ignore the bottom right corner for some time and play an otherwise normal game.
Black does not have a particularly big local follow-up to the 3-5 point.
The biggest move locally for Black is A, forming the standard one-space low enclosure, but then this merely transposes to as if Black started normally with a 3-4 point and then spent sente to enclose the corner - a perfectly normal sequence of play, one that White can easily adapt to.

There is the possibility that Black forms a more nonstandard enclosure, such as B or C.
These are closer to trick plays; there is a reason such enclosures are not commonly played, though it should be said that refuting them is not a perfectly easy task.
However, having a decent understanding of how probes for the standard corner enclosures work goes a long way to finding acceptable lines of play against nonstandard enclosures.

The most important thing when choosing to tenuki against a 3-5 point is to keep your cool.
Danger lies in attempting to "punish" a 3-5 point or a nonstandard enclosure, doubly so if done prematurely.
The opponent generally will know the local continuations better than you do.
Stay calm and play a regular and principled game; the downsides of the position will eventually make themselves known and you can adapt accordingly.

### Complex but important: The 3-4 approach

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" orient="portrait" panels="control+tree+comment" portratio="none" sgf="/assets/sgf/2022-07-29-sgf/03.sgf"></div>

<section markdown="1">

The next option that jumps out is the 3-4 point; however, this position is not the focus of this post.

It is not so easy for White to play this position.
Things are simple if Black opts for the common follow-up of pressing at A and trading territory for influence.
However, if White wants to play this move then White also needs to understand what happens after Black's other options B, C, and D.
B in particular is the notoriously complicated *taisha* jōseki, nicknamed *taisha of the hundred variations*.
The *taisha* is so complex that even professional players do not necessarily know the variations.
There are ways to simplify and avoid the most complex variations of the *taisha*, but this still leaves behind the necessity of understanding C and D.

We mention the 3-4 point here mainly to point out that this position can also arise when White ignores a Black low approach to White's 3-4 point.
This is not inherently bad, and does seem to occur more frequently since the introduction of AI.
However, given the significant potential for complications, for weaker players it is recommended that you simply respond locally if an opponent approaches your 3-4 point.
There are very few scenarios where it is a bad thing to respond to such a move, and if it is not the optimal move it is typically only suboptimal by negligible amounts.

### The 3-3 invasion

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" orient="portrait" panels="control+tree+comment" portratio="none" sgf="/assets/sgf/2022-07-29-sgf/04.sgf"></div>

<section markdown="1">

We now turn to the main focus of this post, the 3-3 invasion.

All lines of the 3-3 invasion are similar in principle.
White intends to give away a fair amount of thickness to Black in exchange for territory.
Most outcomes where White takes territory and avoids getting sealed in on both sides are acceptable.

There are a few notable advantages of choosing the 3-3 point over the 3-4 point.

* It is very difficult for Black to deviate into a complex variation against a 3-3 point. The 3-3 point commits more fully to the corner and essentially guarantees life for the invasion, so there is no real way for Black to get an outcome other than a territory-influence trade.

* Because all outcomes are territory-influence trades, the impact of the invasion on the global board state is relatively easy to understand.

* Many lines of the 3-3 invasion result in similar positions to lines of the 3-3 invasion of the *4-4* point, which helps for evaluating the variations and determining which lines are acceptable if trying to reconstruct a sequence on the fly.

We now proceed to discussing the main variations.
There are roughly three (A, B, and C) to consider, while D leads to a transposition of a 4-4 jōseki.

#### Slant

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" orient="portrait" panels="control+tree+comment" portratio="none" sgf="/assets/sgf/2022-07-29-sgf/05.sgf"></div>

<section markdown="1">

If Black responds to the invasion with the slant, then the simplest response for White is to threaten to cut, then extend along the side.

As we are starting from a slightly atypical position, it may not be clear at first glance why the recommended outcomes given above are acceptable for White.
This is best explained via tewari analysis.
Most of these simple territory-influence exchanges are not very different from outcomes of the standard 3-3 invasion of the 4-4 point and other well-known jōseki.

As with any territory-influence exchange, it is important to avoid mistiming the invasion.
If direction of play considerations dissuade the formation of thickness toward a certain direction, then one should reconsider whether the 3-3 invasion is appropriate.
We reiterate here that tenuki is a viable option: the best Black can do is make a corner enclosure.
These recommended sequences and those that follow are mostly appropriate for a largely empty board where giving away influence is not so dangerous yet.
As the outcomes are similar to outcomes of the 4-4, 3-3 invasion, one could use this as a reference point: if you would be ok with invading the 4-4 point in the given board state, you can typically invade the 3-5 point at the 3-3 point as well.

#### Diagonal move

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" orient="portrait" panels="control+tree+comment" portratio="none" sgf="/assets/sgf/2022-07-29-sgf/05.sgf"></div>

<section markdown="1">

AAAA

#### Large slant
</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" orient="portrait" panels="control+tree+comment" portratio="none" sgf="/assets/sgf/2022-07-29-sgf/05.sgf"></div>

<section markdown="1">

AAAA

#### Attachment

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" orient="portrait" panels="control+tree+comment" portratio="none" sgf="/assets/sgf/2022-07-29-sgf/05.sgf"></div>

<section markdown="1">

AAAA

### Simulated example

Using KataGo, we simulate a scenario in which the 4-4 attachment is a viable approach option to the 3-4 point, and show how play continues.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-08-03-sgf/06.sgf"></div>

<section markdown="1">


### Conclusion

As we have seen from the example, the standard approaches to the 3-4 point are not always viable options due to their lack of immediate pressure and lack of ability to transition the direction of play.
As always on this blog, we emphasize the importance of finding the correct direction of play, and having options to shift the direction of play when necessary.
For that the 4-4 attachment is an essential tool, and is relatively easy to learn as well.
The key to making good use of the 4-4 attachment is to get a feel for when direction of play considerations outweigh the local sacrifice intrinsic to this move.


[Return to the 3-5 Jōseki page.](/35/)

</section>