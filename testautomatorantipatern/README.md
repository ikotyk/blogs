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
> -Henry Ford

Once upon a time there have been teams, and they were slow.
These teams had testers, manual testers, doing manual regression testing. Not just that; they were slow testers.

Well, we want faster testers! What is the car equivilent to that? - Test automation!

The test automator was born.
The tester, rissen from their ashes, not only doing testing faster, but doing it automatically.

## Wearing two hats
As a tester now all of a sudden you're expected to be a car.
You're getting a tune-up, learning some automation skills, devour one tool after another.
The transformation is complete, you now proudly call yourself a test automation engineer.

What is expected from you, a test automator? 

Responsibility for both, expectation to do both.

- If you do both:
- How do you prioritize? "Automation first" attitude.
- How do you balance between automation and exploration of the product?
- Is it ok to do only one, or both poorly?
- What do you lose?
- You can only spend time once.

We value speed so much over quality attributes that we confuse the people guarding the quality of our product. We create a disbalance; prioritizing the automation of checks, that promise a future increase of speed by being repeatable, that we forget about building an actual quality product.

Would you hire a tester, and a test automator?



Often times tester and test automator is the same person in the team. 
Doing end to end testing is a time consuming activity. It happens at the end of the process after the development is done. 
Being responsible for both of these activities doesn't allow you to do good any of them. Often I observe that automation is prioritized over exploration.
This way of organizing a team usually doesn't add quality to the product and creates many problems.

## Blame the Bottleneck
- "throw test automator at them." -Ira

The biggest problem with this approach is that it creates silo, single person in the team has a monopoly on test automation. When something goes wrong, and it does happen quite often, everybody depends on this one person to fix it. 
Very quicklu team members learn not to trust end to end tests. You can see it in their actions. They skip running it altogether. They re-run the tests without even looking at what failed. If that doesn't help, they point a finger at automator asking to look into it.

- Silos
- Flaky, slow tests
- Serial work
- No perceived value, only delay
- 

## The fall of the test automator
- Creating bigger and bigger piles of unmaintainable and overengineered shit.

## Alternative patterns
Experiment with these patterns:
Product requires continuous exploration.
Test automation should be team responsibility

## Epilogue: The rise of the tester

Tester quards the quality of the product throughout the whole proces