# Hackathons

This repository contatins presentations and my codes from the hackathones in which I participated.  
For now it's the following list:

1) [GeneHack 2020](https://nrckigc.ru/genehack) 
2) [AgroCode 2020](https://agro-code.ru/)

## [GeneHack 2020](https://nrckigc.ru/genehack)
### 1st Place (OMG team)
**_GenHack is an online team hackathon for bioinformatics analysis, text and image processing for the development of genetic technologies and molecular biology, provided by [National Research Center «Kurchatov Institute»](http://eng.nrcki.ru/)._**


We proposed a solution for prediction of [phi29-polimerase](https://en.wikipedia.org/wiki/%CE%A629_DNA_polymerase) activity for sequencies of bacterial genomes. 
Our programm takes [CDS](https://en.wikipedia.org/wiki/Coding_region) from bacterial genomes and predict the probobility for such sequence to have phi-29 polymerase activity. 

The algotithm first filter sequences with the use of HMM, to find CDSs, which contain DNA-polimerase B motifs. After that ML-based part predict the probability of this sequence to exhibit phi29-activity based on the presence of key amino-acids in phi-29 protein structure. These key amino-acides we found in literature or discover by ourselfs using structural-alignment of phi-29 known structures and programs, which detect conservative, coevolutionary, specific amino-acids in proteins. 

The full description of the solution is avaliable in the presentation of the progect in this repository as well as the notebook with catboost model training and validadion. 

## [AgroCode 2020](https://agro-code.ru/)
### Participation (Albatross flight team)
**_Agro Hack is a hackathon for solving technological [problems of the russion agroindustry](https://agro-code.ru/#agro-hack) proposed by actual companies._**

We made a web-service for finding an [optimal fertilizer supplier](https://agro-code.ru/task/provider). We constracted a database of fertilizer offers based on websites of large suppliers and offers from local suppliers from telegram channels. Our web-service provides an oportunity to filter fertilizers by acting compound, price, location and suppliers names. And we also developed a ranging algorithm based on stock availability, quality of the offer, location and price. 

The code for telegram channels parsing and presentation with full project description is avaliable in this repository. 



