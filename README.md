 # Exploring Hacker News Posts

[Hacker News](https://news.ycombinator.com/), a site popular among technology and startup circles, was started by the startup incubator, `Y Combinator` where posts submitted by users are voted and commented upon. Posts that make it to the top of Hacker News' listings can get hundreds of thousands of visits as a result.

In this project, we will explore two types of posts from the Hacker News site.That is,posts whose titles either begin with `Ask HN` or `Show HN`. Users submit `Ask HN` posts to ask the Hacker News community a specific question or submit `Show HN` posts to show the Hacker News community a project, product or just something interesting.

In comparison to these two types of posts, we determine :

- Which of the two receive more comments on average?
- Do posts created at a certain time receive more comments on average?

It should be noted that the dataset has been reduced from 300,000 rows to approximately 20,000 rows by removing all submissions that did not receive any comments, then randomly sampling from the remaining submissions.
