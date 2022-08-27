---
layout: post
title: My thoughts on reviews
tags: [review]
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

I am starting a reviews category on this blog, in which I review my games with the help of AI analysis as well as (hopefully) input from stronger players.

Like anybody else, I have my own philosophy on what elements go into an effective review.
I also have my own opinion on how best to incorporate AI analysis into reviewing.
In this post I'm going to explain my overall thoughts on both of these topics, as well as how they will influence reviews that I write for this blog.
Naturally, this post will be more subjective than most on this blog, so I ask that you not take these words as gospel.
My opinions are also liable to shift over time as I improve at the game, and I may return to this post at a later date to adjust my thoughts and recommendations.

### How I review in the age of AI

> I focus on strategic mistakes in the opening and middlegame over tactical mistakes in complex situations.

This is as much a reflection of my personal playstyle as it is a philosophy on what I consider important in reviews.
Although I do not dispute the importance of correcting tactical errors, I believe that for amateurs around my level and below, there is more benefit to studying the mistakes that occur *before* the game devolves into complicated, tactically sharp positions.
This means that I generally focus on issues such as direction of play, jōseki choice, and strength/weakness analysis, and less on what the correct sequence of play was during an important middlegame fight.

My rationale here is that I think these types of strategic concepts in the opening are areas where we can draw the most **actionable** lessons from during review.
Scenarios in the opening often re-occur with relatively minor changes across multiple games.
Correcting for strategic mistakes we make in one opening scenario often leads us to better play across other games going forward.
But a tactical error during sharp fighting isn't always as applicable across many games.
Sometimes, it's hard to draw a lesson from such an error other than "I misread, I should have read more deeply," since outside of shape issues it's rare that a fight develops in the exact same way across two amateur games, and small differences in board position have an outsized impact on local fighting.
And sometimes, the real error in such a scenario comes from earlier, in allowing the situation to develop in the first place.

Moreover, opening mistakes are often relatively straightforward to recognize and to correct compared to tactical errors in complicated fights.
For example, it takes a strong player mere seconds to identify a direction of play mistake in most opening positions.
The remedy to a direction of play mistake is primarily to identify what the correct direction of play is, which also often doesn't take long, as it is based on a fairly simple principle ("play away from strength").
Once this is finished, we've done about 90% of the work, since in many cases we can already get significant improvement by merely playing anything reasonable in the correct direction, even if we don't find the absolutely optimal answer.
A mistake during a complicated battle, on the other hand, often requires exhaustive consideration of deeply read variations.
Not only is this far more effort spent on a single move compared to a direction of play error, it has relatively low returns.
Even if I find the correct variation in the review, in many cases the mistake is highly specific to that game, and in any case I cannot fully address problems in my game arising from shallow reading via review alone.
In actual play I cannot expect to read as deeply as I can during reviews, or with the leisure that unlimited time allows me, or with the advantage of being able to play out the variations in front of me.

Tactical errors are not to be dismissed off-hand, but I generally focus my tactical attentions on issues where general principles can apply; the primary example is good shape vs. bad shape, and recognition of life/death, all *before* the complicated fighting begins.

> *Small* mistakes according to AI are often the most important mistakes.

This is in line with the earlier statement, just with AI analysis now adding additional context.
We often tell players looking to implement AI analysis into their reviews to focus on the big mistakes (commonly we point at -5.0 score as a boundary) and less on the smaller mistakes (like -1.5).
Most AI review interfaces (such as provided in KaTrain, or implemented in places like AI Sensei) do something similar, setting a point cutoff to define a mistake.
There is some amount of sense to this suggestion, as it is relatively rare for amateur games to be decided by narrow margins like -1.5, so why bother focusing on these small mistakes over bigger ones?

However, I think this is shortsighted for all the reasons mentioned above.
Generally, the strategic mistakes of the types mentioned earlier occur in the opening and early middlegame, and generally they constitute relatively small losses.
Even larger direction of play mistakes in the opening are often around the -2.0 range.
However, not only do I consider these the most actionable mistakes, I also think that these numbers are misleading to some degree.

When an AI tells us that a mistake is worth -2.0 points, it means that it is -2.0 points *assuming a superhuman AI takes over for both players from that point on.*
But when a human commits a strategic error, it is rare that the human plays perfectly from that point forward.
What is much more likely is that one strategic error cascades into another error or into a concrete disadvantage that generates further losses.
Part of this is that we do not always recognize a strategic error after we play one.
Another part is that such mistakes are often born of a misconception about the game state, and unless that fundamental problem is corrected we are liable to continue to act on said misconception and commit more mistakes.

Your mileage may vary here, but my personal preference is that I play a relatively error-free opening and early middlegame, even if I am weaker when coming to individual situations in the middlegame.
Ultimately, nothing I can do with AI analysis replaces the need for reading ability in the middlegame.
And I prefer to make those tactical errors in the middlegame rather than come out of the opening with a crippling disadvantage and not have the opportunity to commit those middlegame errors at all.

> AI isn't the solution to everything.

I love AI analysis, but it's important to realize that it cannot be a substitute for all other aspects of improving at baduk.
My opinion is that AI analysis is particularly adept at pointing out misconceptions in opening strategy and shape, and these are consequently the areas where amateurs can derive the greatest benefits from AI.
But it cannot, for example, substantially improve your raw reading ability.
The best AI can do is show you the sequences it has read out.
But nothing improves reading ability more than reading out moves yourself; watching someone else do the reading for you is quite useless.
Similarly, AI can point out life and death issues that arise during the game, but nothing will substitute simply knowing what the basic live groups are or having the raw reading ability to determine group status yourself in-game.
Thus AI is not a replacement for tsumego, or for sequence study, or for memorizing common life/death scenarios.
Consequently, when I review I tend to de-emphasize aspects of the review that are better addressed by these other activities.

> It is not always helpful to focus on playing optimally.

When I break with the AI's recommendation it is often because I distinguish between the optimal move and the move most likely to help me win the game.
AI recommends moves under the assumption that a superhuman player is playing on both sides, and thus either side can realistically expect to generate significant advantages over the other.
However, I am a human playing other human players, and thus I am fully willing to take on even significant losses in score in order to create better opportunities for victory.
Sometimes that means intentionally playing suboptimally when I have the lead, in order to produce a more stable position that I understand more completely.
Sometimes that means intentionally overplaying because I am behind and I must take a risk instead of playing the theoretically optimal sequence toward a guaranteed loss.
I believe it is ok to disagree on such grounds with the AI during a review.
The AI is an assistant; it is not a god dictating the law.

> There are prerequisites to studying effectively with AI.

This is likely going to be a controversial opinion.
I believe there is a minimum level of game knowledge before one can obtain concrete benefits from reviewing with AI assistance.
In particular, I think there is no point to using an AI for reviews until you understand the following concepts:

* [strong and weak groups](/concepts/2021/02/19/strong-weak-groups-1);

* [attack and defense](/concepts/2021/02/20/strong-weak-groups-2-attack-and-defense);

* [direction of play](/concepts/2021/02/22/strong-weak-groups-3-direction-of-play).

If you do not understand these concepts, you do not have the appropriate background to accurately interpret the AI's suggestions, and you are better off continuing to learn via actual play, human teachers, book study, and tsumego for the time being.
And though you might argue that one does not need the ability to interpret to derive *some* benefit from seeing the AI's suggestions, I would disagree strongly on this point.
I think one derives very little lasting benefit from merely viewing sequences.
The only way you can hope to apply this type of training to your games is to memorize all AI responses from a given situation and hope that you are never caught in a position that has deviated from a position you know.

This is not only unrealistic from a sheer human memory capacity point of view, it is inferior to looking to properly understand the AI recommendations from a memorization perspective as well.
Human minds are much better at committing large amounts of information to memory if they can provide a rhyme and reason to how that information is structured.
The player that understands *why* the AI suggests its moves is much more likely to remember *what* the AI suggested several games down the line.
This is like how one derives very little benefit from memorizing jōseki sequences.
It is well-established that encyclopedic knowledge of jōseki is inferior to correct judgment of direction of play and applying it to jōseki choice with a much smaller pool of jōseki.

And although one might hypothetically be able to reason out justifications for an AI's moves without understanding the 3 fundamental concepts given above, the much more likely scenario is that such a player will only be able to provide an incomplete justification at best, at worse a flat-out inaccurate one.
This is also not helpful, and if anything it could be actively harmful.
Misconceptions about the game inevitably lead to errors down the line, even if those misconceptions have their roots from a superhuman AI's suggestions.

Does that mean I am fully prepared to be studying with AI?
Not necessarily, no.
At my level I am still overall better off studying with a human teacher, and I have a lot to gain still from non-AI tools.
However, I like to believe (and hopefully this will be corroborated in the reviews) that I am at least capable of conducting a useful review with AI assistance.

I like to believe that I have a sound understanding of the basic concepts listed above, and that my problems with them largely come down to consistent application, but it is important to be wary of overconfidence.
Thus I do not always entirely grasp the rationale behind an AI's suggestions (and if I did, I'd be at a significantly higher rank).
But I am fairly confident that I can produce a reasonably accurate and partially complete explanation for these suggestions in sufficiently simple board states, and that is a fair place to get started.
I can always turn to other, stronger players in order to complete these explanations.

### How reviews will work on this blog

Reviewing on a blog presents its own set of challenges that I'd normally not have to deal with when reviewing purely for myself.
I'd like to provide a level of detail in reviews that is helpful for players below my level, but this is fairly exhausting work to do for a full game.
I expect most reviews to cover the opening and perhaps the early middlegame, but going beyond that may bring posts to lengths that are frankly unsustainable for me.
Still, the opening and early middlegame are where I prefer to focus my attention anyway, so this isn't necessarily a bad thing.
There's always plenty to say about this stage of the game.
The focus will be on extracting concrete and *actionable* insights and I will try to summarize them at the end of each review post.

As mentioned previously, I am not the strongest player and I am not always going to come up with the most correct or complete interpretation when I employ AI analysis in my reviews.
As such, I welcome comments from stronger players on anything I say, and with their permission I will incorporate their comments into an updated review whenever possible.
This is as much a learning experience for me as it is content for an audience.
I may consider performing reviews for other people as content but naturally I will limit these to players below my rank.

[Return to the Reviews page.](/review/)

</section>