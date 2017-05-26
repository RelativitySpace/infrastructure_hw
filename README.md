## Relativity Space - IT/DevOps candidates' homework
This readme contains problems that candidates can choose to work on as a take-home assignment

### Instructions:
1. Make a repo in github
2. Please solve one or both (optional) of the problems from this repo
    * Depending on your time and level of enthusiasm about the problem you can choose to do only parts of the problem
3. Once done send the link to your repo back to your interviewer
4. Please don't for repo - make sure you make a separate repo for your solution

Open an issue on this repo if you have any questions about the problems.

Adding clarification and description as comments or readme file is welcomed if needed.

### Problem 1: Wrong google search
The goal is to deploy an ngnix server on ubuntu that that reverse proxies google.com but with a catch. Every search that includes "rockets" should be turned into search about "Relativity Space". For example if I go to this server in my browser I will be presented with google's page and if I search for "rockets" I should get results about "Relativity Space".
- Script should be stand alone. I should be able to run it on an ubuntu box with admin access and then hit localhost and get the google page (It should include downloading and installing ngnix and then configuring it to do reverse proxy)
- It doesn't need to support https - http is fine
- Bonus points for deploying the ubuntu image with reverse proxy on it as a docker image in docker hub

### Problem 1: PowerShell deleter
The goal is to write a PowerShell script that accepts three parameters from command line. First is an absolute path to a folder and next two are dates in following format: 'HH mm yyyy dd MM'. The script should then recursively look in all the folders within the path provided and delete files that have been created between the first date and second date provided, and additionally include the word "Copy" in their name.
