Target audience:
 - Hiring managers
 - Scrum teams
 - Test automators
 - Testers

Message:
 - Test automators are siloed by definition
 - Harmfull:
   - Monopoly/responsibility on test automation
   - Bottleneck
   - Late feedback
   - Not testing
   - Don't add customer value
   - Prioritize implementation of checks over exploration
   - Mentality, resonsibility of writing tests, not validating the product
   - Often not real developers
   - Single point of failure
   - Mostly focus on e2e
 - Should be team responsibility
 - Should disappear
 - Shift left





Story:
- Bugs go to prod, should have been found
- Obvious solution: build more tests
-


- Problem --> Speed: manual regression testing takes a long time
- Solution: automated regression testing
- Problem --> Quality: test automator is harmful
- Solution: quality and automation as a team responsibility, people exploring the product



> "That's not the point where you make quality happen."
> - Jochum Börger, about test automation (18-11-2019)

## What is happening with quality?
Throughout my career as a quality engineer, I have developed a deep passion for quality. It goes way beyond the quality of software products, into the quality of interactions, quality of processes, and quality of work and life experience. I strive to bring excellence to every aspect of my life, and it hurts to see when greatness is lacking.

In my working life, I've seen the market focus shift from quality more and more to speed. We build more products than ever before; unfortunately, many of them not up to par.

How IT organizations have tried to fix this confuses me sometimes.

## Encounters with a test automator
It happens from time to time; I join a new team, and one of its members describes themselves as 'test automator' (or, more commonly, 'test automation expert'). Not all groups have them; they don't seem to be a mandatory part.

So, why do some teams need them where others do not? There must be some decisions leading up to these team compositions. What drives your hiring choices? How do you define roles for your teams? Is it about following a market trend? And above all, do you get the expected value?

## The rise of the test automator
In the past, there have been teams, and they were slow. They cared much about the quality, and therefore all of them had testers, doing testing and manual regression testing. As products grew, the regression testing effort was taking longer and longer. We couldn't continue like that anymore; we wanted to go faster.

![Slow quality](images/1-cropped.png?raw=true "Slow quality")

> "If I had asked people what they wanted, they would have said faster horses."
> - Henry Ford

Well, we want faster testers! What is the car equivalent to that? - Test automation! The test automator was born - a tester who is not only doing testing faster but doing it automatically.

## Wearing two hats
As a tester, now all of a sudden, you're expected to be a car. You're getting a tune-up, learning some automation skills, devour one tool after another. The transformation is complete. Now you proudly call yourself a test automation engineer. What is expected from this transformed person, the test automator?

A brief look at job listings will reveal that the expectation is to do both - automation and exploration. Some of the descriptions are specific enough to say that you should have an 'automation first' attitude. So it is safe to assume that in most teams, a test automator is responsible for doing both.

How do you prioritize and balance between automation and exploration of the product? Is it ok to do only one, or both poorly? What do you leave not done? You can only spend time once.

We value speed over quality attributes so much that we confuse the people guarding the quality of our product. We create a disbalance, prioritizing the automation of checks that promise a future increase of speed by being repeatable, that we forget about building an actual quality product.

![Speedy bugs](images/2-cropped.png?raw=true "Speedy bugs")

## Blame the bottleneck
Every approach has its pros and cons. While having automation engineers has many benefits, it also has some downsides. The biggest issue with this approach is that it creates silos, a single person in the team gets a monopoly on test automation. When something goes wrong, and it does often go wrong, the whole unit depends on this silo to fix it.

-- Very quickly, team members learn not to trust automated tests. They get annoyed with it to the point they skip running it altogether. They re-run the tests without even looking at what failed, hoping it will pass this time. If that doesn't help, they point the finger at the automator and ask them to look into it.

-- If we change the resposibility from a tester to that of a test automater, the value is less than that of a faster tester. The metaphor is incorrect. This is not the breakthrough of a car.

It seems obvious that having a single point of failure is terrible, and yet so many companies design precisely that. Do you understand my confusion now?

## The fall of the test automator
There is a solution to this silo problem - a team approach, testing as a team effort. Quality should be a team responsibility! Both quality and speed are possible.

When it comes to test automation, developers are better skilled in designing and writing software, and test automation is nothing but software. Teams need a quality-oriented perspective to identify what to test, so testers and developers should work together in close collaboration.

-- will also shift the focus back to quality and allow for more exploration of the product.

## Epilogue: The rise of the tester
When I think of a tester, I think of someone who guards the quality of the product throughout the whole process, from idea to production. A good tester does that by bringing quality perspective to various team events such as design sprints, refinement meetings, three amigos sessions. A great tester is pairing up with developers on the story and continuously explores the product. An excellent tester, a quality guardian, makes quality a team responsibility by sharing knowledge and coaching developers on how to be better testers.
