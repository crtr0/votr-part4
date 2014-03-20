#Building a Real-time SMS Voting App Part 4: AngularJS

This is the fourth part in a series of blog posts about building a real-time SMS and voice voting application using Node.js. In part one, we created the Node.js application and captured incoming votes over SMS and stored them in a CouchDB. In part two, we created a real-time visualization of the voting using Socket.io and Highcharts. In part three, we tweaked our app to scale to thousands of votes per second and millions of total votes.

Through the first 3 parts of this series we now have a scalable voting application that can process votes for events via SMS or voice and display the real-time progress of voting. However, there is currently no web interface for an administrator. Creating events or modifying them require making changes directly to the documents in CouchDB. In this blog post, I will walk through the process of creating a simple web interface for administrators using AngularJS.

[http://www.twilio.com/blog/2013/08/votr-part-4-angularjs-and-authentication-with-couchdb.html](http://www.twilio.com/blog/2013/08/votr-part-4-angularjs-and-authentication-with-couchdb.html)
