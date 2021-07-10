---
layout: post
title: Dr. Dodge or; How I Learned to Avoid the Pincer and Love the Tenuki
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

I will be the first to admit that 3-4 pincer jōseki terrify me.
They are rife with complications and many lines are quite delicate: a single misstep and the position is irredeemable.
Not only that, it's quite difficult to find a unifying theme for the different variations or even the different types of 3-4 pincer jōseki, in contrast to 4-4 pincers which all work more or less the same way.
And even if you somehow manage to devote enough time to memorize a majority of the lines, ultimately this isn't all that useful: many 3-4 pincer jōseki are extremely sensitive to the global board state and there is no reason to expect a good outcome even if you follow them to the letter.

Fortunately, there is a way around dealing with 3-4 pincers that is more fruitful than religiously memorizing their myriad lines.
It turns out that in the vast majority of scenarios, there is no significant need to dive into the rabbit hole of 3-4 pincers: you can almost always dodge playing out a 3-4 pincer if you so choose.
And lest the responsible among you fear this is a sign of laziness or weakness: the conclusions we draw here bear out perfectly well with AI analysis and professional play.
Even pros will admit that they do not necessarily have an encyclopedic knowledge of 3-4 pincers, and I can point you to times when they have gone on the record saying as much.
The objective of this post is to dispense with the idea that one needs to understand all the complications of 3-4 jōseki, and liberate you from the pressure of the pincer when you consider playing the 3-4.
As a side objective, we will demonstrate the danger in over-reliance on advice from jōseki dictionaries.

### Nobody's making you pincer

> Principle #1: There is rarely ever a need to initiate a pincer yourself.

First let's discuss the pincer from the perspective of the player who does the pincering - the *pincermaster,* if you will.
Obviously the pincermaster has all the agency in the world - if the pincermaster doesn't want to pincer, then that's the end of the story!
So if you don't like or don't have a good understanding of 3-4 pincers, then at least half of your problems are already solved: you can confidently dodge the pincer in those cases where you are the pincermaster.

But that all sounds a little too obvious and trite.
If you want to improve your game you should naturally ask the follow-up question: "Is there ever a situation in which I am the pincermaster and I *should* pincer?"
That is, can an early-game situation arise where the 3-4 pincer is *so* good that it blows its competition out of the water?
In that case, in order to play optimally you would have no choice but to pincer even when you are pincermaster.

The answer to that question is: probably not.
Such a situation would be rather highly contrived.
The thing to understand is that pincers are usually not the absolute best move on the board unless they are supported by a certain global board-state.
That doesn't make them *bad* moves outright in most early game situations: they remain in the class of reasonable opening moves which differ from the optimal moves by only a few decimal points.
But it does mean that usually you don't need to feel like you *have* to pincer.
Here are a few examples to illustrate the point.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-09-sgf/pincer-sgf/01.sgf"></div>

<section markdown="1">

Here we've put down some fairly typical first five opening moves, and had KataGo analyze some of White's follow-ups in the top right.
As we can see, KataGo slightly prefers the corner and side-oriented moves A, B, and C over any of the pincers.
This is a consistent pattern with AI analysis, which tends to dislike 3-4 pincers like these in the very early opening, and which explains why they have largely disappeared from top professional play.
This is also consistent to a degree with classical theory, which would state that the pincer on an empty board like this isn't *bad,* but pincers are really best if they also serve as extensions from a position of strength in the opposite corner.
Here White does have a stone in the opposing 4-4, which is better than nothing, but not nearly as powerful as an enclosure for example.
Of course, these winrate and score differences are not significant enough to make a big difference at the amateur level, but it does mean that at least in this situation, you should not feel like you *need* to play the pincer as White.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-09-sgf/pincer-sgf/02.sgf"></div>

<section markdown="1">

How about if we change the position to one where classical theory would recommend a pincer?
Here Black has spent sente to enclose the bottom right corner and White approaches the bottom left 3-4.
This time KataGo rates the pincer at A more highly as we'd expect, but it still struggles to choose between this and the knight's move at B.
C, D, and E are the next best options according to KataGo, and all other options are rated less positively: in particular, A and D are the only pincers KataGo seems to like.

What we gather from here is that even if the situation is pretty favorable for the pincermaster to pincer, that doesn't necessarily make it better to pincer as opposed to another option.
Here the choice between A and B is largely up to playstyle and jōseki knowledge.
If I am playing White in this position, then I would elect to play B, since if neither one is theoretically superior to the other then I may as well play the jōseki I find easier to play (and most players should find the lines of B far easier to understand than A).

A secondary piece of information we gather is that not all pincers are equivalent.
There are something like 8 different viable pincers in this position for White, but KataGo only thinks A and D are an even result for White.
(I can't say for sure, but this probably has to do with the opposing enclosure being a two-space high enclosure, and White wanting to keep a high and flexible position early on.)
This is an extra burden that the pincermaster needs to deal with: even if you are comfortable with playing the pincer, it's a separate thing entirely to understand just *which* pincer is the appropriate one at any given time.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-09-sgf/pincer-sgf/03.sgf"></div>

<section markdown="1">

Let's go through one last example to illustrate the idea from the pincermaster's perspective.
Here the notable feature is the 3-3 invasion jōseki in the bottom right.
This time, when White approaches, KataGo does consider a pincer to be the best option, preferring the distant pincers A, C, and D above the other options.
(This has to do with the Black wall, which can be prone to turning into a weak group later in the game; the pincer serves as both an extension and reinforcement.)
Nevertheless, KataGo still considers the knight's move at B to be essentially as good as these pincers.

The takeaway from these examples is that at least as far as AI is concerned, if you do not want to play a 3-4 pincer then you're in luck.
Roughly half the time you will be the pincermaster from a 3-4 corner, and these examples illustrate that the pincermaster is almost never *required* to pincer from a 3-4 stone.
As long as the game has not progressed extremely far elsewhere on the board, you will almost certainly have a non-pincer option that is at least as viable as the pincers, if not outright better than them.
So then the only question that remains is: how do I avoid the pincer if I am *not* the pincermaster?

### Dodging the pincer I: When in doubt, tenuki

> Principle #2: Tenuki is usually a viable response to a 3-4 pincer.

If you are around or not yet mid-SDK level, you may be surprised to learn that tenuki is not only a viable option against a 3-4 pincer, it is often one of the best responses!
This is where we break with typical jōseki dictionaries such as Kogo's, which traditionally look very unfavorably upon tenuki in response to a pincer.
As an example, let's see what Kogo's has to say about tenuki in the low approach, one-space low pincer:

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-09-sgf/pincer-sgf/04.sgf"></div>

<section markdown="1">

Kogo's characterizes the one-space low pincer as the "severest attacking move" and claims that it "does not permit White to switch lightly elsewhere."
Upon White passing, Kogo's claims that this "invites a loss" without the ladder.
This is an example of the worst kind of advice that is commonly offered in a typical jōseki dictionary, and a good reason to avoid relying on them to decide what to play.
There are some elements of truth to what is said here, but there's so much missing context that it is easily subject to misinterpretation.

We will use this jōseki as a springboard to illustrate some general principles behind how the tenuki from a 3-4 pincer (of any variety) works.
In particular, we will disavow the notion that White cannot easily switch lightly elsewhere here, and that the tenuki without the ladder "invites a loss."
Instead, switching lightly elsewhere and doing so without the ladder is *precisely* what we are going to do!

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-09-sgf/pincer-sgf/05-1.sgf"></div>

<section markdown="1">

Let's examine how things go if we tenuki here.
Black's most common local continuations are the kick and the attachment on top.
Let's consider the kick first.

After the kick, White main options are twofold.
The most obvious local continuation is to form a pillar.
This outcome is fairly straightforward: Black grabs a little side territory and chases White out toward the center, perhaps looking to play both sides.
White is admittedly weak but not in a huge amount of danger, and will look to balance the tax it pays for this weak group with the gains it made earlier by playing elsewhere.

However, the most incredible thing about this position is that White can tenuki *one more time!*
In that case, Black's best local continuation is to attach on top, completely smothering this White stone (move 3, top variation).
You may well ask: isn't this a disaster for White?
What was the point of approaching at all if White's just going to let Black take such a commanding position in this corner?

Actually, this is a clever sacrifice play from White, which we can unravel using some tewari analysis.
The idea is that after Black attaches on top, this position transposes to if Black started with the squared one-space high enclosure.
In that case, the triangled stone is overconcentrated: it is too close to Black's enclosure, and should really be one space further away.
Granted, the 1-2 exchange is a bad one for White in the presence of the high enclosure, but it is bad mainly in terms of deleting aji (aji-keshi); Black has preemptively limited how large a corner it can build here with the narrow extension.
So ultimately, what happened here is that White and Black each added a suboptimal move to a one-space high extension, but White also played elsewhere twice and has sente.
If you put it that way, things don't sound so bad for White anymore, do they?

Not only that, there is still a tiny bit of value left in the White stone.
For instance, White could continue locally at A to put a few stones on the outside in sente, or perhaps threaten a connection underneath to get an approach from the side in sente.
So despite Black having invested a total of *four* stones in this area to White's one, there's *still* some aji left in this position for White to exploit!

So to summarize, to capture White's stone by attaching on top is overconcentraded and smaller in value than at first glance.
Of course, Black knows this as well.
Therefore Black can *also* tenuki from this position (bottom variation), and the local position becomes very interesting.
Black's goal will be to capture the White stone indirectly, namely by omitting the attachment on top.
White's goal will be to force Black to capture directly, forcing Black into the aforementioned overconcentrated position.
The final evaluation of who comes out on top may not happen for quite a while yet.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-09-sgf/pincer-sgf/05-2.sgf"></div>

<section markdown="1">

If Black opts for the attachment on top instead of the kick, then these are some of the outcomes that can arise.
We first note that by the same logic as before, White does not need to respond immediately to the attachment.
After all, what's Black going to do - spend another move locally to kill?
We've already established that it would be overconcentrated for Black to do so.
This time, there is a difference in that Black can force this corner into a ko if White plays elsewhere again.
But remember that White is already treating this stone lightly by playing elsewhere twice - forcing Black to play a ko to kill is perfectly fine by White's standards.

If White does respond locally then the outcomes are generally some type of Black-thickness-for-White-territory exchange.
Generally these exchanges are locally good for Black, but this is to be expected - Black has at least one extra stone locally, and globally we still need to account for the value of the White tenuki and sente (which White tends to get in these variations).
And as with any thickness-for-territory exchange, ultimately the evaluation of this position isn't really about who came out on top locally.
All such exchanges can only be evaluated in conjunction with the global position and direction of play.
If Black cannot get its thickness pointing in the correct direction of play, then these outcomes are generally good for White.

Once we understand these ideas behind the tenuki in the one-space low pincer, they adapt easily to other pincers as well.
The point here is not to memorize these specific variations, but just the general idea behind why tenuki is a viable response to a 3-4 pincer.
It should of course be said that the variations we've shown are far from the only ones that are possible in the one-space low pincer, tenuki variations.
The gist of it is that there is a good chance that the pincermaster cannot capture the pincered stone cleanly with one move.
For narrow pincers it might even be overconcentrated to kill, while for wide pincers your stones have a bit more breathing room to survive a tenuki in the first place.
Let's now see a few examples of how this works in a simulated game.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-09-sgf/pincer-sgf/06.sgf"></div>

<section markdown="1">

Here we have created a hypothetical early-game position in which White has just pincered in the top left, and we will aim to showcase just a few of the possibilities that can happen if Black ignores the pincer.
We preface by saying that this is not intended to mean that tenuki is the only option.
As a matter of fact, in this starting position it is also viable to respond locally at C; A, B, and C all have similar winrates and are in fact the highest rated choices by KataGo.
The point of this exercise is merely to demonstrate that tenuki is a viable option, to the point that AI considers it among its top choices in this particular board state.

The first line we explore is the kick (top variation), and here to prove our point we in fact take the line where Black plays elsewhere twice.
We see that by completely foregoing any attempt to save the pincered stone, Black can use its two free moves to quickly establish a presence everywhere on the board and even begin going on a counter-offensive in White's opposing corner.
White comes out of this with an extremely strong group in the top left, but otherwise it is so far very limited in what parts of the board it lays claim to.
As a result, Black actually comes out slightly ahead in this line.
There are many other ways to play the kick from this starting position, including responding locally, all of which KataGo considered at least playable.

The second line we explore is the attachment (bottom variation).
Here we note that Black, by virtue of having the bottom right corner, has the ladder and therefore can play the wedge.
By the end of the sequence, White has some decent influence and sente while Black has a respectable corner.
If we do some tewari analysis, this isn't that different from if Black *first* plays the top left corner in a way to exchange the corner for influence in sente, and *then* uses sente to enclose the bottom right corner, as opposed to vice versa.
Such a sequence of events is, of course, nothing new if you've played enough games at the SDK level, and it makes sense that this variation results in no significant change in winrate or score for Black.
Again, this is not the only line KataGo considers viable after the attachment, and things can play out in several ways (including all of the ways we have discussed above).

### Dodging the pincer II: Make a base on the side

> Principle #3: Making a base on the opposing side is usually at least playable.

If you are DDK or high SDK, you might find the previous discussion somewhat intimidating, and that is fair.
To benefit properly from the tenuki requires a certain amount of global intuition that you may not have developed just yet.
However, that does not mean that all hope is lost if you are confronted with a 3-4 pincer
There is another, far simpler way than tenuki around a 3-4 pincer.
This is to simply give up the pincered stone and make a base on the opposite side.

A major reason for why complications arise in 3-4 pincer jōseki is that many lines involve both players working with cut groups, and usually one cannot afford to sacrifice one of the groups right away.
Abandoning this goal entirely drastically simplifies the jōseki.
The basic ideas for why this works are the same as with tenuki; in a sense, we are doing a semi-tenuki, in that we are playing somewhat locally but not locally enough to connect with the pincered stone.
The preceding discussion for the tenuki explains why this is ok: it is rare that the pincermaster can cleanly kill the pincered stone in one or even two more moves, so you can make up for the loss of the stone using the establishment of an outside group and the aji left in the pincered stone.
The tradeoff for this simplicity is that sacrificing the pincered stone immediately is typically not locally optimal.
However, it is usually not so unfavorable to the point that it is unviable.
Often the difference is as small as 0.5 points, which is not something that tends to decide a game at the SDK level, whereas confusion with a jōseki can easily send a game out of control.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-09-sgf/pincer-sgf/07.sgf"></div>

<section markdown="1">

We illustrate this with the two-space high pincer to the one-space high approach.
Here, instead of responding directly to the pincer, White elects to establish a base along the bottom side, inviting Black to cut White apart and take a large corner.
The initial jump feels very similar to other variations of the two-space high pincer in which White jumps out.
The difference is that the jump is intentionally too wide to prevent the cut.
The reason that complications arise after jumping out of a 3-4 pincer jōseki is that normally White wants to continue doing work with its inside stone after the cut, and therefore must commit to a potentially complicated fight to keep it alive.
Abandoning this goal entirely drastically simplifies the jōseki.

The differences between the two variations essentially come down to who takes sente; however, even in the bottom variation where Black takes sente, Black in fact owes White an extra move locally.
White's job will be to use the aji in this position and sente/half-sente to make up for local loss it incurs by allowing Black to take this large corner.
This is, of course, not specific to the two-space high pincer, nor to the high approach: the principle of sacrificing the pincered stone for an outside base works in general.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-09-sgf/pincer-sgf/08.sgf"></div>

<section markdown="1">

Let's see this idea in action.
In response to White's two-space high pincer Black appears to sacrifice the pincered stone.
Now, as we have mentioned previously, such a move is usually not locally optimal, but overall the loss is just 0.5 points and 2.5% winrate - not the kind of difference that decides amateur games.
All moves following the initial jump are essentially optimal according to KataGo, and we see no subsequent loss in winrate or score.

It should be noted that this position is helped a lot by Black having the opposing corner to support Black's wall.
If the position is changed so that the wall faces a White corner, then the score drops by another 0.5 points against Black.
This support allows Black to play a corner enclosure as an extension and establish an imposing Black moyo.

Here we see some of the aji present in the pincered stone come to life early, and this is the kind of aji you need to be aware of to use this strategy, as White's corner is indeed too large to give away completely for free.
There are some lingering questions left on the board: is White's corner large, or is it overconcentrated?
Are Black's stones in the center in prime position to limit the scope of White's expansion, or will Black bleed points as it attempts to stabilize the group against White harassment?
Can White spare a few extra moves on the left, or is Black's moyo too threatening to completely ignore for much longer?
All in all, Black has managed to create a fairly stable position without falling into a labyrinth of complications, and can look forward to a more strategically defined rather than tactically oriented opening.

### Summary and conclusion

In this article we explored ways one can avoid dealing with complications when faced with a 3-4 pincer jōseki.
As pincermaster, there is rarely ever a need to initiate a 3-4 pincer if you are not comfortable with it.
If you are not pincermaster, then tenuki is almost always viable and usually among the top options, while those of you who are less comfortable with the idea can still sacrifice the pincered stone for a position on the side in order to avoid all complications.
In addition, I hope this article reinforces the need for active learning when it comes to jōseki, and the danger of taking the word of jōseki dictionaries as gospel.

[Return to the 3-4 Jōseki page.](/34/)

</section>