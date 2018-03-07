---
layout: post
published: false
category: commentary
title: Sam- Assignment 4 Text Analysis and Alien Reading Commentary
---
## Folger API Text Analysis

Continuing from what I talked about last week, I decided to analyze the text of sounds that were used in Shakespeare's plays. Because the amount of text in sounds section of each play was relatively small and highly variable, I scraped the sounds text from all the plays and clump it into one text file to be analyzed by Voyant and JSTOR-Lab text analyzer.

Ignoring the "sd" that is most frequent because how Folger API formatted their sounds section, the most frequent words were flourish, military, alarum, drum, music, trumpet and sounds respectively. As expected, flourishes were most frequent, followed by military. There were relatively small amount of music compared to flourish, mentioned 120 times compared to 462 times of flourish. Interesting connection that Voyant made was that flourish is more related to trumpet than drums, and military is more related to drums than trumpet, by the number of times each pair of the two terms appeared together. Overall, Voyant tools gave a nice overview on the text as a whole, using graphics that are easy to understand.

Using JSTOR-lab's text analyzer, prioritized terms were music students, drums, trumpets, followed by thunder and military music. Although drums, trumpets and military music were expected, I was surprised to see that the text analyzer extrapolated to include music students as a prioritized term. Furthermore, it seemed that the text analyzer focused on names as important terms, evidenced by the fact names of characters and places were listed as terms below, albeit not prioritized.

Although Voyant tools are quite useful (Not going to analyze what's missing from the text analyzer because there are many things missing from it), something that was missing was to edit the read text. For example, it would have been nice to have an option to somehow remove all the "sd"s from the text that were there due to formatting. Although it would not be hard to do so myself, it would have been nice for Voyant to provide tools to dynamically edit the text.

[Voyant Results](http://voyant-tools.org/?corpus=3249498afaa263d0cdbc238488dca439). 

###Alien Reading Commentary

Like Drucker's points made on speculative coputing, Binder also emphasizes heavily on the nature of who created the machine readers and for what purpose. According to Binder, a lot of the machine reading software has been built for military and scholarly uses, therefore are tailored to return topics related to these subjects. This idea is definitely visible in JSTOR's text analyzer, which returned the term 'music students' as a prioritized when given a text of sounds is Shakespeare. Although I do see the connection between the two, I would not have said that 'music students' carried that much weight in the connection, showing that JSTOR's analyzer had some biases that prioritized certain terms over others, since JSTOR is a database of mainly scholarly articles.

Another topic that Binder focuses on is the topic modeling like LSI that machine readers used to pick out topics prevalent within the text. These models, although they are able to make connections between terms and highlight several topics, breaks down any meaningful structure within the text, making something that Binder calls "bag of words." Another model that is used is LDA, which uses mathematical models to pick out what the text is about. This model presumes that there is a "gold standard" that describes the text as a whole. What I find interesting about both of these models is that I can draw a rather extensive connections between these models and scientific ideas. In the LSI model, the text is broken down into a "bag of words" to analyze the text as a whole, or certain types of words. In similar fashion, in biological analysis of certain biomolecules in organisms, cells are broken open, centrifuged and filtered to arrive at molecules of interest. Then these molecules can be analyzed to see what kind of characteristics they have, how much of them are present, how they interact with other molecules, like how single words serve similar functions in a text as a whole. LDA serves as a mathematical model to extract topics that a text is about, and scientific papers often are heavily structured, allowing easier analysis by LDA, while have a few topics that the text is focused on. There are heavy relations between these models and scientific models which could be interesting to analyze in a great extent.

