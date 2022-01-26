### Which of these statements do you agree with regarding structured vs. unstructured data problems?
* It is generally easier for humans to label data and to apply data augmentation on unstructured data than structured data. Humans are better able to label unstructured data such as images and audio clips than complex, high-dimensional structured data. As well, it's not always possible to apply data augmentation to structured data.

### Take speech recognition. Some labelers transcribe with “...” (as in, “Um… today’s weather”) whereas others do so with commas “,”. Human-level performance (HLP) is measured according to how well one transcriber agrees with another. You work with the team and get everyone to consistently use commas “,”. What effect will this have on HLP?
* HLP will increase since the labels will be more consistent, the labelers will agree with each other more often, raising HLP.

### Take a phone visual inspection problem. Suppose even a human inspector looking at an image cannot tell if there is a scratch. If however the same inspector were to look at the phone directly (rather than an image of the phone) then they can clearly tell if there is a scratch. Your goal is to build a system that gives accurate inspection decisions for the factory (not publish a paper). What would you do?
* Try to improve their imaging (camera/lighting) system to improve the quality or clarity of the input images, x. If even a human looking at the image cannot identify the presence of a scratch, you'll need to improve the optical quality of your camera to improve your system's performance. 

### To implement the data iteration loop effectively, the key is to take all the time that’s needed to construct the right dataset first, so that all development can be done on that dataset without needing to spend time to update the data.
* False. Collecting and labelling data is an iterative process, get into the data iteration loop as quickly as possible.

### You have a data pipeline for product recommendations that (i) cleans data by removing duplicate entries and spam, (ii) makes predictions. An engineering team improves the system used for step (i). If the trained model for step (ii) remains the same, what can we confidently conclude about the performance of the overall system?
It may perform better or worse. It really depends on what changes were made and how they affect the model. However, it's also possible that the performance of the model improves.

### What is the primary goal of building a PoC (proof of concept) system?
* To check feasibility and help decide if an application is workable and worth deploying.

### MLOps tools can store meta-data to keep track of data provenance and lineage. What do the terms data provenance and lineage mean?
* Data provenance refers to where the data comes from, and data lineage the sequence of processing steps applied to it.

### You are working on phone visual inspection, where the task is to use an input image, x, to classify defects, y. You have stored meta-data for your entire ML system, such as which factory each image came from. Which of the following are reasonable uses of meta-data?
* To suggest tags or to generate insights during error analysis.
* Keeping track of data provenance and lineage. Meta-data will contain information about where the data come from and what processing steps were applied to it. This can be helpful when performing error analysis
