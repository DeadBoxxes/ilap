# ilap
*ilap low level programming language*, its free to use! just please remember to update it when any changes are made to this site

ilap originally stood for something but i forgot... oops?
if you want to credit me go ahead! but its not nessisary, programming is something that shoul d be public domain, so aslong as you are not crediting this language as your own, then im completley ok with you making things that use my language!
## facts/other info
some elements of this language are similar to most old languages, however, **im trying to keep this language as simple as possible**, one thing is that i dont really reccomend this for any programming games though, mostly just terminal stuff, or programs, maybe even text adventures, but i think making games with this is torturing yourself, theres no reason you should use this for games unless you hate yourself, just stick to making fun passsion projects :)... they are always better anyways...

i *also* do not mind anyone who makes modifications to my language to their hearts content, like i said, this language is free to use so make your own versions of it if you like, just take C for example, **too many variants...**
thats really all, find stuff, stuff, and tutorials on my language on the website!

i purposely used no (or very little) css as i want to make this site every browser friendly.... no javascript either as i know the 3ds browser doesnt support it...so to anyone who wants to use the web on your 3ds... **you are in luck!**

lastly, the file type for ilap code is **.ilap**
## some things you need to know
- the way ilap works is that every action goes on a seperate line,
- because of this, note that if you wanna add breaks in text, please use PRLNBR instead of the regular PR, PRLNBR (Print LiNe BReak) is used to ad breaks between text, if you are extra lazy though or wanna make a blank break in the text, making a seperate line for a break works, this is just called LNBR... like this: (note that if you wanna add a blank space in between text, PRLNBR needs come after LNBR, if you use a regular PR it will act like a standard PRLNBR...
```
PR"HELLO...."
LNBR
PRLNBR"AAAND GOODBYE!!!!!!"
SV"Desktop/tests/test.ilp"
RUN"Desktop/tests/test.ilp"

HELLO....

AAAND GOODBYE!!!!!!
```
- there can not be blank lines in ilap...
- to hide seeeecret notes in ilap use: NOTE"text here", NOTEs go unrecognised, you cant just leave random text in though as it will regonise it, so none of this:
```
PR"hey bro"
this is a seecret note
SV"Desktop/tests/test.ilp"
RUN"Desktop/tests/test.ilp"

Syntax Error: line 2
```
notes are purely for this reason
here is the correct way:
```
PR"hey bro"
NOTE"this is a seecret note"
SV"Desktop/tests/fixed.ilp"
RUN"Desktop/tests/fixed.ilp"

hey bro
```
- ilap can work in all uppercase or all lowercase, it is not case sensitive, BUT! you cant write it with both uppercases and lowercases like this: PrLNbr, however, if you want some lines to be all uppercase or some to be all lowercase, it will still work, just note that the actions have to be either one or the other, they cant be both.
- if you wanna wrap text but are using a programming enviroment that doesnt allow wraps, you can make a new line and use a - at the start of the line to connect the last line... (PS:  to signal a break in inputs, like PRs, please put the - in these in bre brackets), this is mostly reccomended with text im my opinion...  like this:
```
PR"here is a really lon pr thing that needs to be wrapped but cant as it is far too long for whatever enviro
(-)ment im using"
SV"Desktop/tests/test.ilp"
RUN"Desktop/tests/test.ilp"

here is a really lon pr thing that needs to be wrapped but cant as it is far too long for whatever enviroment im using
```
