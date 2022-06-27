This readme file is created for task1, and elaborates that how the task was completed.

To complete the task, I followed below steps (details about these steps will be given later)
1. created a virtualmachine with docker and docker compose installed
2. created a docker image of jenkins built with docker daemon support
3. used that image to create a presistent jenkins container because my jenkins jobs or other data should not be cleared after reboot 
4. a docker compose file for creating jenkins container will be given in --infra directory
5. In that jenkins instance i installed two different jenkins plugin named Pipeline adn kubernetes deployment
6. set credentials for github, dockerhub in jenkins
7. created a three virual machines in order to create the kubernetes cluster. One for the master node and other two worker nodes.
8. used kubeadm, kubectl, kubelet and calico network for the cluster management (used commands will be given in --infra directory)
9. from the kuberbetes master note after kubeadm init i took the config file and put that in jenkins credentials under kubernetes config section.
10. after setting up the system structure i build the job 

N.B.: Due to my host machine's resource limitations i could not apply some portions of the task in my infrastructure, as example I could only created the system for app1.


##deployed the laravel app in kubernetes 

![running cluster](https://user-images.githubusercontent.com/87854710/175838522-a3b63512-49fb-41ca-a2f0-0dabca2da4e7.png)
