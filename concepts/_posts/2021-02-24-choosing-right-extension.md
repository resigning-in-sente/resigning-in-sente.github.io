---
layout: post
title: Choosing the Right Extension
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

### A proverb that does more harm than good

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-24-sgf/extension-sgf/01.sgf"></div>

When we first start learning baduk, we are commonly taught the following principle governing the length of side extensions:

> Extend two spaces from one stone. Extend three spaces from a two-stone wall. Extend four...

We then learn to judge extensions based on this *N+1* spaces from an *N* stone wall rule, as well as (to some degree) extensions from enclosures.
e.g. "Two spaces from two stones is bad! It should be three spaces, so two spaces is overconcentrated!"
And so on.

However, this proverb is one of the most damaging proverbs in existence.
The truth is that the proper spacing of side extensions is tied to a far more nuanced rule than a formula like *N* goes to *N+1*.
Sometimes you do extend two spaces from two stones, and sometimes you extend *ten* spaces from four!
In this article, we are going to undo the damage the proverb has wrought, and explain the *real* principles behind how one decides on the appropriate distance to extend.
The goal is that by the end of this article, you should be ready to throw the proverb in the trash, and play your extensions with confidence and finesse.

### The real meaning behind the proverb

First let's get an idea of what the real value in the proverb is.

The proverb does exist for a reason, but it's not really about ideal side extensions in the context of a whole-board strategy.
It is a proverb that is more *tactical* in nature rather than *strategic,* meaning its recommendation is more concerned with local considerations than global ones.
This is its true meaning:


> The *N+1* spaces from an *N* stone wall rule is mostly about maintaining the connectedness of your stones. It is a rule of thumb that tells you roughly how many spaces you can extend on the third line while keeping your extension connected to the wall.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="comment+tree+control" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-24-sgf/extension-sgf/02-1.sgf"></div>

<section markdown="1">

Above we see that the two-space extension, in the absence of extra surrounding stones (beyond those already on this board), cannot be cut.
However, that's the *only* thing that the proverb says regarding two-space extensions on the third line.
It says nothing about whether these stones are safe or whether this is an efficient formation.
In fact, in this particular scenario Black is actually under a fair amount of pressure: flanked by White stones one space away from each side, this Black group can only expect maybe *one* eye on the side if White has sente, and possibly not even that considering the aji at B or C.
Too many beginners would leave this Black group alone, thinking it is safe because "the proverb says 2 spaces from 1 stone is ok!"

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="comment+tree+control" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-24-sgf/extension-sgf/02-2.sgf"></div>

<section markdown="1">

The same goes for the three-space extension from a two-stone wall.
Without additional White support nearby, this extension cannot be cut.
But that has nothing to do with whether these stones are weak or strong or claim any territory or *even whether or not it's good for Black to stay connected.*
Some of these connecting sequences shown here might actually be detrimental if we account for the board at large.
Moreover, everything is extremely sensitive to the presence of additional White stones.
A White stone at O3, for instance, will significantly alter the outcome of the White invasion at (A).

With three-stone walls and higher, the value of the proverb becomes even more suspect, because the wider the extension, the more sensitive it is to surrounding stones.
Once we are at four-stone walls, it is difficult to claim that the wall and the extension are actually connected - again, ignoring for the sake of argument whether you would even *want* to connect.

So how do we actually figure out the proper length of an extension?

### Decide on the purpose of the extension

Broadly speaking, there are two types of side extensions in baduk, delineated by purpose.

The first type is an extension whose primary purpose is to help a group settle.
These extensions generally reinforce weak groups and help them establish eyespace on the side; they also claim some side territory as a bonus.

The second type is an extension from thickness.
These are typically extensions from strong groups or walls.
The purpose of such extensions is to make good use of the influence generated by your strong group.

The length of an ideal extension is tied to what kind of group you are extending from.
So, before you do anything else, you need to first take a look at the group you are extending from, and ask:
> Is this a weak group that needs to settle, or a strong group projecting lots of influence?

Only once this question is answered can we start to study the problem in greater detail.

### Extending to settle

Now let's assume that you are working with a weak group, and the purpose of your extension is to help it settle.
In this case, the length of an ideal extension is determined by the following principle:
> When extending to settle, extend as far as you need to secure sufficient eyespace for life, but no further.

Here is the logic behind this principle.
* If you extend further than absolutely necessary to secure eyespace, then your thinness can introduce additional weaknesses into your group. This will give your opponent sente exchanges against your group which are more valuable than the value of extending one or two spaces further.
* If you don't extend far enough to secure eyespace, then your group will be weak by virtue of having limited eyespace. This will again give your opponent sente exchanges against your group. In this case you might as well extend further, since either way your opponent will get sente exchanges but extending further may secure extra eyespace or territory.

Let's see what this means by studying some examples from jōseki.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="comment+tree+control" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-24-sgf/extension-sgf/03-1.sgf"></div>

<section markdown="1">

In this sample game, Black approached high to White's 3-4 point in the top left, and White has just played (1).
To finish the jōseki, Black needs to make an extension to settle its three stones.
Two options seem most reasonable (and are both jōseki): two spaces at (A), or three spaces at (B).
Which is the better option?

If we are following the old rule of *N+1* spaces from *N* stones, it is tempting to treat the three Black stones as a two-stone wall: after all, Black may as well be connected at E17.
This would suggest that (B) is correct, as this would be three spaces from a two-stone wall.

However, if we follow our new principle for determining the length of an extension, then the actual best answer here is (A)!
The key is White's last move at B15: in particular, it is *not* at B18.
Because White does not have B18, this means that extending to (A) is already enough for these Black stones to secure enough eyespace to settle: there is no need to go any further.

Why does this matter?
Wouldn't it be more efficient territory-wise to go one space further to (B)?
Actually, it's the opposite.
Extending three spaces creates a Black weakness at G17.
White can exploit this weakness in order to get favorable sente exchanges against the group.
For instance, after (B), White could approach from the right to get an extension from its stones top right in sente.
Or White could instead press from above at F15, also in sente, which builds White influence toward the center.
Both of these exchanges are better for White than for Black - whatever extra territory is claimed by extending one space further is unlikely to match White's approaches in value.

What happens if Black instead extends conservatively to (A)?
In that case, Black's group is already settled, and does not need to respond to any White approaches.
If White does approach, then Black can simply ignore it and take the next big point on the board, pulling ahead.
So in actuality, playing solidly here *is* playing more efficiently - once we take the weaknesses of our group into account.

KataGo's evaluation confirms our analysis.
Admittedly, it is not a large difference by any means - KataGo prefers (A) by only a tiny margin, as in either case Black's group is secured.
Any White approaches after (A) are ignored.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="comment+tree+control" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-24-sgf/extension-sgf/03-2.sgf"></div>

<section markdown="1">

Let's put our principle to the test by switching up the local situation.
This time White *has* descended to B18.
Once again we ask: should Black extend two spaces to (A), or three spaces to (B)?

Again, the key lies in White's descent to B18.
This stone destroys much of the eyespace that Black previously had when this stone was at B15 instead.
In particular, this means that neither (A) nor (B) secure enough eyespace on the side for unconditional life in a single move.
Therefore the answer here is (B) over (A).

The reasoning is as follows.
Suppose Black opts to extend conservatively to (A), and White approaches from the right at K17.
This White approach is not necessarily sente in the usual sense of the word, but it is a form of delayed sente: Black owes White an extra move here *at some point*.
This is because thanks to White's descent at B18, Black has not yet settled its group, and needs at least one more move to do so.
Which specific move Black chooses in order to settle is not so relevant: the point is that *Black needs to respond in some way to K17 eventually,* effectively turning K17 into a sente exchange.

If Black cannot settle locally in a single move anyway, then Black might as well extend one space further, in order to compensate for the eyespace destroyed by B18.
It is still the case that White can get sente exchanges from above or from the right.
However, these exchanges have the additional effect of helping a weak Black group settle, so Black has nothing to complain about.
When White did not have the descent at B18, these exchanges helped White more mainly because the Black group wasn't that weak to begin with, so Black gained much less out of the exchange compared to when White did have the descent.

Once again, KataGo agrees with this analysis, this time favoring (B) over (A) by a more noticeable margin than in the previous scenario.
KataGo's response to (B) is indeed to approach right away at L17, but this time KataGo sees this as perfectly acceptable for Black rather than a one-sided sente exchange.

### Extending from thickness

In the last section we were working with extensions from weak groups that needed to settle.
Now let us consider the opposite scenario, in which we are extending from a strong group projecting lots of influence.
It turns out that for this scenario, the principle for deciding the optimal extension is *quite* different:

> When extending from thickness, extend further than normal.

Here is the logic behind this reasoning:
* Directly building territory out of thickness is inefficient in terms of territory-per-stone. Making a normal-length extension risks your opponent simply letting you have your territory and playing a big point elsewhere.
* Extending further than normal invites your opponent to enter your moyo by threatening to build more efficiently than usual. This bring your thickness to life, as you can use it to [attack the invader and derive benefits in sente](https://resigning-in-sente.github.io/concepts/2021/02/20/strong-weak-groups-2-attack-and-defense/).

Let's test this principle in a real-game context.

</section>

<div class="besogo-viewer" realstones="on" maxwidth="800" nowheel="true" coord="western" panels="comment" orient="portrait" portratio="none" sgf="/assets/sgf/2021-02-24-sgf/extension-sgf/04-1.sgf"></div>

<section markdown="1">

Here Black has set up a three-stone wall from the lower right corner and has sente.
This wall is a fairly strong group, a topic we discuss in the [early 3-3 invasion series](/44/).
As this is still an early stage of the game, lots of different moves are viable; KataGo likes playing the top side in particular.
However, if Black were to specifically choose to extend from this wall, what would be the best distance to extend?

To answer this question, we have listed all of the reasonable-seeming extensions from this wall consisting of at least four spaces.
For each extension we have listed the resulting change in winrate and score (from Black's perspective).
If the *N+1* spaces from *N* stones principle were correct, then the four-space extensions (A) and (B) should be the best extensions.

But in reality, the four-space extensions are the *worst* extensions among these choices from KataGo's perspective!
Even (C), a five-space extension, is third worst among all extensions.
We can see that KataGo's evaluation tends to improve the further the extension is from the bottom right.
((N) is a noticeable exception, but this has mostly to do with the fact that it is an unorthodox and non-optimal approach to a 3-3 corner.)
The best "extension" is in fact a shoulder hit against White's top right corner, and the next two best extensions are (I) and (K) - a whopping 8 and 9 spaces respectively from Black's three-stone wall!
Now, part of this favorable evaluation does have to do with the fact that the longer extensions double as corner approaches.
But even the extensions that are a fair distance away from the top right are seen as better than the narrow extensions (A), (B), and (C).

How does play continue after these approaches?
* KataGo ignores (A), (B), and (C), choosing instead to turn at G16, which is a very big move. White does not bother invading this extension; instead, White simply treats the area between the wall and the extension as a no-go zone for a large portion of the game.
* The approaches (I) and (K) are met by White protecting its corner, which is fairly standard as 3-3 jōseki go. Then will Black extend back to (D) or (F). Now the right side is actually worth a substantial amount of territory, since Black has claimed a much wider chunk of it.
* (O) is met by a standard 3-3 4-4 approach jōseki. This could go in a few different ways, but KataGo seems to prefer Black taking the top side and White taking the corner and parts of the top right side. Neither side gets to claim much of a moyo on the top or right in this scenario.

The major problems with the narrow extensions (A), (B), and (C) are the following:
* They don't claim enough territory to be efficient on a per-stone basis. Black has already invested four stones after the extension, but it is *still* not secure: there are far more secure combinations of four stones to secure this amount of territory. Black probably needs another three or four stones before it can really claim that all the territory between its wall and its extension belongs to Black - at which point it becomes obvious that Black is not getting much value out of each individual move.
* Because it doesn't claim enough territory, White has no incentive to go anywhere near Black's extension - it does not require much reduction or invasion, especially not right away. This makes the early investment into Black's wall in the lower right for naught, as influence shines brightest when it can be used to attack weak groups, but Black's wall will have nothing to attack if White doesn't enter the extension.
* Because White doesn't need to do anything about Black's extension, this immediately gives up sente.
* These narrow extensions are better than the wider extensions at one thing: they reinforce the Black wall, giving a potential way to secure eyespace or support in the case of a fight breaking out nearby. But as we mentioned earlier, the Black wall is already a fairly strong group by itself, and hence does not really require additional reinforcement. Thus the narrow extensions are somewhat redundant.

These considerations are fairly universal for extensions from strong groups.

### Summary and conclusion

To summarize what we have learned:

* The proverb "extend *N+1* spaces from *N* stones" is mostly about connectedness. In terms of whole-board strategy it actually tends to produce bad recommendations. It is best not to rely on it.
* When looking to extend, first you need to identify the purpose of the extension.
	* When extending from a weak group with the purpose of settling, you should extend as far as you need to best secure life, but no further.
		* Extending further than necessary tends to expose weaknesses in your group, leading to favorable sente exchanges for your opponent that could have been avoided.
	* When extending from a strong group, you should usually make a significantly wider extension than normal.
		* Narrow extensions from a strong group tend to be redundant and inefficient.
		* Wide extensions from a strong group allow you to make good use of your thickness rather than letting it go to waste.

With this, you are now hopefully ready to throw away the *N+1* spaces from *N* stones proverb for good, and start playing extensions according to fundamental strategic principles rather than via a formula.

[Return to the Concepts hub.](/concepts/)

</section>