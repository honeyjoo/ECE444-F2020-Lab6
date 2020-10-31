# ECE444-F2020-Lab6



# Pros and Cons of Test Driven Development
## 1. Pros
- You write small tests at a time, so your code becomes more modula. TDD is a good practice to learn and understand modular design
- TDD forces good architecture. You need to have a unit test for your code, so the code has to be modular in a proper way. You can spot varous architecture problem early on by writing unit tests.
- easier to maintain and refactor your code with TDD. TDD gives a safety net when refactoring the code you just wrote.

- Makes collaboration easier and more efficient, team members can edit each others code with confidence because the tests will inform them if the changes are making the code behave in unexpected ways.
- TDD prevents defects because design or requirement issues will arise in the beginning of development, which is easier to fix.
- TDD Helps programmers really understand their code.
- TDD helps to clarify requirements because you have to figure out concretely what inputs you have to feed and what outputs you expect.
- Unit tests are useful when the code needs to be changed to either add new features or fix an existing bug. 
## 2. Cons
- It is hard to learn at first, especially trying to learn it on your own. 
- If you had old legacy code, hard to appy it.
- Continous housekeeping need for a quick runtime and avoid redundant tests
- creating tests for failures can be tedious
- Unless everyone on the team correctly maintains their tests, the whole system can quickly degrade.
- Compared to just coding and writing tests in the end, writing code followed by a unit test can slow down the whole development
