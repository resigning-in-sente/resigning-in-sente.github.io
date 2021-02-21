---
layout: post
title: 4-4 Low Approach - Slide or Attach?
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

In this post we will analyze two of the most common responses to the 4-4, low approach, low extension jōseki: the slide (A) and the attachment (B).

</section>

<div class="besogo-diagram" realstones="on" maxwidth="550" nowheel="true" nokeys="true" coord="western" sgf="/assets/sgf/2021-02-18-sgf/slide-attach-sgf/01.sgf"></div>

<section markdown="1">

For a long time (A) was the most commonly taught jōseki for beginning players, as its conclusion is particularly simple and the exchange is relatively easy to understand.
The advent of AI has significantly changed the landscape, as AI prefers (B) in the early game.
However, kyu players often do not know the nuances behind this AI preference, and nowadays many of them simply opt for (B) over (A) automatically "because the AI says it's better."
This is far from the truth: all jōseki are situational, and so it is the case with (A) and (B).
Our goal in this post will be to compare and contrast the two jōseki to understand when one prefers to slide and when to attach.

First, let us see the basic lines of each jōseki.
We will not list out an exhaustive account of all of the variations, only the ones necessary to make our point.

### The slide

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-18-sgf/slide-attach-sgf/02.sgf"></div>

<section markdown="1">

After the slide, Black has a choice between (A) and (B). After (A) we arrive at the normal conclusion of the slide variation - very likely the first jōseki that every beginner learns.
It is a straightforward and peaceful sequence, where both sides settle on the side and the corner remains half-claimed.

Later, (A) becomes a fairly significant point of contention for yose. In the middlegame, Black may be able to approach at (B) to exploit to some bad aji for White at (D), while White can similarly approach at (C) to exploit some aji if White pushes at (A). Both sides can also look to press the other low and build influence.

However, for move 2 Black can also choose to pincer at (B), essentially inviting White to enter the corner.
This is locally a loss, but can make sense in the context of preexisting Black support in the lower left corner.
In fact, if Black has good influence from the left, this is the preferred response by AI as well.

Lastly, Black has the option to tenuki for move 2.
This is the preferred response to the slide by AI in the very early game.
If White takes the 3-3, Black can always settle by extending to 1.
This is also how Black settles when Black pincers.

### Attachment: Preliminaries

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-18-sgf/slide-attach-sgf/03.sgf"></div>

<section markdown="1">

Now let us examine the attachment.
After White 5, Black has the choice between connecting at (A) or pushing through at (B).
(Tenuki is also an option, but for the sake of discussion we will not explore this possibility today.)
We will consider each move separately.

### Attachment: Connection

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-18-sgf/slide-attach-sgf/04.sgf"></div>

<section markdown="1">

If Black connects, then White 2 usually also connects back with (A), and here Black is once again faced with a choice: to push at (A) or to descend at (B).
This decision is largely made based on the status of the lower left corner.

If this corner belongs to White, then Black 3 typically pushes at (A), though (B) is possible as well. Due to White's support from the left, Black cannot expect much development on the bottom side.
Hence there is little opportunity cost in pushing White along the bottom side: Black wasn't going to play the bottom side anyway!
This additionally keeps White pressed low in an area where White would prefer to push up and start developing a moyo.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-18-sgf/slide-attach-sgf/04-2.sgf"></div>

<section markdown="1">

If the corner belongs to Black, then Black 3 typically descends to (B), though (A) is still possible.
Then it is White's turn to make a choice between pushing up at (A) and extending to (B).

(A) is the usual choice for White 4 if the lower left corner is White's.
The key point here is the Black peep on the second line.
The idea is that as long as White owns the lower left corner, it can quite feasibly play out the resulting fight in the center.
Otherwise, if the lower left corner is Black's, then White will often choose to settle with (B), as the fight following the peep does not favor White.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-18-sgf/slide-attach-sgf/04-3.sgf"></div>

<section markdown="1">

Lastly, White 2 could also be used to cut, with the intention of taking the corner.
This is considered a slight local loss for White, but there are some specific situations where it may be called for.
Namely, if Black already has support near the triangled point, then White is not yet settled after connecting outside, and therefore takes the corner to avoid being harassed on the outside. Later in the middlegame, White can exploit the aji at 1 to invade the side at 2.

### Attachment: Pushing through

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-18-sgf/slide-attach-sgf/05.sgf"></div>

<section markdown="1">

If Black pushes through, then White takes the corner at the cost of being sealed in.
However, this is gote for Black, and Black is somewhat thin: there is fairly bad aji if White connects at A after Black 7, so Black needs to aim to indirectly defend against this move.
In a vacuum, this result is considered to be somewhere between even and slightly favoring White.

### Similarities

</section>

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-18-sgf/slide-attach-sgf/06.sgf"></div>

<section markdown="1">

On the whole, though the attachment has a greater variety of outcomes, the basic outcomes between attachment and sliding are actually quite similar if both sides pursue the most peaceful option.
We can determine this with some tewari analysis.
In this variation of the attachment jōseki, the triangled stones are part of the slide jōseki.
From this perspective, this variation of the attachment adds to the slide jōseki the 1-2 exchange which favors White (Black would prefer to have the 2-2 point), but the exchange of White 3 & 4 for Black 5 & 6 likely favors Black, since Black gets a thick and high central position while White is pressed low.


### Differences

So what are the major differences between the slide and the attachment?
This is best understood in terms of the variations in which White takes the corner.

<div class="besogo-viewer" realstones="on" maxwidth="550" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-18-sgf/slide-attach-sgf/07.sgf"></div>

Suppose that Black has extra support on the bottom side. In this case White may prefer to slide rather than attach. If White attaches in this situation, then there is a strong possibility that White ends up taking the corner: either because White does not want to risk fighting outside with Black support so nearby, or because Black forces White's hand. The key point is that in this case, the original approaching stone (marked by a triangle) inevitably ends up being cut off from the main White group. This is the main advantage that sliding has over the attachment: there are no variations of the slide variation in which the approaching stone is cut off from the main group.

### Conclusion

So why does AI prefer the attachment over the slide in the early game?

The main advantage to the slide over the attachment is that the slide keeps all of White's stones connected in case of strong Black support from the flank. But in the very early game, it is unlikely that Black has this support in place. Moreover, the slide simply does not demand an immediate response out of Black, something AI is quite sensitive to. Attaching is a way to play the corner with slightly more agency, preventing Black from taking the initiative and dictating the direction of play first.

However, these are all fairly minor advantages, and for kyu-level players there is usually no significant difference whether one plays the slide or the attachment variation. Getting significant benefit out of playing elsewhere in response to the slide is a fairly advanced skill, and there is not much to be lost by responding classically and defending the corner. The main moral of this comparison is to reaffirm the basic principle that the surroundings are what determine the correct jōseki to use.
Here, an extra stone along the bottom side is enough to tip the scales in favor of the slide, despite the attachment being favored in almost every other opening context.

[Return to the 4-4 Jōseki page.](/44/)

</section>