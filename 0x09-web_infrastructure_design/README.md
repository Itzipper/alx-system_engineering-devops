0x09. Web infrastructure design

Requirements General A README.md file, at the root of the folder of the project, is mandatory For each task, once you are done whiteboarding (on a whiteboard, piece of paper or software or your choice), take a picture/screenshot of your diagram This project will be manually reviewed: As each task is completed, the name of that task will turn green Upload a screenshot, showing that you completed the required levels, to any image hosting service (I personally use imgur but feel free to use anything you want). For the following tasks, insert the link from of your screenshot into the answer file After pushing your answer file to GitHub, insert the GitHub file link into the URL box You will also have to whiteboard each task in front of a mentor, staff or student - no computer or notes will be allowed during the whiteboarding session Focus on what you are being asked: Cover what the requirements mention, we will explore details in a later project Keep in mind that you will have 30 minutes to perform the exercise, you will get points for what is asked in requirements Similarly in a job interview, you should answer what the interviewer asked for, be careful about being too verbose - always ask the interviewer if going into details is necessary - speaking too much can play against you In this project, again, avoid going in details if not asked

Tasks To Complete 0. Simple web stack 0-simple_web_stack contains the URL of an image containing the design of a one server web infrastructure that hosts the website that is reachable via www.foobar.com. Start your explanation by having a user wanting to access your website.

Components to be used in the design:

✔ 1 server.

✔ 1 web server (Nginx).

✔ 1 application server.

✔ 1 application files (your code base).

✔ 1 database (MySQL).

✔ 1 domain name foobar.com configured with a www record that points to the server IP 8.8.8.8..

Distributed web infrastructure
On a whiteboard, design a three server web infrastructure that hosts the website www.foobar.com.

Requirements:

You must add:

✔ 2 servers

✔ 1 web server (Nginx)

✔ 1 application server

✔ 1 load-balancer (HAproxy)

✔ 1 set of application files (your code base).

✔ 1 database (MySQL).

Secured and monitored web infrastructure On a whiteboard, design a three server web infrastructure that hosts the website www.foobar.com, it must be secured, serve encrypted traffic, and be monitored.
Requirements:

You must add:

✔ 3 firewalls

✔ 1 SSL certificate to serve www.foobar.com over HTTPS.

✔ 3 monitoring clients (data collector for Sumologic or other monitoring services).

Scale up Application server vs web server Requirements:
You must add:

✔ 1 server

✔ 1 load-balancer (HAproxy) configured as cluster with the other one

Split components (web server, application server, database) with their own server
