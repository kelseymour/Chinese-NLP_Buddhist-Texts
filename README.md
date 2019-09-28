# Chinese-NLP_Buddhist-Texts
This proof-of-concept notebook uses a (Modern) Chinese SpaCy library as a base to tokenize and analyze parts of speech for a short Buddhist text. Mistakes in the tags were corrected by hand to train an improved model for Pre-Modern Literary Chinese Texts. It was built with Pandas, SpaCy, Xiaoquan Kong's Chinese SpaCy models. It implements a Part of Speech tagger and visualizations using diSplaCy.

~.~.~~.~.~~.~.~~.~.~~.~.~..~,D, ~.~  :.~..~.~ ,~ ~.~~.~.~~.~
.~ ~ .~.~  ~.~ .~.~..~.~ :~MDDD:.~.~~.~.~~.~ :,.~.~ .~.~. ~.
~.~ ~~.~.~~.~.~~ ~.~~.~ ~.+DDDDN~.~ .~.~..~.~.,~.~.~~.~.~~.~
,,,,.,,,,,,,,,,,,,,,,,,,,DDDDDDDDD,.,,,,,,,,,,,,,,,,,,,,,,,,
.~.~..~.~  ~.~ .~.~..~ ~DDDDDDDDDDN~~.~ ~~.~.~,.~ ~..~ ~. :.
~.~ ~~ ~.~~.~.~~ ~.~~.~ DDDDDDDDDDD..~.~..~.~.,~.~.~~.~.~~.~
.~.: .:.:. :.:..~.~..~.:DDDDDDDDDDD~~.:.~~.:.~,.~.:..~.:  :.
 ~ ~. ~ ~..~ ~..~ ~  ~ ,DDDDDDDDDDD:~.~ ~~ ~.~, ~ ~..~ ~,.~ 
~.~ ~~.~.~~.~ ~~ ~ ~~ ~ DDDDDDDDDD7..~.~  ~.~.,~.~.~~.~.~~.~
.~.~ .~.~  ~ ~ .~ ~ .~.~M=DDDDDDD?.~~.~ ~~.~ ~,.~.~  ~.~. :.
~ ~.:~ ~ ~~ ~ ~: ~ ~~ ~ ~.8DDDDDO ~..~ ~  ~ ~ :~ ~.~: ~ ~~.~
~.~.:~.~.~~.~.~~ ~.~~.~ ~.NDDDDDD ~ .~.~..~.~ ,~.~.~:.~.~~.~
.~.~ .~.~  ~.~  ~ ~..~8DDDDDDDDDDDDNO.~.~~.~ ~,.~.~  ~.~. :.
~.~ ~~.~.~~.~ ~~ ~.:DDDDDDDDDDDDDDDDDDD:..~.~.:~.~.~~.~.~~.~
.~.~ .~.~  ~.~ .~.~DDDDDDDDDDDDDDDDDDDDN~~.~ :,.~.~ .~.~. ~.
 ~ ~..~.~  ~.~ .~.~DDDDDDDDDDDDDDDDDDDDD~~.~ ~,.~ ~  ~.~. ~.
~.~ ~~.~.~~.~ ~~ ~DDDDNNDDDDDDDDDDDDDDDDM.~.~.,~.~.~~.~.~~.~
.~.~..~.~  ~.~ .~.NDDD MDDDDDDDDDDDM~DDDN:.~ ~,.~.~  ~.~  :.
~ ~.~~ ~.~~ ~ ~~.~DDDD~.DDDDDDDDDDD..DDDD.~ :.:~ ~.~~ ~ ~~.~
~ ~.~~ ~.~~ ~ ~~ NDDD.~ NDDDDDDDDDN..~DDDN~ ~ ,~ ~.~~ ~ ~~.~
.~.~ .~.~. ~.~ .~NDDD~.~DDDDDDDDDDD~~.DDDD.~ ~,.~ ~  ~.~  :.
~.~ ~~.~.DDNN.~~ NDDDD~ NDDDDDDDDDDD~DDDDN~.~.NDDD ~~.~.~~.~
 ~.~  ~ ~DDDDDDDN.~DDDDDDDDDDDDDDDDDDDDD~,NNDDDDDD~ .~ ~  ~ 
.~.~  ~.~MDDDDDDDDDNNDDDDDDDDDDDDDDDDNDDDDDDDDDDD,~. ~.~  ~.
~.~ :~ ~.:DDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDD~ ~~.~.~~.~
MDDDNM= ~ NDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDO : :NNNDDN.
~.NDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDD:.~
~.:,NDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDD,~~ ~
.~.~.,DDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDD?.~. :.
~.~.~~.:DDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDD:~.~.~~.~
.~.~. ~ :.+NDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDDD?.~..~ ~..: 
.~.~ .~.~  ~ :8DDDDDDDDDDDDDDDDDDDDDDDDDDDDNM:,.~.~ .~ ~  ~.
~.~.~~.~.~~.~ ~~ ~.~~.~ ~..~ ~..~ ~ .~.~ .~.~.,~.~.~~.~.~~.~

