## Questions
----
Q1: What are the 4 values of Agile development ?

Q2: One of the core feature of *Git* is branching. When working in a project, more often than not you may have many branches. Why is that, why should we have branches ?

Q3: When you finish your project now you need to deploy it, but what is *Deploy* ?

Q4: How can you choose which framework to use ?

Q5: You have learned about *Scrum* and heard about *Agile* but isn't it the same thing ? What is the difference?

## Answers
----
A1: The 4 values of Agile development is

1. **Individuals and interactions** over processes and tools
2. **Working software** over comprehensive documentation
3. **Customer collaboration** over contract negotiation
4. **Responding to change** over following a plan

Ref: [Agile manifesto](http://agilemanifesto.org/)

A2: When you're working on a project, you're going to have a bunch of different features or ideas in progress at any given time – some of which are ready to go, and others which are not. Branching exists to help you manage this workflow.

When you create a branch in your project, you're creating an environment where you can try out new ideas. Changes you make on a branch don't affect the master branch, so you're free to experiment and commit changes, safe in the knowledge that your branch won't be merged until it's ready to be reviewed by someone you're collaborating with.

Ref: [Understanding Github flow](https://guides.github.com/introduction/flow/)

A3: Software deployment is all of the activities that make a software system available for use, including things like

* Setup and configure environment (ex. Server)
* Install your software on that environment.
* Update and replace earlier version.
* Doing CI/CD

A4: Consider following

* Timing

  We often have a short time for delivering a project and introducing a new framework will almost certainly cause delays. Therefore in terms of planning ahead on timing we must check the quantity of code that this framework will make us write. Not only the actual time that we will take to write it, but also how complex will the code that you and your team will have to write as it will also cause a not little time loss.

* Technical properties and features

  Is the framework suitable to the type structure that we have or that we would like to implement?
  
  Will it be better in terms of performace?

  If we are choosing a front-end framework it is important to check the cross browser compatibility.

  You need to know the basics: to be able to choose a framework correctly you need to know the basics and the requirements to fully comprehend it. 

* Community involvement

  How many people talk about it on the web?
  
  How many people keep using it?
  
  How frequently does the developer answer to the issue reports?
  
  How many pull requests?

* Consequences of choice

  Before finalizing the choice we should take a moment to think about the possible consequences of what the choice of the new framework could result in, in your development environment.

Ref: [How to choose framework: Hackernoon Medium](https://hackernoon.com/how-to-choose-a-framework-ea8b5b1e1f44)

A5: Agile is a software development method while Scrum is one of a incremental agile software development method. So, scrum is a type of Agile approach. Specifically scrum is a project management framework for Agile approach.

Ref: [Scrum: Wikipedia][1]

  [1]: https://en.wikipedia.org/wiki/Scrum_(software_development)
