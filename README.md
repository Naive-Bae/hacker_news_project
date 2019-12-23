
# Hacker News Project
What type of Hacker News posts are most likely to generate user interaction?

## Predicting Community Engagement for Hacker News Posts
This project will look at a sampling of approx. 20,000 user posts to the Hacker News online forum (dataset available here).

The data set includes the following:

`id` (Hacker News's unique comment ID number)  
`title` (post's title)  
`url` (url that the post links to)  
`num_points` (number of upvotes post received minus number of downvotes post received)  
`num_comments` (number of user comments on post)  
`author` (name of post's author)  
`created_at` (date and time of post - in %-m/%-d/%Y %-H:%M format)  
  
Specifically, the project will examine two primary classes of posts: those whose titles begin with either Ask HN or Show HN.  
  
"Ask HN" are posts to ask the Hacker News community a specific question.  
  
"Show HN" are posts to show the Hacker News community a project, product, or just generally something interesting.  
  
We'll compare these two categories of posts to deterimine the following:  
  
Do Ask HN or Show HN posts receive more comments on average?  
Do posts created at a certain time receive more comments on average?  
Do Ask HN or Show HN posts receive more points on average?  
Do posts created at a certain time receive more points on average?  

## Findings  

From our analysis, we have seen that:

- Ask posts are more likely to receive comments than Show posts.
- Ask posts are most likely to receive comments during the hour of 15:00 (UTC -5).
- Show posts are more likely to receive points than Ask posts.
- Show posts are most likely to receive points during the hour of 23:00 (UTC -5).

More broadly, we can also see by looking at the top five most active hours (for both Ask post comments and Show post points) that the times span from noon to 2:00 a.m., but that the greatest community engagement generally occurs in two time pockets: 3:00-6:00 p.m. and 8:00 p.m. to midnight. There are no daytime morning hours in the top 10.
