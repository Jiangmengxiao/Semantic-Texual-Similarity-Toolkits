# Semantic Textual Similarity Toolkits

[![Gitter](https://badges.gitter.im/owner/repo.png)](https://gitter.im/ecnunlp/Lobby?)

This is the code by [ECNU team](http://aclweb.org/anthology/S/S17/S17-2028.pdf) submitted to SemEval STS Task.

## Installation

```bash
# download the repo
git clone https://github.com/rgtjf/Semantic-Texual-Similarity-Toolkits.git
# download the dataset and stanford CoreNLP tools
sh download.sh
# run the demo
python demo.py
```

## Results

you can configure `sts_model.py` to see the performance of different features on STSBenchmark dataset.

### STSBenchmark

| Methods              | Dev    | Test   |
|----------------------|--------|--------|
| aligner              | 0.6991 | 0.6379 |
| idf_aligner          | 0.7969 | 0.7622 |
| BOWFeature-True      | 0.7584 | 0.6472 |
| BOWFeature-False     | 0.7788 | 0.6874 |
| nGramOverlapFeature  | 0.7817 | 0.7453 |
| BOWFeature           | 0.7639 | 0.6847 |
| AlignmentFeature     | 0.8163 | 0.7748 |
| WordEmbeddingFeature | 0.8011 | 0.7128 |

### Reference
[STSBenchmark board](http://ixa2.si.ehu.es/stswiki/index.php/STSbenchmark)


## Contacts
Any questions, please feel free to contact us:
rgtjf1 AT 163 DOT com