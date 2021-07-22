---
title: Values, Preferences, Meaningful Choice
author: |
  | Joe Edelman[^joe]
date: 14 July 2021 --- \textsc{draft}
abstract: |
  Many fields (social choice, welfare economics, recommender systems) assume people express what benefits them via their 'revealed preferences'. Revealed preferences have well-documented problems when used this way, but are hard to displace in these fields because, as an information source, they are *simple*, *universal*, *robust*, and *high resolution*. In order to compete, other information sources (about participants' values, capabilities and functionings, etc) would need to match this. I present a conception of values as *broad-benefit attention policies*, which match many of these features of revealed preference, and show how to build an alternative preference relation, *Meaningful Choice*.
classoption:
  - twocolumn
papersize: a4
thanks: Thanks to B. Gabbai, A. Morris, A. Ovadya, J. Stray, & F. Noriega
bibliography: vpm.bib
csl: default
header-includes:
  - \usepackage[font={footnotesize},justification=centering]{caption}
geometry:
  - margin=0.5in
---

[^joe]: School for Social Design joe.edelman@gmail.com

# Introduction

In his 1938 paper introducing revealed preference, @Samuelson1938 warned:

> I should like to state my personal opinion that nothing said here... touches upon at any point the problem of welfare economics, except in the sense of revealing the confusion in the traditional theory of these distinct subjects.

Similar sentiments followed, in @Arrow1951, @Sen1977, @Anderson2001, etc. As an information basis for welfare, optimality, social choice, etc, revealed preference has been much critiqued.

 All the same, it's hard to see how to move away from it without paternalism: people know best for their own lives---shouldn't we trust their choices, and avoid imposing "better values" from above?

One way to respond is to say that people *do* know best, and have wise values, but that their revealed preferences aren't the last word on those values. But to establish this, you'd want another source of information on people's values---one that retains much of the resolution, robustness, simplicity, and universality of preference.

I'll develop such an information source here, by taking two 'steps back' from revealed preference, widening the information collected. Then I'll argue that my new source corresponds with one definition of "values" used in common speech. Finally, I'll show how this new source can be used in social choice and welfare calculations.

# Preferences

A rich literature covers how revealed preferences---which, when summed up, are called *engagement metrics*---lead us astray. You can often get people to choose something without serving their real interests: you can misinform them, or leverage their misplaced hopes.

Or, you can make it so people *need* your thing for what once was possible without it: they need your car to get to work, your socal media account to find a job, your dress to socialize with their friends, etc.

More broadly, you can manufacture social circumstances where people choose your thing to "keep up with the Joneses", to signal allegiance with their tribe, or because they've lost the ability to coordinate a real solution.[See discussions of the prisoner's dilemma in e.g., @Sen1973; @Anderson2001]

In some cases, the person will know their choice doesn't express their true interests---that they are bucking to external pressure, caught in the system, or setting aside their goals to conform to a social rule.[See @Sen1977; @Anderson1993 on 'commitment'] In other cases, options have been limited or biased behind our backs.

Given these problems, why does revealed preference still play a role in notions of benefit and measures of optimality? It has huge advantages as an information source: in the resolution and robustness of the data provided, and their near universal applicability, and their democratic simplicity:

* Preferences are informed by our local situations and priorities, and say fine-grained things how about each of us wants to live.
* Preferences get at our *real*, battle-tested priorities: what we choose in the final analysis, not just what we *say* we want. And they often leave verifiable trails: purchase histories, voting records, etc.
* Preferences can represent all-things-considered judgements, combining morality and self-interest, and work in many domains of life.
* Finally, those who aren't introspective or eloquent can still express a preference.

# Attentional Policies

I'll try to address the problems with preference, holding on to these benefits. To do so, I want to take two 'steps back'. The first step is to widen the conception of choice to include option set formation.

A revealed preference takes the options as given. As other authors have pointed out[@Smaldino2012], this doesn't fully reflect how choice works.

Consider my choice, with colleagues, to say something witty. At $t_1$, I choose to say *that* in particular (over staying silent, or saying my second-place quip). But, at some earlier point $t_0$, I decided to invest my attention in finding witty things to say. I've tried witty phrases on in my mind, and tested situations for witty reframings.

At $t_0$, I made a much bigger choice--I adopted[^adopted] an attentional policy of 'looking for witty quips and reframes'. This is how I assembled the option set for my choice at $t_1$.

I think this earlier choice, at $t_0$, reveals more about me than the latter one. Indeed, these **attentional policies (APs)** might account for much of what's called my "personality": When making friends, am I cautious or bold? When considering a purchase, is my focus on price, quality, or durability? When speaking, do I try to be witty, precise, or down to earth? These may not just be "character traits" I was born with, but policies I adopted, which work together for my way of life.[This characterization of an identity as composed of APs shares something with @Anderson2001; and @Velleman1989]

[^adopted]: I adopt APs (just like I make plans, adopt heuristics, comply with norms, follow through with intentions) because my bounded rationality and social needs make it expedient.[@Bratman1987; @Simon1955; @Taylor2016]

To collect APs, instead of preferences, you could (e.g., in an interactive survey) for the users' common contexts (socializing, at work, in difficult conversations), and have them pick what they attend to most in each.[^other-methods]

If they claim to have AP $a$ in context $c$, you could verify that with followup questions: First, you could ask them about recent moments in $c$, and what options they've found using $a$. Someone with a policy of vulnerability should be able to cough up various opportunities for vulnerabily, recently considered; some taken, some not.

Additionally, that person will also know when *exactly* vulnerability is called for, and when something else takes the fore. I don't try to be vulnerable when giving directions to a stranger, or with my dad. Generally, someone with $a$ in $c$ knows the shape of $c$ well.

While many may claim vulnerability is what they attend to with friends, only some will answer these questions easily, and in detail.

How do such data compare with the resolution, robustness, universality, and democratic simplicity of revealed preference?

* Like preferences, APs are informed by our local situations and priorities, and say fine-grained things about how we want to live. Indeed, they have a higher resolution than I've let on so far: an AP about 'honesty' or 'vulnerability' is always short for a more specific policy, like "attend to what I feel about each thing we discuss, and let my feeling show", or "attend to false impressions a listener may get from my statements, and head them off with a disclaimer". That is: having honesty as a policy requires a substantive interpretation of honesty, and these differ from person to person.
* APs are battle-tested. I wish I could craft my words to simultaneously be kind, honest, tactful, humble, and inspiring. I wish I could, at the same moment, be precise in my speech, aware how each word lands, aware of my own feelings; transparent, calm, and centered; passionate; physically graceful, like a dancer. But APs *compete* for my attention. So, my choice to look for witty things to say crowds out many other options.

APs are applicable across all domains in life---the moral, the self-interested, etc, and apply to many kinds of contexts. But, they score worse on democratic simplicity than revealed preference.

[^other-methods]: Social attestations, also, could be a source of AP information: someone who is widely admired for their wit likely has an AP about it. Behavioral data may also work: if someone shops by price or by quality, that may show up in purchase or click data.[Using, perhaps, approaches like @Chang2001; or @Levi1990.]

# Broadly-Supported Choices

My second 'step back' considers why a choice was made. Consider these four choices:

(@) I had to take the job, it was the only way to feed my family.

(@) I watch the road while driving. I don't want to crash.

(@) I'm careful with my speech at work. My boss fires anyone who speaks imprecisely.

(@) I recently opened up to a friend about a struggle of mine. Since then, the relationship feels more intimate, and stronger; it's easier for me to think about what to say; my friend is unexpectedly helpful. I've decided to be more honest with friends from now on.

The first three have something in common---my reasonng for making those choices lands heavily on one concern[^concern] of mine (my desires, respectively, to feed my family, to stay alive, and to keep my job). In each case, if that concern were removed from consideration (such as if there were other ways to feed my family, if I was going to crash anyways, if my speech had no bearing on whether I'd be fired), I'd change my choice.

In example 4, on the other hand, my concerns, individually taken, are not what the choice is about. For instance, although I like it when "my friend is unexpectedly helpful", my choice doesn't depend on that, or any other single concern.

With the first three, I'll say the choice was *narrowly-supported* by one of my concerns. In cases like (4), I'll say it's *broadly-supported*.

This distinction only works if you're clear on what's being decided. If I decide to write a letter to my friend, because I want to open up to him, then opening up is a dominant reason for writing. I wouldn't write the letter if I didn't want to open up. However, the choice to open up *itself* may count as broadly-supported.

Why are some choices narrowly-, others broadly-supported? One explanation is that there are clusters of densely-connected, mutually-supportive policies and practices in a person's life. My honesty with friends is part of such a cluster: it works well with other aspects of my friendships, with my habit of taking a walk each day, with my courageous approach to my work life, and so on.

When a choice is part of one of these densely-connected, mutually-supportive bundles, it will be broadly-supported. There will be less concern about any particular benefit panning out.[This argument descends from @Boyd1988] The chooser may even sense they've only *just started* discovering reasons for their choice. In other words, that the reasons are *bountiful*, *redundant*, and *untracked*.

In contrast, choice about more logistical, contingent, or hypothetical concerns (including concerns from outside pressure and limited options) will tend to be narrowly-supported.

[^concern]: I'm being careful to use the word "concern" here, rather than reason. Following @Velleman1989; @Bond1983, I take reasons to be logical chains that connect our concerns to possible actions. E.g.: { I want to get rid of this toothache \rightarrow{} the dentist will probably know what to do \rightarrow{} I'll call the dentist }. The concern is the thing on the left. The space of concerns is smaller and more managable than the space of reasons.

[^values]: I'm using "values" here as it's used in everyday speech. In philosophical writing, values are often considered as evaluative criteria or attitudes (@Chang2004, @Velleman1989). My treatment of them as policies works there too, I think: an evaluative attitude or criterion can be viewed as something a person does when making an evaluation or choice.

# Values as Broadly-Supported Attention Policies

I want to suggest that some of an agent's APs deserve to be called their values[^values]. Specifically, those APs which were adopted as broadly-supported choice. I'll illustrate this with a personal story:

> Earlier in my career, I chose work colleagues for their brilliance, efficacy, and a shared sense of play. One day, with one colleague in particular, I recognized a different thing we shared: we were excited to participate in the same long-term trends. This felt meaningful.

> Later, when choosing teammates, I began looking for this alignment first. My teams now seem more likely to stick together. But that's just one benefit of many. Even if I knew my teams *wouldn't* last longer, I'd still hire with this in mind.[^eventually]

In this story, I gained a broad-supported AP (a BAP). The story fits two senses in which we use the word "values". But before I go into those, I'll bracket one common sense of "values" which *doesn't* fit BAPs: visions of what's right for everyone, or for a group. What a family should be like, how a father should behave, what a nation should be like, etc.

In my story, I don't gain *that* kind of value. It's inspiring for me, and if I was in a mentoring situation I might suggest it, but I don't come to think everyone should hire this way. It's not a political cause (like inclusiveness, freedom, etc), nor is it some standard to which I hope others will conform, and to which I try to conform myself (like masculine or feminine dress-codes). BAPs have little to do with these uses of the word values.[^visions]

But, there are two other uses of the word values which are just as prevalent, and fit snugly:

First, we use values to mean things that feel right and meaningful when you do them---such as being vulnerable, taking stage, being creative, etc. My BAP qualifies in this sense.

Second, we use values to mean those individual sources of meaning that keep institutions working---e.g., in expressions like "the values of science" or "democratic values". Sometimes this is meant to point to visions of what's right, which I bracketed aside above: a free country, an inclusive process.

But sometimes it's used to mean something more personal: a scientist's values might include intellectual humility, passionate pursuit of the truth, etc. These aren't just meaningful for scientists, they keep the institution of science on the rails.[^collective]

Even though they're BAPs are individual, they seem to capture this kind of knowledge[^wisdom]---knowledge about the smooth operation of social life.

[^eventually]: Eventually, I suppose having teammates like this will cease to be meaningful to me---it will just be how my life is. But when I'm hiring, it will still be an attentional policy I've adopted for broad benefits.

[^wisdom]: In popular speech, knowledge with a dominant reason is *know-how*, whereas knowledge with broad-support is *wisdom*. I.e., wisdom could be defined as "knowing from experience which policies are broadly beneficial." BAP knowledge.

[^collective]: APs may offer an account for the rationality of collective action---compared to the prisoner's dilemma arguments in @Anderson2001 and @Sen1973. In contrast, my approach follows @Velleman2005, ch 11, closely.

![BAPs from our database, [meaning.supplies](http://meaning.supplies).](i/ms.png)

[^visions]: These social visions *do* lead to attentional policies. People often try to be *inclusive* or *feminine* based on such a vision. But if this is done purely with a vision to spread, this is a one-reason affair. Once someone has many reasons to be inclusive or feminine, it ends up in the 'personally meaningful' bucket, in sense 2. (Note: the situation is complex, because spreading a vision of inclusivity may be something you attend to *because of* a BAP. E.g., because you look for opportunities to *respond deeply to the world-situation as you find it*.)

# Meaningful Choice

Finally, I want to suggest that some revealed preferences express more of our values than others. Consider the preference of Janet, who takes a job at Soulcrushingjobs.com. She says:

> It's the only way my kids can eat. If I didn't go work there, I'd feel a crushing guilt. And my kids might get taken away. Also, I believe in taking responsibity for my family, and this is the way to do that.

We can inquire about her choice of Soulcrushingjobs.com: what AP led Janet to it? Various candidates emerge from her testimony: perhaps she was searching for ways to take responsibility? Or, perhaps she was searching for any job that would feed her family. These would be very different search processes.

We can verify "taking responsibility" is a BAP for her, by asking her when that AP is important, and how she decided it's important then. If "taking responsibility" has a clear context and is broadly-supported, it's a BAP.

If this BAP drove her search process, she would have found a wide variety of ways to take responsibility as part of her job search. If, on the other hand, she was more focused on finding any job that'd feed her family, we would expect a narrower collection of options.

In this case, it's likely that the BAP didn't drive this particular choice.

how expressive is Janet's choice to work at Soulcrushingjobs.com of her value of "taking responsibility"?

I believe this choice is less expressive of "taking responsibility" than other ways Janet might take responsibility, had she more options, and less pressure. Why? Because her choice is highly-constrained by the concerns which aren't BAPs.

Imagine you asked Janet to partition her concerns into two subsets, $A$ and $B$, such that, without the concerns in set $A$, she could think of many nicer ways to address the concerns in $B$. She might say: yes, she could think of many nicer ways to take responsibility (set $B$), if she didn't have to address her goal of feeding the family, or her two fears about that (set $A$).

This answer indicates that it's the goals and fears, not the BAP, that are pruning Janet's options.

Contrast Janet's choice with Josh's, to teach at Dartmouth rather than Harvard. Josh also has a goal of making tenure someday, and at Dartmouth this seems a bit more likely. More important in his choice, he wants to enjoy the fresh air of New Hampshire, and build relationships with his students, which he thinks will go better at Dartmouth.

Josh says that, if he didn't have to address his policies of 'enjoying fresh air' or 'building relationships with students' (set $A$), he could think of many better ways to ensure tenure (set $B$).

Formally, we can say that, in situations like Janet's and Josh's, a choice is constrained by the concerns in set $A$. But in Josh's case, there are BAPs in set $A$, whereas in Janet's case, all of her BAPs are in $B$. I claim that cases like Josh's are most expressive of our values, because they are less bound by logistical or other kinds of instrumental[^intrinsic] concerns. I would like to use the term 'meaningful choice' for a revealed preference like Josh's.

[^intrinsic]: Indeed, I believe a focus on broad-benefit eliminates much of what philosophers call instrumental reasons--what's done merely to keep our jobs, to fit in with a friend group, to achieve specific goals, or to get good sensations.

# Conclusion

Suppose that surveys could be run, to determine people's BAPs and constraining concerns, and that these surveys wouldn't require so much introspection or articulacy that they would limit the population of respondants^[Perhaps they are interactive, or infer BAPs from other data. In any case, we must be careful: people often lack access to reasons, are inarticulate about them, and when asked, may misrepresent them.].

Suppose, also, that the data so-obtained can be made robust, verifiable, and auditable.^[The kinds of surveys I've described introduce a fuzzy factor that would likely need to be overcome, especially to make good social choice mechanisms.]

In that case, one proposal for fixing welfare calculations and social choice, is to substitute meaningful choice for the standard preference relation.This has the advantage of maintaining the normal structure of welfare economics. @Bernheim2009.

Returning to where I started, with recommender systems, social choice mechanisms, and welfare calculations: to alter these, one could substitute

Doing so would, we hope, cease the reward to those who rig people's choices through misinformation, market manipulation, etc. It could address other areas where preferences are misaligned with values: clickbait, internet addiction, populism, obesity, etc.

It might also do something to preserve the individual meanings that keep science, democracies, etc on the rails. These values are often lost, due to coordination problems, in revealed preferences. They may be less likely to be lost in BAPs.

Unfortunately, meaningful choice as I've described it doesn't go far enough. It doesn't count Janet's choice of Soulcrushingjobs.com as an endorsement---and that's good. But it should count Janet's lack of meaningful choice as an indictment! We'd like a measure that increases the number of meaningful choices, relative to the total: to give more people more such choices. To do that, we'd need to give welfare more of an overhaul.

# References
