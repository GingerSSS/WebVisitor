# WebVisitor

### This is a simple web app that help me familiar with using docker.

## Idea
Make a docker container that contains the web application: 
  Show the number of visitors on web page. 
  (no styling in this project)
  
## Details
To acheive the functions above, I made two docker component: 
* Node app
* redis(visits)
  
## Design
There are multiple node app containers, but only one redis container, 
Reason:
    I want to use only one counter to count the number of visits.
