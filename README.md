# NTU Chinese Causal Corpus
# Introduction
A Chinese causal corpus containing 1,314 pairs of arguments based on the [Chinese Discourse Treebank (CDTB)](https://aclanthology.org/D14-1224/) by Li et al. (2014).

# Format
Each line is an instance consists of seven columns separated by tabs:
DOC_ID: The name of the CDTB document.
Sentence_ID: Number of the sentence in the document.
Causal directionality: Reason-Effect or Effect-Reason
Causal type: Purpose, Background, Hypothetical, Inference, Condition, or Cause-Result
Explicity/Implicity: Explicity or Implicity
Tense of Argument 1: Past, Present, or Future
Tense of Argument 2: Past, Present, or Future
# Example
As the example shown as follows, this line denotes the causal information of the 14th sentence in the document 001.xml from CDTB. The discourse relation of this sentence is Purpose (Explicit), and the causal direction of this sentence is Reason-Effect. The tenses of its first and second arguments are Present and Past, respectively.
<sub>
001.xml 14 Reason-Effect Purpose Explicit Present Past
</sub>
# Download
Click [here](http://nlg.csie.ntu.edu.tw/nlpresource/chinese_causality/chinese_tense.txt) to download data.

# How to Cite this resource
Please cite the following paper when referring to our corpus in academic publications and papers.

<sub>
Hen-Hsen Huang, Chang-Rui Yang, and Hsin-Hsi Chen. 2016. Chinese Tense Labelling and Causal Analysis. In Proceedings of the 26th International Conference on Computational Linguistics (COLING 2016), December 11-16, 2016, Osaka, Japan.
</sub>
