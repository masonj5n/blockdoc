# Overview
_Overview of the purpose of the class, introduction of how teams were split_

# Reinvent
### Objective


### Process


### Results


### Conclusion

### Supporting Documentation


# Reuse
### Objective


### Process


### Results


### Conclusion

### Supporting Documentation

# UI
### Objective
Create a modular front end to work with each back end. The front end should protect from SQL injection, cross-site scripting, and password validation issues. For this reason, we run the front end as a desktop application with secure communication to the backend. The front end must also be visually appealing and easy to use. 

### Process
The Front end had three design phases: design, implementation, and testing. During the design phase, we completed mock-ups for potential application designs. For the implementation phase, we broke up into Mobile and Desktop teams. The Mobile team worked towards a proof-of-concept to show that voting from home could be viable in the future. The Desktop team worked towards creating a secure application that can connect to the backend and register votes. During the testing phase, we ran test-votes and made sure that all of the information was taken from the backend correctly, displayed well, gathered voter information correctly, and sent that information back to the backend efficiently. On top of these three design phases, we also created a website for the class and created an administrator app to enter in voting data and facilitate launching multiple voting applications.

### Results
We have a functioning desktop app and a proof of concept for the mobile app. For each implementation, the user can log in with a passcode or a QR code. After that, they can easily move around the ballot without losing their place or accidentally skipping a vote. The administrator app is currently just a mode for demonstrating these features from the backend as well as facilitating the demonstration of the features of each backend. With some additional work, these could be spun out into a viable voting mechanism. More testing would be needed in conjunction with the backend to ensure the success of the system as a whole. In future iterations of the work, you could potentially see who you voted for, however there is concerns with this kind of implementation. 

### Conclusion
The UI team created multiple apps to show the functionality of each backend in a clear and easy-to-use way. The desktop app being the main center peice, it allows our users to cast a vote and see that it was counted. The mobile app serves as a proof-of-concept that such an app could be used to vote from home utilizing the security and trust that a blockchain gives. 

### Supporting Documentation
https://web-design-weekly.com/2014/07/09/front-end-security-thing-concerned/

# DevOps/Support
### Objective
The objective was to provide licensing information, deliver a project-wide documentation, acquire computing resources and deploy the software.

### Process
The DevOps team was divided into documentation team and the system integration team based on the area of interest of the team members. The documentation team focussed on obtaining licensing information for each software used by the other teams and the license terms were documented. The licensing information mainly consisted of the terms of use or copyright. The system integration team worked on acquiring the computing resources and running the implementation of Reinvent team. Amazon Web Services were used for computing resources.
For the overall documentation, we created a markdown file in the github repository to document the work done by each team.

### Results
The softwares used by the teams, mainly Reinvent and Reuse included Flask, SQLAlchemy Python DB, Java JDK/JRE Version, Ecdsa Python Library. Flask is BSD-Licensed, which is a three-clause license, that is, user has the freedom to do anything they want with the conditions that the disclaimer and copyright is present and conditions are present as it is. 
SQLAlchemy Python DB is licensed under MIT. Under the MIT license, the user is allowed to reuse, but the only conditions are to add acopy of the license terms and the copyright notice.



### Conclusion

### Supporting Documentation

# Class Conclusion


### Supporting Documentation
