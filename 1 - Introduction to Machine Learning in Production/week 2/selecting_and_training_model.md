### Which of these is a more accurate description of a data-centric approach to ML development?
* Holding the training data fixed, work to improve your neural network’s architecture to do well on the problem.
* Holding the neural network architecture fixed, work to improve the data to do well on the problem.

The **second one**. Data-centric means you focus your efforts on improving the data to raise the system's performance, while keeping the code fixed. 

### Say you have an algorithm that diagnoses illnesses from medical X-rays, and achieves high average test set accuracy. What can you now say with high confidence about this algorithm?
* High average test set accuracy is a great achievement, but there is more work to be done to ensure the algorithm works well on real-world data, is fair, and performs well on rare classes of diseases.

### Establishing a baseline
* You can establish a baseline using an older system or via a literature or open source search.
* Human level performance (HLP) is generally more effective for establishing a baseline on unstructured data problems (such as images and audio) than structured data problems
* For unstructured data problems, using human-level performance as the baseline can give an estimate of the irreducible error/Bayes error and what performance is reasonable to achiev

### On a speech recognition problem, say you run the sanity-check test of trying to overfit a single training example. You pick a clearly articulated clip of someone saying “Today’s weather”, and the algorithm fails to fit even this single audio clip, and outputs “______”. What should you do?
* Debug the code/algorithm/hyperparameters to make it pass this sanity-check test first, before moving to larger datasets. Something is clearly wrong with the implementation if the algorithm is unable to overfit to a single training example! Find the root cause, fix the problem, and then move onto larger datasets. 
