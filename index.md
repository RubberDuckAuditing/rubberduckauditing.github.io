---
layout: default
---

# Rubber Duck Auditing

The rubber duck auditing method is as follows:

1. Beg, borrow, steal, buy, fabricate or otherwise obtain a rubber duck (bathtub variety).
2. Place rubber duck on desk and inform it you are just going to go over some code with it, if that's all right.
3. Explain to the duck what your code is supposed to do, and then go into detail and explain your code line by line.
4. At some point you will tell the duck what security assumptions you're making next and then realise that those assumptions don't actually hold. The duck will sit there serenely, happy in the knowledge that it has helped you find a vulnerability.

**Note**: In a pinch a coworker might be able to substitute for the duck, however, it is often preferred to confide potential vulnerabilities to the duck instead of your coworker.

## The Questions

For any piece of code you review—whether it's a function, contract, file, variable, or struct—explain to your duck:

- **What** does this code do?
- **Why** does it exist?
- **How** does it do it?

Then, challenge your assumptions:

- **What** could go wrong?
- **What if…?**

## FAQs

- **If ducks are so smart, why don't we just let the ducks do all the auditing?**
  While ducks are excellent listeners, smart contract auditing requires the human ability to think adversarially and question every assumption. The duck's real power lies in forcing you to articulate your security model out loud—it's during that explanation where you'll catch the edge cases, realize when your invariants can be broken, and spot the vulnerabilities before an attacker does. The duck won't write the audit report, but it will help you find what goes in it.

- **Where can I learn more about rubber duck auditing?**
  More information about the rubber duck method can be found at <a href="http://en.wikipedia.org/wiki/Rubber_duck_debugging" target="_blank" rel="noopener noreferrer">wikipedia.org</a>, <a href="http://lists.ethernal.org/oldarchives/cantlug-0211/msg00174.html" target="_blank" rel="noopener noreferrer">lists.ethernal.org</a>, and <a href="https://blog.codinghorror.com/rubber-duck-problem-solving/" target="_blank" rel="noopener noreferrer">codinghorror.com</a>. The technique applies perfectly to smart contract auditing.

- **Where can I hire my own duck?**
  Great question! <a href="https://www.amazon.com/s/ref=nb_sb_noss?url=search-alias%3Daps&field-keywords=rubber+duck" target="_blank" rel="noopener noreferrer">Amazon.com</a> hosts a wide selection of affordable ducks that have earned top placements in competitive audit contests.

- **Why does this site exist?**
  Forked from the classic rubber duck debugging technique from <a href="https://rubberduckdebugging.com/" target="_blank" rel="noopener noreferrer">rubberduckdebugging.com</a>, this site adapts the method for smart contract auditing. Explaining your code's security assumptions to a duck is one of the most effective ways to find vulnerabilities before attackers do.
