# MACHINE_LEARNING_WITH_DEVOPS-MLOPS
  In this project we have integrated the machine Leraning with the DevOps as there are so many machine learning projects that never     intergrated due to the training time of the machine learning
# Task description
   # step 1 :
      create container image thtas has python3 and keras or numpy installed using Dockerfile .
   # step 2 : 
     when we launch this image ,it should automatically starts train the model in the container. 
   # step 3 :
     create a job chain of job1,job2,job3,job4 using build pipeline plugin in jenkins.
   # step 4 :
     job1 : pull the Github repoo automatically when some developers push repo to Github.
   # step 5 : 
     job2 : By looking at the code or programfile ,jenkins should automatically start the respective machine  learning software installed interpreter install image container  to deploy code and he start training (eg: if code uses CNN,then jenkins should start the container that has already installed all required for the cnn processing but in my case i use knist model ).
   # step 6 :
     job3 : traiin your model and predict accuracy or metrics , metrics accuracy is less than 80% ,then tweak the machine learninng model architecture.and Retain the model or notify that the best model is being created .
   # step 7 :
     job4 : one extra job (job4)for monitor: if container where app is running fails due to any reason then this job should automatically 
     start the container again from where the last trained model left.
# Built With 
  RHEL-8 Running in Virtual Box  \n
  Docker 
  Dockerfile 
  GitHub
  Jenkins
# Author
 Shyamendra pratan singh sengar
  
