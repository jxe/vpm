---
title: Values, Preferences, Meaningful Choice
author: |
  | Joe Edelman[^joe]
date: 3 August 2021 --- \textsc{draft}
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

 All the same, it's hard to see how to move away from it, without paternalism: if people know best for their own lives---shouldn't we trust their choices as the final proof of their intentions? How else can we avoid imposing "better values" from above?

One way to respond is to say that people *do* know best, and have wise values, but that their revealed preferences aren't the last word on those values. But to establish this, you'd want another source of information on people's values---one that retains much of the resolution, robustness, universal applicability, and democratic simplicity of preference.

I'll develop such an information source here, by taking two 'steps back' from revealed preference, widening the information collected. Then I'll argue that my new source corresponds with one definition of "values" used in common speech. Finally, I'll show how this new source can be used in social choice and welfare calculations.

# Preferences

A rich literature covers how revealed preferences---which, when summed up, are called *engagement metrics*---lead us astray. You can often get people to choose something without serving their real interests: you can misinform them, or leverage their misplaced hopes.

Or, you can make it so people *need* your thing for what once was possible without it: they need your car to get to work, your socal media account to find a job, your dress to socialize with their friends, etc.

More broadly, you can manufacture social circumstances where people choose your thing to "keep up with the Joneses", to signal allegiance with their tribe, or because they've lost the ability to coordinate a real solution.[See discussions of the prisoner's dilemma in e.g., @Sen1973; @Anderson2001]

In some cases, the person will know their choice doesn't express their true interests---that they are bucking to external pressure, caught in the system, or setting aside their goals to conform to a social rule.[See @Sen1977; @Anderson1993 on 'commitment'] In other cases, options have been limited or biased behind our backs.

Given these problems, why does revealed preference still play a role in notions of benefit and measures of optimality? It has huge advantages as an information source: in the resolution and robustness of the data provided, its near-universal applicability, and the democratic simplicity of its collection:

* Preferences say fine-grained things how about each of us wants to live, informed by our local situations and priorities.
* Preferences get at what we choose in the final analysis, our *real*, battle-tested priorities, not just what we *say* we want.
* Preferences work in many domains of life, and represent all-things-considered judgements, combining morality, prudence, whims, etc.
* Finally, those who aren't introspective or eloquent can still express a preference. And preferences leave simple-to-understand, verifiable trails: purchase histories, voting records, etc.

# Attentional Policies

I'll try to address the problems with preference, holding on to these benefits. To do so, I want to take two 'steps back'. The first step is to widen the conception of choice to include option set formation.

A revealed preference takes the options as given. As other authors have pointed out[@Smaldino2012], this doesn't fully reflect how choice works.

Consider my choice, with colleagues, to say something witty. At $t_1$, I choose to say *that* in particular (over staying silent, or saying my second-place quip). But, at some earlier point $t_0$, I decided to invest my attention in finding witty things to say. I've tried witty phrases on in my mind, and tested situations for witty reframings.

At $t_0$, I made a much bigger choice--I adopted[^adopted] an attentional policy of 'looking for witty quips and reframes'. This is how I assembled the option set for my choice at $t_1$.

I think this earlier choice, at $t_0$, reveals more about me than the latter one. Indeed, these **attentional policies (APs)** might account for much of what's called my "personality": When making friends, am I cautious or bold? When considering a purchase, is my focus on price, quality, or durability? When speaking, do I try to be witty, precise, or down to earth? These may not just be "character traits" I was born with, but policies I adopted, which work together for my way of life.[This characterization of an identity as composed of APs shares something with @Anderson2001; and @Velleman1989]

[^adopted]: I adopt APs (just like I make plans, adopt heuristics, comply with norms, follow through with intentions) because my bounded rationality and social needs make it expedient.[@Bratman1987; @Simon1955; @Taylor2016]

Collecting an agent's APs is part of my proposal to improve the information basis of welfare, social choice, and recommenders. How could that work? You could use an interactive survey to collect the agent's common contexts (socializing, at work, in difficult conversations), and have them pick what they attend to most in each.[^other-methods]

If they claim to have AP $a$ in context $c$, you could verify that with followup questions: First, you could ask them about recent moments in $c$, and what options they've found using $a$. Someone with a policy of vulnerability should be able to cough up various opportunities for vulnerabily, recently considered; some taken, some not.

Additionally, that person will also know when *exactly* vulnerability is called for, and when something else takes the fore. I don't try to be vulnerable when giving directions to a stranger, or with my dad. Generally, someone with $a$ in $c$ knows the shape of $c$ well.

While many may claim vulnerability is what they attend to with friends, only some will answer these questions easily, and in detail.

How would such data compare with the resolution, robustness, universality, and democratic simplicity of revealed preference?

Like preferences, APs are informed by our local situations and priorities, and say fine-grained things about how we want to live. Indeed, they have a higher resolution than I've let on so far: an AP about 'honesty' or 'vulnerability' is always short for a more specific policy, like "attend to what I feel about each thing we discuss, and let my feeling show", or "attend to false impressions a listener may get from my statements, and head them off with a disclaimer". That is: having honesty as a policy requires a substantive interpretation of honesty, and these differ from person to person.

APs are battle-tested. I wish I could craft my words to simultaneously be kind, honest, tactful, humble, and inspiring. I wish I could, at the same moment, be precise in my speech, aware how each word lands, aware of my own feelings; transparent, calm, and centered; passionate; physically graceful, like a dancer. But APs *compete* for my attention. So, my choice to look for witty things to say crowds out many other options.

Like preferences, APs are applicable across all domains in life---the moral, the self-interested, etc, and apply to many kinds of contexts.

But, they score worse on democratic simplicity than revealed preference. And, for now, it's unclear how an agent's APs would provide a substitute for revealed preference. I'll get to that.

[^other-methods]: Social attestations, also, could be a source of AP information: someone who is widely admired for their wit likely has an AP about it. Behavioral data may also work: if someone shops by price or by quality, that may show up in purchase or click data.[Using, perhaps, approaches like @Chang2001; or @Levi1990.]

# Broad Evaluation

My second 'step back' considers the process of evaluation by which an agent makes a choice. Look at these three cases:

(@) I watch the road while driving. I don't want to crash.

(@) I'm careful with my speech at work. My boss fires anyone who speaks imprecisely.

(@) I've decided to be more honest with friends. I recently opened up to a friend about a struggle I'm having. Since then, the relationship feels more intimate, and stronger; it's easier for me to think about what to say; my friend is unexpectedly helpful.

The process of evaluation that lead the agent to adopt the first two APs is different than the third. Some APs are adopted mainly to achieve, maintain, ensure, or avoid a known outcome. The first two examples are of this type.


I think, in these cases, there's not just a difference in degree (in the number of reasons), but that a different kind of evaluation is used: In the case of clear outcomes, we evaluate based on an expectation of known benefits and costs, much as a rational choice theorist might hope. But the other case features a more Rawlsian[@Rawls1971; also @Velleman1989; and @Boyd1988] kind of evaluation, where we look for an overall fit for the new activity within the constellation of practices and aims that make up our life. We guess how the new thing might fit, even with practices we haven't fully catalogued. We reconnoiter the space of potential benefits, looking for an overall trend, rather than a clear outcome. In doing so, we ask ourselves a question like "does this activity belong in my best life?" and evaluate based on how it fits with whatever we've already answered yes to.

- Does she gives a small number of reasons, pointing towards one state of the world, $s$, that she's working to achieve, maintain, or ensure (such as 'staying alive', or 'keeping her job')?
- Do those reasons seem to capture her rationale fully? To test this, ask her how she'd feel if they were they taken out of consideration (e.g., if she discovered she'd crash anyways, or that her speech had no bearing on whether she'd be fired): Would she select a different AP for $c$ and consider herself better off, free to focus on something else? Or similarly, would she consider it a net gain if she could clone herself, and have the clone handle doing $a$ in $c$? Or otherwise automate the achievement of $s$?
- While doing $a$, does she split her attention, so that she can reconsider, if needed, the efficacy of $a$ in achieving $s$?

Positive answers indicate a narrow-evaluation. On the other hand:

- Does she have diffuse reasons for adopting $a$ in $c$? Does she sense she's only *just begun* discovering the benefits of $a$, and more will come?
- Imagine her current reasons were taken out of consideration (e.g., if she were assured that, without opening up to friends, she could magically get the same benefits---an easier time speaking, more helpful friends?). Would she still want to do $a$ in $c$? Relatedly, if she could clone herself, would she reserve for herself the task of doing $a$ rather than give it to the clone (or otherwise automate it)?
- While doing $a$, is her attention unified, with no worry about whether she's achieving/maintaining/ensuring $s$?

Positive answer mean we can say that $a$ is, for this agent, a BAP.[^intrinsic]

I'll refer to this as broad-evaluation. When an AP is adopted from a broad-evaluation, I'll call it a "BAP"---a *broadly-evaluated attentional policy*. An agent's APs can be filtered, and the BAPs highlighted: If an agent uses AP $a$ in context $c$, you can ask her why $a$ is wise in $c$:

[^intrinsic]: This eliminates much of what philosophers call instrumental reasons--what's done merely to keep our jobs, to fit in with a friend group, to achieve specific goals, or to get good sensations. Whatever's due to logistical, instrumental, or hypothetical concerns (including concerns from outside pressure and limited options).

[^values]: I'm using "values" here as it's used in everyday speech. In philosophical writing, values are often considered as evaluative criteria or attitudes (@Chang2004, @Velleman1989). My treatment of them as policies works there too, I think: an evaluative attitude or criterion can be viewed as something a person does when making an evaluation or choice.

# Values as BAPs

I want to suggest that an agent's BAPs deserve to be called their values[^values]. I'll illustrate this with a personal story:

> Earlier in my career, I chose work colleagues for their brilliance, efficacy, and a shared sense of play. One day, with one colleague in particular, I recognized a different thing we shared: we were excited to participate in the same long-term trends. This felt meaningful.

> Later, when choosing teammates, I began looking for this alignment first. My teams now seem more likely to stick together. But that's just one benefit of many. Even if I knew my teams *wouldn't* last longer, I'd still hire with this in mind.[^eventually]

In this story, I gained a BAP. Did I gain a value? There are two senses in which the word "values" is commonly used, by which I did gain a value. But before I go into those, I'll bracket one common sense of "values" which *doesn't* fit BAPs: visions of what's right for everyone, or for a group: what a family should be like, how a father should behave, what a nation should be like, etc.

In my story, I don't gain *that* kind of value. It's inspiring for me, and if I was in a mentoring situation I might suggest it, but I don't come to think everyone should hire this way. It's not a political cause (like inclusiveness, freedom, etc), nor is it some standard to which I'll push others to conform, or try to conform myself (like masculine or feminine dress-codes). BAPs have little to do with this use of the word "values".[^visions]

But, two common uses of the word values are just as prevalent, and fit snugly:

First, we use values to mean things that feel right and meaningful when you do them---such as being vulnerable, taking stage, being creative, etc. My BAP qualifies here.

Second, we use values to mean those individual sources of meaning that keep institutions working---e.g., in expressions like "the values of science" or "democratic values". ^[Sometimes this is meant to point to visions of what's right, which I bracketed aside above: a free country, an inclusive process.] In this sense, a scientist's values might include intellectual humility, passionate pursuit of the truth, etc. These aren't just meaningful for scientists, they keep the institution of science on the rails.[^collective]

BAPs are adopted by individuals, but they seem to capture well this kind of wisdom[^wisdom]---knowledge about the smooth operation of social life.

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

* Voice Note

# Conclusion

Suppose a survey were developed to determine people's BAPs and their role in choice, and that these surveys could be simplified, to the point where the introspection or articulacy required wouldn't limit their applicability^[E.g., with rich interactivity, or by infering BAPs from other data.].

Suppose, also, that the data so-obtained can be verifiable, auditable, reliable, and legitimate.^[Granted, a tall order.]

Then, welfare calculations and social choice mechanisms could be modified: by substituting meaningful choice for the standard preference relation.[Maintaining the normal structure of welfare economics, see @Bernheim2009.]

These new mechanisms might cease to reward to those who rig people's choices (through misinformation, market manipulation, etc). They could address other areas where preferences are misaligned with values, like clickbait, internet addiction, populist politics, and obesity.

They might also better support those values that keep science, democracies, etc on the rails---values which are often lost in revealed preference due to coordination problems.

And this might be an information basis for mechanisms and calculations which go much further than meaningful choice: We could develop a measure that increases the number of meaningful choices, relative to the total: to give more people more such choices.

# References
