---
layout: post
title: The 3-3 Invasion 2-1 - The Double Hane
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

> This is the third article in the series "The 3-3 Invasion," and the first part of a 2-part article on the double hane line. The second part can be found [here](/joseki/44/2021/02/21/44-33-invasion-2-2-34-invasion/).


In this article we discuss the basic theory of the double hane line of the early 3-3 invasion.
This is the first of two articles on the double hane.

### The double hane

</section>

<div class="besogo-viewer" maxwidth="550" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-21-sgf/double-hane-sgf/01.sgf"></div>

<section markdown="1">

The double hane is one of the main lines of the 3-3 invasion in the AI era.
It is used when Black wants to keep the corner.
In exchange for sacrificing the corner stones, White gets a ponnuki on the side and sente.
It is the least complicated of all lines of the 3-3 invasion: there is relatively little room to deviate.

In the very first moves of the game, there appears to be little impact on AI winrate whether you choose the double hane or to extend.
Feel free to choose based on preference and how much you want to keep sente.

### Direction of play

The first thing you should do before you use the double hane is to determine the direction of play.
The position is symmetrical: White could choose to block on the left (A) or on top (B), and then the same jōseki plays out but mirrored.
The important thing to note here is that White's choice of direction determines where Black's ponnuki ends up.
If White blocks at (A), then Black gets the ponnuki on the right side.
If White blocks at (B), then Black gets a ponnuki on the bottom side.
White wants to choose the direction of White's ponnuki in a way that favors White as much as possible.

</section>

<div class="besogo-viewer" maxwidth="550" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-21-sgf/double-hane-sgf/02.sgf"></div>

<section markdown="1">

White should look at the opposing corners to decide the direction of play.
Typically one of the opposing corners will be Black's, and the other will be White's.
The general rule of thumb is that White should block in the direction that will place Black's ponnuki in the direction of the opposing corner belonging to White.
Thus, in this above diagram, (A) is preferable over (B) because (A) places Black's ponnuki in the direction of White's top right corner, while (B) places it in the direction of Black's lower left corner.
The heuristic holds almost regardless of the type of corner: for instance, the same would hold if White's stone was at the 3-4 point in the top right.

The logic behind this is that if Black's ponnuki faces an opposing White corner, then the White corner limits the development Black can expect on that corresponding side.
This makes sense in the context of Black's usual local follow-ups, which involve Black extending upwards from the ponnuki (more on this in a bit).
On the other hand, if Black's ponnuki faces an opposing Black corner, then the corner and ponnuki synergize well with each other and discourage White operations on the corresponding side.

One might argue that with (B), White is having its own strong lower right face its own top right corner.
Won't White's two corners synergize as well?
This isn't entirely wrong, but they likely won't synergize as well as you'd think, for two reasons:
* There is some aji in White's corner, which Black can exploit to support operations on the right side. (More on this in a bit.)
* Black has sente, and can start developing the synergy between its distant stones before White can.

Is it a huge mistake if you put the ponnuki on the "wrong" side?
Not really - the difference is fairly slight, and either way is still quite playable.
KataGo gives (A) a 0.1% advantage in winrate over (B) in this particular setting.
Regardless, life is a bit easier for White if it does not let Black's stones synergize too easily.

There are "exceptions" to this rule, of course.
Or perhaps it is better to say that this rule can be fine-tuned using basic principles of group strength and weakness.
Here is one example.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-21-sgf/double-hane-sgf/03.sgf"></div>

<section markdown="1">

Consider this position arising from a Kobayashi-style fuseki by Black.
When White invades the 3-3, Black has two choices of where to place the ponnuki: either on the bottom side, near the White stones on the left, or on the right side near the Black stones on the top.
Should Black, as before, place the ponnuki on the right, to avoid having White's stones synergize together?

The answer is no: this time, it is better for Black to place the ponnuki on the bottom side!
The reason is that in this situation, White's stones on the bottom left are already fairly strong by themselves, and do not need the additional reinforcement.
Placing a ponnuki here is closer to overconcentration for White rather than synergy.

If the ponnuki is on the right, however, then White can get some extra value out of its ponnuki, based on the fact that the Black group in the top right is now under a bit of additional pressure.
This Black group is generally fairly secure, but does have some bad aji at points like (A) if it starts getting surrounded.
Black has essentially surrounded its top right group on two sides in gote, and may owe a move later to further help it settle.

KataGo rates the difference between the two as 0.5 points, about ~6% in terms of winrate.
This is fairly significant (especially compared to the first example), though in terms of amateur play this is still a fairly slight difference between the two directions.
But it does serve to illustrate the overall principle: in the 3-3 invasion, the defender has total freedom of choice of the direction of play, and can extract advantages by choosing the direction correctly.

### Local continuations and aji

We now examine how play can continue from the double hane jōseki.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-21-sgf/double-hane-sgf/05.sgf"></div>

<section markdown="1">

For starters, it is common for White to make the sente exchange of the descent for the 2-2 point.
The difference between playing and omitting the descent is rather minor: it is essentially a probe that asks if Black will descend to the 2-2 point to keep the corner.
If Black does, then this activates some of the aji in the corner, but the aji is generally active to some degree anyway, so the differences are slight.
At kyu level, it rarely makes a difference, so you can choose based on preference.

There are essentially two forms of the aji in this corner.
The first has to do with if White has additional stones on top of the Black group:

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-21-sgf/double-hane-sgf/06.sgf"></div>

<section markdown="1">

The second has to do with if White approaches from the side:

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-21-sgf/double-hane-sgf/07.sgf"></div>

<section markdown="1">

These considerations mean the following about the local follow-ups:
* When White pushes upward from the ponnuki, Black will usually want to respond locally to avoid a situation like the first diagram.
* A White approach from the side is usually sente.

This leads to the following (non-exhaustive, but pretty close) range of follow-ups for the double hane jōseki:

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-21-sgf/double-hane-sgf/08.sgf"></div>

<section markdown="1">

There is not much difference in most lines whether White makes the descent or not.
White can pursue these options later if necessary, but (aside from (A), which is essentially a free exchange) if White does play here immediately then (B) is the most common.
Note here that the aji of the second line approach means that White may be ok with pushing from behind and letting Black build on the sixth line, normally something that is heavily frowned upon; however, whether this is actually viable does depend a lot on the rest of the board.


### What if you don't like the direction?

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-21-sgf/double-hane-sgf/04.sgf"></div>

<section markdown="1">

Sometimes, in response to the double hane, you see the invader (White in this case) hane in the opposite direction.
Outside of DDK games where the players don't know the jōseki, this generally occurs when White doesn't like that Black has total freedom to choose the direction of the ponnuki.
With this, White does technically have the ability to place a ponnuki on the bottom side rather than the right.

However, the result is locally favorable to Black.
White may succeed in getting a ponnuki in the direction of their choice, but the cost is that Black's corner now has much less aji compared to the original double hane jōseki.
There are scenarios when this is still playable for White if the directional considerations are really that important, but this variation should normally be treated as highly situational.

There is, however, a more refined way for White to keep some agency in the direction of play.

### Conclusion and takeaways

In this article we studied the basic theory of the double hane line of the early 3-3 invasion, including its aji and follow-ups.
The biggest takeaway from this article should be the value of the defender's freedom to choose the direction of play.

The second part of this two-part article will address the [3-4 invasion](/joseki/44/2021/02/21/44-33-invasion-2-2-34-invasion/) - a twist on the double hane line that allows the invader to choose the direction of play.

[Return to the 4-4 Jōseki page.](/44/)

</section>