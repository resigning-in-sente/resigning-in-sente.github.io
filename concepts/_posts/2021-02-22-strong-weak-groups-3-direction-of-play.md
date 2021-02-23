---
layout: post
title: Strong and Weak Groups 3 - Determining the Direction of Play
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

> This is the third article in the series "Strong and Weak Groups."

> [Previous article](https://resigning-in-sente.github.io/concepts/2021/02/20/strong-weak-groups-2-attack-and-defense/), [Next article](/concepts/).

In the [first article](/concepts/2021/02/19/strong-weak-groups-1/) in this series, we identified how to recognize when groups are weak or strong.
In the [second article](https://resigning-in-sente.github.io/concepts/2021/02/20/strong-weak-groups-2-attack-and-defense/), we discussed how one exploits imbalances in the strength and weakness of groups to play profitable moves.
In this article, we will explain how to synthesize these concepts into the strategic principle and decision known as *direction of play.*

### What is the direction of play?

When we first start learning to play baduk, we are commonly taught the following basic principles of baduk strategy:
* First play the corners, then the sides, then the center.
* Play urgent moves before playing big moves.

Direction of play is a concept that consolidates these and all similar concepts into one.
It asks a question with a simple premise: *in what general area of the board should I play my next move?*
Of course, the simplicity of this question is deceiving: anyone who has played more than a few games of baduk knows the feeling of being lost in the vastness of the 19x19 board.
However, it may surprise you to learn that determining the direction of play is actually fairly straightforward a lot of the time.
The key to it all is the concept of strong and weak groups.

### The most important proverb in baduk

The fundamental principle in the determination of direction of play is summarized by the following proverb:

> Play away from strength.

Simple and understated, this proverb is in fact the deepest and most important one in all of baduk.
Nearly all opening and middlegame strategic concepts can be boiled down to this one.
Its meaning is precisely as it states: the correct direction of play is away from the strong groups on the board, and close to the weak groups.
This means to play away from both your opponent's strong groups *as well as your own,* and to play near your opponent's weak groups *as well as your own.*

The logic behind this idea is the following:
* You should not play near your opponent's strong groups, because by definition a strong group will not be pressured by such a move.
* You should not play near your own strong groups because your strong groups do not need to be reinforced.
* You should play close to your opponent's weak groups, because this will put pressure on your opponent's groups.
* You should play close to your own weak groups, because this reinforces your weak groups into strong groups.

We'll do a full accounting of these four ideas later.
For now, there's no better way to learn this concept than to see some examples.

### Example 1-1

</section>

<div class="besogo-diagram" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-22-sgf/direction-of-play-sgf/01.sgf"></div>

<section markdown="1">

Let's examine the above position from a sample game.
White has just played (1) as part of the 4-4, double low approach jōseki.
At the moment the game is fairly even, with KataGo assigning about ~50% winrate and a score of ~B+0.
In which general direction should Black play next, and why?

##### Determining the weak and strong groups

Before we do anything here, we first need to take a look at the state of the board, and account for the strength of each of the groups.
Remember our criteria from the [first article in this series](/concepts/2021/02/19/strong-weak-groups-1/) for determining which groups are weak and which are strong:
* Groups are stronger the closer they are to unconditional life, and weaker the farther away they are from it.
* Groups are strong if they can ignore many moves from the opponent before feeling threatened, and weak if they have many moves against them that threaten them.

With these criteria firmly in mind, let's go through this board carefully, corner by corner.

</section>

<div class="besogo-diagram" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-22-sgf/direction-of-play-sgf/01-1.sgf"></div>

<section markdown="1">

White's corner in the top right is **strong.**
Generally enclosures are strong shapes in the early stages of the game.
There is nothing Black can do to this corner at the moment that will make White fear for the status of its stones.
Later on when Black has more stones nearby Black might aim at some of the aji associated to the large knight's move enclosure, but to do so at this moment is premature.

Black's corner in the bottom right is **strong.**
The reasons are the same as for White.
With no White stones in the vicinity, White does not have the necessary support to really threaten the safety of these stones.
Again, that's not to say that there's no aji here - there is a lot!
But if we're purely talking about life and death, then Black can afford to ignore multiple White moves in this area before it really needs to start taking care of these stones.

</section>

<div class="besogo-diagram" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-22-sgf/direction-of-play-sgf/01-2.sgf"></div>

<section markdown="1">

White's group in the lower left is **strong.**
These stones have a fairly nice shape for making two eyes, as well as emergency exits to the side and to the center if things get hairy.
They should not struggle to make life unless White ignores several moves against them.
Even then, there is the possibly that White treats part of this group lightly: killing the entire group should be a near impossibility.

Black's group in the lower left is **strong.**
Like the nearby White stones, the Black stones have a nice little base for making eyeshape, as well as ways out to the left side and center.
If Black gets C2 then Black might as well just be considered unconditionally alive.

</section>

<div class="besogo-diagram" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-22-sgf/direction-of-play-sgf/01-3.sgf"></div>

<section markdown="1">

Lastly we turn to the top left corner, and here things get a bit interesting.

White's group, marked with triangles, is **weak.**
The first reason is the cutting point at (A), which is an active weakness thanks to the presence of the circled Black stone.
Although Black does not necessarily want to cut at this very moment, it does mean that White owes Black a move here if White wants to stay connected.
The second reason is that even if White connects up, White's entire group is a bit far from making two eyes.
White does have some eyespace in the corner, but if you work this out carefully then this eyespace only amounts to one eye *in gote.* (We will cover the details of this statement in our [4-4 double low approach series](/44/).)
Therefore White has some work to do before it secures its second eye.

Black's group on the left, marked with squares, is **weak.**
This largely has to do with the cutting point at (B).
Again, White doesn't want to cut right away, but the aji behind this cut makes even just a casual White approach a serious threat to this group's survival.

Lastly, Black's lone stone on the top, marked with a circle, is **weak.**
This stone is clearly a long ways from life: in fact, bunched up so close to so many White stones with a high position, it is under quite a bit of pressure.
A White pincer at C or nearby could rob this stone of its eyespace and force it to run out to the center to survive, but with White having a towering position over it, this stone will likely need several moves before it can run sufficiently far out to collect its breath.

#### Using weak and strong groups to determine the direction of strength

So let's summarize what we've learned:
* All groups in the top left corner are weak to some degree.
* All other groups on the board are strong. In particular, the Black bottom left corner is a strong group.

Now let's apply this to determine the direction of play.
The goal here is not necessarily to guess the *best* next move: merely the general *area* where the best next move is located.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="comment+tree+control" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-22-sgf/direction-of-play-sgf/01-4.sgf"></div>

<section markdown="1">

Black's typical continuation from in this jōseki is either to extend from the group on the left, or to reinforce the stone on the top.
Here this is consistent with direction of play, as both Black groups in this corner as well as the White group are weak, and direction of play suggests that we play near both our own and our opponent's weak groups.
However, since we cannot play two moves at once, we only have the opportunity to take care of one of the two sides.
Which should it be?

The key to answer this question lies in the bottom left corner.
Here there is a strong Black group, and since we want to play *away* from our own strong groups, this suggests that the correct direction of play is to reinforce the stone on the top, such as at (A) or (B), rather than to extend on the left, like at (C), (D), or (E).

This is indeed the case.
(A) and (B) result in no significant loss of winrate, and even a gain of winrate in the case of (A).
(C), however, is about a 4% loss in winrate and about a 0.5 point loss in score for Black.
(D) and (E) are significantly worse, being about a 1.5 point and a 2.5 point loss respectively.
As we can see, the closer our stones get to the bottom left corner, the worse KataGo evaluates it, but that's not all: (D) and (E) are also *farther away from White's weak group on the top right.*

The sequences following each choice are just some of the many possible continuations, which serve to illustrate how these differences in winrate play out in concrete fashion.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="comment+tree+control" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-22-sgf/direction-of-play-sgf/01-5.sgf"></div>

<section markdown="1">

Just to further verify that out theory on the direction of play is correct, let's check out how KataGo likes it when we *really* mistake the direction of play.
* (A) is reinforcing a Black enclosure that doesn't need it, so is value is purely in terms of the territory it claims and the influence generated by the enclosure. It is certainly valuable, but with the situation in the top left still unfolding, now is not the time.
* (B) is slightly better in that it puts a little pressure on White's group, which does have some bad aji at (A) and (B) with this Black stone nearby. But ultimately, this is still a strong White group that Black is approaching, which is not nearly as important as the three weak groups in the top left.
* (C) is also too close to Black's strong corner. It does limit the potential of the top right corner, but it is just another move that purely claims and denies territory without doing anything for the stones it is supporting.
* (D) is in the right direction, but it is one step too far from Black's weak group. Since both White and Black are weak in the top left, it is better for Black to play more solidly here. Black becoming stronger here correspondingly makes White's stones even weaker. White will invade at A (which is supported by its strong top right corner), hoping to settle its top left by exploiting the thinness of Black's stones.
* (E) is interesting - unlike the others, it leads to no drop in winrate. Its meaning is just as a sente exchange - Black wants White A before returning to the top right. This is a minor loss locally as it eliminates all the aji in White's group, but Black's reasoning is that having this outside stone may help the fight on top or just help Black get out to the center later.

### Example 1-2

</section>

<div class="besogo-diagram" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-22-sgf/direction-of-play-sgf/02.sgf"></div>

<section markdown="1">

Let's now try this again, with a small modification to the previous scenario.
This time White has played a 3-3 invasion jōseki in the lower left corner.
Once again, in order to determine the direction of play we need to evaluate the strength and weakness of each of the groups.
Since the only difference is in the lower left, we simply update our evaluation there.

The White group in the lower left corner is **strong.**
It is obviously unconditionally alive and can even escape out to the side or center if it needs to.

The Black group in the lower left corner is **strong,** although this is not nearly as obvious as for White.
This is based on prior knowledge of the aji in this jōseki, which will be covered in our [early 3-3 invasion series](/44/).
The basic idea is that Black's wall has a few emergency escape options to help it settle even if White denies its eyespace on the bottom side: (A) and (B) are sente against the corner, and the aji there give Black a way to secure either eyespace on the side or a way out to the left side.

Based on this analysis, we arrive at the same conclusion as before, which is that both groups in the bottom left are strong.
Therefore our direction of play should be the top side, same as before.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="comment+tree+control" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-22-sgf/direction-of-play-sgf/02-1.sgf"></div>

<section markdown="1">

Indeed, KataGo bears out our analysis when we examine the same five moves from before.
Either play reinforcing the top Black stone is near optimal, while each of the extensions on the left are received poorly.
Once again, the further the extensions on the left, the worse the reception by KataGo - because they are closer to the strong stones in the lower left, and farther from White's weak group in the top left, hurting the ability for Black to fight on the top.

### Example 1-3

</section>

<div class="besogo-diagram" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-22-sgf/direction-of-play-sgf/03.sgf"></div>

<section markdown="1">

To demonstrate that this isn't just a case of the top side always being better, let's change the situation one more time.
This time in the bottom left, White played out a 4-4 low approach jōseki from the *left* side.
Is there a difference in the direction of play, and does KataGo think differently about the top left corner?

First, let us evaluate the strength and weakness of the groups once more.
Again, only the bottom left needs re-evaluating.

The Black group on the bottom left is **strong.**
There is some aji against it, but it has a decent base for eyespace and access to the center and the side.

The White group on the bottom left is **slightly weak.**
The issue, as always in this shape, is the peep at (A).
If White is forced to connect in response to the peep, then the whole group does not have two eyes and is liable to be chased around.

With this the status of the bottom left corner has changed: instead of both groups being strong, now there is a slightly weak White group.
This should now introduce some changes into the direction of play.
The extensions from the Black group on the left should better than before, because they are now also approaches to the weak White group on the bottom left.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="comment+tree+control" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-22-sgf/direction-of-play-sgf/03-1.sgf"></div>

<section markdown="1">

Once again KataGo confirms our intuition.
(A) and (B) are as good as before: our analysis of these moves has not changed significantly.
But now, (C), (D), and especially (E) are much more positively viewed by KataGo, with (E) (the closest to the bottom left) being considered the best out of all five options.
This is because the extensions further weaken White's bottom left, with the threat of the peep looming ever closer.
With Black having settled one weak group, now White has two weak groups to Black's one, forcing White to find a way to somehow settle both groups while Black only needs to focus on one.

These examples should hopefully convince you that the intuition from the principle "play away from strength" bears out in actual play.

### Summary

Once again, there is only one rule you need to follow: "play away from strength." Let's take a moment to summarize how things can go wrong when you, and how things can go well when you follow it.

#### Playing close to your opponent's strength

What happens when you play close to your opponent's strong groups?
* Since by definition strong groups don't really need taking care of, your opponent could just ignore your move and play something more valuable - in other words, you would give up sente.
* Since your opponent is strong in the area, your move is unlikely to make much territory, as your opponent could use their strong group as support for a reduction or invasion.
* If your approaching stone is weaker than your opponent's strong group, then in the worst case scenario your opponent could go on the attack.

#### Playing close to your own strength

What happens when you play close to your own strong groups?
* Since your own strong groups don't need reinforcement, an extra stone close to them would be a redundant move that could have fulfilled a more meaningful purpose elsewhere.
* Since strong groups tend to consist of a multitude of stones in close proximity, adding another stone nearby could lead to overconcentration.

#### Playing close to your opponent's weakness

What happens when you play close to your opponent's weak groups?
* Since weak groups are still a ways away from settling, your move is likely to be sente against the group, meaning at the very least you can keep the initiative.
* Using the basic ideas outlined in the [Attack and Defense](https://resigning-in-sente.github.io/concepts/2021/02/20/strong-weak-groups-2-attack-and-defense/) article, you can exploit the weakness of your opponent's group to derive benefits in sente.

#### Playing close to your own weakness

What happens when you play close to your own weak groups?
* Adding an extra stone near a weak group will help it get closer to settling; if it settles entirely it may even turn into a strong group, which can support your other stones.
* Reinforcing a weak group will make it more difficult for your opponent to derive benefits from attacking it, and may even forestall such attacks permanently.

### Caveat

This sounds very simple and all: as long as you can accurately determine which groups are strong and which are weak, it is easy to determine the correct direction of play.
There is, however, one thing that makes this a nontrivial problem.
Determining the strength of groups is already pretty hard!

In fact, this is the greatest obstacle to being able to correctly determine the direction of play.
The strength of groups is not always as readily apparent as in the examples we have chosen to explain the concept.
Most mistakes in direction of play arise from miscalculating the true strength and weakness of groups.

Since strength and weakness of groups is ultimately tied to their life and death status, this makes life and death practice fundamental to all baduk players.
In fact, this is the single most important reason for you to practice life and death problems: it allows you to properly evaluate the strength of each group, which allows you to determine the correct direction of play.

### Conclusion and takeaways

In this article we have introduced the concept of direction of play, and how it can be determined using the concept of strong and weak groups.
We have also seen simple examples of how this calculation works in practice.

Direction of play is a deep concept, and this is far from the last time we will touch upon the subject.
Later articles in the series will further develop this concept with more varied examples of using direction of play to inform opening and middlegame decision-making.

[Return to the Concepts hub.](/concepts/)

</section>