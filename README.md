# starters-aws-cloudformation-configurations
Creating a personal hello world cloudformation configuration on aws, as away to setup an EC2 Instance. This has two security groups configurations and using parameters defined within the same file.

## Add execution permissions to the script files - cli
- ``chmod +x create.sh update.sh``

## Create cloudformation stack - cli
- ``./create.sh STACK-NAME network.yaml``

## Update cloudformation stack - cli
- ``./update.sh STACK-NAME server.yaml``

### AUTHOR
- Matembu Emmanuel Dominic
