Data Science Resources
================================  

From my experience the most important areas to excel on data science projects are:  

1. Communication & Clarity  
2. Prototyping/Data Exploration  
3. Scaling Up Prototypes  

I would say if you get #1 & #2 right than everything else will fall into place. 
Below I've detailed some resources for helping to develop these skills. 
Its important to note that most of these just require focused effort and practice. 
I personally find that #1 is the most difficult to improve but the most important.  

## 1 - Communication & Clarity  

As discussed above, this is probably the most important but the most difficult to improve. 
The most important here is practice, for this I would reccomend just writing about things you are interested in. 
A blog could be a good place to start (doesn't have to be public) or there are some internal Accenture magazines you could look to contribute to.
The key here is to find a way to get feedback.   

### Resources  

I don't have a lot of resources here but I have heard that the following books are great references:  

1. [Style: Lessons in Clarity and Grace](http://amzn.com/0321898680) is the go to for written communication (It's on my personal list)  
2. [Made to Stick](http://amzn.com/1400064287) I've heard is great for presentation form  
3. [The Pyramid Principle](http://amzn.com/0960191038) is another classic that helps put a framework around writing and communication  

Additionally, the following coursera courses are very useful (And quick)  

1. [Reproducible Research](https://www.coursera.org/learn/reproducible-research) is great for thinking about problems in a reproducable way  
2. [Developing Data Products](https://www.coursera.org/learn/data-products) is great for learning actual tools such as shiny  

Some other resources that may be quicker and are also useful are:  

1. Anything written by Hadley Wickham. [Reproducable Example](http://adv-r.had.co.nz/Reproducibility.html) is a good read that has a corresponding stack overflow post  
2. Github Readmes - When writing a readme or tutorial, I usually just look back through those of popular projects and use it as a starting point for brainstorming    

The last point I'd like to add on communication is that practicing and structuring things also can be a helpful way to guide research and discovery.  

## 2 - Prototyping & Data Exploration  

This can be the most interesting part of any project and one of the most important. I would recommend getting either really good in either R or Python and then atleast conversant in the other. 
Additionally, I think SQL is also quite invaluable to learn as well (See note below on Hive). I unfortunately don't know a great resource for learning SQL other than hands on. 
Its only a personal opinion but I prefer R for exploratory work as it required less work to get up and going and plotting.  

For R I would recommend learning getting really familiar with the Hadley tools:  

1. ggplot2  
    * [Exploratory Data Analysis](https://www.coursera.org/learn/exploratory-data-analysis) is a great coursera course for learning r plotting.  
2. plyr & dplyr  
    * [Getting & Cleaning Data](https://www.coursera.org/learn/data-cleaning) is a great coursera course for learning R data manipulation.  
4. The devtools suite  
    * See Hadley's book on R packages  

## 3 - Scaling Up/Architecture  

Here it is tough to predict the future as to what the tools available will be, but I think most important is to understand the fundamentals and then the basics of the popular tools. 
I would spend some time getting familiar with the following:  

1. HDFS & Map Reduce - I would spend some time trying to get a cluster running in local and pseudo distributed mode. I would then also work through the examples of compiling java map reduce jobs. Yes, you won't be doing this in production most likely... But learning the fundamentals is important.  
    * Bonus Points - Attempt to get a cluster running in distributed mode on AWS (Remember to tear it down!)  
2. Hive - Hive is a workhorse in terms of relational data processing on hadoop and I see it only getting more popular (or Impala). Learning how it works both architecturally as well as being able to tactically write scripts would be time well spent.  
    * Bonus Points - Get it running on the same Hadoop cluster that was previously set up
3. Spark - This seems to be the direction most of the on cluster data processing is going. Spark itself isn't all that complicated, so I would focus more on the point below.   
4. Functional Programming -  I would recommend using Scala to learn functional programming as its what you'd write Spark code in. More importantly, I think forcing yourself to think in a functional way and to practice writing code in that manner is very worthwhile. I've listed a couple resources below for this:  
    *[Functional Programming Principles in Scala](https://www.coursera.org/course/progfun) - This is taught by the creator of Scala and you can work through the content at any time.  
    *[Functional Programming in Scala](http://amzn.com/1617290653) - I found this book a much more thorough deepdive into the understanding of functional programming. I haven't worked through much but I reccomend it as a companion to the Coursera course.


