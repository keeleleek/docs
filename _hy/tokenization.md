---
layout: base
title:  'Tokenization'
udver: '2'
---

# Tokenization

The low-level tokenization of the Armenian UD treebank follows the tokenization of the
[ՀայՇտեմ - Armenian Dependency Treebank 1.0](http://armtreebank.yerevann.com/) (ArmDT):

* In general, tokens are delimited by whitespace.
* Punctuation (recognized by the corresponding Unicode property) that is conventionally written adjacent to the preceding or following word is separated during tokenization.
  Some special cases worth mentioning:
  * An abbreviation marked by a period, as in *թ.* “year”, becomes two tokens, *<b>թ</b>* and *<b>.</b>* .
  * A compound containing a hyphen becomes three tokens (two words and the hyphen), as in *անգլո-ամերիկյան* “anglo-american”, *պատմա-բանասիրական* “historical-philological”.
    In these cases, the first token is a special form of adjective that never occurs independently.
    Compounds without a hyphen are not split, thus _ռազմածովային_ “navy” is one token but _հասարակական-քաղաքական_ “civic-social” would be three tokens.
    Another common case of splitting-on-hyphen are reduplicative or echo words as in _մեծ-մեծ_ “very big”, _շուն-մուն_ “dog or something”.
  * Exception: Decimal numbers are normalized (the Armenian decimal comma is converted to the English decimal point) and kept as one token, e.g. *<b>2.1</b>*.
* Most of the time, every punctuation character constitutes a token of its own. Thus *<b>»,—</b>* will become three tokens.
  * Exceptions are conventional multi-character punctuation marks: *<b>...</b>* , *<b>....</b>* , and emojis and smileys: *<b>:)</b>* , *<b>^_^</b>*, etc.
  Conventional non-armenian multi-characte  punctuation marks and terms are tokenized as single tokens: *<b>?!</b>* , *<b>°С</b>* .

### Verb forms, analytical grammatical forms, negation

* the forms of necessitative mood, analytical causative, complex tenses, complex comparatives, etc. are splitted
according to the orthographic principle: { <b>պիտի</b> , <b>վազեն</b> } “”, { <b>գրել</b> , <b>տվեց</b> } “”, { <b>վազում</b> , <b>եմ</b> } “”, { <b>ավելի</b> , <b>լուրջ</b> } “more serious”.
* <b>մի</b> and <b>ոչ</b> used as negation markers with verbs, adjectives, pronouns and other words are tokenized according to the orthographic rules: { <b>մի</b> , <b>գրիր</b> } “”, { <b>ոչ</b> , <b>պաշտոնական</b> } “unofficial”, { <b>ոչ</b> , <b>մի</b> , <b>կերպ</b> } “in no way”.
