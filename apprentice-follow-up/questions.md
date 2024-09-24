# Follow up questions

Commit your answers to these questions in your copy

## Part 1
Answer these after a day or two after the course 

1. Which exercise did you find the easiest? and why

Exercise 3 - By this point I had a clear idea of what can be included in a workflow file. By separating the steps by giving each run command a different name, the workflow was easier to write as it became clear what step i needed to include next

1. Which was most difficult? and why

Exercise 7 - Rather than creating the workflow from scratch, like in a number of the previous exercises, we were using one from GitHub docs. I found this harder to follow and understand the connections between the various steps


## Part 2

After some reflection and perhaps investigation while on your delivery

1. Which pipeline types are used on your delivery? 
Scheduled, manual and those triggered by pushing changes to github 

1. What techniques are in place that make pipelines more secure on your delivery?
Github secrets to prevent data breaches and ensure others don't have access to the inner workings and configuration of the project 

1. Describe something you have learned that you were able to use directly in your delivery. 
Storing sensitive information in Github secrets 
I was involved in creating a workflow yaml file which contains commands to execute a script, store the result in a file and use a curl command to post its contents into a private slack channel. The url of this slack channel was stored in a shared github account for Bichard as a secret. This was then referenced in the yaml file as a variable name to ensure that, while the contents of the yaml file is visible in version control, the url is not. 





