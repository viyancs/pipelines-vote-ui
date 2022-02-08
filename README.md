# Voting app for Tekton Pipeline examples

# Test
====
- change 1 
- change 2

# localhost.run integration reverse proxy
====
1. from local machine that can access to container using /etc/hosts 
2. setup ```
ssh -R 80:event-listener-git-pipeline-tutorial.apps.devocpcluster.imdevocplab.com:8080 localhost.run -vvv 
``` 
3. from container create new route from response url number 2
4. change git webhook to url number 2