# docker-Related-Cmds

# To check docker is properly installed or not
--------------

1. docker -v
2. docker run hello-world

-----------------------------------------------------
# Intallation method 1

1. install docker software and dockerized supported sandbox
    (hortonworks sandbox, most probably)



2. suppose sandbox name is hdp3.



3. go into that directory. cd hdp3.



4. sh <scriptname>.sh [This process will take some time, it'll download
                         the docker image for sandbox.]
    for eg: ./docker-deploy-hdp.sh [ in linux]
            sh docker-deploy-hdp.sh [ maybe in windows, or search google]

- verify hdp sandbox was deployed successfully by this cmd:
     ---> docker ps

5. After that process. Run this url on browser
   ---> 127.0.0.1:1080/splash.html or, 
   --> sandbox-hdp.hortonworks.com:1080 (any one open port server address)
    
    
    ----------------------------------------------------------

docker and sandbox error mitigations
-----------------

Go to this link for error documentation: 
https://medium.com/tech-weekly/cloudera-sandbox-deployment-and-install-guide-6ae12bffe03e



-----------------------------------------------------------

By Shubham Dhungana
