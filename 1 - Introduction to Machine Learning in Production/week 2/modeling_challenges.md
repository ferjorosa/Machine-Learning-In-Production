### You are working on a binary classification ML algorithm that detects whether a patient has a specific disease. In your dataset, 98% of the training examples (patients) don’t have the disease, so the dataset is very skewed. Accuracy on both positive and negative classes is important. You read a research paper claiming to have developed a system that achieves 95% on ____ metric. What metric would give you the most confidence they’ve built a useful and non-trivial system? (Select one) 
* F1 score is recommended on skewed datasets, as it combines precision and recall into one metric.

### On the previous problem above with 98% negative examples, if your algorithm is print(“1”) (i.e., it says everyone has the disease). Which of these statements is true?
* The algorithm achieves 100% recall. Since it would classify everyone as having the disease and therefore not have any False Negatives. Remember, recall is the number of True Positives / (True Positives + False Negatives).

### True or False? During error analysis, each example should only be assigned one tag. For example, in a speech recognition application you may have the tags: “car noise”, “people noise” and “low bandwidth”. If you encounter an example with both car noise and low bandwidth audio, you should use your judgement to assign just one of these two tags rather than apply both tags. 
* False. Each example should have as many tags as is necessary to accurately classify it. This will help you develop an accurate understanding of where your errors are coming from, which will in turn help you focus your efforts in reducing the errors.

### You’re considering applying data augmentation to a phone visual inspection problem. Which of the following statements are true about data augmentation? (Select all that apply)
* GANs can be used for data augmentation. 
* Data augmentation should try to generate more examples in the parts of the input space where you’d like to see improvement in the algorithm’s performance. 
* 