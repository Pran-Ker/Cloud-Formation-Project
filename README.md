# Cloud-Formation-Project
Deploying commerical level Launch Configuration using AWS Cloud Formation.

Cloud Formation is AWS Cloud Services' answer to creating and configuring AWS services through Yaml (in the form of code). This uses AWS CLI tool ( [TO DOWNLOAD](https://aws.amazon.com/cli/) ).

## USAGE

 1. Download the AWS CLI tool (given above) and configure it with your AWS account.
 1. Clone this repo on to your machine.
 1. In network folder you will be able to see a README which will explain where and how to create a similar diagram. This diagram is perfect for presentaions and getting a clear a picture on how you want the project to be.
 1. Alter the JSON file for changing the configuration of the different tools.
 1. In order to add or remove a certain tool (fundamental change), edit the YAML file.
 1. Run create.sh to create the stack (deploying using cloud formation).
 1. Run update.sh to change anything after deployment.
 1. Run delete.sh to delete the stack.
 
 ## TIPS
 
 For any doubts [click here](https://aws.amazon.com/cloudformation/)
 This link provides all the documentation required to configure the Yaml or Json files.
 
 Also, it is a good practice not to run update.sh, if there is an error. Instead delete and recreate it.
 
 DO NOT HARD CODE VALUES IN THE YAML FILE.
 This can cause alot of problems while scaling up or editing. 
 
