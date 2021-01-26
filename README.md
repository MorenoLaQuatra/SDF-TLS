# SDF-TLS
Data collection and resulting timelines for the paper Summarize Dates First : a paradigm change in timeline summarization (currently under review).

## Dataset Sars-Cov-2
The data collection proposed in the paper could be easily reconstructed by using:
- The `data-sars-cov-2/list-URLs.tsv` file contains the pubdate and the link to the original documents, one per line (tab-separated-values)
- The `data-sars-cov-2/timeline.txt` contains the ground-truth timeline parsed from [covidreference website](https://covidreference.com/). It follows the [tilse](https://github.com/smartschat/tilse) ([tilse framework](https://arxiv.org/pdf/1810.07949.pdf) [tilse evaluation metric](https://www.aclweb.org/anthology/E17-2046.pdf)) annotation format.
