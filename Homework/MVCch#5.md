MVC CH# 5
--


1. What is a view engine?

--The view engine is responsible for creating HTML from your views. Views are usually some kind of mixup of HTML and a programming language. The pattern behind most of these is called two-step view.

2. What is Razor?

--Razor is a Microsoft internal extension to ASP.NET MVC. You seem to be under the impression that Razor is provided by the community or is an off-shoot of the MVC base components, which is entirely false. Razor also provides syntactically cleaner code than ASPX.

3. What do views do? List two speciﬁc things ih your answer to this question.

--In an MVC application, the view only displays information; the controller handles and responds to user input and interaction. For example, the controller handles query-string values, and passes these values to the model, which in turn might use these values to query the database.

4. How does Razor respond when it encounters statements that begin with the at character (@)? Be speciﬁc.

--reads code

5. How does Razor respond when it encounters statements that begin with the at character followed by the colon (@:)? Be speciﬁc.

--doesnt read code

6. Describe how you implement a standard formatting for all pages in an ASP.NET application.

--specify a lab

7. What is the diﬀerence in using Razor to interpolate data values as stand-alone HTML elements and as attributes to HTML elements. What is the similarity?

--detracts from the pattern of MVC

8. What is a view start ﬁle and where is it located?

--located in the views folder

9. What is a Razor code block? What is the syntax of a Razor code block?

--traslates code to HTML

10. Describe the diﬀerent roles of action methods and views.

--action passes data to view, the view displays information

11. Describe the use of the @using statement. Give an example of how you would use it.11. 
 

--add namespace for using reference
