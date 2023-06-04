# BrevE and CLaro

Para español, ve [aquí](./LEEME.md).

This is the repository for our paper "BrevE and CLaro: an evaluation of Spanish text simplification". 
- BrevE is a corpus designed for Spanish complex sentence identification (CSI).
- CLaro is a corpus for complex word identification (CWI).

Both corpora have been annotated by native Spanish speakers. This is important because:

- Spanish is a language spoken by almost half a billion people!
- Spanish morphology is quite different than English, and the sentence structure / word order allows for nuances that are not easily translated.

Text simplification (TS) is an important area of NLP, and is designed to make written material more accessible to a variety of users. 
However, it has been shown that identifying sentences that _need_ simplification on the first place considerably improves the performance of any TS system. 
Our work is meant to benchmark this. 

If you use BrevE or CLaro in your work, please considering citing our paper:

```
@article{placeholderpaper
   TBD
}
```

As well as the original works for the corpora we used to build BrevE and CLaro:

```
@inproceedings{oscar1,
  author    = {Julien Abadji and Pedro Javier Ortiz Su\'{a}rez and Laurent Romary and Beno\^{i}t Sagot},
  title     = {Ungoliant: An optimized pipeline for the generation of a very large-scale multilingual web corpus},
  series = {Proceedings of the Workshop on Challenges in the Management of Large Corpora (CMLC-9) 2021. Limerick, 12 July 2021 (Online-Event)},
  editor    = {Harald L{\"u}ngen and Marc Kupietz and Piotr Bański and Adrien Barbaresi and Simon Clematide and Ines Pisetta},
  publisher = {Leibniz-Institut f{\"u}r Deutsche Sprache},
  address   = {Mannheim},
  doi       = {10.14618/ids-pub-10468},
  url       = {https://nbn-resolving.org/urn:nbn:de:bsz:mh39-104688},
  pages     = {1 -- 9},
  year      = {2021},
}

@inproceedings{oscar2,
  author    = {Pedro Javier {Ortiz Su\'{a}rez} and Beno\^it Sagot and Laurent Romary},
  title     = {Asynchronous pipelines for processing huge corpora on medium to low resource infrastructures},
  series = {Proceedings of the Workshop on Challenges in the Management of Large Corpora (CMLC-7) 2019. Cardiff, 22nd July 2019},
  editor    = {Piotr Ba\'nski and Adrien Barbaresi and Hanno Biber and Evelyn Breiteneder and Simon Clematide and Marc Kupietz and Harald L\"{u}ngen and Caroline Iliadi},
  publisher = {Leibniz-Institut f\"{u}r Deutsche Sprache},
  address   = {Mannheim},
  doi       = {10.14618/ids-pub-9021},
  url       = {http://nbn-resolving.de/urn:nbn:de:bsz:mh39-90215},
  pages     = {9 -- 16},
  year      = {2019},
}

@inproceedings{yimam1,
    title = "Multilingual and Cross-Lingual Complex Word Identification",
    author = "Yimam, Seid Muhie  and
      {\v{S}}tajner, Sanja  and
      Riedl, Martin  and
      Biemann, Chris",
    booktitle = "Proceedings of the International Conference Recent Advances in Natural Language Processing, {RANLP} 2017",
    month = sep,
    year = "2017",
    address = "Varna, Bulgaria",
    publisher = "INCOMA Ltd.",
    url = "https://doi.org/10.26615/978-954-452-049-6_104",
    doi = "10.26615/978-954-452-049-6_104",
    pages = "813--822",
}

@inproceedings{yimam2,
    title = "{CWIG}3{G}2 - Complex Word Identification Task across Three Text Genres and Two User Groups",
    author = "Yimam, Seid Muhie  and
      {\v{S}}tajner, Sanja  and
      Riedl, Martin  and
      Biemann, Chris",
    booktitle = "Proceedings of the Eighth International Joint Conference on Natural Language Processing (Volume 2: Short Papers)",
    month = nov,
    year = "2017",
    address = "Taipei, Taiwan",
    publisher = "Asian Federation of Natural Language Processing",
    url = "https://aclanthology.org/I17-2068",
    pages = "401--407",
}

```

# Contributing

See [here](./CONTRIBUTING.md).

# Legal Notices

See [here](./NOTICE.md)
