---
title: "matthewninja today: Polyfills, Philosophy, & Getsummit"
date: 2020-02-13T12:46:16-05:00
draft: false
---

## PharoJS Slackbot Polyfill Dependencies 🤖
Yesterday, I ended development on my Slack App with a completed skeleton that handles post requests to the transpiled Express App. But, I hadn't yet dealt with dependencies needed to parse requests and make API calls to other services. 

The two needed node modules are bodyparse and request. I added polyfills for both. I also re-factored PjExpressApp. It makes more sense now.

The Slack app works perfectly! It gets a request and echo's it back to the channel received in. Check it out here: [PharoJS-Slackbot](https://github.com/matthewninja/PharoJS-Slackbot)

More funcitonality to come soon. Stay tuned ...

## Philosophy Test 🤔
I had my first midterm of the semester today. It was for PHL 214: Critical Thinking. The test covered logical validity, soundness of arguments, and analysis of *The Challenge of Cultural Relativism* by James Rachels.

For logical validity, an argument is valid if and only if the conclusion logically follows from the premises. Here's an example of a valid (but not sound) argument: 

> *Frogs are mammals. All mammals are blue. Therefore, frogs are blue.*

The above example is a valid (modus ponens), but not sound argument. For an argument to be sound, it must be valid **and** the premises must be true. Here's an example of a (probably) sound argument: 

> *Socrates was a man. All men are human. Therefore, Socrates was a human.*

Regarding the paper on Cultural Relativism, Rachels disputes both the cultural differences and Cultural Relativism arguments. 

The cultural differences argument goes like so:

> *The Greeks believe that X is wrong. The Callatians believe that X is not wrong. Therefore, X is not objectively right nor objectively wrong.*

Rachels points out that this is not a sound argument because it is not valid. Indeed, the conclusion cannot be logically deduced from the premises. This is a non-deductive argument, and a better conclusion would be something along the lines of *It is likely that X is not objectively right nor objectively wrong.*

Some of the major claims made by the Cultural Relativism argument are:

* Different societies have different moral codes.
* The moral code of a society determines what is right within that society.
* There is no objective standard that can be used to judge one society’s code as better than another’s.
* The moral code of our own society has no special status; it is but one among many.
* It is arrogant for us to judge other cultures. We should always be tolerant of them.

Rachels acknowledges these claims and then disputes the argument by pointing out some profound consequences of Cultural Relativism. Firstly, cultural differences can often be explained by differing belief systems. Cultures might very well share the same values. But differing belief systems causes them to appear to have different values. Here's an arbitrary example of two cultures sharing a moral value while holding different beliefs, resulting in different cultural norms:

> *Culture X and Y both hold the value that killing humans is wrong. Culture X believes that the souls of humans reside in cows. Culture X does not kill cows, but culture Y does.*

Moreover, Rachels points out that Cultural Relativism results in cultures being infallible and thus, never wrong. There are countless examples of cultural norms causing people to commit atrocities. But by maintaining the belief of Cultural Relativism, these norms cannot be wrong.

There are countless other arguments made by Rachels. Please read the paper if you want to find out what else he argues!

## Getsummit ⛰
In October of last year, I attended YHack at Yale University. My team made a cool tool for parsing resumes and ranking candidates. We did it all in 1 weekend.

A few weeks ago, I got a notification that GCP wanted to charge me **FIFTY DOLLARS** for the services used. This seemed outrageous because we took down the demo and only left a static web page online. So, I took the site down. Today, I made a hosted zone on Route53. I'm waiting for the updated NS records to propogate, then I'll re-upload the site. I'll update this post when it's live again.