# Backend Coding Challenge

Here is a quick coding challenge. It's important to note that it's by no means a test with a single correct answer, we just want to get a sense for how you write code and approach solving problems.

You'll be building a simple component for managing communications with our customers: a templating service:

![Templating Service Overview](assets/img/overview.svg)

 In short, think of it as a small communications hub which provides the following functionality:

* Agents can manage a set of stored templates in terms of create, retrieve, update, and delete
* Systems can generate and send messages using the templates over a channel by indicating a payload like:
    * the template to be used
    * the set of metadata to bind
    * the channel
    * and the destination information relevant to the channel
* Not all templates should be able to be sent over all channels

### Instructions

* We prefer Java with Spring Boot, building with Maven -- or Go with go-kit, building with Make ourselves, but please choose the framework within the two languages you are most comfortable with currently to approach the challenge 
* Our agents can create, read, update, and delete templates
* Templated messages can be sent over a variety of channels, e.g. SMS, E-Mail, Push Notification, Carrier Pidgeon, etc.
* We don't expect the channels to work and you don't need to implement the consumer services, behaviour for sending over a channel from the templating service can be faked and simply log the fact
* You do not need to worry about authentication and authorization of agents or systems for now
* You're free to use as many third party libraries that you see fit

### Do I need to write tests?

As mentioned we just want to get a sense for how you write code and solve problems, so treat this as any other piece of production code you deliver using the test toolchain of your choice.

### Submitting your results

* The results have to be shared as a git repository
* You can either create a public repository on your favourite git hosting provider (GitHub, GitLab, BitBucket) and share the link
* Or send the whole repository, zipped (including the .git directory!)
* Please include both build and run instructions, we use a mix of Windows and Mac on our end
* Important note, please only submit your challenge when you feel you are completely done!
