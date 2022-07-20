# BANK-NOTE-AUTHENTICATION
### The Objective of this project is to predict whether the bank note is authenticated or not
Why Dockers?

      For Example, you are shifting the house, While shifting you forget some items in the previous house, in order to overcome this, 
while we shift you place all items in a container and move to the new house. So, the problem of forgeting items in the previous house has overcome by using cantainer.

      In IT industry , for example Developer A has created web application in a system with some system configuration like Operarting System, Ram, CPU etc. 
 Now the developer had given this web application to testing team. Testing team has different system configuration then the web application is not working
 because the system configurations are different. The Machine Learning application depends on Operating System for example if the first system is Linux and 
 second system is windows  in this case their is a lot of library compatability issues will come. To Prevent this we will put all the application in a container called DOCKER CONTAINER and gives to testing team.

Advantages of Dockers

Environment Standardization
Build Once , Deploy it anywhere
Isolation
Portability


Lets Talk about what was the problem using Virtual Machine and how dockers is solving the problem:-
   For example i have 3 Virtual Machines V1,V2,V3 with diffferent configuration. The Main disadvantage is if V1 is not used more & V2,V3 are used heavily the
   resources of V1 is not used by the V2,V3 i.e the unused resources of V1 is not allocated V2 and V3.


-->Dockers are used to solve the above problem, in dockers the concept of virtualization is used i.e on top of the operating system we create dockers and each 
dockers as its won properties, id,root folder, Network Configuration i.e Port Number etc. For example we crated 6 dockers on top of the operating system App A,App B,App C,App D,App E,App F. If App C is not utilized more App A,App B,App D,App E,App F can utilize the resouces of App C.

Dockers with Machine Learning:-
        Whenever we create project in conda environment we usually create new environment with library mentioned in requirement.txt  i.e it looks like we are 
        creating separte virtual machine with library mentioned in requirement.txt. After creating environment, we create the environment as docker container. 
        This container can be deployed anywhere.


class o represnets fraud & class 1 represents not a fraud.
Random Forest Classifier is used for model creation
By Using Random Forest Classifier got an accuracy score of 98%
Created the Pickle file
Deployed model using Flask, Flassger and Dockers
Contanarized the model using dockers
