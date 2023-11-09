# Chapter 1: Propositional Logic

 - [What tf is proposition?](#11-what-tf-is-proposition)
 - Dang compound propositions...
 - Examples
 - Converse, Inverse, Contrapositive and tautology and more...
 - Logical Equivalence By Identities and Laws

## 1.1: What tf is proposition?
Well "A proposition is a declarative statement that is either true or false, but not"
Example:
- "I was told am very handsome-" is a proposition! (And it's true of course!)
- "You are ugly!" Is not :v its an opinion, which may be true or false... kinda like X + Y = 5, how do you know it's right? Dunno!

Note: In a question, [[]] means the question asks you to find the truth value (True/false) of the thing inside [[]]
Example: He told you, [[You are dumb]] --> True! (Well actually no, since that's an opinion so that doesn't count :p)


## 1.2: Dang compound propositions...

 1. Negation ( - )
 2. Conjunction ( ^ )
 3. Disjunction ( V )
 4. Implication (→)
 5.  Others!
 
Yadiyada ik negation should be slightly longer and conjunction be as big as disjunction but what givessss

**Conjunction**
| p |q  | p^q|  
|--|--|--|
|T|T|T|
|T|F|F|
|F|T|F|
|TF|F|F|

aka "AND" , yeah.. i assume yall know what an AND gate is

**Disjunction**
|p|q|pVq|  
|--|--|--|
|T|T|T|
|T|F|T|
|F|T|T|
|F|F|F|

So. "OR" gate. if one is True then it's true! 

**Implication**
|p|q|p→q|  
|--|--|--|
|T|T|T|
|T|F|F|
|F|T|T|
|F|F|T|

Weird one, I know I don't get it too well, it normally means
- "if p, then q"
- "p only if q" [not recommended and confusing] (Yes I know it got something to do with sufficient conditions and necessary conditions, but its quite confusing)
- "p is necessary for q"
- "q when/if p"
- "p implies q" [recommended]

If you make it into sentence it'll make tons of sense tho! 
 - You get hurt when you kill yourself (True!)
 - You don't get hurt when you kill yourself  (You're... practically immortal if you don't get hurt!)
 - you get hurt when you don't kill yourself (aka you can get hurt other ways)   
 - you don't not get hurt when you don't kill yourself (Mr Obvious?)

**If and only if** and **Exclusive Or**
|p|q|p<->q|  
|--|--|--|
|T|T|T|
|T|F|F|
|F|T|F|
|F|F|T|

for "Exclusive Or", its just negation of "If and Only If"!
As you see from the "Implication" 3rd Example, you get hurt if and only if you don't kill yourself, that doesn't makes sense now does it! 

## 1.3 Examples
alright lads now examples time! 
Given that:
p: You are dumb
q: You get 0 marks
r: Your dog is clever

Express: r ^ (p → q)  V p 

Oh yeah and note that the priority table goes as follow

 1. ()
 2. -
 3. ^
 4. v
 5. →
 6. <-> 

Answer: Your dog is clever and if you are dumb, then you get 0 marks or you are dumb!
Yeah sounds weird, but hey discrete functions! Amirite- 

## 1.4 Converse, Inverse, Contrapositive and tautology and more...
the converse of p → q is q → p
the inverse of p → q is -p → -q
the contrapositive of p → q is -q → -p
Aka
Change Position
Negative
Negative n Change Pos !

Alright now for classifications of compound propositions (long ik)
A compound proposition is called
• a tautology if it is always true
• a contradiction if it is always false
• a contingency if it is neither a tautology nor a contradiction, aka its not all true/false.
Taking from textbook...
 
Example: Given
p: Today is raining.
q: I am going out.
p V -p is a tautology.
p ^ -p is a contradiction.
p V q is a contingency.

Tbh just look at their truth table (make it yourself! Am lazyyy). If you get all true it's... am not gonna repeat that

## 1.5: Logical Equivalence By Identities and Laws
p and q is said to be logically equivalence when p <-> q is always true, aka tautology

it can be writen as... 
p ≡ q
p ⇔ q
yeah whichever, both means "logically equivalence"
(Am not explaining the truth table part :<, If all is true then its logically equivalence! No questions asked!)

Oh and uh am not gonna write about identities and laws, too much of a hassle... learn it yaself
