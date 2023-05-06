# Datasets

Data used in Prototype1.


# Dataset SLMHM_Education_SmplRel_01 

File: SLMHM_Education_SmplRel_01.csv
Content: Education Related Messages Ranked according to SLMHM Model.

Simple Learning Mootivations Hierarchy Model (SLMHM) was created to be used in modeling and analyzing education processes. Main part of the dataset was built on the base of text phrases from the Internet messages collected by requests "Problems of education" and "News of education". The phrases are assessed to the SLMHM levels. Determination of the SLMHM levels allows us to evaluate the education processes and plan steps for their improvement.

It is the first attempt to automate SLMHM in education. The aim of the dataset is to demonstrate the ability to evaluate the education processes by means of trained AI models. It does not aim to be used in actual applications. It can also be used as an exercise in learning.

The dataset contains 420 records. Columns have the following meanings:
Id - Unique Identifier;
Case - Case according to the basic article (see link below);
Year - Year of publication of the message;
Message - The message text;
kw01-kw16 - Keywords, that could be useful to determine the level;
r01-r16 - Level. 0 - no presence. 100 - full presence. More than one level can correspond to the message;
Remarks - Remarks on why the specific level was assigned.

The data were prepared according to the following study: "Education Development Strategy on Base of the Analysis of Messages in the Russian-Speaking Segment of the Internet using SLMHM Model" (https://doi.org/10.35542/osf.io/cnh6q)

Proposed actions:
* Analyse by means of the basic statistics;
* Analyse bias;
* Build and trains AI models. 

