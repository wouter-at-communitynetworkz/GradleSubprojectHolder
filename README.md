# GradleSubprojectHolder
## Parent project to contain subprojects

Directory app contains a gitsubmodule tagged src, referring to depository LogToLogstashConsumer, containing a java main method, used to test LogToLogstash library  
and  
directory common contains a gitsubmodule tagged src, referring to depository LogToLogstash

Clone this repository with the --recurse-submodules flag: 


    git clone --recurse-submodules https://github.com/wouter-at-communitynetworkz/GradleSubprojectHolder.git
    
    
then run 

    gradle build

and  

    gradle run

