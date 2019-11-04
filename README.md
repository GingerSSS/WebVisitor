# WebVisitor

Make a docker container that contains the web application: 
  Show the number of visitors on page.
  
To acheive the functions above, I made two docker component: 
  Node app, redis(visits)
  
  There are multiple node app containers, but only one redis container, 
  Reason:
    I want to use only one counter to count the number of visits.
