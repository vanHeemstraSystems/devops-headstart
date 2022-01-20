# 700 - Learn Infrastructure Automation

We no more create servers manually. Infrastructure automation has become an essential aspect of every organization. 

As per a [report from Redhat](https://www.redhat.com/en/blog/red-hat-global-customer-tech-outlook-2019-automation-cloud-security-lead-funding-priorities), many organizations are investing in their automation initiatives. Check out this data.

![image](https://user-images.githubusercontent.com/12828104/150319900-c621fc07-19bc-4af6-beba-58612060974d.png)

From provisioning servers, application configuration, deployment, everything should be automated. You can learn any of the following [DevOps toolsets that fit your needs](https://devopscube.com/devops-tools-for-infrastructure-automation/).

| For Dev Environment |
| --- |
| Vagrant |
| Docker Desktop |
| Minikube |
| Minishift |

| For infrastructure provisioning |
| --- |
| Terraform |
| CLIs (of respective cloud provider) |

| For Configuration Management |
| --- |
| Ansible |
| Chef |
| Puppet |
| Saltstack |

| VM image management |
| --- |
| Packer |

Here are my tips on learning automation tools

1. Learn the basics from the official documentation or through a course.
2. If you want to write an Ansible playbook for Nginx, first configure Nginx manually and see how the components and configs work. Then start writing the playbook.
3. Ensure you learn test-driven infrastructure development. There are testing tools for every automation tool. ([Ansible-test](https://www.ansible.com/blog/introduction-to-ansible-test), [terratest](https://terratest.gruntwork.io/) etc.)
4. Community modules are a great reference to learn. You can learn complex logic from community modules.
5. When using community modules, ensure you know what each block of code does.

**Resources:**
1. [Learn DevOps: Infrastructure Automation With Terraform](https://devopscube.com/recommends/terraform-course/)
2. [Ansible for the Absolute Beginner – Hands-On – DevOps](https://devopscube.com/recommends/ansible-course/)
