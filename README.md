# Why?
This is a sample app for the use of TDD, Android Architecture components, Github and CI
* TDD: Test Driven Development. I think is time to start learning this methodology so I will begin with a simple project.
* Android Architecture Components: Not much to say, I have never tried this library but it looks great. I usually follow MVP for Android apps but I will try this MVVM with advices in guidelines: https://developer.android.com/topic/libraries/architecture/guide.html
* Github: I love Git and every project is a good oportunity to practice and learn new concepts, have ssome bitbucket repos but now I'm going with Github and open source mind. I will follow **feature branch workflow**, for now I'm the only dev but will try to use PR for merges, etc.
* CI: As I will follow TDD is a good time to learn about CI and Github facilities, I'm a bit new in Android testing but will try to do some instrumentation test, not just unit tests.

# What?
**Common request**, it will be a simple app to create scheduled and periodic network request, it can be used to check status of servers or owned machines.

## Core features:
* Requests
  * HTTP HEAD, GET and POST Requests
  * Schedule requests, let them to execute at specific time
  * Program periodic requests, execute very minute/5 minutes/10 minutes...
* Create requests
* See request list
* Edit request
* Delete request
* See request details: Last execution result and time...

## Plus features:
* ICMP Requests
* Notifications: when request fails, etc.
* Statistics
