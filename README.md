# ArmTDP-NER

A corpus of ~150K tokens with highly accurate manual annotations ("gold standard") of named entities, based on selected newspaper articles (1,949 pieces of text) in Modern Eastern Armenian from various domains, following the OntoNotes 5.0 markup scheme (with some modifications for Eastern Armenian-specific issues). Useful for EDT and NER tasks.

The corpus was developed by the ArmTDP team led by Marat M. Yavrumyan at Yerevan State University, in collaboration with the 'Armenia National SDG Innovation Lab' and the 'UC Berkley's Armenian Linguists' network'.

A pre-trained NER model based on the corpus can be found under [Stanza models](https://stanfordnlp.github.io/stanza/ner_models.html) and has been provided by [Shake Hakobyan](https://github.com/stanfordnlp/stanza/issues/1206). 

The corpus uses 18 named entity types, whose short descriptions are given below:

* PERSON - People including fictional
* NORP - Nationalities or religious or political groups
* FACILITY - Buildings, airports, highways, bridges, etc.
* ORGANIZATION - Companies, agencies, institutions, etc.
* GPE - Countries, cities, states
* LOCATION - Non-GPE locations, mountain ranges, bodies of water
* PRODUCT - Vehicles, weapons, foods, etc. (Not services)
* EVENT - Named hurricanes, battles, wars, sports events, etc.
* WORK OF ART - Titles of books, songs, etc.
* LAW - Named documents made into laws
* LANGUAGE - Any named language
* DATE - Absolute or relative dates or periods
* TIME - Times smaller than a day
* PERCENT - Percentage (including “%”)
* MONEY - Monetary values, including unit
* QUANTITY - Measurements, as of weight or distance
* ORDINAL - “first”, “second”
* CARDINAL - Numerals that do not fall under another type.

From the list of 18 types of named entities 17.632 labels were used:

* PERSON – 3502
* NORP – 823
* FACILITY – 601
* ORGANIZATION – 3388
* GPE – 3290
* LOCATION – 166
* PRODUCT – 107
* EVENT – 211
* WORK OF ART – 156
* LAW – 466
* LANGUAGE – 47
* DATE – 1995
* TIME – 405
* PERCENT – 112
* MONEY – 267
* QUANTITY – 343
* ORDINAL – 608
* CARDINAL – 1145

## Citation

Please cite this corpus as:

```tex
@misc{ArmTDP-NER,
  title={{ArmTDP-NER}: Named Entity Corpus of Modern Eastern Armenian 1.0},
  url={https://github.com/myavrum/ArmTDP-NER},
  note={Corpus available from https://github.com/myavrum/ArmTDP-NER},
  author={
    Marat Yavrumyan
    },
  year={2020},
}
```

```
Contributor: Yavrumyan, Marat M.
Contact: marat.yavrumyan@gmail.com
```
