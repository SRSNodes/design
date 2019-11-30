This bibliography^W doucment in it's current iteration is primarily informed by the case study on developing this system for the Japanese language.
Feel free to bikeshed the organization of this document.

Technical Design
================
abstract components:
  backend
    knowledge database (data representation)
    path finding algorithms (simple dependency tree traversal really?) (reachability construction)
  frontend
    domain specific input component (e.g. japanese IME)
      -> domain specific output component?
    reasonable configuration language? (dhall? -> plus domain specific processing extensions by necessity? -> so not dhall anymore...)
      -> do we need to go full proglang?

Bibliography
============

TODO:
- I find it hard to believe there would be no existing work on this, I need to do some literature search
- Look into how (TODO: oh no accidentally a word here??)
- Look into existing Japanese corpuses

SRS
---
I was assigned this as mandatory reading https://www.supermemo.com/en/articles/history

Knowledge representation
________________________

Software Engineering
--------------------
TODO ugh licensing, ugh getting paid

Language learning
-----------------

Japanese Case Study
...................
TODO: whats the state of the art on japanese linguistics
TODO: oh no am i basically trying to build a dictionary but also more than that stuff?
TODO: trawl tofugu
existing software:
  https://github.com/blastrock/kakugo
    personal gripe: doesnt let you use romaji for some variants - I want to do this because my kana aren't perfect yet - yes one should learn to not rely on romaji ASAP(: design goal?: domain specific easy modes + warnings? <- lowers learning curve?)
  https://getbunpo.com/
  wanikani

japanese wordnet
  "Disclaimer: We estimate that this release contains errors in as many as 5% of entries. We decided to spend more effort in increasing the cover than in checking. As we translate the glosses and sense tag text, we expect to fix many of the errors."
    could a web frontend be made for this for helpful people to suggest fixes?

research question: not all information is lexical, is there any reasonable way to integrate cltural information? (i.e. people write big blog posts about pieces of languages for a reason)
  can you just uhh....tag stuff with a link to the article? >_>
  do i need to build entire cross referenced language wikis now?
    sidenote: languages arent static structures, is there a good way to handle temporal changes?

uuuuhhhh....dialects?

postmortem:
  if this is successful, why was it succesful?
  can it be applied to other languages?
  are there better approaches?

note from experimental design: training cases and test cases need to be different

https://fasiha.github.io/post/kanjibreak/ seems like this guy might know how to code
some criticisms on kanjidamage, should probably talk to this guy https://github.com/Shinmera/writing/blob/master/Kanji%20-%20138.txt

uhhh a lot of links http://nihongo.monash.edu/japanese.html

https://github.com/jhspetersson/KanjiDamageApp
