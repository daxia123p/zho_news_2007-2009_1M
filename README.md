# zho_news_2007-2009 1M Chinese Source Corpus

This repository contains the Chinese source corpus used in the sequence-level experiments of our Chinese Braille transcription study.

## Included File

* `zho_news_2007-2009_1M-sentences.txt`

The file contains the 1,000,000-sentence downloadable subset of the `zho_news_2007-2009` Chinese news corpus.

## Original Source

* **Corpus:** `zho_news_2007-2009`
* **Provider:** Leipzig Corpora Collection / Wortschatz Leipzig
* **Institution:** Leipzig University
* **Original download page:**
  `https://wortschatz.uni-leipzig.de/en/download/zho#zho_news_2007-2009`

This repository does not claim ownership of the original Chinese sentences. The file is redistributed solely to identify and preserve the exact source corpus used in the accompanying experiments.

Users should review and comply with the original corpus license and attribution requirements before reusing or redistributing the data.

No endorsement by Leipzig University or the Leipzig Corpora Collection is implied.

## Use in This Study

The Chinese sentences in this corpus were processed to generate Chinese–Braille Unicode parallel data.

The processing included:

1. removing sentence identifiers;
2. filtering unusable records;
3. normalizing Chinese text;
4. converting Chinese sentences into Braille Unicode sequences;
5. processing Braille tone marks; and
6. dividing the processed sentence pairs into training, validation, and test sets.

The processed Chinese–Braille data are not included in this repository.

## Processing Code

The complete data-processing and dataset-generation code is available at:

`https://github.com/daxia123p/chinese-braille-mt5`

Relevant directory:

`https://github.com/daxia123p/chinese-braille-mt5/tree/main/data_preparation`

The source code is released separately under the MIT License. The MIT License does not apply to the third-party corpus file contained in this repository.

## Related Image Dataset

The natural-scene Braille image dataset used in the image-based experiments is available at:

`https://github.com/daxia123p/natural_scene_braille`

## Citation

Users of the original corpus should cite:

Goldhahn, D., Eckart, T., and Quasthoff, U. (2012). Building Large Monolingual Dictionaries at the Leipzig Corpora Collection: From 100 to 200 Languages. In Proceedings of the 8th International Conference on Language Resources and Evaluation (LREC 2012).
