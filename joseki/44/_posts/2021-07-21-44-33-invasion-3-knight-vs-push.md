---
layout: post
title: The 3-3 Invasion 3 - The Knight's Move vs. the Push
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

> This is the fourth article in the series "The 3-3 Invasion."

> [Previous article](/joseki/44/2021/02/21/44-33-invasion-2-2-34-invasion/), [Next article](/44/)

### Outside & sente vs. outside & sente

In the previous articles of this series, we gave a fairly thorough account of the double hane line of the 3-3 invasion, which (to summarize) results in the defender taking the corner in gote, while the invader gets a ponnuki on the outside in sente.
We now turn to the other lines of the 3-3 invasion, which generally involve the defender taking the outside and sente.
For the reasons we discussed in the [first article](/joseki/44/2021/02/21/44-33-invasion-1-intro/), we restrict ourselves to the lines where the defender extends from the push, as shown in the diagram below.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-21-sgf/01.sgf"></div>

<section markdown="1">

In later articles we will discuss each line individually in detail.
However, in this article we will take a moment to answer a question that you've probably asked in your own games: what's the difference between the knight's move and the push?
After all, both results appear similar on paper: the defender (Black in this case) takes the outside in sente and gets to choose the direction, while the invader (White) takes the corner in gote.
Does it matter if we choose one over the other, and if so, what ideas go into the choice?
By the end of this article, we will hopefully have a good understanding of this common early-game decision.

### The short version: It really doesn't matter

Let me just put the answer up front:

> The distinction between the knight's move and the push is extremely minor and realistically only matters in professional play.
> You can play whichever one you prefer and be perfectly fine deep into dan level.

If you've got things to do, you can feel free to stop reading here: with complete seriousness, that's all you need to know.
Our initial assessment of the difference between the two joseki is correct: the most important aspect of these joseki is that the defender chooses the direction of play and takes the outside in sente, while the invader takes the corner in gote, and what differences exist are fairly minor relative to this fact.
So for example, if you only play the knight's move as the invader, nobody will yell at you and tell you you're totally wrong, including our lord and savior KataGo.
Most of the time, if one is indeed better than the other, it is only by a difference of 0.1 score, and almost never more than 0.2.
The most important reason to learn both lines is simply that half of the time, you will be the defender rather than the invader, so you at least need to know how the defender responds to both lines.

Consequently, this article isn't going to be the most important article in this series.
We are having this discussion mainly as a fun little side excursion to warm up for the detailed analysis of the individual lines.
However, it will still be instructive for you to follow along, as we *are* going to introduce some basic concepts that we will refer to when we do start these individual analyses.

However, does that mean that there's literally no difference between the two lines?
Not at all!
There are fairly specific, albeit subtle, differences between the knight's move and the push, and we will be spending the rest of this post describing them: there are some interesting strategic concepts here that are good to keep in mind as we continue learning about the 3-3 invasion.
It's just that if all we're concerned about is winrate and score, then these differences are still sufficiently minor that amateurs can get away with either joseki and come out perfectly fine.

### The medium version: The knight's move is never *bad*

For those of you who don't have anywhere to be right now, but also aren't interested in watching me explain something that literally only makes a 0.1 score difference, here's the working summary of how the choice between the knight's move and the push works.

> 1. In the push variation, it is often a priority to be the player that returns to the corner first.
In the knight's move, it is rarely urgent for either side to continue locally.
> 2. The knight's move is an all-purpose option.
> It is essentially never a mistake: neither side can expect to get a significantly favorable or disadvantageous follow-up.
> 3. The push is slightly more swingy.
> Given the right board-state, some lines can be judged to favor one side over the other.

Ultimately, what this means is that if you don't want to think too hard about your joseki, you might want to adopt the knight's move as your main option.
If you know the lines of the knight's move well, it is basically impossible for you to make a serious mistake and come out with an uneven result.
You don't need to worry all that much about timing a local continuation, since it is relatively rare that a local continuation from a knight's move is overwhelmingly better than any other option.
However, it also means that there is very little opportunity for you to punish your opponent for a mistake.
It is a joseki with a very even keel.

With the push the probability of an unfavorable outcome increases slightly, and you need to match it to the global board-state a little more carefully.
However, if you play it well, you also have the possibility of coming out slightly ahead.
It's a joseki where you want to know the ins and outs pretty well to get the most out of it.
Realistically, if you're at the level where you're capable of getting the most out of the push variation, then you're way too strong to be reading this blog.

### The long version

Now, let's finally get into the details.
The nature of the difference between the two joseki can be stated quite briefly:

> In the push variation, the invader owes an extra move locally, and the joseki has a tendency to favor whoever returns to the position first.
> In the knight's move variation, neither side gets any significant local advantage by playing the first follow-up.

Explaining this dichotomy, however, requires us to understand some basic ideas specific to these joseki.
The first of these is to understand the strength of the groups involved.

#### Why is tenuki possible for the defender?

To explain the strength of the groups involved in each joseki, it is instructive to explore the question: why is Black able to tenuki at this stage?
Let's first consider this question for the knight's move.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-21-sgf/02.sgf"></div>

<section markdown="1">

In the knight's move variation, Black's group is able to withstand quite a lot of pressure from White before having to respond.
This is because in the knight's move, Black has access to sente moves against the corner which revolve around the critical shape point at the 3-2 point and the jumping tesuji at the 2-5 point.
Since Black's group is able to survive multiple approaches from White with ease, it is considered to be a strong group.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-21-sgf/03.sgf"></div>

<section markdown="1">

The push variation tells a similar story.
Even if White attempts to pressure Black, the weakness at the 3-2 point means that Black has sente moves against the corner to help it settle.
Therefore the Black group in the push variation is also considered fairly strong.
Of course, in both cases it is also fine for Black to extend from its wall before it comes under pressure: the point is that Black is at least not *obligated* to do so.

#### If the invader plays first

So we see that in terms of the outside standing up to pressure, both lines are essentially equivalent.
The first difference between the two will arise when we consider how each line evolves after each player returns to the corner down the line, and can be summarized as follows:

> The invader gets a lot out of playing first in the push variation, and not that much in the knight's move variation.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-21-sgf/04.sgf"></div>

<section markdown="1">

First we will consider how the knight's move variation develops if the invader gets the first move locally.
The typical local continuation for White is the diagonal move, which aims to pressure Black by repairing some of White's aji and taking away Black's aforementioned escape routes.
However, here we run into a weakness inherent to the knight's move: because of the low position of White's stones, and because White still needs to mind Black's jump tesuji in the corner, ultimately White can only exert so much pressure on Black with this move.
We see here that White is unable to mount a fierce resistance if Black decides to press from above, and ultimately Black's stones remain fairly secure.
The takeaway here is that in the knight's move variation, the invader tends not to get a whole lot locally even if it gets to play first.
Consequently, in high-level games this diagonal move tends to go unplayed until the mid-late stages of the opening.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-21-sgf/05.sgf"></div>

<section markdown="1">

However, if we run the same exercise for the push variation, things change rather drastically.
When White plays first in this joseki, White gets a nice atari in sente and a very important descent to the 3-2 point (funny how that point keeps coming up, eh?) which is deceptively large by virtue of accomplishing important goals simultaneously.
The takeaway here is that in the push variation, the invader gets quite a lot out of coming back to the corner first - the first significant departure from the knight's move.
This is a sequence that is well worth playing early if the invader gets the opportunity.

#### If the defender plays first

Now let's try this exercise again, but this time assuming that the defender gets the first move locally.
This discussion is a bit more complicated, because there are many ways for the defender to play locally, especially in the knight's move variation.
But the executive summary is as follows:

> The defender can essentially force a sequence in the push variation which is favorable with the ladder.
> In the knight's move variation the defender cannot force such a favorable sequence, and the invader can generally come out with an even result.

The idea here is to note the key shape differences from the defender's perspective in both variations.
In the push variation, the invader's group is pressed up against the defender's outside group, and consequently has a noticeable shortage of liberties if the defender takes the 3-2 point, which we noted comes to great effect when the defender needs to settle against pressure.
The invader effectively owes a move locally (the 3-2 point), and with first move the defender can collect on this debt.
As a consequence of this shortage of liberties, the defender is better able to dictate the invader's response.
The knight's move variation essentially removes two stones from the push variation, which adds an extra liberty to all of the defender's stones.
This extra liberty makes it hard for the defender, even with first-move advantage, to force the invader into any particular sequence, so the invader is generally able to dodge sequences it deems unfavorable in light of the global board-state.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-21-sgf/06.sgf"></div>

<section markdown="1">

The above diagram shows the forcing sequence in the push variation when the defender plays first.
Because of White's shortage of liberties, it is quite difficult for White to deviate from the eventual double hane, which allows Black to take advantage of its favorable ladder.
Moreover, note that in playing this forcing sequence, Black is also denying White the first move, which we previously noted to be big for the invader in the push variation.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-21-sgf/07.sgf"></div>

<section markdown="1">

For the knight's move variation, the defender has a multitude of ways to play the first move locally, but options B and C in the above diagram are fairly peaceful.
Black generally lets White leave easily in the corner in exchange for expanding its moyo, and none of the outcomes significantly favor either side locally; as usual, the status of such territory-influence exchanges comes down to the global board-state.
Option A is the most combative option, and there is a single line here in which Black benefits from a favorable ladder.
However, White has the freedom to dodge this line, at two separate points no less.
Although A takes the same critical 3-2 point that we keep coming back to, in the knight's move variation taking A does automatically give the defender all the agency in the choice of joseki.

#### The game plan

So, to summarize:

1. In the push variation, returning to the corner first tends to be fairly valuable.
With first-move advantage, the invader gets to play a very large descent, while the defender denies this descent and can potentially force a locally favorable joseki with a favorable ladder.

2. In the knight's move variation, returning to the corner first tends not to be all that valuable.
The invader cannot do much to extract a huge advantage even with the first move, and the defender doesn't have many ways to force any specific type of favorable response.

With this we are finally ready to describe how one chooses between the two variations, and how one develops their game plan around them.

> The invader plays the push variation with the intent of spending sente fairly early on to return to the corner.
> This will usually happen via the defender spending sente to play a large move elsewhere, and the invader will look to arrange for this to happen rather than the defender playing the corner first.

> The invader plays the knight's move with the intention of leaving the corner alone for quite a while.
> Neither player will find it urgent to follow up in the corner first, and both players will wait until bigger moves have been played or some global need to decide the local situation quickly arises.

At amateur level, these differences are unlikely to really matter.
Kyu players can't be expected to consistently play the push variation optimally: you need a pretty sophisticated understanding of opening theory to successfully arrange for you to get sente just as returning to the corner becomes the biggest move on the board.
But all you really need to know to effectively play the push variation is that returning to the corner tends to become the biggest move on the board pretty quickly, so you should make it a relative priority.
And all you really need to know to effectively play the knight's move is that you can use it essentially at any time, but unless you have a specific reason, you should stay away from the corner once it has been played as it is not urgent for either player.

### Examples from simulated play

As usual, we end this article by putting our ideas to the test with the aid of AI.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-21-sgf/08.sgf"></div>

<section markdown="1">

In this KataGo experiment, we set up a typical opening scenario and simulate a number of games from the same position based on White taking the knight's move or push variations in the top right corner.
Our goal is to identify general trends in how KataGo changes its play based on which variation we select.

Our simulations demonstrate virtually all aspects of the ideas we have described above.
When using the push variation, KataGo makes it a priority to return to the corner first, barring some specific cases as the defender in which the first move is discouraged by an unfavorable ladder *and* direction of play.
In the top left corner, we even see an example in which Black manipulates the direction of play and a favorable ladder to discourage White from playing first.
With the knight's move variation, we see that KataGo is perfectly happy to let the rest of the board play out before returning to the corner, if it does so at all: the first time this occurs is top variation, move 30.
We also see an instance of KataGo using the defender's emergency escape option in the knight's move variation when the defender comes under pressure from the outside.

### Conclusion

With this we have covered the main strategic differences between the push and the knight's move variations of the 3-3 invasion.
Ultimately, at amateur level it is perfectly acceptable to use either one as you see fit.
The important aspect of these variations is not how to choose which one to play, as they are nearly equivalent in value in most situations.
Rather, the key point is to understand that though these joseki are usually similar in terms of value, they do play fairly differently in the continuations, and you must adapt your play accordingly.

In the next articles in this series, we will start looking at the individual variations (knight's move, push, one-space jump) in greater detail.

[Return to the 4-4 Jōseki page.](/44/)

</section>