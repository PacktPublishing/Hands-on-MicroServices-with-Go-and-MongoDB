## Hands-on Microservices with Go and MongoDB

This is the code repository for [Hands-on Microservices with Go and MongoDB [Video]](https://www.packtpub.com/web-development/hands-on-microservices-with-go-and-mongodb-video). It contains all the supporting project files necessary to work through the video course from start to finish.

## About the Video Course
How do you build a service-oriented architecture, using microservices system that should not only be scalable with high performance but also handle frequently changing features? This is a real-world problem and it’s important that you empower yourself with the knowledge, tools, and skills today, so that you can build these systems with confidence!
This course dissects the real-world problem into various aspects for understanding the data models, large-scale request processing, communication strategies, securing the system, and even testing. It will help you with all the knowledge needed to build scalable, extensible, and highly performant and future-proof systems that will make you proud of your work! We shall use a real-world example of managing a large number of events from wearable devices to showcase all the aspects of a performant system.
By the end of this course, you will have all the knowledge and tools to build a scalable and extensible service-oriented system.

## The Sweat Bead ##

This is an entirely hypothetical attempt to build a platform using differnet microservices. 
In this example, we don't concentrate on the hardware but only the process of building different 
microservices incorporating the Single Responsibilty principle.

Did you know that Sweat can be used for various health deductions including diabeties? Well, I have
still to find a really good sweat analyzer but we shall assume that a sweat-bead is one such device.

### The Architecture ###

We manage multiple microservices microservices to manage sweat and user/device data, to provide
alerts and reports. 

The SweatMgr manages all Sweat data.
The UserMgr manages all user data
The ReportsMgr is a client to query the SweatMgr

This is a Hands-on tutorial and you're expected to make it work (not see it work)

<H2>What You Will Learn</H2>
<DIV class=book-info-will-learn-text>
<UL>
<LI>Build scalable and extensible microservices using Go and MongoDB
<LI>Discover ideas about when to use microservices and how to design them to be scalable and more rigorous tested
<LI>Benefit from real-world examples that you can relate to so that you can choose the right tool and the right knowledge to do things right!
<LI>Learn when to use a single datastore across microservices and when to keep data exclusive to each microservice
<LI>Build microservices that can be easily tested using Go
</LI></UL></DIV>

## Instructions and Navigation
### Assumed Knowledge
This course is for experienced full-stack developers who have or will have the responsibility to build large-scale systems that need to change flexibly. If you believe that is you and you have a passion for not just building systems but also ensuring that they are well tested, then this course is for you!
You need to know the basics of MongoDB, should have coded in Go and should be comfortable working on Mac or Linux. Knowledge of gRPC is good but not mandated as this course will give a brief overview of gRPC.	


### Technical Requirements
This course has the following requirements:<br/>
Be familiar with the Go programming language<br/>
Have access to a MongoDB server, locally or cloud installed<br/>
Vim code editor<br/><br/>

Recommended Hardware Requirements<br/>
For an optimal experience with hands-on labs and other practical activities, we recommend the following configuration:<br/>
OS: MacOS Mojave<br/>
Processor: Intel Core i5<br/>
Memory: 8GB memory<br/>
Storage: 256 GB storage<br/><br/>

Software Requirements<br/>
Golang 1.11.2 or higher<br/>
MongoDB v4.0.6 or higher<br/>



## Related Products
* [Go Programming Cookbook - Second Edition](https://www.packtpub.com/application-development/go-programming-cookbook-second-edition)

* [Hands-On Microservices with Go [Video]](https://www.packtpub.com/application-development/hands-microservices-go-video)

* [Ruby and MongoDB Web Development Beginner's Guide](https://www.packtpub.com/web-development/ruby-and-mongodb-web-development-beginners-guide)
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781838648558">https://packt.link/free-ebook/9781838648558 </a> </p>