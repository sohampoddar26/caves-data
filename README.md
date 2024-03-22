# Concerns About Vaccines with Explanations and Summaries (CAVES)

This repository contains the datasets, corresponding to the paper titled "CAVES: A Dataset to facilitate Explainable Classification and Summarization of Concerns towards COVID Vaccines", which was accepted at **ACM SIGIR 2022 (Resource Track)**. 
A preprint version is available on: [arXiv](https://arxiv.org/abs/2204.13746 "arXiv").

*NOTE: The dataset was updated since the publication of the paper, details have been updated in the preprint version*


## Data Description
The "gold_summaries" folder contains summaries of each of the classes by 3 different annotators.
The "labelled_tweets" folder contains the labels and tweet IDs in standard CSV format, and the label-explanation tuples in standard JSON format. The "start" and "end" indices in the explanations represent the index of the corresponding tokens in the text when split just by whitespaces.

For example, for a start and end index of 2 and 6, the explanation for the tweet: *"They are making huge $$$ profits ! won't take it!"* will be *"making huge $$$ profits"*.

For queries please mail me at: [Email ID](mailto:sohampoddar@kgpian.iitkgp.ac.in) 


If you use our data, please cite the following paper:
```
@inproceedings{poddar2022caves,
  title={CAVES: A dataset to facilitate Explainable Classification and Summarization of Concerns towards COVID Vaccines},
  author={Poddar, Soham and Samad, Azlaan Mustafa and Mukherjee, Rajdeep and Ganguly, Niloy and Ghosh, Saptarshi},
  booktitle={Proceedings of the 45th International ACM SIGIR Conference on Research and Development in Information Retrieval},
  year={2022}
}
```

## Classification Models on the Dataset
- **MuLX-QA** is method that identifies multiple label-explanation tuples from social media posts. This method was accepted for the ACM Transactions on the Web (TWEB) Journal in 2024. 
[Link to paper](https://dl.acm.org/doi/10.1145/3653303) [Link to Github](https://github.com/sohampoddar26/MuLX-QA)

