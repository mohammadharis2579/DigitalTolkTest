I have chosen refactoring code task

The code is average using repository pattern with dependency injection but the controller and repositorty length can be shorten by moving code to  separate controllers and repositories.
The name of the controller is not much relevant to the tasks going on inside controller, it should be JobController or something else.
In distancefeed method, its directly accessing model which violates repository pattern.
In many places try catch blocks are missing,and DB transactions while storing data in multiple tables.
There should be a JobRepository, i have seen many methods which can move from Job model to JobRepository.
Some methods dont have proper comments

Logic in some places is not good as there is a lot of redundancy in code.So many if else conditions. 

Formatting is good, but spaces are required in some places for example in if condition clause to make code more readable.