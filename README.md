# GradleSubprojectHolder
## Parent project to contain subprojects

##### Combine git submodules and gradle multi project setup

Directory app contains a gitsubmodule tagged src, referring to depository LogToLogstashConsumer, containing a java main method, used to test LogToLogstash library  
and  
directory common contains a gitsubmodule tagged src, referring to depository LogToLogstash

Install gradle if needed.

Clone this repository with the --recurse-submodules flag: 


    git clone --recurse-submodules https://github.com/wouter-at-communitynetworkz/GradleSubprojectHolder.git
    
    
then run 

    gradle build

and  

    gradle run


---

see http://blog.joncairns.com/2011/10/how-to-use-git-submodules/

and 

https://rominirani.com/announcing-gradle-tutorial-series-5fd134223bf8

https://rominirani.com/gradle-tutorial-part-1-installation-setup-2ea77729fc8c

https://rominirani.com/gradle-tutorial-part-2-java-projects-5aaf99368018

https://rominirani.com/gradle-tutorial-part-3-multiple-java-projects-5b1c4d1fbd8d


and

https://docs.gradle.org/current/userguide/application_plugin.html

