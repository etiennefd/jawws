---
layout: post
title:  "Paper Review: Writing Accessible Theory in Ecology and Evolution: Insights from Cognitive Load Theory"
date:   2022-01-15 15:05:00 -0500
categories: blog
---

Serendipity struck this week as a fellow alumnus from my master's degree in evolutionary biology, [Gil Henriques](https://twitter.com/_Gil_Henriques), co-authored a very relevant paper to my work on JAWWS: [Writing Accessible Theory in Ecology and Evolution: Insights from Cognitive Load Theory](https://academic.oup.com/bioscience/advance-article-abstract/doi/10.1093/biosci/biab133/6482999?redirectedFrom=fulltext) by Ou, Henriques et al. (unfortunately, it is behind a paywall). 

In ecology in evolution, as elsewhere, theory is heavy with math. But empiricists — the people who go into the field or the lab to collect data and perform experiments — tend to shy away from math. As a result, theoretical work is often ignored or incorrectly cited by the researchers who collect new data. One possible solution would be to improve the mathematical training of empirically-focussed biologists, but a big part of the responsibility rests on the people who try to communicate theory, i.e. the theoreticians themselves. How can they make their math more accessible?

The paper focusses on the problem in ecology and evolutionay biology, but the recommendations easily generalize to any science in which there's a dichotomy between theory and empiricism. Indeed, they generalize fairly well to almost any communication problems between scientists, which is exactly the point of JAWWS.

## Cognitive load theory

Ou, Henriques et al. use the framing of cognitive load theory. Cognitive load is how much of short-term memory is being used when accomplishing a task such as reading and understanding a paper. This is very similar to something I've called "[reading friction](http://127.0.0.1:4000/blog/2021/10/04/scientific-style-guide.html)" in my essays: the principle of "making things easier for the reader." Cognitive load theory formalizes this principle, which I'm thankful for.

The authors explain that there are three types of cognitive load: 

- **intrinsic load** refers to the inherent complexity of a situation
- **extraneous load** refers to complexity in the way the situation is presented
- **germane load** refers to how much the situation is familiar to the reader. (More germane load = easier to link to known stuff, which is good. I find it confusing that one type of load is good and the other two are bad, but whatever.)

You can't really do anything about intrinsic load: a problem is what it is, and unless you discuss an entirely different problem, there's going to be some complexity to deal with. To make a paper more accessible, then, you can either increase germane load — i.e. make it easier for readers to link the theory with what they already know — or decrease extraneous load — i.e. make the presentation easier to understand.

## Recommendations to increase germane load

Ou, Henriques et al. recommend five strategies to help readers link complicated models with what they already know.

1. Use metaphors and analogies
2. Provide narrative context
3. State assumptions and explain their purpose
4. Define terms and their biological meaning
5. Provide links to empirical research

Some of these seem obvious but are worth insisting on — since things that seem obvious to a writer may not be obvious to a reader! For example, **defining mathematical terms** (#4) isn't groundbreaking advice, but it's not uncommon for people to incorrectly assume that their readers know the terms. It could be due to not realizing that readers have a different background and therefore may interpret the terms in a way that you hadn't thought of. 

Recommendations #1 and #2 are rather basic techniques for making an argument, and yet **metaphors, analogies, and narratives** are indeed used too rarely in scientific writing. A narrative means explaining your line of reasoning: what questions were you asking, why did you use some particular math technique, what did it tell you? For some reason, it's often tempting to just give the final result of your thought process, but spelling it out is very often much clearer to readers. As for metaphors and analogies, everyone knows they are extremely useful, but, like [concrete examples](https://jawws.org/blog/2021/10/12/examples.html), they can seem disposable when you're limited by the word count.

Recommendation #3, about **assumptions**, is also hugely important and not discussed enough in my experience. When you're assuming something to simplify the world into a model, you have to say how and why! Otherwise it seems you're not perfectly aware of what you're doing, and your readers will be lost.

Recommendation #5 is interesting: in the context of biological theory, it says theoreticians should **give suggestions of empirical experiments** that could validate the theory. When you present a model, you immediately ask, "How could we test this?" This can kickstart the readers' thought process about the next steps.

## Recommendations to decrease extraneous load

The authors suggest four ways to remove the obstacles in the presentation of a theory paper:

1. Adjust the level of mathematical detail and use signposting
2. Use consistent and intuitive notation
3. Provide scripts and programs
4. Visualize models and results

**Adjusting the level of math** (#1) is very much about *knowing your audience*. If you're writing for theoreticians, then a lot of equations can be fine; if you expect the paper to be read by empiricists, students, or a wider audience, then you should limit them. The same is true of jargon.

Recommendation #2 on **consistent notation** is fairly obvious but again, it's worth mentioning the obvious. Pick mathematical symbols that are easy to remember. Generalizing beyond math, you should also pick words and abbreviations that are easy to understand and consistent with established usage.

I like #3 (**sharing code and programs**) because it does not, like scientific publishing so often does, pretend that computers don't exist. A lot of research these days use code, and it is a missed opportunity whenever that code isn't accessible. Ou et al. also emphasize that comments in code are important, and suggest that some papers can benefit from a companion app ([here's an example app they give](https://mmosmond.shinyapps.io/criticalsplines/)).

Finally, recommendation #4 is about **figures**. I think everyone agrees that providing visual support is generally a great idea, but their (visual!) illustration of this is so good that I'm reproducing their figure 2 here, with permission: 

<img src="/assets/images/seed dispersion.png">

Sections a, b, and c all illustrate the same model of seed dispersion on three islands. The first is three confusing equations. With some math knowledge you can gain an understanding of what they mean, but this takes time and effort. Section b is a highly abstract illustration of the same thing, where we can more intuitively grasp how seeds are dispersing between islands (or staying on the same island). But section c is where it suddenly becomes incredibly clear. Thanks to color, cartoons, and arrows, it takes seconds to understand what's going on. 

## Conclusions

This paper formalizes some of the stuff I've been discussing with using my own bespoke vocabulary, like "reading friction" instead of "cognitive load." I suppose I was reinventing the wheel, not that there's shame in that. In fact, I'm happy to have found a more scholarly discussion of my ideas: it shows that some scientists also recognize that there are problems in intra-science communication, and care about improving the situation. 

The paper is specific to theoretical biology, but it generalizes well, and its specificity actually makes it pleasantly concrete. I imagine I will be referencing this paper a lot from now on.

To critique the writing a little bit: it's not a difficult paper to understand, but at times it feels a bit needlessly heavy, with long paragraphs and captions on the figures. Perhaps that's a necessary thing to be taken seriously — as a science paper rather than a blog post — but it defeats the purpose a little bit. Also, ironically, the paper fails at least once at upholding its own recommendations. In figure 2 (the seed dispersion one above), the letter *b* is used both as a parameter in the example model *and* as an identifier for the top-right subfigure. This goes against the idea that notation should be consistent! 

But perfect is the enemy of good. Any improvement to intra-science communication is helpful, and this paper does a good job of recommending sensible techniques, especially when math is involved, as well as justifying them with cognitive load arguments.

## Reference

William J-A Ou, Gil J B Henriques, Athmanathan Senthilnathan, Po-Ju Ke, Tess N Grainger, Rachel M Germain, Writing Accessible Theory in Ecology and Evolution: Insights from Cognitive Load Theory, _BioScience_, 2022; [https://doi.org/10.1093/biosci/biab133](https://doi.org/10.1093/biosci/biab133)