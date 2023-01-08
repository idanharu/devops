# DevOps Is Great
## How I did it
For refernce I used this: https://hub.docker.com/_/docker and https://www.jenkins.io/doc/tutorials/build-a-python-app-with-pyinstaller/ - Docker in Docker, it's not very recomended - probably will be bad with security here. Used ngrok to get webhooks from github: ngrok http 8080 - put the link inside github webhooks settings, and also put it in jenkins system configuration as the Jenkins URL with port 8080.
The files here are not complete.. but if you follow https://www.jenkins.io/doc/tutorials/build-a-python-app-with-pyinstaller/ steps so after getting jenkins up and running you need to install github pull request builder plugin, just create pipeline and put this github in the settings to work with the jenkinsfile and it's done.
need to check "Build every pull request automatically without asking (Dangerous!)." although it's dangerous - it will do what needs to be done.

Thanks for the opportunity, I've learned a lot from this exam.

Idan.
