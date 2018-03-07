---
layout: post
published: false
category: commentary
title: Schembri - Week 4 Text Analysis Activity
---
## Schembri - Continuing to develop a Bechdel Test for Shakespeare's plays

In last week's activity with the Folger API, I worked with Ashley on developing a sort of Bechdel Test for Shakespeare. In order to pass the Bechdel Test, a work must have at least two female characters, they must speak to each other, and the conversation must be about something other than a man. Last week, I pulled all of the female dialogue from Shakespeare's play with the API and analyzed it in order to figure out what percentage of the play's total dialogue was spoken by women. 

This week, I focused my attention on analyzing what female characters say in female-to-female dialogue, by plugging the text from a few scenes into the Voyant text analyzer and Jstor's Topicgraph prototype. I first picked three scenes in which females have substantial conversations with each other, which I defined as more than 20 lines of continuous back and forth dialogue without interruption from male characters. The three scenes I chose are:

1. As You Like It; Act 3, Scene 2 - Conversation between Cecilia and Rosalind
2. All's Well That Ends Well; Act 1, Scene 3 - Conversation between Countess and Helena
3. Othello; Act 4, Scene 3 - Conversation between Emilia and Desdemona 

Results:

1. [Voyant Results](http://voyant-tools.org/?corpus=b1509e1d4bd3ee86edf57d0babec8f34)

From the "trends" graph, it's pretty obvious that this conversation is about a man, as its trend line is stable throughout the whole passage, while other frequently occurring words spiking up for a brief period of time as they are used repeatedly in a phrase or expression - i.e. wonderful, prithee. In the "links" tab, it's also clear that the word man is central in the clauses in which it is used, whereas "wonderful" and "prithee" are less so, and could be left out without much altering the meaning of the line.

[TopicGraph](https://labs.jstor.org/topicgraph/monograph/2cb2170fac900dd654377d95a3778b6a)
    
The TopicGraph provides a more thematic analysis - clustering some terms into broader categories (sometimes erroneously) as well as offering some structural comments (I guess "linguistic
agreement" and "interrogative sentences" are topics?). While the analyzer does pick up on ideas related to the passage's content - reciting verses, poetry, the organs of speaking and listening, Heaven, modesty - it misinterprets a few words, particularly "thou," which it uses as evidence for topics of "The Ten Commandments," "Quintessence," and Jewish ethics." Perhaps the AI has seen a pattern of usage for this pronoun in certain kinds of texts, and is incorrectly assuming this passage contains the themes discussed in those texts. 

2. [Voyant Results](http://voyant-tools.org/?corpus=ebe19a0c4cc7bb7d4171d8271167a734)

While this conversation is about Helena declaring her love for the Countess' son - it does include some mediation on familial love/romantic love, and the nature of motherhood, as the Countess has served as Helena's surrogate mother for all of her life. Even in the discussion of motherhood, however, you can see the conversation biasing towards the mother-son relationship, as opposed to the mother-daughter relationship, since "son" is said far more frequently than "daughter." But "mother" is the central linking word is many of the most frequently said sentence in this passage, so it stands that at least a female is near the center of this dialogue, albeit only because she links the two people who will ultimately become romantically involved.

[TopicGraph](https://labs.jstor.org/topicgraph/monograph/e5aa0d7f4234df91f896bc556c72fdfe)

Again, the TopicGraph provides a broader thematic analysis of the text, and does come up accurately with some of the themes in the text, even those that aren't mentioned explicitly, but more implied, which is pretty neat. "Passion," "Truth," and "Affection" are all topics into which lines of dialogue could be accurately classified. Again, the AI seems to hone in on some topics erroneously, especially related mining, since it picks up on the word "mine" which is used this case as a posessive - i.e."mine heart" - and not as a noun. The program also brings out some themes are not apparent in the voyant analysis - like Helena's apprenticeship in medicine under her father, which she plans to use to get closer to the Countess' son. 

3. [Voyant Results](http://voyant-tools.org/?corpus=f240d6108989c8a890f484e0461f5490)

This scene is still about a man - Desdemona's husband Othello - but operates on a couple levels of symbolic abstraction. For this analysis, male-associated words don't even make it into the top 5. "Willow" comes up 15 times in this section, which might seem strange, but digging a little deeper, you see that the phrase "willow, willow, willow" pops up four seperate times, which accounts for 12 of the instances. Digging into the word links graph, willow doesn't seem that integral to the other most used words. "World," which pops up 8 times, is far more integral to the overall structure of the dialogue. In this passage Desdemona ruminates with her maidservant Emilia on the nature of marital fidelity and true love, all implicitly related to her feelings about her husband Othello, but through an anecdote about her mother's maid who used to sing a song about willows. I guess this also brings up a messier question with the Bechdel Test - if a conversation is explicitly about willows and the nature of marital fidelity, does it still pass the test if it is implicitly about one specific man? Are we counting words or meaning? 

[TopicGraph](https://labs.jstor.org/topicgraph/monograph/7dcd58e583a6b611764fcdbb55cf5c3c)

This TopicGraph gets a little messy, I think partly because it's so short and there isn't too much for the AI to crunch - but it again picks up on some mostly obsolete words and tries to make topics out of them. For example, it sees the words "Heaven," "think," and "false" as apparent evidence of the topic of Swedenborgianism - a particular flavor of Christianity that was inspired by the writings of Emanuel Swedenborg. Some the religious topics are appropriate for this text - Desdemona feels stuck in a kind of limbo or purgatory, between Heaven and Hell, so these topics make sense. Interesting, the AI did nothing with "willow," which was featured so heavily in the Voyant graphs. 

