---
layout: post
style: text
title: Mechanical Turk Workshop
class_date: 2013-08-10 - 2013-09-11
upcoming: true
start: noon
end: 5pm
location: Brooklyn, NY
registration_url: http://www.eventbrite.com/event/6678476503
fee_list: [["Students", "$100"],
           ["Freelancers", "$200"],
           ["Corporate", "$600"]]
published: true
instructor: Jeff Crouse
---

####This workshop takes place on August 10th and 11th, noon-5pm

In 2005, Amazon launched <a href="https://www.mturk.com/mturk/">Mechanical Turk</a>, a crowdsourcing ("Artificial Artificial Intelligence") platform that made it possible to integrate human intelligence directly into software. The service was mostly aimed at businesses in need of quick, cheap, almost-mindless labor. But artists quickly began to explore both the creative potential and the significant ethical and cultural concerns surrounding the practice of using the Internet as a labor marketplace, leading to some great projects (see below). Although the buzz about crowdosourcing has died down somewhat, the technique is still incredibly prevelant on the web, with new services frequently popping up that attempt to harness the creative and labor potential of an Internet of "workers".

In this two-day workshop, we will start by discussing crowdsourcing in general and MTurk specifically, in order to orient ourselves in the current landscape. We will then move on to learning how to create our own Mechanical Turk projects using tools like Node.js, Express, Mongodb, and the <a href="http://docs.aws.amazon.com/AWSMechTurk/latest/AWSMturkAPI/Welcome.html">MTurk API</a>. Finally, we will launch our projects using another Amazon service: <a href="http://aws.amazon.com/ec2/">Elastic Compute Cloud</a> (EC2). Participants should come with some idea of a project that they'd like to start.

##Schedule
####Saturday
	
* Introductions
* Discussion
* Share project ideas, get feedback (optional)
* Creating a foundation for our application with [Node.js](http://nodejs.org/) / [Express](http://expressjs.com/) / Twitter Bootstrap
* [mongojs module](https://github.com/gett/mongojs) and [Mongolab](https://mongolab.com/welcome/)
* Introduction to MTurk: terminology, manually creating HITs, manual HIT management, Requester/Worker Sandbox


####Sunday

* [Mturk nodejs module](https://github.com/jefftimesten/mturk): Creating HITs from within our application, qualifications, fetching results, approving/rejecting answers
* If time permits, <a href="http://www.twilio.com/">Twilio</a> <a href="http://twilio.github.io/twilio-node/">for nodejs</a>
* Begin working on projects
* Deploying on EC2

##Prerequisites/Preparations

1. Please sign up for a <a href="https://www.mturk.com/mturk/">Mechanical Turk</a> account before the workshop. Amazon requires that you deposit money into your account before posting a job to Mturk. This money is used to pay the workers when/if they complete an assignment. Please deposit $10-$20 for the purposes of this workshop.
1.  As much as I would have liked to make this workshop language-agnostic, I don't see a way to do this without delving deep into the MTurk API, which is outside of the scope of what is possible in one weekend. With that in mind, I've chosen Node.js - mostly because I wrote the mturk nodejs module for a previous project. Therefore, in order to keep the focus of the workshop on MTurk and not Nodejs, some experience with Node.js and Express is required. If you've never these tools, please make sure to complete the following tutorials before attending the workshop. If have questions while completing these tutorials, please contact us. It also may be possible to arrange some private tutoring before the workshop.
	* [Express Guide](http://expressjs.com/guide.html) and [Express examples](https://github.com/visionmedia/express/tree/master/examples)
	* [Make yourself a MongoLab account](https://mongolab.com/signup/)
	* [Node.js and MongoDB - Getting started with MongoJS](http://howtonode.org/node-js-and-mongodb-getting-started-with-mongojs)
1. Please sign up for [Amazon Web Services](http://aws.amazon.com/) before the workshop. Note that there will be a nominal fee for starting a web instance for use in this workshop. If you are feeling ambitious and want to get a head start, check out [Ben Adel's tutorial on setting up an EC2 instance for a Node project](http://www.bennadel.com/blog/2321-How-I-Got-Node-js-Running-On-A-Linux-Micro-Instance-Using-Amazon-EC2.htm) or [a similar one for Windows](http://iconof.com/blog/how-to-install-setup-node-js-on-amazon-aws-ec2-complete-guide/)).
1. Please read the (mostly short) articles and check out the projects below

## Reading List

* [Representing Labor: Ten Thousand Cents and Amazon's Mechanical Turk](http://www.furtherfield.org/reviews/representing-labor-ten-thousand-cents-and-amazons-mechanical-turk)
* [What Does Crowdsourcing Really Mean?](http://www.wired.com/techbiz/media/news/2007/07/crowdsourcing)
* [&ldquo;I make $1.45 a week and I love it&rdquo;](http://www.salon.com/2006/07/24/turks_3/)
* [Internet as Playground and Factory](http://digitallabor.org/)

## Selected Projects

* [Social Turkers: Crowdsourced Dating](http://socialturkers.com/)
* [Descriptive Camera](http://mattrichardson.com/Descriptive-Camera/)
* [Crowd Workers of the World, Unite](http://www.crowdworkersoftheworldunite.com/)
* [Learning to Love You More](http://learningtoloveyoumore.com/)
* [The Johnny Cash Project](http://mashable.com/2010/10/27/johnny-cash-project/)
* [Aaron Koblin](http://www.aaronkoblin.com/): Sheep Market, Ten Thousand Cents, Bicycle Built for Two Thousand, The Single Lane Super Highway
* Shamless Self Reference: [Invisible Threads](http://www.jeffcrouse.info/project/invisible_threads.html) and [Laborers of Love](http://laborersoflove.com/)