# LiterallyWikidata 
- The dataset and implementation described in the [**paper**](https://link.springer.com/chapter/10.1007/978-3-030-88361-4_30) accepted in ISWC 2021.
- A Benchmark for Knowledge Graph Completion using **Numeric** and **Text Literals** extracted from **Wikidata** and **Wikipedia**. 
- It can be used to evaluate both **unimodal** and **multimodal** Knowledge Graph Embedding approaches. 
- The collection contains three differnet datasets **LitWD1K**, **LitWD19K**, and **LitWD48K**. 

## Dataset Statstics and Analysis
|           | LitWD1K | LitWD19K | LitWD48K |
|----------:|--------:|---------:|---------:|
|\#Entities | 1,533   | 18,986   | 47,998   |
|\#Relations| 47   | 182   | 257   |
|\#Attributes|81   | 151 |297|
|\#Structured Triples|29,017 |288,933| 336,745|
|\#Numerical Attributive Triples|10,988|63,951|324,418|
|\#Train|26,115|260,039|303,117|
|\#Test|1,451|14,447|16,838|
|\#Valid|1,451|14,447|16,838|

## Literals

- We have extracted **labels**, **aliases**, and **descriptions** from wikidata for entities, relations, and attributes. There also long text descritions for entities extracted from the summary sections of thier corresponding **English**, **German**, **Russian**, and **Chinese** Wikipedia pages. 


## Benchmarking <!--- Results -->

- Link predection experiments are conducted with three models **DistMult**, **ComplEx**, and **DistMultLiteral** on all datasets using [**Pykeen**](https://pykeen.readthedocs.io/en/latest/).  
- the configurations for each of the models are given in the Benchmarking diectory. 

<!--- ## LitWD1K

<!--- #|| MRR| Hits@1| Hits@10 |
#|----------:|--------:|---------:|



<!--- ### LitWD19K
|| MRR| Hits@1| Hits@10 |
|----------:|--------:|---------:|

<!--- ### LitWD48K
|| MRR| Hits@1| Hits@10 |
|----------:|--------:|---------:|


##Citation

'''
@inproceedings{GeseseAS21,
  author       = {Genet Asefa Gesese and
                  Mehwish Alam and
                  Harald Sack},
  editor       = {Andreas Hotho and
                  Eva Blomqvist and
                  Stefan Dietze and
                  Achille Fokoue and
                  Ying Ding and
                  Payam M. Barnaghi and
                  Armin Haller and
                  Mauro Dragoni and
                  Harith Alani},
  title        = {LiterallyWikidata - {A} Benchmark for Knowledge Graph Completion Using
                  Literals},
  booktitle    = {The Semantic Web - {ISWC} 2021 - 20th International Semantic Web Conference,
                  {ISWC} 2021, Virtual Event, October 24-28, 2021, Proceedings},
  series       = {Lecture Notes in Computer Science},
  volume       = {12922},
  pages        = {511--527},
  publisher    = {Springer},
  year         = {2021},
  url          = {https://doi.org/10.1007/978-3-030-88361-4\_30},
  doi          = {10.1007/978-3-030-88361-4\_30},
}
'''

