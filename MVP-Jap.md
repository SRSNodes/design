Minimum Viable Product - Japanese Case study
============================================
"Goal": learn how to read a simple sentence with simple gramamr and some kanji
top-down requirements:
#  (TODO: categorize this stuff with linguistic terminology like grapheme morpheme etc somehow? -> probably time for a computational linguistics book or something)
#  - knowledgebase has structurally decomposed sentence examples (Research question: how reliably can this be handled for machine processing arbitrary input?) (https://en.wikipedia.org/wiki/Parse_tree)
#      -> so at least the split into parse tree and terminals for sentences, and parse tree and terminals for kanji? - and later the whole deal with phonemes and morphemes and idk?
#    - (spread out / structural information;) knowledgebase has grammar
#    - (individual characters) knowledgebase has dependency tree of radical based kanji 
  (The linguistic terminology here probably does not map correctly onto kanji)
  - knowledgebase has sentence examples with parse tree information
  - KB has grammar explanations/lessons for parse tree components
  - KB has lessons for terminal nodes i.e. words
  - KB has lessons for kanji
    - KB has lessons for kanji radicals

Implementation
--------------
1. Interaction:
  a) can display knowledge items
    i) on a terminal prompt
  b) can accept and process user input
    i) on a terminal prompt

1a) requires
  2. machine processable Japanese knowledge corpus
    ??? how do i make the information first class? how do i store and process it???


SRS Algorithm

Dataset
- kana
- kanjidamage

-> construct dependency graph
    test with graphviz or something
