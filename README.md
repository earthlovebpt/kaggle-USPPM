# kaggle-USPPM
### U.S. Patent Phrase to Phrase Matching  
Help Identify Similar Phrases in U.S. Patents

### Describe
In this competition, you will train your models on a novel semantic similarity dataset to extract relevant information by matching key phrases in patent documents. Determining the semantic similarity between phrases is critically important during the patent search and examination process to determine if an invention has been described before. For example, if one invention claims "television set" and a prior publication describes "TV set", a model would ideally recognize these are the same and assist a patent attorney or examiner in retrieving relevant documents. This extends beyond paraphrase identification; if one invention claims a "strong material" and another uses "steel", that may also be a match. What counts as a "strong material" varies per domain (it may be steel in one domain and ripstop fabric in another, but you wouldn't want your parachute made of steel). We have included the Cooperative Patent Classification as the technical domain context as an additional feature to help you disambiguate these situations.

Can you build a model to match phrases in order to extract contextual information, thereby helping the patent community connect the dots between millions of patent documents?

### Dataset
In this dataset, you are presented pairs of phrases (an <code>anchor</code> and a <code>target</code> phrase) and asked to rate how similar they are on a scale from 0 (not at all similar) to 1 (identical in meaning).  
[Download kaggle dataset](https://www.kaggle.com/competitions/us-patent-phrase-to-phrase-matching)  
[Download additional dataset](https://www.kaggle.com/datasets/xhlulu/cpc-codes)

### Evaluation
Submissions are evaluated on the **Pearson correlation coefficient** between the predicted and actual similarity scores.  

### Result
|model| cv | public-score |private-score|
|---|---|---|---|
|xxx|xxx|xxx|xxx|
|xxx|xxx|xxx|xxx|
|xxx|xxx|xxx|xxx|

