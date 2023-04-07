# Web stack debugging #
Debugging is the process of finding and fixing errors in software that prevents it from running correctly. As you become a more advanced programmer and an industry engineer, you will learn how to use debugging tools such as gdb or built-in tools that IDEs have. However, it’s important to understand the concepts and processes of debugging manually. This project covers a second part of the optimal framework and blueprint for debugging web stack (remote containers this scenario) bugs

Challenge:

Using your debugging skills, find out what’s keeping your Ubuntu container’s Nginx installation from listening on port 80. Feel free to install whatever tool you need, start and destroy as many containers as you need to debug the issue.

This was the second in a series of web stack debugging projects. In these
projects, I was given broken/bugged webstacks in isolated containers,
and tasked with fixing the web stack to a working state. For each
task, I wrote a script automating the commands necessary to fix the
web stack.

## Tasks :page_with_curl:

* **0. Nginx likes port 80**
  * [0-nginx_likes_port_80](./0-nginx_likes_port_80): Bash script that
  configures Nginx to run and listen to port 80 on all of a server's active IPv4's.

* **1. Make it sweet and short**
  * [1-debugging_made_short](./1-debugging_made_short): Bash script that
  configures Nginx to listen to port 80 without running on all of a server's
  active IPv4's.
