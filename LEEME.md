# BrevE and CLaro

For English, see [here](./README.md).

Este es el repositorio para nuestro artículo "BrevE and CLaro: an evaluation of Spanish text simplification" (t. BrevE y CLaro: una evaluación de la simplificación de textos en español). 
- BrevE es un conjunto de datos diseñado para identificación de oraciones complejas (CSI, en el original en inglés) en español.
- CLaro es un conjunto de datos hecho para identificación de lenguage claro (PLI, en el original en inglés).

Los dos conjuntos han sido etiquetados por hispanoablantes cuya lengua materna es el español. Esto es importante porque:

- El español es un lenguaje hablado por casi medio millón de millones de personas!
- La morfología del español es muy diferente a la del inglés. La estructura de las oraciones y el ordenamiento de las palabras permite matices que no son fácilmente traducibles. 

La simplifación de textos (TS en inglés) es un área muy importante del procesamiento del lenguaje natural. La meta principal del TS es hacer textos más accesible a más usuarios. 
Sin embargo, se ha demostrado que identificar oraciones que _necesitan_ simplificación en primer lugar mejora el desempeño de sistemas para TS. 
Nuestro trabajo está orientado a evaluar este fenómeno.

Ve en `documents` la documentación de nuestros conjuntos de datos, y nuestro artículo (enlace TBD) para nuestros hallazgos en CSI y PLI en español. 

Si usas BrevE o CLaro en tu trabajo, por favor considera citar nuestro artículo:
```
@misc{dewynter2023usercentered,
      title={A User-Centered Evaluation of Spanish Text Simplification}, 
      author={Adrian de Wynter and Anthony Hevia and Si-Qing Chen},
      year={2023},
      eprint={2308.07556},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
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

# Noticias 

- 5 de Junio 2023: publicamos BrevE y CLaro

# Contribuciones

Ve [aquí](./CONTRIBUTING.md) (en inglés).

# Avisos legales

Ve [aquí](./NOTICE.md) (en inglés).
