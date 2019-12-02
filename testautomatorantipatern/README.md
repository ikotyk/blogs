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


# What do you expect from a test automator?
It happens from time to time; I join a new team and one of its members describes themselves as "test automator" (or, more commonly: test automation expert).
Not all teams have them, they don't seem to be a mandatory part.
So, why do some teams need them where others do not?

There must be some decisions leading up to these team compositions.
What drives your hiring? How do you choose roles in a team? Compulsive pattern following? Do you reflect on these decisions? Do you get the value you expected?

## The rise of the test automator
> “If I had asked people what they wanted, they would have said faster horses.”
> Henry Ford

Once upon a time there have been teams, and they were slow.
These teams had testers, manual testers, doing manual regression testing. Not just that; they were slow testers.

Well, we want faster testers! What is the car equivilent to that? - Test automation!

The test automator was born.
The tester, rissen from their ashes, not only doing testing faster, but doing it automatically.




## Wearing two hats
As a tester, now, all of a sudden, you're expected to be a car. 
The need for speed has broung to life number of tools with record-and-play options, meant for people without development experience. Now the same scenarios that were performed manually have been recorded and played by the tool. End to end testing was born. It seemed like a good idea, but is it actually good? 
People withot development experience started writing the test code. 
There are number of issues with end to end testing: flaky, slow, difficult to write, debugging is not easy
Finding the root cause for a failing end-to-end test is painful and can take a long time. 


There are different flavours of test automators on the market: ex-manual testers doing automation only, ex-manual testers trying to balance both automation and exploratory testing, automators without prior testing experience, ex-developers. This list is not exhaustive and there is more to add, these are just the most common paths.
Let's have a closer look at each type. 
1. Ex-manual testers doing automation only
These guys are good in testing but they don't what they are good at anymore, they just create some end to end scenarios.

## Blame the Bottleneck
- "throw test automator at them." -Ira

## The fall of the test automator
- Creating bigger and bigger piles of unmaintainable and overengineered shit.

## Alternative patterns
Experiment with these patterns:
Product requires continuous exploration.
### 
