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
- [X] Check with grammarly
- [X] Editing - second iteration on each section
- [ ] Review
- [ ] Fix comments
- [X] Come up with the title and subtitles
- [X] Create new picture for context switching
- [ ] Fix Epic focus image epic in title
- [X] Link to source for lack of collaboration reasons
- [ ] Consider SEO
- [ ] Move it to wordpress and publish
- [ ] Distribute via social media, etc.
- [ ] Celebrate
- [ ] Measure # of views every day, drink if it is high :), drink if it is low :(


# Value Focus: Measure your way to a better time to market
There are several recurring wishes our clients bring to us, one of which is speed, shorter time to market. However, there is no dial that we can turn to deliver value faster. Software teams are not like cars; there's no acceleration pedal. Even if we try to speed up by adding more resources, in many cases, the actual bottleneck will just become more apparent.

In our search for increased delivery of value, we hunt for these bottlenecks. No two contexts are the same, and for this story, we have a particular context in mind. Symptoms in different organizations are often similar, and our story might apply to your setting if you recognize the problems we encountered.

## Observing the symptoms
Like doctors, we always start by observing the symptoms of the bottlenecks that can cause an increased time to market. There might be numerous signs one can notice in an organization, we would like to bring your attention to three we encountered:
 1. Perception of slowness
 2. Lack of collaboration
 3. Team has nothing to present
  
### Perception of slowness
Speed is a new currency. If you are fast, chances are you are going to be the first on the market with that new exciting feature. It is not about being better; it is about getting there first. Everyone is consumed by what's new. Few people are interested in what's better.

Therefore, the lack of value delivered is noticed quite quickly. While competitors are already delivering features that are on your future roadmap, you still struggle to answer what value was added to your product last quarter or even last year. Although you might have done a lot of work, if it did not result in tangible and significant customer-facing changes, the perception might be that nothing was changed at all.

### Lack of collaboration
Collaboration is the action of working with someone to produce something. In working together, there is an exchange of ideas; new and enhanced ideas are born. It allows you to deliver the best designs and the best software. Collaboration is a source of creativity and innovation; it promotes healthy employee relationships. It also creates a faster feedback loop and allows issues to be found and resolved earlier in the process.

At the heart of collaboration is communication. Look at how people around you communicate, do they prefer face-to-face communication, or are email and slack their goto options? Do you see people working on one computer? Do they look like a team?

There are [many reasons](https://www.forbes.com/sites/carolkinseygoman/2014/03/02/the-story-of-why-people-dont-collaborate/) why people don't collaborate. They don't see the benefits of it, are afraid of being wrong and therefore vulnerable, don't trust their teammates, or they've tried before only to have their opinion ignored. Or maybe there is nothing to collaborate on?

### Team has nothing to present
As a coach, I like to use the sprint review as a vantage point to do observations. Do the sprint review meetings happen regularly? Do the teams have something to review? Do you feel like there is continuous progress? Perhaps you catch yourself wondering what the teams have been doing the entire sprint as they have very little or nothing to review. 

> "If you can't measure it, you can't improve it." 
> - Peter Drucker
  
## Measuring the process with the Value Stream Map
The symptoms we observe are a good starting point for change. We now want to support these observations with data. One way to examine your development process is to [create a value stream map or VSM](https://xebia.com/blog/how-to-create-a-value-stream-map/). It is an inventory of all the activities that happen before a piece of software hits production. You also want to know how much time each activity takes. Make sure to record all the waiting times, such as waiting for code review, waiting for approval(s), waiting for deploy, etc.  Once you have that, you can put them in two buckets: value-adding and non-value adding activities or, in other words, waste. It is quite intuitive that activities such as writing code, writing tests, and reviewing the code, are considered as value-adding while all kinds of waits belong to waste. 

Here is the visualization of our VSM and how it changed over time as we tweaked the process.
![VSM](images/VSM.png?raw=true "Value Stream Map")

By performing this exercise, you will identify the waste in your process, and it will become clear what parts of it need change. Of course, you still don't know what work items are valuable by themselves. For that, you need another metric.

## Drilling down into the backlog with the Value Focus Metrics
#### 1. Indentify value-adding and non-value adding backlog items
By building a value stream map and eliminating waste, you can speed up your processes. We would like to offer you a similar exercise only performed not against activities, but your backlog items. This exercise can give you insight into the speed of your feature delivery and value focus. 

Put all the completed work into two buckets: value-adding and non-value adding. We chose to mark new features as value-adding and bugs and technical debt items as the non-value adding. Both are important; we need to add new value while maintaining the existing value of our products. 

![Distribution of tickets](images/value-adding-vs-non-value-adding.png?raw=true "Value-adding vs non-value adding PBIs")

Once you have a distribution of work, e.g. the ratio between value-adding and non-value adding items, you can drill down on each of them and get even more insights. In our situation we see that adding new value gets less priority than maintaning the existing value. It could mean that there is a lot of bugs, and there is a quality problem, or perhaps, it is a [tech debt](https://xebia.com/blog/using-metrics-to-find-the-pain-points-in-a-legacy-codebase/) that's holding them back and doesn't allow extending the product. Having a lot of non-value adding work might create a perception of slowness in the eyes of the stakeholders.

#### 2. Calculate the feature delivery speed
As a next step, we decided to look deeper into the value-adding bucket. We used features as value-adding work. For each feature, we identified the duration (in days) and the number of work items completed within that period. By dividing the number of completed tickets by duration, we calculated the time to market of the feature.

![Feature delivery speed](images/delivery-speed.png?raw=true "Feature time to market")

For comparison, we calculated the total delivery speed.

What is the speed of your feature delivery? Is it fast? Or is it slow? Only you can answer this question as it's unique for your situation. 
In our context, we felt that feature delivery was way too far from the total speed, and we wanted to know why. In search of an answer, we decided to look into parallel work.

#### 3. Visualize feature focus
We plotted the features into a Gantt chart. 

![Feature focus](images/epic-focus.png?raw=true "Feature focus")

By plotting the work on the different value-adding contexts over time, you can see where work on these different contexts overlaps. Number of overlaps shows your focus, the higher the number the lower the focus. Working on various contexts in the same timeframe suggests context switching. 

## Context switching - the enemy of focus
Most likely, you already know that context switching is not your friend, but rather an enemy, that is stealing your precious time without you noticing it. The modern world is full of distractions: new email comes in, someone sends you a Slack message, one of the numerous apps on your phone sends you a notification, social media continually screaming for your attention. The world is designed to distract you. It takes discipline and practice to restrain yourself from all these temptations, calling you every minute. But let's leave these daily distractions for now and focus on another level of context switching: project-level. 

Many companies or individual product managers lack the means to prioritize and order their backlogs properly or have difficulties saying 'No' to their various stakeholders. As a result of these shortcomings, teams are tasked to work on everything at the same time. As time goes by, everything is in progress, and little is finished. Half done isn't done at all. The cost of such decisions is very high. Gerald Weinberg, in his book Quality Software Management: Systems Thinking, offers an illustration of the cost of context switching:

![Context Switching](images/context-switching.png?raw=true "Waste percentage from switching context")

Jeff Sutherland, in his book Scrum: The Art of Doing Twice the Work in Half the Time, speaks at length about damages of context switching. He calls waste a crime and encourages agile teams to do one thing at a time. 

Eureka! Every symptom we observed can be explained. It felt slow because of the lack of focus, everything was being worked on in parallel and took ages to complete. Teams didn't collaborate because there was no shared goal - the sprint backlog was a selection of unrelated stories and tasks. Nothing tangible could be shown during the review, as they had little progress in various directions. They were going everywhere and arriving nowhere.

## Increase focus
Acknowledgment of a problem is the first step towards its solution. There are several things you could do next. And at first, we aspired to give you some tips. But those seemed obvious and tricky at the same time. We wanted to tell you to focus, focus on the right stuff, but often it is easier said than done. 

We don't know your context and the reasons why this might be happening in your organization. Perhaps you're struggling to identify the right priority from many options, or maybe you have difficulties explaining to your stakeholders why you're putting their project on hold. 

So, instead of giving advice, we would like to ask you what you would do? How would you tackle this dysfunction? Would you address it at all?

We strongly believe that by increasing focus and reducing context switching, you can expect a boost in productivity.

## Dream of engagement
Our story is complete. The symptoms we observed led us through different measurements to find a bottleneck that we can now solve. Our resources can be more productive. Numbers go up, stakeholders are happy.

But are we happy? The resources we're dealing with they are human beings; even worse, they are knowledge workers. When we're dealing with people, we dream of increasing engagement. When trying to create more focus, we should start with a clear and compelling goal to give our teams a purpose.

Create focus not to increase productivity alone, but to grow engagement as well. Now we need to look for a fourth metric to validate — the measure of engagement.

### Acknowledgements
Neither the research nor this blog would see the world if it wasn't for [Jochum Börger](https://xebia.com/blog/author/jborgerxebia-com/), my colleague and friend, who has supported me all this time by co-creating, giving continuous feedback, and actually writing it together with me. Thank you, your contribution is invaluable!  

