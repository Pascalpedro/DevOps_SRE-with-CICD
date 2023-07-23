# DevOps_SRE-with-CICD
## DevOps and SRE implementation of a VOTING APP using a Continuous Integration and Continuous Delivery pipeline.

In the course of this Project, we will be building and developing a VOTING APPLICATION to demonstrate and practice implementing a Continuous Integration and Continuous Delivery pipeline. 

A brief overview of the APP is thus:
- The application will allow a user to vote on a webpage and then view the results on a different webpage.
- The vote page is written in the Python framework Flask.
- The vote application sends the vote to a Redis backend.
- A Worker application, written in Java, pulls the information from Redis and pushes the vote to a Postgres database. 
- Finally, the Result application, implemented with NodeJS, reads the result from the Postgres Database and displays the percentage of votes for each entry.
