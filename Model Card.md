## About

>The data was extracted from the 1994 Census bureau database by Ronny Kohavi and Barry Becker (Data Mining and Visualization, Silicon Graphics). Records were extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1) && (HRSWK>0)). The objective is to classify a surveyed member of the census for income above $50K.


| Feature | Type | Description |
| ------  | ---- | ----------- |
| **income** | **Output** | Binary classification <50k or >=50k |
| age     | Input| Age of the census participant |
| workclass     |  Input| Professional affiliation          |
| education     |  Input| Highest level of education          |
| marital status     | Input| Single, married, or divorced           |
| occupation     | Input| Primary profession           |
| relationship     | Input| The participant's role as a member of a family     |
| race     | Input| Racial category           |
| gender     | Input| Gender           |
| capital gain     | Input| Net capital gain           |
| capital loss     | Input| Net capital loss           |
| hours per week     | Input| Employment hours           |
| native country     | Input| Country of birth or citizenship           |
    

### Relevant research
Ron Kohavi, [Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid](http://robotics.stanford.edu/~ronnyk/nbtree.pdf), Proceedings of the Second International Conference on Knowledge Discovery and Data Mining, 1996. (PDF)

## Model Checklist

- [ ] MLFlow experiment with logged parameters
- [ ] MLFlow experiment with model quality metrics
- [ ] Published error analysis
- [ ] Risk analysis report published
- [ ] 1st and 2nd LoD reviews completed

## Model Performance & Analysis

[Responsible AI Dashboard](https://rev4demo12597.product-team-sandbox.domino.tech/modelproducts/6461635126cd6979a0457257)

![Performance Metrics Table](https://github.com/vsridhar-ddl/Rev4Chapter3/blob/main/Accuracy%20Scores.png)

### Probability Distributions
![Probability Distribution](https://github.com/vsridhar-ddl/Rev4Chapter3/blob/main/Census%20Data%20Prob%20Distribution.png)

### Feature importances
![Feature Importances](https://github.com/vsridhar-ddl/Rev4Chapter3/blob/main/Income%20Pred%20Feature%20Importance.png)