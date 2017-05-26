## Relativity Space - IT/DevOps candidates' assignment
This readme contains assignment for infrastructure candidates

### Instructions:
1. Make a repo in github
2. Please solve both of the problems in this repo and provide the solution in your github repo
    * Depending on your time and level of enthusiasm about the problem you can choose to do only parts of the problem
3. Once done send the link to your repo back to your interviewer
4. Please don't fork this repo with solutions

Open an issue on this repo if you have any questions about the problems.

Adding clarification and description as comments or readme file is welcomed if needed.

### Problem 1: Wrong google search
The goal is to deploy an nginx server on ubuntu that reverse proxies google.com but with a catch. Every search that includes "rockets" should be turned into search about "Relativity Space". If I go to this server in my browser I will be presented with google's page and if I search for "rockets" I should get results about "Relativity Space".
- I should be able to run your submitted script on an ubuntu box with admin access and then hit localhost and get the google page (It should include downloading and installing nginx and then configuring it to do reverse proxy)
- It doesn't need to support https - http is fine
- Bonus points for deploying the ubuntu image with your reverse proxy as a docker image in docker hub

### Problem 1: PowerShell deleter
The goal is to write a PowerShell script that accepts three parameters from command line. First is an absolute path to a folder and next two are dates in following format: 'HH mm yyyy dd MM'. The script should then recursively look in all the folders within the path provided and delete files that have been created between the first date and second date, and also contain the word "Copy" in their name.
