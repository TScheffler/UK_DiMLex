# UK_DiMLex: Lexicon of Ukrainian connectives #

## Introduction ##

This repository contains the first public, computer readable lexicon of Ukrainian connectives. It is free to use (under the MIT license) and provided as is, without any warranty. 

The lexicon is searchable online via the multilingual interface at [connective-lex](www.connective-lex.info).

## Structure of the Lexicon ##

The lexicon is an xml file roughly following the DiMLex standard. Each entry consists of:
* a numerical ID and the lemma
* an English translation `<english_equivalent/>`
* one or more orthographic variants `<orth/>`
* a syntactic class `<syn/>`

## References ##

If you use this data, please cite the following references:

* Tatjana Scheffler, Veronika Solopova, Olha Zolotarenko, and Mariia Razno. A computational lexicon of Ukrainian discourse connectives. In: Proceedings of the First Ukrainian NLP Workshop, pp. 692--704. CEUR-WS: ICTERI. 2021. [PDF](http://icteri.org/icteri-2021/proceedings/volume-2/202110692.pdf)
* Tatjana Scheffler, Veronika Solopova, Olha Zolotarenko, and Mariia Razno. Automated identification of connectives in Ukrainian. In: xxx (eds.) Communications in Computer and Information Science, vol xxx. Springer. 2022. [PDF]()

	```bibtex
    @InProceedings{SchefflerEtal2021-UKNLP,
      author    = {Tatjana Scheffler and Veronika Solopova and Olha Zolotarenko and Mariia Razno},
      title     = {A computational lexicon of Ukrainian discourse connectives},
      booktitle = {Proceedings of the First Ukrainian NLP Workshop, ICTERI-2021, Vol II: Workshops},
      year      = {2021},
      address   = {Kherson, Ukraine/online},
      publisher = {CEUR},
      pages     = {692--704},
      url       = {http://icteri.org/icteri-2021/proceedings/volume-2/202110692.pdf},
    }
	```
	```bibtex
    @InCollection{SchefflerEtal2022-UKconn,
      author    = {Tatjana Scheffler and Veronika Solopova and Olha Zolotarenko and Mariia Razno},
      title     = {Automated identification of connectives in Ukrainian},
      booktitle = {xxx},
      editors = {xxx},
      year      = {2022},
      address   = {Cham},
      publisher = {Springer},
      pages     = {xxx}
    }
	```


Please also consider citing the GRAK corpus, on which some of this work builds:

Шведова, М., фон Вальденфельс, Р. , Яригiн, С., Рисiн, А. , Старко, В., та iн.:
Генеральний регiонально анотований корпус української мови (ГРАК) (2017–
2021), [LINK](http://uacorpus.org)
