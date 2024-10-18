## Topic :
I have explored 7 most known youtubers with in the same niche (Data Analytics, Data Science, Data Engineering, etc..). We are going to see how much subs they have individually and their number of views. We will also see that if those numbers are directly translate to revenue amount for those content makers?

## Dataset :
The dataset i am using is youtube’s API for each individuals. It has 328 rows and 6 column which includes Title of the videos, statistics (means: number of subscribers count, view counts, likes, comments and upload date).


## Hypotheses :
Dose having more subscribers on youtube have benefits than having more views? In the sense of getting more revenue, comments or likes?

## Cleaning Process :
The data dose not need much cleaning but rather, i have Identified critical fields and avoided unwanted columns because they don’t bring any value for my research. 

- I have made a change on data types for numerical data’s. (to Int and DateTime)
- I have sorted data’s for comparison purpose.
- I have checked if there is any duplicated or null values.
- I have controlled if there are poor naming on the column but it was all good. 

## Challenges :
The data it self is almost clean to deal with but other than that, there are few challenges like:
- Difficulty understanding complex youtube API documentations. 
- Authentication and authorization.
- Facing countless syntax errors on Jupiter note book and trying to debug those errors.
- Time consuming.

## Methods used and solutions :
- To understand the complexity of the Api documentation, i try to research how other people in the online community dealing with a specific problem and learn from them and apply. So Google becomes your best friend.
 
- For the Authentication and authorization, just Pay attention to your daily limit for sending API requesting. Otherwise if you run that API request multiple times, you will face authorization problem and suddenly you will get errors in side you code. 

- When i run in to this kind problems, I try to stay calm and wait the next day to get API access. But in the mean time, to use my time effectively while waiting, i have used some time management tool like a Kanban board software / browser. With that, i was able to monitor my progress with the dead line in mind. That helps me accomplish important tasks for the project like preparing documentations, presentation slides, etc. Basically, while i was waiting my new quota for the day, i was doing something that dosen’t need API or Jupyter note book.

## Insights and patterns discovered :

According to my findings, from all 7 youtube channels listed, Corey Schafer has the most Subscribers with more than a million subs. ( 1.370,000 ) to be exact. And his total views from his 239 videos is 98.362,676.

Alex The Analyst in the other hand has ( 885,000 ) subs and the number of videos uploaded is about 327. Those videos have got 40,718,278 views

## Major Obstacle :
I have hard time understanding why my note book dose not responding immediately after executing a command. A code working in one day gives you a bunch of errors in another day. I literally was finished my data retrieving very early but then i have to deal with it until the last moment.

The lesson i have learned not to fall under this kind of problem is to have clean code and avoid unnecessary codes. It is as simple as that.

## Conclusions & Insights :
### Hypotheses Results :
Depending on how you are getting your earnings. In my opinion, views are all that matters. If you earn money only on ad revenue then views are important. You don't get paid for subscriptions amount unless they also watch your videos. Subscribers typically do that, so they drive views higher, but subs don't account for any payment by themselves.

The only thing subscribers really help with is if you have more of them it will do two things, you will have a quicker view count and people to share your video on other platforms. Both of these things help your SEO and as a result your view count as well.
### Main Takeaway :
If you aren’t just looking to cash in with ads then subscribers have more weight, especially subs who are highly devoted to you and engaged in your content. With these kinds of subs you have a better chance of getting pledges on patreon for more consistent revenue. They also will be more inclined to buy merchandise you make or products you decide to sell or promote with sponsorship. 

Otherwise Views are the money making in my opinion

### Unanswered questions :

I have no proof to support my hypotheses. I could not find revenue information based on their number of subscribers or views.






