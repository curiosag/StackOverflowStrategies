# Stack Overflow Strategies

A collection of strategies and approaches, from good to evil, to get going on and get along with the [Stack Overflow](https://stackoverflow.com/) site. 

```java
public enum Approach {
    GOOD, LEGITIMATE, DOUBTFUL, EVIL
}
```
OP ... original post

## When answering

- **GOOD** remain respectful, also in the face of an hair raising OP. Apart from any moral aspect you're creating a barrier for the questioner to accept your answer, when, while maybe correct and technically helpful, it conveys a judgment about the OP being an idiot. Watch your words, contemt may even sneak in between the lines. Display of respectful communication might also be a trigger that earns you up-votes, I do suspect. In any case it creates a distinctly satisfying experience, IMHO, to treat others as human beings despite possible technical flaws, instead of snapping at them. Unless you've the misfortune of being a clinical psychopath [(F60.2)](https://www.icd10data.com/ICD10CM/Codes/F01-F99/F60-F69/F60-/F60.2). 

- **LEGIT** edit posts. You're entitled to do so from the start, each accepted edit earns you +2. Easy wins are code formatting, weeding out non-gender-neutral addressing of the audience ("Hello, guys"), adding detailed information ("I'm using a scanner" -> "I'm using java.util.Scanner") or setting stuff straight ("I'm using an array" -> its often an ArrayList actually) and re-tagging the post (e.g. 'java' confused with 'javascript')

- **LEGIT** Be fast, be first. Have your IDE up and running and google's search page open. Make a quick solution and put it out. Later posts fare worse.

- **LEGIT** Choose your time. Sometimes you find yourself in a swarm of lightning fast predators hunting for reputation. You realize it when you see a pristine OP just 15 seconds old, place your answer at 2:20, just to find out that in the meantime 3 others have been faster. More often its just one predator, who isn't online every day. Depends also on its wake/sleep patterns and time zone. Afer a while you know all of them intimately.

- **LEGIT** Add additional explanation and links to the post once it is out. Some text and links seems to impress people more than bare bone code. References in general, to scientific papers in particular and stuff like Java language specification impress (and may be helpful too).

- **LEGIT** Add at least a snippet of code whenever possible. 
```java
String msg = "The grey square and syntax highlighting convey professionality and deep knowledge.";
```

- **LEGIT** Apply a catchy formatting with paragraphs, horizontal rules, quotes and all.  

- **LEGIT** follow up on comments, augment your answer as they unfold.

- **LEGIT** recycle. Maintain bookmarks of your recent answers if you think they're valuable, but got not sufficient attention. There will be more occasions to put them on stage again.

- **LEGIT** specialize, perhaps in a frequent topic that comes in many flavours and cases and can't be boiled down to *"duplicate of...<single answer>"*. [BasilBourque](https://stackoverflow.com/search?q=user:642706) is the Date/DateTime guru for example.

- **LEGIT** be a karma-whore. If you posted an answer and the OP signalled acceptance by commenting on the line of "thank you so much, very helpful" without accepting it, ask him if he/she/whatever could "consider to accept the answer by clicking the check mark". Many new posters aren't aware of those formalities. 

- **DOUBTFUL** Scavenge from later answers, if that's compatible with your moral compass. Don't try it with earlier answers, the approach will stink a mile against the wind.

- **EVIL** use sock puppet accounts and amplify certain answers. Don't overdo it, you'll quickly get weeded out.

- **EVIL** conspire with others to mutually up-vote answers/questions. Will get you weeded out in no time.

## when commenting

- **LEGIT** imagine you're sitting next to the OP and tell him your comment. Helps me to remain respectful and empathic, especially when the comment is has to convey criticism. Sometimes people including myself forget that even SO is a sort of communication platform, not just a place where some entities throw information at each other.

## When asking
- follow the guidlines(https://stackoverflow.com/tour). Well - nobody reads the guidelines. 

  **They'll snap at you and down-vote you to death when you do any of these:**

    - paste no code at all, paste images of code, paste links to images of code
    - paste code that doesn't compile, is badly formatted or not formatted at all (you can format it using the `{}` button).
    - just dump your whole project without singling out a [minimal reproducible example](https://stackoverflow.com/help/minimal-reproducible-example)
    - just copy/paste homework assignments without your solution attempts ("That's a do-my-homework question")
    - don't document your own effort you put into it and point out where and why you're stuck ("This is not a free coding/debugging service...") 
    - mention errors but post no exception, call stack and the line the exception is raised (there are no line numbers at SO)
    - don't post sample input that leads to observed errors
    - don't describe expected behavior
    - sound demanding

- and you got down-voted to death, you'd want to work on your way of asking or your choice of questions. **But** if you also want to restore your SO reputation to where it was before, then just delete the post. As long as there hasn't been an answer that's supposed to be ok. Afterwards I'm not sure, but a post of that kind isn't likelely to yield any answers anyway. Don't re-post it, though, this will get you're account blocked.
