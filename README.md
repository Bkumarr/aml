# Objective

The idea behind this project is to implement AML (Anti Money Laundering) using big data technology stack.

In the beginning, we would basically create a tools which could verify a million names against the terrorists data based published by various security agencies and governments.

This project should be easily pluggable or modifiable to fit the need of individual organizations.

[http://www.investopedia.com/terms/a/aml.asp (More)]

It is a community project [CloudxLab.com]. Feel free to be the contributor.

## Plan

+ Get all the sources of data and clean and upload those in HDFS
+ Upload the transactions users' data in HDFS
+ Using spark compare and publish the results.

The comparision could involve either of the following algorithms:
+ Bigram
+ Phonetic

http://users.cecs.anu.edu.au/~Peter.Christen/Febrl/febrl-0.2.2/febrldoc-0.2.2/node37.html
https://www.census.gov/srd/papers/pdf/rr97-2.pdf
https://docs.oracle.com/cd/E19509-01/820-2652/ref_sme-bigram_c/index.html

