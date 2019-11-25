# Stack Overflow Survival Guide

A collection of strategies and approaches learned the hard way. They range from good to evil, intended to get going and get along on the rugged terrain of the [Stack Overflow](https://stackoverflow.com/) site and its diverse population. 

```java
public enum Approach {
    GOOD, LEGITIMATE, QUESTIONABLE, EVIL
}
```
 - SO ... stack overflow
 - OP ... original post

## When answering

- **GOOD** Remain respectful, also in the face of an hair raising OP. Apart from any moral aspect you're creating a barrier for the questioner to accept your answer, when, while maybe correct and technically helpful, it conveys a judgment about the OP being an idiot. Watch your words, contemt may even ooze out between the lines. 

  Display of respectful communication might also be a trigger that earns you up-votes, I do suspect. In any case it creates a distinctly satisfying experience, IMHO, to treat others as human beings despite technical shortcomings, instead of snapping at them. Unless you've the misfortune of being a clinical psychopath [(F60.2)](https://www.icd10data.com/ICD10CM/Codes/F01-F99/F60-F69/F60-/F60.2). 

- **GOOD** Edit posts. You're entitled to do so from the start, each accepted edit earns you +2. Makes stuff easier to find, to comprehend and nicer to look at. 

  Easy wins are code formatting, weeding out non-gender-neutral addressing of the audience ("Hello, guys"), adding detailed information ("I'm using a scanner" -> "I'm using java.util.Scanner") or setting stuff straight ("I'm using an array" -> its often an ArrayList actually) and re-tagging the post (e.g. 'java' confused with 'javascript')

- **LEGIT** Be fast. Have your IDE up and running and google's search page open. It's horrible to have an answer at your fingertips while IntelliJ keeps on indexing. Create an acceptable answer, publish it asap, improve later. Later answers fare worse.

- **LEGIT** Add additional explanation and links to the post once it is out. Some text and links seems to impress people more than bare bone code. References in general, to scientific papers in particular and stuff like Java language specification impress (and may be helpful too).

- **LEGIT** Choose your time. Sometimes you find yourself in a swarm of lightning fast predators hunting for reputation. You realize it when you see a pristine OP just 15 seconds old, place your answer 2 minutes later, just to find out that you're the 4th to do so. More often its just one - well - co-contributor, who isn't online every day. Depends also on its wake/sleep patterns and time zone. Afer a while you know all of them intimately and become just as fast.

- **LEGIT** Add at least a snippet of code whenever possible. 
```java
String msg = "The grey square and syntax highlighting convey professionality and deep knowledge.";
```

- **LEGIT** Apply a catchy formatting with
***  
  > paragraphs, horizontal rules, quotes and all.  
***

- **LEGIT** Follow up on comments, augment your answer as they unfold.

- **LEGIT** Recycle. Maintain bookmarks of your recent answers if you think they're valuable, but didn't get the attention they deserve. There will be more occasions to put them on stage.

- **LEGIT** Specialize, perhaps in a frequent topic that comes in many flavours and cases and can't be boiled down to *"duplicate of...single answer"*. [BasilBourque](https://stackoverflow.com/search?q=user:642706) made piles of rep with his Java Date/DateTime expertise for example.

- **LEGIT** Be a karma-whore. If you posted an answer and the OP signalled acceptance by commenting on the line of "thank you so much, very helpful" without accepting it, ask him if he/she/whatever could "consider to accept the answer by clicking the green check mark". Many new posters aren't aware of those formalities. 

- **QUESTIONABLE** Scavenge from later answers, if that's compatible with your moral compass. Don't try it with earlier answers, the approach will stink a mile against the wind.

- **EVIL** Use sock puppet accounts and amplify certain answers. Don't overdo it, you'll quickly get weeded out.

- **EVIL** Conspire with others to mutually up-vote answers/questions. Will get you weeded out in no time.

## when commenting

- **GOOD** Imagine you're sitting next to the OP and tell him your comment. Helps me to remain respectful and empathic, especially when the comment has to convey criticism. Sometimes people including myself forget that even SO is a sort of communication platform, not just a place where some entities just throw information at each other. Even if SO might suggest [otherwise](https://stackoverflow.com/tour) at the moment ("There's no chit-chat").

## When asking
- **GOOD** follow the [guidlines](https://stackoverflow.com/tour). Well - nobody reads the guidelines anyway. 

  **They'll snap at you and down-vote your post to death when you do any of these:**

    - in the order of severeness: paste no code at all, post links to images of code, post images of code
    - paste code that doesn't compile, is badly formatted or not formatted at all (you can format it using the `{}` button).
    - just dump your whole project without singling out a [minimal reproducible example](https://stackoverflow.com/help/minimal-reproducible-example)
    - just copy/paste homework assignments without your solution attempts ("That's a do-my-homework question")
    - don't document your own effort you put into it and point out where and why you're stuck ("This is not a free coding/debugging service...") 
    - mention errors but post no exception, call stack and the line the exception is raised (there are no line numbers at SO)
    - don't post sample input that allows to reproduce errors
    - don't describe expected behavior along the things the program does, but isn't supposed to do
    - sound demanding, snooty ... You know, people do it for free. Its more like asking for a favor than to get a service delivered. Well, most may also do it for reputation, but at least they're not getting paid. Only SO makes money, at least it tries to.

- **GOOD** and you got down-voted to death, you obiously should work on your way of asking or your choice of questions. Well, no, **you must, otherwise you'll get banned from asking sonner or later**, aside from getting no answers and causing as well as experiencing plenty of frustration. 

- **LEGIT**   **But** if you and you got down-voted to death and also want to restore your SO reputation to where it was before, then just delete the post. As long as there hasn't been an answer that's supposed to be ok. Afterwards I'm not sure, but a post of that kind isn't likelely to yield any answers anyway. 

  Don't re-post it, though, this will get you're account blocked. And don't repeat the trick as a staple, you'll get blocked anyway (see previous point).
  
  But don't blare this advice out, all over the place. Deleting seems [officially legitimate](https://meta.stackoverflow.com/a/311812/1428369) but the mods online will still consider such an advice illegitimate.
