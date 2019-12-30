# Test automator anti-pattern
## What is happening with quality?
Throughout my career as a quality engineer, I have developed a deep passion for quality.
It goes way beyond the quality of software products, into the quality of interactions, quality of processes, and quality of work and life experience.
I strive to bring excellence to every aspect of my life, and it hurts to see when greatness is lacking.

In my working life, I've seen the market focus shift more and more from quality to speed.
We build more products than ever before; unfortunately, many of them are not up to par.

How IT organizations have tried to fix this confuses me sometimes.

## Encounters with a test automator
It happens from time to time; I join a new team, and one of its members describes themselves as 'test automator' (or, more commonly, 'test automation expert').
Not all organizations have them; they don't seem to be a mandatory part.

So, why do some teams need them where others do not?
There must be some decisions leading up to these team compositions.
What drives your hiring choices?
How do you define roles for your teams?
Is it about following a market trend?
And above all, do you get the expected value?

## The rise of the test automator
I remember teams that were slow.
They cared much about the quality, and therefore all of them had testers, doing exploration and manual regression testing.
As products grew, the regression testing effort was taking longer and longer.
Regression testing was a visible point of delay.
They couldn't continue like that anymore; they wanted to go faster.

![Slow quality](images/1-cropped.png?raw=true "Slow quality")

> "If I had asked people what they wanted, they would have said faster horses."
> - Henry Ford

Well, we want faster testers! What is the car equivalent to that?
- Test automation! The test automator was born - a tester who is not only doing testing faster but doing it automatically.

## Wearing two hats
As a tester, now all of a sudden, you're expected to be a car.
You're getting a tune-up, learning some automation skills, devour one tool after another.
The transformation is complete.
Now you proudly call yourself a test automation engineer.
What is expected from this transformed person, the test automator?

A brief look at job listings will reveal that the expectation is to do both - automation and exploration.
Some of the descriptions are specific enough to say that you should have an 'automation first' attitude.
So it is safe to assume that in most teams, a test automator is responsible for doing both.

How do you prioritize and balance between automation and exploration of the product?
Is it ok to do only one?
Or both poorly?
What do you leave not done?
You can only spend time once.

We value speed over quality attributes so much that we confuse the people guarding the quality of our product.
We create a disbalance by prioritizing the automation of checks, that promise a future increase of speed by being repeatable, and we forget about building an actual quality product.

![Speedy bugs](images/2-cropped.png?raw=true "Speedy bugs")

## Blame the bottleneck
Every approach has its pros and cons.
While having automation engineers has many benefits, it also has some downsides.
The biggest issue with this approach is that it creates silos, a single person in the team gets a monopoly on test automation.
When something goes wrong with the automated tests, and it does often go wrong, the whole unit depends on this silo to fix it.
Over time distrust builds in the team, and they condemn the tests.

It turns out that instead of removing a bottleneck, a new one got created.
The test automator is not like the breakthrough of a car.
It's not even as good as faster horses.
The distrust diminishes the potential value of a test automator.

It seems obvious that having a single point of failure is undesirable, and yet so many companies design precisely that.

## The fall of the test automator
There is a solution to this silo problem - a team approach, testing as a team effort.
Quality should be a team responsibility! Both quality and speed are possible.

![Fast quality](images/3-cropped.png?raw=true "Fast quality")

When it comes to test automation, developers are better skilled in designing and writing software, and test automation is nothing but software.
Teams need a quality-oriented perspective to identify what to test, so testers and developers should work together in close collaboration.

## Epilogue: The rise of the tester
When I think of a tester, I think of someone who guards the quality of the product throughout the whole process, from idea to production.

A good tester does that by bringing quality perspective to various team events.

A great tester is also pairing up with developers on the story and continuously explores the product.

An excellent tester, a quality guardian, makes quality a team responsibility, and coaches developers to be better testers.
