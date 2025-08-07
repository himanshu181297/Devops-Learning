[200~# Day 5 – Jenkins Freestyle Job

## What I did:
- Set up Jenkins using Docker
- Created a Freestyle job
- Job runs a simple shell command

## Commands used:
```bash
docker run -d \
  --name jenkins \
    -p 8080:8080 -p 50000:50000 \
      -v jenkins-data:/var/jenkins_home \
        jenkins/jenkins:lts

