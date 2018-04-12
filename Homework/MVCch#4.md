Ch 4 MVC
--


1. Using automatic properties is a shortcut that avoids several explicit steps. List the steps that the use of automatic properties avoids.

--You can change the statements in the Get and Set blocks instead of changing the classes that depend on the property

2. Using the object initializer syntax is a shortcut that avoids several explicit steps. List the steps that the use of object initializers avoids.

--You can skip the steps of constructing a new object and then assigning values to the properties.

3. What is the purpose of creating extension methods?

--It allows you to add methods you do not own and cannot modify directly

4. What is the one feature of extension methods that will always allow you to identify a method as an extension method?

--The presence of the MyExtensionMethods class

5. How do you create an extension method that ﬁlters the results returned by the method on a user speciﬁed criterion?

-- FilterByCategory

6. Explain the syntax of a lambda expression. The term “lambda expression” originates in the lambda calculus developed by the mathematician Alonzo Church in the 1930’s. There is a class of programming languages that are based on the fundamental ideas of lambda calculus.

--Func<Product, bool> categoryFilter = prod => prod.Category == "Soccer"

7. This will require some outside research. What is the distinction between an anonmously typed variable and a dynamically typed variable?

--An dynamically types variable infers the variable type without the programmer having to specify it

8. You are having a discussion about C# with a friend of yours that uses another language. You are tellig him about C#’s LINQ library. How would you describe to him the diﬀerence between LINQ’s SQL-like notation and LINQ’s dot notation?

--The "dot" notation is usually called Lambda syntax. SQL-like notation is called query syntax. Lambda is more concise but performing multiple table joins is more difficult. Joins are just much cleaner with the query syntax. The flip side is that there are a number of LINQ operations that only exist within the Lambda syntax: Single(), First(), Count() etc.

9. What, exactly, does the await keyword do?

--The await operator is applied to a task in an asynchronous method to suspend the execution of the method until the awaited task completes. The task represents ongoing work.

10. What is the connection between await and the async keywords?


--The async keyword can be used as a modifier to a method or anonymous method to tell the C# compiler that the respective method holds an asynchronous operation in it. The await operator is applied to a task in an asynchronous method to suspend the execution of the method until the awaited task completes. The task represents ongoing work.