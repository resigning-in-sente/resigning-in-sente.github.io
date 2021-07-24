---
layout: post
title: Strong and Weak Groups 2 - Attack and Defense
tags: 
tags: [general-strategy, strong-weak-groups, attack-defense]
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

> This is the second article in the series "Strong and Weak Groups."

> [Previous article](/concepts/2021/02/19/strong-weak-groups-1/), [Next article](/concepts/2021/02/22/strong-weak-groups-3-direction-of-play/).

In the [first article](/concepts/2021/02/19/strong-weak-groups-1/) in this series, we identified how to recognize when groups are weak or strong.
In the remainder of the series, we will examine how this concept is applied on the strategic level.
Our first goal will be to establish the most basic strategic application of weak/strong groups: attack and defense.

### Weak groups are targets for attack

First let us define what it means to attack.

> Attacking is the exploitation of an opponent's weak groups to derive benefits.

Here the key words are "weak groups" and "benefits."
Attacking is fundamentally tied to the strength and weakness of groups: one cannot go on the attack without identifying which groups are weak and which are strong.
As for the ways one can benefit from an attack, these are varied and depend on the specific situation at hand.
Let us see some of these ways via example.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-20-sgf/attack-defense-sgf/01.sgf"></div>

<section markdown="1">

Here Black has adopted a sanrensei fuseki, and White has ill-advisedly approached from *inside* the formation rather than outside.
Black responds with the kick, and White can only afford a one-space extension due to the presence of Black's stone at K4.
This results in a weak White group as we saw in the previous article in the series: White cannot easily establish life on the side and likely needs to jump out to the center.
The question at hand is how Black can exploit this weak group for profit.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-20-sgf/attack-defense-sgf/02.sgf"></div>

<section markdown="1">

Black accomplishes this by harassing the White group and demanding that White treat Black's moves as sente against the group.
There are many different ways Black could go about this, corresponding to different ways Black can benefit.
Black could:

* secure territory on the right and bottom sides in sente;
* build influence toward the lower left or left sides;
* get free placements facing the top side to support eventual stones in the area;
* or some combination of these.

Moreover, Black does not necessarily have to go on the offensive right away.
Black could wait to see how the rest of the board plays out before it decides on how to make use of what are essentially guaranteed moves in sente in the lower right.
Black could even benefit from this weak group without ever playing directly against it.
For instance, if a fight in the center breaks out, White may be unable to respond aggressively, either because of the looming threat of Black's sente moves against its group in the lower right, or conversely because White must avoid certain outcomes of the center battle due to their effect on the lower right.
The great thing about this situation for Black is that Black has nearly complete freedom to dictate *how* it profits from this weak group, and can choose based on the state of the game elsewhere.

Observe in each of these scenarios that the stones Black is placing are useful in some way, having value either in terms of territory or influence or both; White's stones, on the other hand, are merely for survival and do not contribute the same type of value.
This is key to deriving benefit from attacking:

> Attacking entails using your opponent's weakness to make exchanges that are more valuable for yourself than for your opponent.

Observe also that Black is not looking to kill White.
Attacking and killing are very far from synonymous.
Attacking often uses the *threat* of killing to elicit favorable exchanges, but usually does not actually involve killing the group under attack.
This is a key difference between weak and strong players: weak players look to kill, while strong players look to profit from attacking and only kill when necessary.

#### Creating weak groups and attacking for profit

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-20-sgf/attack-defense-sgf/03.sgf"></div>

<section markdown="1">

Here is another example from the opening.
Here Black has opened with the Kobayashi fuseki, and White has made the mistake of making the one-space high approach to Black's 3-4 point.
Black responds with a two-space high pincer, which denies White the opportunity for any eyespace along the side.
Thus White wants to escape along the left side and to the center, but E10 stands in its path.
Normally White can deal with a pincer by building influence and countering with a pincer of its own against the pincer stone, but here the fact Black chose the two-space pincer means that a counter-pincer is unfeasible.

In terms of attack and defense, the mistake White made here was that it made too close an approach to Black's corner in light of the presence of the E10 stone.
For an unsettled group to avoid turning into a weak group, it should have either a way to make eyespace or a way to escape to the center.
Here, with E10 waiting along White's path to the center, White's stone is in danger of turning into a weak group if Black can remove the remaining method for White to settle, which is what the pincer accomplishes.

Once the White group has been made weak, Black goes on the offensive and starts extracting value out of the situation.
Note the four marked stones for Black versus the four for White.
Black's stones are making a tidy profit along the left and bottom sides.
White's stones are not accomplishing much at all; they are making no territory and any influence they generate is counteracted by the strong Black presence along the bottom side.
As a matter of fact, the White group is still unsettled and floating without room for a base, and E10 leaves it with only one direction for escape, leaving them as potential targets for further attack by Black.
For this reason, the classical approach to the 3-4 point in the Kobayashi is the two-space approach at F3, which forestalls the pincer and thus gives White the opportunity to extend along the side.

Once again, at no point during this process does Black actually attempt to go after the kill.
It would be unreasonable to do so at such an early stage in the game, even with Black's local advantage in numbers. and any such attempt would likely be an overplay that would ultimately compromise Black's position.

#### Different types of profit

One of the subtleties to attacking in baduk is that there are so many different ways to derive benefit out of an attack.
Consequently, one of the most important considerations when planning an attack is determining what type of benefit you want to extract; this is a topic for another article.
The various benefits you can derive via the course of an attack (or even the mere threat of an attack) include:

* building territory in sente;
* gaining influence in sente;
* invading or reducing enemy territory or frameworks in sente;
* settling your own unsettled groups in sente;
* influencing outcomes in distant battles;
* further weakening neighboring enemy stones, to put *them* under attack;
* reinforcing your own weaknesses indirectly.

Here is an example of the last of these.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-20-sgf/attack-defense-sgf/04.sgf"></div>

<section markdown="1">

In this diagram Black has opened with the low Chinese, and White has made a standard invasion with the one-space high approach to the 3-4 point.
The key move here is Black 5, which in tandem with L3 denies White eyespace along the side.
This leaves White with a weak group.
Black takes advantage of this in two ways.
First, Black can take L5 in sente (ignoring it leads to White being sealed in with limited eyespace or chased out toward the center), which is a pretty nice strategic point looking toward expanding Black's moyo on the left.
Second, Black uses the weakness of White's group to indirectly cover for the weakness in its shape at (A), created by playing Black 5 as a descent rather than as a tiger's mouth.
Black can omit from defending against it for the time being because White is too busy trying to settle its group on the bottom to try to capitalize on Black's weakness just yet.
Ideally, Black would like to play the likes of (B) in sente as part of the process of attacking White's group, so that it can defend against (A) more efficiently.

That White's group is weak does not necessarily mean the outcome is bad for White; this position is in fact close to jōseki in the low Chinese.
In this case White has jumped into the Black formation fully aware that it will end up with a weak group.
Since White essentially jumped into a pincer it is obvious that the local result will favor Black, who has the numerical advantage.
White's goal here is to settle without giving up too many advantages as it defends against Black's offensive.
Once White settles, it can look to take advantage of the fact that Black has spent an extra stone on its own side of the board at L3, limiting the speed of Black's expansion to the other side of the board.

### Defending against potential attacks

> Defending is the strengthening of a weak group in order to preempt a later attack by your opponent.

It is important to extract advantages out of your opponent's weak groups, but it is just as important to prevent your opponent from doing so more than necessary.
It is impossible to play well without creating any weak groups at all: if you only create strong groups then your play is likely slow and overconcentrated, a topic we will touch on in a later article.
Weak groups arise naturally as part of efficient baduk, the White group in the previous diagram being a good example.
Nevertheless, it is important to avoid the creation of more weak groups than absolutely necessary, and thus defense is another critical skill to master.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-20-sgf/attack-defense-sgf/05.sgf"></div>

<section markdown="1">

Here is an example of a defending move that arises in a jōseki context.
This is a middlegame followup in the familiar 4-4 low approach slide jōseki.
Black's corner position has some bad aji if Black ignores a White approach at (A), as Black cannot block the White push into the corner.
If Black does do so, then White connects out to the approaching stone and Black is left with a very weak group with no eyes and surrounded by White stones - a perfect target for attack.

Black may therefore respond to a White approach in a number of ways, for example by preventing the White push and securing its corner eyespace.
However, this then makes the White approach effectively a sente exchange.
Though blocking off the corner is a fairly large yose move in itself, there may be situations in which being able to approach from the side in sente favors White: for instance, this stone could support other White stones on the right side.
In that case, successfully making this approach in sente is already a successfully concluded attack against the Black corner for White.

For this reason, in some games it is appropriate for Black to preempt the White approach and extend out to the side.
Not only does this defend against virtually all White attacks against Black's group, the extension itself has reasonable inherent value.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-20-sgf/attack-defense-sgf/06.sgf"></div>

<section markdown="1">


Here is another jōseki-related example.
In this common 3-4 low approach position, the triangled point is a weakness of Black's shape due to Black's keima.
In the middlegame, White can look to attack Black's corner by approaching at (A) and threatening the cut.

If Black fails to respond, then the cut is fairly devastating.
If Black cuts in kind, then White splits apart Black's stones, neither of which are settled, and Black will find it difficult to ensure the safety of both sides.
If Black descends in order to remain connected, this opens up a whole new can of worms in the corner: White could take the corner in gote or take outside thickness in sente.

But if Black does respond to White's approach, then this now sente exchange may be good for White in and of itself.
From a territorial perspective Black's response is not worth all that many points, and White's approaching stone could find value in conjunction with White stones on the bottom side or the lower left corner.
If anything, there is the feeling that White has made Black overconcentrated in sente.

Therefore in many games Black prevents White's attack against the corner by extending to (B).
Though the one-space extension may appear slow, it is in fact efficient because it accomplishes multiple things at once: it defends against a White approach, claims some territory on the side, and also establishes a position on the fourth line that could later support Black stones elsewhere.

### How do attack and defense influence strategy?

Attack and defense is the central consideration informing almost all strategic decisions in the opening and middlegame.

This all makes sense if you have an appreciation for the value of sente in baduk.
Attack and defense are ultimately ways to organize our understanding of *what* is sente and *how* sente can be used for benefit.
It is important to remember that baduk is not won by building a lot of territory.
Baduk is won by building territory *more efficiently* than your opponent.
This entails more than just playing lots of big moves: it means playing moves that serve many purposes at once, and above all it means making good use of sente while denying it to your opponent.
This is precisely the essence of attack and defense.

Ultimately, this means that the opening and middlegame revolve around the identification of weak and strong groups.
Players avoid creating more weak groups than necessary in order to avoid being attacked and giving up advantages to the opponent in sente.
At the same time, players seek to exploit their opponent's weak groups and create new ones if possible.
This also leads to a more nuanced understanding of what moves are big or small.
Strong players rarely play moves based solely on how much territory they claim or how much influence they generate: such moves are in fact often very small.
Instead they look to balance territory-taking and influence-building with threatening their opponent's weaknesses and reinforcing their own.

The next article in this series will elaborate on how these considerations play into the determination of direction of play - one of the most important aspects of baduk strategy.

[Return to the Concepts hub.](/concepts/)

</section>