# Section 1: Basics and Containers

**Question 1:**
You want to limit a container's memory usage to 512MB to avoid consuming all available system memory. Which option will you use in the docker run command?

1.     --memory=512mb
2.     --limit-memory=512mb
3.     --mem-limit=512m
4.     --resource-limit=512m

**Question 2:**
You need to run a container in detached mode while naming it web_app. Which command achieves this?
1.     docker run --detach --name web_app
2.     docker container create --detach web_app
3.     docker create web_app
4.     docker run web_app --detach

**Question 3:**
How can you restart all running containers at once?

1.     docker restart all
2.     docker restart $(docker ps -q)
3.     docker container restart
4.     docker service restart all

**Question 4:**
You want to see the real-time resource usage (CPU, memory, etc.) of running containers. Which command will you use?
1.     docker info
2.     docker stats
3.     docker ps -a
4.     docker usage

**Question 5:**

How can you forcefully stop a container that isn’t responding to the docker stop command?
1.     docker terminate
2.     docker kill
3.     docker container delete
4.     docker force-stop