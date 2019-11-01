# Progress
- [X] Create a framework
- [X] Value stream
- [X] Metrics
- [X] Create introduction
- [X] Create Symptoms
  - [X] Perception of slowness
  - [X] Lack of or no collaboration
  - [X] There is nothing to show during the sprint review
- [X] Context switching
- [X] Research the research on context switching
- [X] Solutions
- [X] Ending
- [X] Add images
- [ ] Check with grammarly
- [X] Editing - second iteration on each section
- [ ] Review
- [ ] Fix comments
- [ ] Come up with the title and subtitles
- [ ] Consider SEO
- [ ] Move it to wordpress and publish
- [ ] Distribute via social media, etc.
- [ ] Celebrate
- [ ] Measure # of views every day, drink if it is high :), drink if it is low :(


# How to assess your team focus / Focused team is a happy team / Driving engagement by creating focus
## Deliver value faster
There are several recurring wishes our clients bring to us, one of which is speed. However, there is no dial that we can turn to deliver value faster. Software teams are not like cars; there's no acceleration pedal. Even if we try to speed up by adding more resources, in many cases, the actual bottleneck will just become more apparent.

In our search for increased delivery of value, we hunt for these bottlenecks. No two contexts are the same, and for this story, we have a particular context in mind. Symptoms in different organizations are often similar, and our story might apply to your setting if you recognize the problems we encountered.

## Symptoms
As doctors, we always start by observing the symptoms of the problem at hand. There might be numerous symptoms of slowness one can notice in an organization, we would like to bring your attention to three we encountered:
 1. Perception of slowness
 2. Lack of collaboration
 3. Team has nothing to present
  
### Perception of slowness
Speed is a new currency. If you are fast, chances are you are going to be the first on the market with that new exciting feature. It is not about being better; it is about getting there first. Everyone is consumed by what's new. Few people are interested in what's better.

Therefore, the lack of speed is noticed quite quickly. While competitors are already delivering features that are on your future roadmap, you still struggle to answer what value was added to your product last quarter or even last year. 

### Lack of collaboration
Collaboration is the action of working with someone to produce something. In working together, there is an exchange of ideas; new and enhanced ideas are born. It allows you to deliver the best designs and the best software. Collaboration is a source of creativity and innovation; it promotes healthy employee relationships. It also creates a faster feedback loop and allows issues to be found and resolved earlier in the process.

At the heart of collaboration is communication. Look at how people around you communicate, do they prefer face-to-face communication, or are email and slack their goto options? Do you see people working on one computer? Do they look like a team?

There are many reasons why people don't collaborate. They don't see the benefits of it, are afraid of being wrong and therefore vulnerable, don't trust their teammates, or they've tried before only to have their opinion ignored. Or maybe there is nothing to collaborate on?

### Team has nothing to present
As a coach, I like to use the spring review as a vantage point to do observations. Do the sprint review meetings happen regularly? Do the teams have something to review? Do you feel like there is continuous progress? Perhaps you catch yourself wondering what the teams have been doing the entire sprint as they have very little or nothing to review. 


> "If you can't measure it, you can't improve it." 
> - Peter Drucker


## Value stream
The symptoms we observe are a good starting point for change. We now want to support these observations with data. One way to examine your development process is to [create a value stream map or VSM](https://xebia.com/blog/how-to-create-a-value-stream-map/). It is an inventory of all the activities that happen before a piece of software hits production. You also want to know how much time each activity takes. Make sure to record all the waiting times, such as waiting for code review, waiting for approval(s), waiting for deploy, etc.  Once you have that, you can put them in two buckets: value-adding and non-value adding activities or, in other words, waste. It is quite intuitive that activities such as writing code, writing tests, and reviewing the code, are considered as value-adding while all kinds of waits belong to waste. 

Here is the visualization of our VSM and how it changed over time as we tweaked the process.
![VSM](images/VSM.png?raw=true "Value Stream Map")

By performing this exercise, you will identify the waste in your process, and it will become clear what parts of it need change. Of course, you still don't know what work items are valuable by themselves. For that, you need another metric.

## Metrics
#### 1. Value-adding vs non-value adding product backlog items
By building a value stream map and eliminating waste, you can speed up your processes. We would like to offer you a similar exercise only performed not against activities, but your backlog items. This exercise can give you insight into the speed of your value delivery. 

Put all the completed work into two buckets: value-adding and non-value adding. We chose to mark new features as value-adding and add bugs and technical debt items to the non-value adding bucket. Both are important; we need to add new value while maintaining the existing value of our products. 

![Distribution of tickets](images/value-adding-vs-non-value-adding.png?raw=true "Value-adding vs non-value adding PBIs")

Once you have a distribution of work, e.g. the ratio between value-adding and non-value adding items, you can drill down on each of them and get even more insights. It could be that you have a lot of bugs, and there is a quality problem, or perhaps, it is a tech debt that's holding you back and doesn't allow extending the product. Having a lot of non-value adding work might create a perception of slowness in the eyes of the stakeholders.

#### 2. Speed of the feature(s) (items per day)
As a next step, we decided to look further into the value-adding bucket. We used features as value-adding work. For each feature, we identified the duration (in days) and the number of work items completed within that period. By dividing the number of completed tickets by duration, we calculated the speed of feature delivery.

![Epic delivery speed](images/delivery-speed.png?raw=true "Epic delivery speed")

For comparison, we calculated the total delivery speed.

What is the speed of your feature delivery? Is it fast? Or is it slow? Only you can answer this question as it's unique for your situation. 
In our context, we felt that feature delivery was way too far from the total speed, and we wanted to know why. In search of an answer, we decided to look into parallel work.

#### 3. Number of parallel value-adding contexts
We plotted the features into a Gantt chart. 

![Epic focus](images/epic-focus.png?raw=true "Epic focus")

By plotting the work on the different value-adding contexts over time, you can see where work on these different contexts overlaps. Working on various contexts in the same timeframe suggests context switching. 

## Context switching
Most likely, you already know that context switching is not your friend, but rather an enemy, that is stealing your precious time without you noticing it. The modern world is full of distractions: new email comes in, someone sends you a Slack message, one of the numerous apps on your phone sends you a notification, social media continually screaming for your attention. The world is designed to distract you. It takes discipline and practice to restrain yourself from all these temptations, calling you every minute. Let's leave these daily distractions for now and focus on another level of context switching: project-level. 

Many companies or individual product managers lack the means to prioritize and order their backlogs properly or have difficulties saying 'No' to their various stakeholders. As a result of these shortcomings, teams are tasked to work on everything at the same time. As time goes by, everything is in progress, little is finished. Half done isn't done at all. The cost of such decisions is very high. Gerald Weinberg, in his book Quality Software Management: Systems Thinking, offers an illustration of the cost of context switching:

![Context Switching](images/context-switching.png?raw=true "Waste percentage from switching context")

Jeff Sutherland, in his book Scrum: The Art of Doing Twice the Work in Half the Time, speaks at length about costs of context switching. He calls waste crime and encourages agile teams to do one thing at a time. 



--> Add reflection to symptoms


## Solutions
Acknowledgement of a problem is the first step towards its solution. There are number of things you could do next. And at first, we wanted to give you some tips. But those seemed obvious and tricky at the same time. We wanted to tell you to focus, focus on the right stuff, but often times it is easier said than done. We don't know your context and the reasons why this is happening in your organization. You might struggle to identify the right one from many or, perhaps, have difficulties explaining to your stakeholders why their project has to be put on hold.
So, instead of giving an advice, we would like to ask you what would you do? How would you tackle this dysfuction? Would you address it at all?

There is one more thing that we wanted to warn you about. Now, having the time to market calculated as a single number, it might be tempting to use it as a baseline and set a target to grow it, turn it into the new KPI. To be honest, that was my first instinct. After discussing it, we came into conclusion that it is not a good idea. The number can be easily gamed without giving you extra speed back. For example, by creating more of smaller size tickets the speed number will go up, but are you really going faster? We think it would benefit you to re-measure your focus and speed some time after you've implemented a change to see what is the effect of it. 

We strongly believe that by increasing focus and reducing context switching, you can expect a boost in productivity.

## Dream of engagement
Our story is done. The symptoms we observed led us through different measurements to find a bottleneck that we can now solve. Our resources can be more productive. Numbers go up, stakeholders are happy.

But are we happy? The resources we're dealing with they are human beings; even worse, they are knowledge workers. In general, we can assume that having a variety of responsibilities or different contexts is a strong motivator. Focus might have an opposite effect.

When we're dealing with people, we dream of increasing engagement. People that are engaged in the work they are doing are more productive. This is shown time and again by periodic research done by [Gallup](https://news.gallup.com/reports/191489/q12-meta-analysis-report-2016.aspx). Not only does it have a positive effect on productivity, but it also correlates, for example, with higher quality work.

We can influence engagement. There is a [strong correlation](https://files.eric.ed.gov/fulltext/EJ1096700.pdf) between engagement and intrinsic motivation, and improving intrinsic motivation is what we like to do! There are [many motivators](https://noop.nl/2013/02/champfrogs.html) that drive people intrinsically. So how can focus be an influence here?

A lack of focus might cause a lack of a goal, a clear purpose. When we try to create more focus, we should start with a clear and compelling goal and go from there. Focus can also positively influence order, a more stable environment. Or it can increase relatedness from the required collaboration.

Focus not to increase productivity alone, but to increase engagement as well. Now we need to look for a fourth measure; to validate — the measure of engagement.

### Acknowledgements
Neither the research nor this blog would see the world if it wasn't for Jochum Börger, my colleague and friend, who has supported me all this time by co-creating, giving continuous feedback, and actually writing it together with me. Thank you, your contribution is invaluable!  

