# kubernetes-project
Create yaml formatted Kubernetes manifest for below task
1 - Run uname command in a single busybox container. The command should run every minute and must complete within 10 seconds or be terminated by Kubernetes. The CronJob name and container name should be both be "hello"
2 - Create a pod named myapp with 4 containers, using nginx, redis, memcached, consul images
3- Find a pod which is using the most CPU resources and pipe the name to report.txt file 
    - create the report.txt file
4- Create a new pod, from redis image, running in web namespace and listening at port 9090
    - create the namespace if it doesn't exist
5- Create a pod in test namespace and set resource limit to 1Gi of memory and 200m CPU 
    - create the namespace if it doesn't exist
Done by Mustafa Calik
