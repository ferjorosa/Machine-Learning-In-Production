### You’ve built a new system for making loan approval decisions. For now, its output is not used in any decision making process, and a human loan officer is solely responsible for deciding what loans to approve. But the system’s output is logged for analysis. What is this type of deployment called?
* Shadow mode deployment. It is a type of deployment where the ML algorithm runs in parallel with the user but it’s output isn’t used for any decision making.

### On a new social media platform, you’re rolling out a new anti-spam system to flag and hide spammy posts. Your team decides to roll out the anti-spam filter via a canary deployment, and roll it out to 1% of users initially. Which of these would you advocate?
* Monitor that 1% of users’ reaction, and either gradually ramp up (if it’s going well) or rollback (if not)

A canary deployment allows you to monitor the performance of an algorithm on a subset of all traffic and then either ramp up to more traffic or rollback if an issue is detected.

### You’re building a healthcare screening system, where you input a patient’s symptoms, and for the easy cases (such as an obvious case of the common cold) the system will give a recommendation directly, and for the harder cases it will pass the case on to a team of in-house doctors who will form their own diagnosis independently. What degree of automation are you implementing in this example for patient care? 

* Partial automation. This type of approach offers some automation, but still requires a human in the loop

### You have built and deployed an anti-spam system that inputs an email and outputs either 0 or 1 based on whether the email is spam. Which of these will result in either concept drift or data drift?

* Spammers trying to change the wording used in emails to get around your spam filter.
* Cloud computational costs going down, resulting in a lower cost to process each email received.
* Updating a monitoring dashboard to keep track of new metrics.
* None of these will result in either concept drift or data drift.

The **first one**: spammers trying to change the wording.

### Accurate description of deployment?
* It is an iterative process, where you should expect to make multiple adjustments (such as metrics monitored using dashboards or percentage of traffic served) to work towards optimizing the system.

Don't plan or expect to perfect the deployment on your first attempt, it's much more reasonable and efficient to iterate on the process and optimize its performance over time. 