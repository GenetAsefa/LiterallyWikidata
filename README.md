# LiterallyWikidata 
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


## Benchmarking

- Experiments have been done with three models **DistMult**, **ComplEx**, and **DistMultLiteral** on all datasets using **Pykeen**.  





