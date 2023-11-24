# Analysis of the Degree of American-focus in Reddit and its Changes from COVID

## Abstract

Reddit is an American social media platform, that has communities (subreddits) tailored towards topics focused on other nations, with a considerable number of users being members of these other subreddits. We aim to find out how much of a focus Reddit has on American users, topics, and content, and whether the impact COVID had on Reddit, was largely driven by the impact COVID had on Americans rather than the world as a whole. This can give insight on other analyses of Reddit, and how applicable their conclusions are to the world, compared to just Americans.



## Research Questions

- How American-focused is Reddit's content?
- Is there a difference between the change in behavior as a result of COVID, between Americans and non-Americans?



## Additional datasets

- "Quantifying social organization and political polarization in online platforms."[1] has a Word2Vec embedding of subreddits. Provided with it is a way to generate dimensions on which subreddits can be placed, to indicate their closeness towards given seed values. We can use this provided system and attempt other classification methods to determine how much each subreddit of the Pushshift Reddit datasets, are focused on the U.S.



## Methods

### Exploratory analyses

- Generating potential dimensions from Word2Vec embedding of subreddits based on user comments

### Statistical summaries

- Median of metrics (such as user post count), split between American and non-Americans
- Proportions of users being American for various tasks (such as sign ups)

### Modelling approaches

- Word2Vec
- Clustering in Word2Vec embeddings of subreddits

### Visualization techniques

- Line charts, such as 1 for each topic against time
- log odds ratio of words used, pre- and post-COVID



## References

[1] Waller, I., Anderson, A. Quantifying social organization and political polarization in online platforms. Nature 600, 264–268 (2021). https://doi.org/10.1038/s41586-021-04167-x
Github: https://github.com/CSSLab/social-dimensions
[2] Knight, K. (2022, October 24). Why Movies Set in Seattle Are Filmed in Canada, and How the City Wants to Change That. MovieWeb. https://movieweb.com/why-are-films-set-in-seattle-filmed-in-canada/
[3] Veselovsky V., Anderson, A. Reddit in the Time of COVID. ICWSM 2023. https://www.cs.utoronto.ca/~ashton/pubs/reddit-covid-icwsm23.pdf

