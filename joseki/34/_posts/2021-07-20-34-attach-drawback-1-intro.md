---
layout: post
title: The Attach-Draw Back Jōseki 1 - Introduction
tags: [34-joseki, 34-high-approach]
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


> This is the first article in the series "The Attach-Draw Back Jōseki."

> [Next article (to be written)](/34/)


</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-20-sgf/01.sgf"></div>

<section markdown="1">

The attach-draw back jōseki (main line shown above) is beloved by amateurs for its simplicity, yet it stands up very well to AI analysis and is a common sight in professional play as well.
It is a fantastic all-purpose opening jōseki that every baduk player should have in their arsenal.
Despite its ubiquity, however, it is common that players do not have a complete understanding of the significance of the position even all the way to SDK level.
In this series we will aim to develop a fairly thorough understanding of the main lines of the attach-draw back jōseki and how one plays with them in the middlegame.
The first article will serve as an introduction to the main lines and the overarching principles governing their middlegame followups.

### Main variations and decision points

First, let us establish some basic knowledge of the main lines of this jōseki.
We will only aim for surface-level knowledge at this point.
Our aim here is just to learn enough to recognize which outcomes are jōseki, because as we progress through this series we will discuss why one might choose one variation over another.
We leave a detailed discussion of individual lines to later articles.
For brevity we will refer to the approaching side as "White" and the defending side as "Black" in this article, and the diagrams will be consistent with this usage; hopefully it is clear that what we say applies when the colors are reversed too.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-20-sgf/02.sgf"></div>

<section markdown="1">

The above is a substantially abridged tree of the attach-draw back jōseki, focusing on the main lines and its minor variations.
Once we enter the jōseki (move 5) there are, roughly speaking, 3 main decision points - two for White (moves 5 and 7) and one for Black (move 6).
The decisions that need to be made at these points are generally fairly similar between the variations: for instance, in all cases at move 7, White is mainly choosing between extending or tenuki, along with some more minor options which are more situational.
We will address what ideas go into the decision-making process in later articles.

### The primary objective

Ultimately, this means that most outcomes in the attach-draw back jōseki basically boil down to the following:

> Black gets a decently-sized, fairly secure corner. White settles on the outside (possibly in sente, if White is willing to tenuki).

The key to playing the attach-draw back jōseki well is to constantly keep this outcome in mind and treat it as the goal, especially as White (and more generally, the approaching side).
We will summarize these objectives in the form of two principles:

> 1. White just needs to settle in some form with decent shape to get an acceptable result.
> 2. White effectively has no territory on the side. It is not worth defending nor is it worth invading during the opening.

The most common failure with this jōseki in kyu-level play is to continue naïvely without consideration for how the follow-ups interact with these objectives.
DDK and high-SDK players in particular are prone to interpreting White's extension as territory and focusing too much of their effort into reducing/invading it or guarding against such reductions/invasions.
Playing the attach-draw back jōseki requires you to make a very important step in your development as a baduk player: the appreciation of the hidden and incalculable value of things like tenuki, influence, and settling, and becoming comfortable with giving up concrete value (secure territory) for these things.
In the rest of this article we will give a high-level explanation of how these concepts apply to the attach-draw back jōseki.
We will revisit many of these ideas in greater detail in subsequent articles in the series dealing with the minutiae of individual variations.

> Aside: These ideas are not unique to the attach-draw back jōseki.
> They have to do mostly with the fact that the extensions in this jōseki are three-space extensions, which inherently are more about settling than about securing territory.
> We would fight much harder for the side territory if we were working with two-space extensions.
> We develop these and related ideas in the article [Choosing the Right Extension](/concepts/2021/02/24/choosing-right-extension/).

### The extension is resilient

As a simple example, let us consider one of the lines of the attach-draw back jōseki in which Black invades the extension.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-20-sgf/03.sgf"></div>

<section markdown="1">

In the secure connection, high extension variation of the attach-draw back jōseki, the above diagram describes the standard invasion.
(The details do change if Black has another stone nearby, but let's keep the discussion simple for now.)
Attaching to the invasion stone on the side is a fighting-oriented option, best used if White has support nearby.
Here, however, Black is the one who has support from the corner, so White's best option is to attach on top, letting Black's invasion connect to the corner in exchange for thickness, decent shape, and in this case sente.

Depending on playstyle, kyu players have a tendency to dislike this result for White, going so far as to spend sente to add an extra stone here as White or invading right away as Black.
In reality, this result is generally better for White, especially in the early game where influence and sente have the greatest value.
The reason for this dissonance is that weaker players are more likely to think of the area under White's extension as rightfully belonging to White, and thus it feels like a great loss when Black can slide under just like that.
The correct way to think about this position is to remember our two principles: let go of the idea of making territory with White's stones, and focus on settling with good shape.
If we adopt this paradigm, then the invasion jōseki starts to make a lot more sense.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-20-sgf/04.sgf"></div>

<section markdown="1">

Let's see this play out in practice with the aid of KataGo.
Here we simulate a game in which Black attempts the same invasion at the earliest possible opportunity.
Now, the invasion itself is not the best move on the board, but at only -0.2 score it is also not a major mistake by any means.
However, if we take the jōseki to its conclusion then White has amassed a significant advantage of +8.9% winrate and +1.4 score.
The big problem occurs at move 5 (all other moves are close to optimal).
KataGo agrees with our assessment that finishing the sequence is far better for White given its extremely clean shape and sente, and its solution is to leave the invasion unfinished as a sente exchange.
Since White is unlikely to spend an extra move locally to prevent Black from connecting back just yet, it is not as if the invasion has failed just yet for Black.
Black can look for an opportune moment to resume the invasion sequence or exploit its aji in some other way, omitting all this funny business of helping White make good shape.
In the meantime Black can spend its sente accomplishing bigger things on this early board, and perhaps even prepare a better boardstate to continue the invasion sequence.
White is not too badly off either if Black plays elsewhere at move 5: the H2-H3 exchange is better for White in a vacuum, because it connects up White's three-space extension and discourages a Black approach from the bottom right, which is much less likely to be sente now.

### So resilient, you can tenuki

The great thing about abandoning any attachment to the side territory in the attach-draw back jōseki is that it opens up a world of options to us, the best of them being tenuki.
If you're not afraid of losing the side territory, that makes it a lot easier to ignore someone threatening to take it!
This is an essential feature of the attach-draw back jōseki for high-level play: it does depend on the surroundings and the specific type of approach, but usually it is resilient enough for White to ignore most approaches once, as long as we stick to the game plan of just aiming to settle with good shape.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-20-sgf/05.sgf"></div>

<section markdown="1">

In the above diagram, White is playing with the secure attachment, high extension variation, and ignores Black's low approach from the right.
Black's main followups consist of invading the middle of the 3-space extension, but there is nothing Black can really do to force White into a weak position.
Notice how White has no interest at all in taking the side territory, nor in denying it to Black.
Not having to waste moves on the side allows White to make good shape and settle with ease.
The point of this diagram isn't about memorizing the sequence of moves: instead, try to focus on what general outcomes White is aiming for.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-07-20-sgf/06.sgf"></div>

<section markdown="1">

Let's see if these variations bear out in practice.
Here White ignores Black's approach in favor of enclosing its corner.
This happens to be essentially optimal, by the way - KataGo likes the tenuki just as much as we do!
That said, Black's approach is also considered essentially optimal; just because White can ignore it does not mean that the move is bad for Black.

Right off the bat, KataGo disapproves of Black's invasion, especially on the third line (which tends to result in a much cleaner shape for White and a low position for Black).
This basically boils down to what we were saying with the previous AI simulation.
Ultimately, all outcomes here lead to White settling with good shape on the outside, while Black at best manages to carve out a small chuck of side territory (which, remember, we weren't thinking of as belonging to White in the first place) and slightly enlarge its corner.
Keeping in mind that White has played elsewhere once, these outcomes are eminently playable for White.
In fact, KataGo considers all of the above outcomes as fairly significant improvements from the starting position.

Also, just to drive the point home regarding the side territory: after Black 1, KataGo considers all moves defending the side territory to be serious mistakes for White.
K2, for instance, consists of a change of -1.0 score for White (which, this early in the game, makes it one of the worst among semi-reasonable moves for White).
It would mean that Black's initial approach at M3 is a sente exchange, in which case Black gets the better end of the deal since White is overconcentrated; and even after all that, there is still a ton of bad aji at H2, so White will probably be forced to spend an extra move locally at some point.
So not only is defending the side territory as White unnecessary: there is a good chance that it is an outright mistake.

### Conclusion

To summarize the above discussion:

1. The main objective for the approaching side in the attach-draw back jōseki is to settle on the outside with decent shape.
Most outcomes of this type are acceptable.

2. The side territory is relatively worthless early on.
Giving it up is acceptable (or even downright optimal), and doing so makes it easier to achieve the main objective.

3. The outside group tends to be fairly resilient, and can possibly withstand one tenuki while achieving the main objective.

4. There is nothing to fear about an early invasion of the 3-space extension.
Such invasions are generally premature and help the approaching side more than the invader.

Keeping these four points in mind is already enough to serve as a decent basis from which you can play the attach-draw back jōseki by ear.
Of course, in this article we have only scratched the surface of this jōseki.
In the remainder of this series we intend to discuss several of the lines in detail, and refine some of the concepts we have developed above.
However, the philosophical framework of all of these subsequent discussions will be based on the principles and objectives for the jōseki we have described here.

[Return to the 3-4 Jōseki page.](/34/)

</section>