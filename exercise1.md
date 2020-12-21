# Exercise 1 of part 11 in Fullstack Open

### This text will focus on tools and for Python

If JavaScript has Eslint, Python has Pylint. Pylint can be run from the command line and will give similar feedback, e.g. for unnecessary semicolons.

For testing Python code, there are also several options. One simple example is the assert keyword, with which you can test if a condition is true.
There are also testing libraries in Python one can import, e.g. unittest and pytest.

As Python is an interpreted language, the build step is more about test execution than compiling the code.


### Alternatives for Github Actions and Jenkins

One alternative is a service called Buddy. It has a lot of ready-to-use actions for your pipeline and good integration possibilities.
Another one is TeamCity from JetBrains. I guess this could be a good choice for developers using other Jetbrains software, such as IntelliJ Idea and PyCharm.
And to list a few others:
  - GoCD
  - Bamboo
  - Gitlab CI
  - Codeship
 
### Self-hosted or cloud-based?

A self-hosted setup will give you more control over the setup but will also mean more work as you need to keep the setup up-to-date.
Another concern is security. As security is such a varying topic, it would be better to go with a cloud-based setup instead of your own. It takes a ton of work to keep the security up-to-date by yourself.
Self-hosted service is probably going to be cheaper to use.
A big part of the setup is also its integration possibilities and cloud-based services have the upper hand in there as they usually have several other systems where they can be integrated with little to no work.
