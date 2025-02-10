





* tf is  free and opensource tool which is developed by hashicorp(ibm acquired in 2024april)
* hashicorp founder mitchell hasimoto ,armon dadgar
* tf written in go language
* tf defines the resources and infrastructure in human readbale format.
* for ex: key and value {}
* tf follows hcl (hashicorp configuration language), declarative config uration and manages your infrastructure lifecycle.
* as a being devops engineer write tf files with .tf extension.
*in tf we have keywords like provider , resources,module and conditional statements any prog language have programming constants
* in tf no syntax and no space issue.
* go defined the app in easy way
* when we install tf internally (tf engine in go lang)
* files communicate with tf engine
* in tf the code look like yaml and json format
* all inspired by java ,json query,xml,yaml,jmespath,jq,yq
* what is tf lifecycle?
* tf will allow you to build change and version the infrastructure safely and efficiently.
*tf creates the infra in almost all the cloud platform like public cloud , private cloud , kubernetes ,saas (outh vmware workstation(onpremise)) mostly in cloud
it does with the help by using tf providers , providers are like plugins , plugin is like software or like api any cloud platforms communicate with the help of api you will be able to communicate with the api (it needs url username and paasword) later it coommunicate
how the providers are going to get by register (then we called terraform registry)
* tf is stateful applications , it keeps track of everything it builds in your cloud envi ,maintain state of every resources which is been created.
*k8s cluster stateful ,maintains all the pods
* tf will create state file (tf.tfstate)(in json format)

* **tf-adv**

*tf can manage infra on multicloud platforms(aws,azure) complex architecture 
* the tf config files are human readable format that helps you to write the code quickly.
* tf statefile allows you to keep track of resources changes throughout the deployment.
* you can even commit your configuration files to some version tools (git) to safely collabrate on infrastructure.
* version tool ==> jira ==> user stories
* 