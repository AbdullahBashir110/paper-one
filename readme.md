# Need for tweet. How open-source developers use Twitter to talk about their GitHub work

Authors.
### Hongbo Fang, Daniel Klug, Hemank Lamba, James Herbsleb, Bogdan Vasilescu


## Published

### Tue 30 Jun 2020 16:00 - 16:10 at MSR:Zoom - Developer Collaboration Chair(s): Bogdan Vasilescu

## Description
Social media, especially Twitter, has always been a part of the professional lives of software developers, with prior work reporting on a diversity of usage scenarios, including sharing information, staying current, and promoting one’s work. However, previous studies of Twitter use by software developers are generally restricted to surveys or small samples, and typically lack information about activities of the study subjects (and their outcomes) on other platforms. To enable such future research, in this paper we propose a computational approach to cross-linking users on Twitter and GitHub, the dominant platform for hosting open-source development, revealing 70,428 users active on both. As a preliminary analysis of this dataset, we report on a case study of 800 tweets by open-source developers about GitHub work, combining precise automatic characterization of tweet authors in terms of their relationship to the GitHub items linked in their tweets with a deep qualitative analysis of the tweet contents.

## Link
https://cmustrudel.github.io/papers/msr20tweets.pdf


### CROSS-LINKING GITHUB AND TWITTER

This section presents our heuristic approach to cross-link GitHub
and Twitter user accounts, based on mining GitHub user profile
pages and personal blogs for explicit URLs pointing to Twitter.

### CASE STUDY: HOWGITHUB DEVELOPERS TALK ABOUT THEIRWORK ON TWITTER
As a preliminary analysis of our dataset, we perform an exploratory
case study of the content of a sample of tweets by GitHub users in
our dataset, that contain links to GitHub artifacts. As a key contribution
compared to prior work, we use the cross-links between the
two platforms to automatically characterize the relationship of the
tweet authors to the GitHub artifacts their tweets point to, and use
this information as part of our analysis.

Sample Selection. To create our case study sample, we first collected
all the tweets returned by the Twitter API for each of the
70,427 users in our dataset (max 3,200 most recent per person),
and kept the recent ones, posted between January 1, 2018 and July
1, 2019. 
### Discussion
Implications. We found that among the tweets whose authors
have an identifiable relationship to the repository (i.e., non-Other),
most are posted by the repository owner and only a few are posted
by followers. This suggests that people engaged in the development
of the repository post most of the tweets linking back to GitHub.

## Research 
Cross-linking data across online platforms where open source developers
participate (in this paper GitHub and Twitter) is feasible
and it can help provide deeper insights into how the activities of
developers on one platform are moderated by the roles they play
on the other. 