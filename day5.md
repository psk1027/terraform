


* required software installation
* how to write first terraform files?



* chocolatey software in windows 
* latest windows machine (terminal)
* choco installation
* chocolatey install in windows 
* installation terraform

* **install awscli:**
* execute once install this command
* aws --version
* why we need aws cli ?
* aws cli will authenticate & authorization the aws cloud by aws configure with access or secret key
* in tf with one single tf file you can manage the environments or you can create various diff env of infrastructure
* tf will allow parallel execution by multiple users across orginization.
* we need to learn how to write tf file ,hcl is same as json,yaml have key and value pair

* **important terminologies**
* 1. provider: where want to create the resources(aws,azure,gcp)
* 2. resource: the individual infra element to be created
* 3. modules: reusable templates
* 4. arguments: inputs are refered as argument
* 5. attributes: outputs are refered as atrributes
*tags: very imp key in managing in terraform

* every module has some version number ,in .tf we need to provide details

* terraform{ it is block
it is an argument
}
* post apply the resources is created and whatever the output we get we call it as attributes
* where it is stored access/secret key in dir .aws
* when we do aws configure ,by default it stored or create .aws folder(hidden folder)
* whenever you login to linux machine,we have to use pem key
* diff ways to login
for ex linux server in aws in mumbhai region, login to server from local laptop,by default aws provide ,vm or resource by using pem key or file like authentication
* by default passwd is disabled.
* by using third party software putty,git-bash,mobaxterm,superputty
*gitbash needs .pemfile,putty needs .ppk file,through a pem file we can create .ppk with the help of putygen
* terratest test our infra
