# Detecting-Fraudulent-Users-In-StackOverflow
This is a project for the course work Social Media Mining. This project aims to find fradulent users in Stack Overflow.

Stackoverflow is an on-line community of users who are involved in questioning and answering on a wide range of topics in computer programming. The trustworthiness or importance of a person is mostly based on the reputation(i.e. points). Each member earns additional reputation for posting quality questions or answers or both. The reputation might get deducted sometimes. The deduction happens often when the other people in the community find that the question or answer posted by a user is non-relevant or does not meet the stackoverflow quality.

Since the reputation of each person is determined by other users in the community, this creates a loophole for fraudulent activity. If a person 'X' hates user 'Y', all user 'X' needs to do is to go to every question or answer posted by user 'Y' and down-vote it(i.e. mark it as non-relevant). This might decrease user 'Y' reputation severely and thus decreasing his importance. On the contrary, if user 'X' likes user 'Y', user 'X' can actually up-vote all questions and answers posted by user 'Y' and increase user 'Y' reputation. Such users usually post unrelated answers or comments randomly on some other people useful questions or answers or comments. There might be a group of users who are involved in such kind of activity. Their victim might be a single user or a group of users. I call them fraudulent users and I am interested in finding out group/s of users involved in such activity.

DataSet used - http://snap.stanford.edu/data/sx-stackoverflow.txt.gz

