# cka_2nd_edition_live_lessons_by_pearson
A Terraform module to spin up a CKA cluster required for the CKA 2nd Edition Video course published by Pearson IT Certification


### General information
The Packer shell script still needs some work, I missed a script the instructor created thats needed to create the lab.  

WIP 


Each AWS resource is a Terraform root module, which is created by calling modules from various [terraform-aws-modules](https://github.com/terraform-aws-modules) repos.  

WIP

## I should have this wrapped up soon, holidays were busy

## requirements
```
user ~ $ ssh-keygen
..
..

user ~ $ ll .ssh|grep cka
-rw-------   1 user  staff   2.5K Nov  8 15:48 cka_lab_rsa
-rw-r--r--   1 user  staff   578B Nov  8 15:48 cka_lab_rsa.pub
user ~ $
```
WIP
### INPUTS
my_current_ip 

WIP - create table
### OUTPUTS
```
kube_controller_public_ip

```
WIP - create table
