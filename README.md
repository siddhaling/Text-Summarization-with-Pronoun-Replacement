# Text-Summarization-with-Pronoun-Replacement
This is the python program which performs text summarization with pronoun replacement method. This method initially identifies pronouns in the text and replaces them with nearest proper noun. With the help of replacement, frequency of proper nouns will increase thereby improving the quality of the summarization.

![alt text](https://github.com/siddhaling/Text-Summarization-with-Pronoun-Replacement/blob/master/fig.jpg)

### Preprocessing 

The input text file is read and initial preprocessing is carried out such as tokenization and removing stop words. Then each word is tagged using nltk tagger.
### Pronoun Replacement

The pronouns are place holders for proper nouns. The words which are tagged as pronouns are replaced by nearest proper noun. This replacement increases the frequency of proper noun.

### Weight computing for words and sentences

Based on the frequency of words the weight of words is computed. The weightage for a sentence is the summation of weightage each word present in that sentence.

### Summary formation

All the sentences are assigned a priority value depending on their weightage. The summary is formed based on the user-specified ratio by extracting higher priority sentences from the original text.

# Research Paper

This method and results are published in papers:

(https://ieeexplore.ieee.org/document/8256947)

(https://ieeexplore.ieee.org/document/8308170)
# Cite this work

Please cite as 

Siddhaling Urolagin, Jagadish Nayak, Likitha Satish, “A Method to Generate Text Summary by Accounting Pronoun Frequency for Keywords Weightage Computation”, in IEEE, Scopus Indexed, The International Conference on Engineering and Technology, Turkey August 21-23, 2017.

Siddhaling Urolagin, Likitha Satish “Improving the Quality of Text Summarization using Pronoun Replacement Technique”, in IEEE International conference on Recent Trends in Electronics Information and Communication Technology, Bangalore, pp. 1991-1995, India, 2017.

# Further Projects and Contact

For further reading and other projects please visit

www.researchreader.com

siddesh_u@yahoo.com


