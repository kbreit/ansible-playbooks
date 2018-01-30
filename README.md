# ansible playground
This is a lab where I can experiment with Ansible. Do not consider these to be production playbooks.

## update-all.yml
Updates all Linux servers defined in the inventory. Simple and straightforward.

## docker-httpd.yml
Creates an AWS environment to display a web page. Provisions the following items:

* ASG
* ELB
* Route53 based subdomain
* Docker
* Apache container

## docker-https-delete.yml
Delete most of the items created in the previous playbook.