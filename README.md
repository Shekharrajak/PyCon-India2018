# PyCon-India - Hyderabad - 2018


### Slides [Not finalized]

https://slides.com/shekharrajak/deck-7#/

### Contents

Selected topics from the books:

* [Docker in Action](https://books.google.co.uk/books/about/Docker_in_Action.html?id=Lt_BsgEACAAJ&redir_esc=y&hl=en)
* [Docker in Practice](https://books.google.co.uk/books?id=ODLPswEACAAJ&dq=docker+in+practice&hl=en&sa=X&ved=0ahUKEwjP1vG2s77bAhXSQ8AKHQYTA4sQ6AEIJzAA)
* [Docker up and Running](https://books.google.co.uk/books?id=IDvcCQAAQBAJ&printsec=frontcover&dq=docker+in+production++amazon&hl=en&sa=X&ved=0ahUKEwiFn5fSs77bAhXQN8AKHcRlAP0Q6AEIMzAC#v=onepage&q=docker%20in%20production%20%20amazon&f=false)
* [Orchestrating Docker](https://www.amazon.co.uk/Orchestrating-Docker-Shrikrishna-Holla/dp/1783984783) 
* I will be refering topics from other books like Pro Docker, The Docker books.

-----------------

# Containerizing Your Application is the solution

What's a good way to Set up **many** development version(s) ? Developers need **consistent isolated**  development environment, running exact same container(s) as what **runs in production** , automated **test** tools, package, **ship** & deliver. Let's touch features of docker to make it run for **Python** programs/web apps.

# Description

**Outlines**

*  First 5 minutes, I'll be talking about current developers need and present solution.
* Next 5 minutes, what is [docker](https://www.docker.com/) and how it can solve these problems.
* Next 10 minutes, I'll be demonstrating, how I use docker for in my Python development tasks (Python library, Python web app).
* After 20 minutes I will have delivered the enough knowledge for the docker, and next 5 minutes I will let the audience know about the some advance features in docker that they can learn from various resources, to get the maximum power of docker. Q/A along with this.

**Detail description**

[Wikipedia says](https://en.wikipedia.org/wiki/Docker_(software)) : 

"Docker containers wrap up a piece of software in a complete filesystem that contains everything it needs to run: code, runtime, system tools, system libraries — anything you can install on a server. This guarantees that it will always execute the same, regardless of the environment it is running in." 

**Basic terms of docker** 

* [Docker Container](https://www.docker.com/what-container)
* [Docker Image](https://docs.docker.com/engine/reference/commandline/images/#list-image-digests)
* [Dockerfile](https://docs.docker.com/engine/reference/builder/)
* [Docker Compose](https://docs.docker.com/compose/)
* [Docker Repository and Docker Hub](https://docs.docker.com/docker-hub/repos/)
* [Docker Daemon, Docker Client and Docker Engine](https://docs.docker.com/engine/docker-overview/#docker-engine)
* [Docker Swarm](https://docs.docker.com/engine/swarm/)
* [Docker Machine](https://docs.docker.com/machine/)

**Docker for Developers**

* Reproducibility and Developer teams
* Isolation
* Security
* Environment Management
* Continuous Integration

**Creating Custom Images and Containerizing Your Application**

Sample Dockerfile to **build** an image of an small python program. We will **run** the image and play with this container. Using Docker Compose in development adds an important constraint: your services are not on the same machine anymore.

**Container Logs**

Learn how you can see or capture the logs of  the container(s) and services. 

**Docker for Python developers**

In this section I will demonstrate, how you can setup a development version of real world software.
I will setup the development version.  After creating an image and running it in a container, I will show volume sharing techniques as well. Audience will understand how I have created an consistent isolated container,  integrated CI which is easy and fast to ship.

**Docker for Python Web applications**

Django and Flask web app will be run under the docker container, different environments in one system. We will learn how to use microservices and advantages of making services using docker-compose.

**Advance and new features of docker** 

Now audience have understood the docker and they can learn many more powerful features of docker. I will share some good resources and let them know about docker swarm,  docker machine, Dealing with Logs, etc .

# Prerequisite

Prior experience with docker is not a necessity but having some exposure to Python development, version control system, Unix System is recommended.

At the starting talk basic developers need, basic docker features will be covered. So **starting point, anyone (entry/intermediate)** can understand the docker concepts. Slowly moving to **docker for developers, expert Python developers** will get ideas to use docker in their development system and how they can solve most of the development conflicts because of using having multiple environments.

# Speaker

A guy who loves challenging stuffs and learning new technologies along with the 'Time'. Shekhar has learnt C, C++, Java in his college time and worked as student developer in Google Summer of Code (GSoC) 2016 (under [SymPy][1] organisation - Python language) and 2017 (under [SciRuby][2] organisation - Ruby language), also contributed to open source projects like [bundler][3] gem. Shekhar is mentoring 3 Projects in [GSoC'18][4]. Currently he is working in Benguluru India as Software developer (Angular 5 & Spring boot). Shekhar loves playing chess, cricket watching and reading about ancient India, spirituality and travelling.


  [1]: http://www.sympy.org/en/index.html
  [2]: http://sciruby.com/
  [3]: https://bundler.io/
  [4]: https://summerofcode.withgoogle.com/
  
  # Speakers Link:
  
  1. [Shekhar's personal webpage][1]
 2. [Blog][2]
 3. [Github][3]
 4. [Twitter][4]
 5. [LinkedIn][5]


  [1]: http://s-hacker.info/
  [2]: http://shekharrajak.github.io/
  [3]: https://github.com/Shekharrajak
  [4]: https://twitter.com/Shekharrajak
  [5]: https://in.linkedin.com/in/shekharrajak
  
