# Online-Sexism-Detection
NLP Project

Group Members:
Abhliash Datta - 19CS30001 /br
Sunanda Mandal - 19CS10060 /br
Rohit Raj - 19CS10049 /br
Haasita Pinnepu - 19CS30021 /br
Vishnu Vardhan - 18CS30022 /br

Online sexism has become a significant challenge. Today, sexist content may be found and evaluated at scale using automated technologies, but most of these tools just classify information into broad categories without providing any extra information. This project supports the development of more accurate and comprehensible English-language sexism detection models by providing fine-grained classifications for sexist content.

The project contains three hierarchical subtasks:

TASK A - Binary Sexism Detection: A two-class (or binary) classification where systems have to predict whether a post is sexist or not sexist. We used “DistilBert-Uncased” for the classification task. Obtained F1-score of 0.6567 and Accuracy_score of 0.85.

TASK B - Category of Sexism: For posts which are sexist, a four-class classification where systems have to predict one of four categories: (1) threats, (2)  derogation, (3) animosity, (4) prejudiced discussion. Used the RoBERTa base model. Obtained F1-score of 0.5846 and Accuracy_score of 0.5906.

TASK C - Fine-grained Vector of Sexism: For posts which are sexist, an 11-class classification where systems have to predict one of 11 fine-grained vectors. We now classify each of the 4 categories of sexism into their respective subcategories. Used the RoBERTa base model. Obtained F1-score of 0.7363 and Accuracy_score of 0.8181.


The dataset has 4 columns, the text, it’s label_sexist, the label_category and the label_vector.
