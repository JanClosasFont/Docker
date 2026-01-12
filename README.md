<h1 align="center">Docker</h1>
<h2>Introduction</h2>
This repository should serve as a guide for me and anyone willing to learn how dockers actually works, a repository which i will keep updating with more advanced stuff, both theorical documentation and practical examples such as containers i create myself. 

<br> I created this repository as inspiration from THM (TryHackMe), a web page with a full load of activities and challenges for any technician out there hopping to learn about cybersecurity and more.

<h2>basic concepts</h2>
Docker is used to execute code and create an accesible link via any port, being really useful to host any code with only the necesary resources. Although it is quite useful to include Docker in your personal or educational projects, it can sometimes be a little confusing to use, that is why before any practical example i am gonna explain some basic concepts to, at least, understand at first what we are working on.

Let's start with what we create when using Docker; Containers. Containers is what we use to run our code and manage the mentioned one.

Creating a container is like baking a cake actually, as you need an image (not the images and photos you may have stored in your phone) to run it, similar to how you put the dough inside the oven. Before that, the dough (image) has to be made obviously, and that can be accomplished by mixing a Dockerfile and simple application code.

At last, we just need to know how to obtain these two inngredients. A Dockerfile is a simple text document with a bunch of commands and instructions to create the image, and there are a lot of images out there, modified to fulfill the owner's requirements. The code can be made by yourself or taken from others, for example, public projects from others on github.

All these actions can be interpreted via command line, both in the CMD system (Windows, Linux...) or through the one in Docker Desktop.

<h2>installation process</h2>
Installing Docker Desktop (which is recommended for a better experience) is as simple as following the installation guide shown when executing the .exe downloaded from https://www.docker.com .

<br> I will not further develop this section unless i find any complementary process which requires installation for Docker.

<h2>Commands</h2>
When running containers, we need to know or have noted down a couple necesary commands, which will be listed below:
- Docker run.- Execute containers
- Docker ps.- Lists existing containers
- Docker images.- Lists images
- Docker pull.- Download image
- Docker start.- Start or run a container
- Docker stop.- Stop or power down a running container
- Docker restart.- Reboot a container
- Docker rm.- Delete (remove)

The current section will be updated on the future, constantly adding more basic and useful commands that i learn about. (12/01/2026)

<h2>First dockerfile</h2>

<h2>Docker volumes</h2>

<h2>Docker compose</h2>

<h2>Common errors</h2>

