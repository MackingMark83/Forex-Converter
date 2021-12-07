### Conceptual Exercise

Answer the following questions below:

-1. What are important differences between Python and JavaScript?

Python is a high-level general-purpose interpreted programming language that was developed to emphasize code readability. JavaScript is a programming language that conforms to the ECMAScript specification. 2. It is a scripting language used for developing both desktop and web applications.

-2. Given a dictionary like ``{"a": 1, "b": 2}``: , list two ways you
  can try to get a missing key (like "c") *without* your programming
  crashing.

  values(), get()

-3. What is a unit test?

Unit tests are used to test small components inside of software. They are conducted by developers and test the unit of code he or she developed. It is a testing method by which individual units of source code are tested to determine if they are ready to use. It helps to reduce the cost of bug fixes since the bugs are identified during the early phases of the development lifecycle.

-4.  What is an integration test?

An integration test is used to test components that rely on each-other. Integration testing is executed by testers and tests integration between software modules. It is a software testing technique where individual units of a program are combined and tested as a group. 

-5. What is the role of web application framework, like Flask?

A web framework is a software framework that is designed to support the development of web applications including web services, web resources, and web APIs. Web frameworks provide a standard way to build and deploy web applications on the World Wide Web.

-6. You can pass information to Flask either as a parameter in a route URL
  (like '/foods/pretzel') or using a URL query param (like
  'foods?type=pretzel'). How might you choose which one is a better fit for an application?

  You can generally use query string parameters if you are describing the object you are on vs using the route for the object itself. For example, in the above case I would use /foods/pretzel and then use a query string parameter if I am decribing the pretzel such as /foods/pretzel?type=salty or /foods/pretzel?type=sugar.


-7. How do you collect data from a URL placeholder parameter using Flask?

request.args

-8. How do you collect data from the query string using Flask?

request.url

-9. How do you collect data from the body of the request using Flask?

request.args.get

-10. What is a cookie and what kinds of things are they commonly used for?

Cookies are pieces of data that are tied to a users computer that will be accessed whenever you visit a website. This could be search history, user preferences, etc.

-11. What is the session object in Flask?

A session is similar to a cookie, as it stores information on a users computer that is carried over during the course of a browsers life. This can help keep track of constantly updating variables that will be referencable as long as the browser\window remain open. Not affected by refreshes.

-12. What does Flask's `jsonify()` do?

Jsonify will return flask variables\data that need to be turned into the JSON format for frontend API's to consume
