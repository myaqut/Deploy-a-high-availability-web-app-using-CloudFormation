## Deploy a high-availability web app using CloudFormation

The following project includes deploying AWS infastructure on both server and network level in order to deploy a web app. The project includes the following parts :
- Diagram : describes the design of the network.
- Template Files: two yml files in order to deploy the network and the servers.

### Steps For Run:
1. Run the following command in the directory of the create.sh file. ``./create.sh Stack-Name network.yml network-parameters.json  us-east-1 ``

2. Run the following command in the directory of the create.sh file. `` ./create.sh Stack-name servers.yml server-parameters.json  us-east-1``

3. Get the DNS name from the load balancer section and paste it in your browser.


### Load Balancer DNS:
    proje-WebAp-1KFHIGBUHO2IA-204652255.us-east-1.elb.amazonaws.com
