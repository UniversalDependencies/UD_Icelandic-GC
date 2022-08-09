# Summary

UD_Icelandic-GC is a conversion of the gold part of [GreynirCorpus](https://github.com/mideind/GreynirCorpus), which has been manually corrected and verified. The corpus is parsed into full constituency trees, and converted using [UDConverter-GreynirCorpus](https://github.com/thorunna/UDConverter-GreynirCorpus).


# Introduction

The treebank consists of text which was extracted from news and governments sites on the web in the years 2015-2021.

The GreynirCorpus data was split into a development set and a test set, and that split is preserved. The test set consists of 10% of the total number of sentences, chosen at random. The test set in UD_Icelandic-GC is the same. The original development set is now the training set, excluding every tenth file, which is now in the development set.

The treebank consists of 99,611 tokens in total. The training set consists of 79,395 tokens, the development set of 10,694 tokens and the test set of 9,522 tokens.


# Acknowledgments

This project was funded by the Language Technology Programme for Icelandic 2019-2023. The programme, which is managed and coordinated by Almannarómur (https://almannaromur.is/), is funded by the Icelandic Ministry of Education, Science and Culture.


# Changelog

* 2022-11-15 v2.11
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.11
License: CC BY-SA 4.0
Includes text: yes
Genre: news government
Lemmas: manual native
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: converted from manual
Contributors: Þorsteinsson, Vilhjálmur; Óladóttir, Hulda; Arnardóttir, Þórunn; Þórðarson, Sveinbjörn; Símonarson, Haukur Barri; Ásgeirsdóttir, Katla
Contributing: elsewhere
Contact: thar@hi.is
===============================================================================
</pre>
