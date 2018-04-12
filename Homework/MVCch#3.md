MVC Ch# 3
--


1. The book states, “Interactions with an MVC application follow a natural cycle of user actions and view updates, where the view is assumed to be stateless.” What does it mean for the view to be stateless?

--A stateless app is an application program that does not record data generated in one session – such as information about user settings and events that occurred -- for use in the next session with that user.

2. The book identiﬁes two kinds of models. Brieﬂy desdribe each of them.

--The view model and the domain model

3. Give an example of separation of concerns from your own life experience. This should be a simple, everyday example.

--A time for eating, a time for sleeping, a time for working out

4. What is a view engine?

--The view is effectively your application's ambassador to the user. The view is responsible for providing the user interface (UI) to the user. After the controller has executed the appropriate logic for the requested URL, it delegates the display to the view. Unlike file-based web frameworks, such as ASP.NET Web Forms and PHP, views are not themselves directly accessible. You can't point your browser to a view and have it render. Instead, a view is always rendered by a controller, which provides the data the view will render.

5. The book notes that the three-tier structure, or n-tier model, is “the most widely used pattern for business applications.” Why do you think that this is true? An answer like, “Because it works well,” is not a suﬃcient answer to this question.

--it allows users to output code to HTML


6. This question requires some outside research. When we study UWP, you will see that the UWP design pattern is the Model-View-ViewModel (MVVM). What is the diﬀerence between MVC and MVVM that makes the ﬁrst good for ASP.NET MVC and the second good for UWP?

--Has to  do with the statelessness of MVC. 

7. Describe the two parts of the dependency injection (DI) design pattern.

--high cohesion, low coupling.

8. Give an example of loose coupling from your own life experience. This should be a simple, everyday example.

--Leasing a car

9. What are the two types of testing discussed in the book?

--unit testing and integration testing

10. What are the seven steps of the test driven development 

--determine the need to add a new feature to your application
--write the test
--run the test and get a red light

--Write the code that implements the new procedure

--Run the test again and correct the code until
you get a green light

--Refactor the code if required 

--Run the test to confirm your changes work
