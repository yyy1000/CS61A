# CS61A
Homework1
1. Can assign a function directly
2. no self-increment, use val+=1
3. max or min function in Python can be given a lot of parameters

Homework2
1. Nested Definitions
2.  Functions as Returned Values

Homework3
1. use helper function in the function as a nested and the out funtion return an instance of it
2. lambda expression's level:
   eg : (lambda f: lambda k: f(f, k))(lambda f, k: k if k == 1 else mul(k, f(f, sub(k, 1))))
   here, we create a lambda expression which has 2 order (lambda f: lambda k: f(f, k))
   and the follow (lambda f, k: k if k == 1 else mul(k, f(f, sub(k, 1)))) as the first parameter.
   
   
Cats
1. res = [[] for _ in player_indices], to create 2 dimension list
2. try to use abstraction as much as possible
3. READ the text CAREFULLY
