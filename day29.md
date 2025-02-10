# TERRAFORM MODULES:

* 1 ===> Modules are small, reusable terraform configurations that allow us to manage a collection of related resources. modules serves a container for multiple resources that are used together or we can define module is a set of terraform configuration files(.tf files) in a single directory.

* 2===> Whenever we create a project we create a new directory , for example terraform-aws is folder name inside we have .(tf files), called root module.

* 3===> Even a single terraform configuration file in a directory becomes a module, we have diff types of modules child,root,etc.
 When terraform commands start executed directly from such  a directory, the content of that dir are considered to be  root module .

* 4===> We can largely define a module is a method for packaging and reusing the configurations of resources.
*        ==> for example, different environments like  dev,test,stage,prod
                           dev env ==> created dev directory then create tf files like  main.tf,provider.tf 
* To begin with dev env, create dev dir, then tf files same as for test,prod, stage.

*  5===> When building a project for diff env 40-50 resources created. wth same or slite modification do in other env we should copy and modify in other env.
* 6===> Repeated things in diff env, easily avoid with modules
 For dev env 1 resource need, pass parameters, then test env need 4 resources with the help of variables we can pass it.

* 7===> Redis Cache will different for different env, prod env have huge resource.
* 8===> Terraform Modules help us to group diff infrastructure resources into just one unified resources, so it implies that you can reuse them with possible customization without duplicating the resource block each time you require them, which is pratical for big projects with complicated designs


```
    sudo apt update -y
    sudo apt install httpd -y
```
