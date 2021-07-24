---
layout: post
title: Strong and Weak Groups 1 - What are Strong and Weak Groups?
tags: [general-strategy, strong-weak-groups]
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

> This is the first article in the series "Strong and Weak Groups."

> [Next article](/concepts/2021/02/20/strong-weak-groups-2-attack-and-defense/)

In this article we introduce the concept of the strength/weakness of a group.
This is arguably the most important strategic concept in baduk - almost all strategic considerations can be distilled to this one idea at their core.
It is a necessary idea to understand in order to bridge the gap between high SDK and low SDK play.

The learning goal of this article is to be able to identify which groups are strong and weak.
Follow-up articles in this series will explore the implications of strong and weak groups on global strategy.

### Definitions

For such a fundamental concept, it is a little difficult to formulate a precise definition of a strong or weak group.
Thus, rather than a single definition, we will instead describe some characteristic features of strong and weak groups.
The two main ones we identify are:

* Strong groups are close to making life. Weak groups need several moves before they can make life.

* Strong groups are independent and do not need babysitting against enemy threats. Weak groups have several moves that are sente against them and need attention to ensure their survival.

#### Criterion no. 1: Proximity to life

The most clear-cut characterization of a group's strength and weakness is based on its life and death status.
In fact, we can use this as a working definition:

> A strong group is unconditionally alive or close to making unconditional life.
A weak group is several uncontested moves away from making life.

By this characterization, a group can be strong or weak based on a variety of different factors.
Some examples:

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-19-sgf/strong-weak-groups-sgf/01.sgf"></div>

<section markdown="1">

Here we have a typical result from an early invasion of a sanrensei.
After move 11, White has the triangle-marked group in the middle of Black's formation.
White's group is weak because it lacks the space on the side to establish its eyespace.
At best it can likely only get one eye on the bottom side, and possibly only at the cost of reinforcing Black's corner or right side.
Its only realistic option for making life will be to run into the center.

Black's groups on both sides are fairly strong. The lower left corner is yet unfinished because of the remaining aji at points like (A) and (B), but it has the beginnings of sufficient eyespace for making life as well as an emergency exit to the left side and center if necessary. The circled stones on the right are perhaps a bit far apart to refer to as a "group," but they play well in tandem with each other and can support each other in establishing life.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-19-sgf/strong-weak-groups-sgf/02.sgf"></div>


<section markdown="1">

This is a classical outcome when White wedges at K3 in response to a Black 4-4 & shimari opening.
The triangled White stones are very strong, having essentially secured life already.
The squared Black stone is looking a little weak, as the presence of White strength nearby supports a later invasion at A.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-19-sgf/strong-weak-groups-sgf/03.sgf"></div>

<section markdown="1">

Here White has opened with double 3-5 points, and Black has invaded one of them.
Because Black is nearly sealed in, the marked stones are a little weak right now and should extend to A to secure life.
Neglecting to do so (for instance, looking to nullify White's influence with (B)) results in White playing (A) instead, which is sente against Black's corner, looking toward the vital point at S18 and threatens seki or a favorable ko for White.

#### Criterion no. 2: Resilience and independence

Another way to think about strong and weak groups is in terms of how resilient they are to enemy threats.

> A strong group has little need to respond to the placement of additional enemy stones nearby. A weak group has many points which are sente against the group when played by the opponent.

Again, this is a sliding scale.
The more moves that are sente against the group, the weaker the group tends to be overall.
The strongest groups need no additional support and can impose their influence on the board without much regard for their own safety.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-19-sgf/strong-weak-groups-sgf/04.sgf"></div>

<section markdown="1">

Here, both White and Black groups in the top right are fairly strong. White's group has excellent shape for making two eyes, and Black would probably need something along the lines of all three X-marked points to seriously threaten its life.
Since White can probably safely ignore several Black approaches against the group, it is a very strong group.

Black's group also has good shape and a sufficiently wide base along the side to establish life.
One might worry about if a White stone at (A) would be sente, but here Black is still fairly safe as White does not have the descent at S18, which gives Black enough leeway on eyespace to safely ignore (A).

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="control+tree+comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-19-sgf/strong-weak-groups-sgf/05.sgf"></div>

<section markdown="1">

Here we change up the previous diagram just a little bit.
White has opted to descend to 1 instead of the previous jōseki at 2.
Black in turn has extended one space further than before, as the descent threatens its eyespace and Black must secure more of it.

In this scenario, both White and Black are slightly weak, as these slight changes have added moves to the board which are sente against each group.
In Black's case, the three-space extension leaves behind an obvious invasion point at (B).
White can look to exploit this by approaching at (A), which now has a good chance of being sente.
Being sealed in is also likely to be a significant threat to the well-being of this group, and thus White stones from above are also likely to be near-sente as well.

As for White, descending to 1 instead of forming a tiger's mouth at 2 has introduced a significant flaw into White's shape, namely the attachment at (C).
Black can look to capitalize by approaching at (D) in sente.
Because allowing such an approach in sente is quite valuable, White typically does not employ the descent except as part of a strategy in which White exploits the weakness of the Black group on the left to deny Black the timing to exploit the attachment (one of the key concepts in Chinese-style fuseki, for example).

### Conclusion and takeaways

In this article we have established two criteria for identifying whether a group is weak or strong: based on their proximity to unconditional life, and based on whether nearby enemy approaches are likely to be sente against the group.
As nearly-live groups are more resilient to enemy approaches and unsettled groups are less so, these concepts mirror each other.
Therefore in practice, one can get a feel for the strength and weakness of a group by determining its proximity to life, which is something you are probably already doing anyway.

Determining the strength and weakness of groups is something that one must do for the entire duration of a game, as all high-level strategic concepts are based primarily on this consideration.
This is the reason that life-and-death practice is so fundamental to baduk: it is the basis by which one establishes the strength and weakness of groups, thereby forming the basis of all advanced strategy.

Future articles in the series will address how this concept is applied in a strategic context.

[Return to the Concepts hub.](/concepts/)

</section>