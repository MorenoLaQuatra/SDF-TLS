# SDF-TLS
Data collection and resulting timelines for the paper 

Summarize Dates First: A Paradigm Shift in Timeline Summarization.

Moreno La Quatra, Luca Cagliero, Elena Baralis, Alberto Messina, and Maurizio Montagnuolo. 2021. Summarize Dates First: A Paradigm Shift in Timeline Summarization. In Proceedings of the 44th International ACM SIGIR Conference on Research and Development in Information Retrieval (SIGIR 21). Association for Computing Machinery, New York, NY, USA, 418–427. DOI:https://doi.org/10.1145/3404835.3462954 

Access through ACM website: https://doi.org/10.1145/3404835.3462954

## Code
The complete code both for date summarization and selection will be updated after the paper acceptance/conference presentation.

## Dataset CovidTLS
The data collection proposed in the paper could be easily reconstructed by using:
- The `data-sars-cov-2/list-URLs.tsv` file contains the pubdate and the link to the original documents, one per line (tab-separated-values)
- The `data-sars-cov-2/timeline.txt` contains the ground-truth timeline parsed from [covidreference website](https://covidreference.com/). It follows the [tilse](https://github.com/smartschat/tilse) ([tilse framework](https://arxiv.org/pdf/1810.07949.pdf) [tilse evaluation metric](https://www.aclweb.org/anthology/E17-2046.pdf)) annotation format.

## System Output
The folder `system_output` contains the best performing algorithm that can be used for performance comparison. The output for each benchmark data collection is stored separately in a dedicated folder (e.g., `system_output/TL17_bestds/` include the output timelines for the best performing method in date selection). 
