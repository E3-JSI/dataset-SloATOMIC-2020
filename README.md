# SloATOMIC 2020 Data Set

[![CC BY 4.0][cc-by-shield]][cc-by]

The SloATOMIC 2020 contains the Slovene translated examples of the [ATOMIC 2020][atomic-2020] data set.
The translation was done using the [DeepL][deepl] translation service.

The main purpose of the data set is to train [Slovene commonsense reasoning models][slomet-atomic-2020].

## 🗃️ Data

The data set is available in the [data](data) folder which contains the following files:

- [sloatomic_train.tsv](data/sloatomic_train.tsv): The training set.
- [sloatomic_dev.tsv](data/sloatomic_dev.tsv): The development set.
- [sloatomic_test.tsv.automatic_all](data/sloatomic_test.tsv.automatic_all): The test set containing all of the automatically translated examples.
- [sloatomic_test.tsv.automatic_10k](data/sloatomic_test.tsv.automatic_10k): The selection of 10k examples from the complete test set.
- [sloatomic_test.tsv.manual_10k](data/sloatomic_test.tsv.manual_10k): The manually inspected and fixed examples of the _automatic 10k_ subset.

### Data Format

The data is in the tsv (tab-seperated) format. Each line contains one example. The columns are:

- **head_event**: The head event of the example.
- **relation**: The relation between the head event and the tail event.
- **tail_event**: The tail event of the example.

## 📚 Papers

The data set was used in the following papers:

- **[SLOmet - Slovenian Commonsense Description.][published-paper]**
  Adrian Mladenić Grobelnik, Erik NOvak, Dunja Mladenić, Marko Grobelnik
  SiKDD Slovenian KDD Conference, 2022.

## 📣 Acknowledgments

This work is developed by [Department of Artificial Intelligence][ailab] at [Jozef Stefan Institute][ijs].

The work is supported by the Slovenian Research Agency and the [RSDO][rsdo] project.

[deepl]: https://www.deepl.com/translator
[atomic-2020]: https://allenai.org/data/atomic-2020
[slomet-atomic-2020]: https://github.com/eriknovak/RSDO-SLOmet-atomic-2020
[ailab]: http://ailab.ijs.si/
[ijs]: https://www.ijs.si/
[rsdo]: https://www.cjvt.si/rsdo/en/project/
[published-paper]: https://ailab.ijs.si/dunja/SiKDD2022/Papers/SiKDD2022_paper_5674.pdf
[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
