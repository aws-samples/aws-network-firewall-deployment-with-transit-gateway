---

---

# AWS Network Firewall deployment with Transit Gateway

This repository contains cloudofrmation template to deploy a single VPC with inspection using AWS Network Firewall. This helps you understand how to deploy AWS Network firewall with Transit Gateway. We will be seeing how we can include Inspection VPC (Network Firewall VPC).

AWS Network firewall is a Managed network firewall for a VPC with advanced filtering (including domain name filtering) capabilities and intrusion prevention. AWS Network Firewall automatically scales with your network traffic and can support hundreds of thousands of connections, so you don’t have to worry about building and maintaining your own network security infrastructure. AWS Network Firewall provides real-time firewall activity monitoring through Amazon CloudWatch metrics.

## Prerequisites

- You should have active AWS account
- You should have permission setup IAM role and policies
- You should have permissions to execute cloudformation template

## Code Principles:

- Writing DRY (Do No Repeat Yourself) code using a modular design pattern

## Usage

## Getting started

To make it easy for you to get started with GitLab, here's a list of recommended next steps.

Already a pro? Just edit this README.md and make it your own. Want to make it easy? [Use the template at the bottom](#editing-this-readme)!

## Add your files

- [ ] [Create](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#create-a-file) or [upload](https://docs.gitlab.com/ee/user/project/repository/web_editor.html#upload-a-file) files
- [ ] [Add files using the command line](https://docs.gitlab.com/ee/gitlab-basics/add-file.html#add-a-file-using-the-command-line) or push an existing Git repository with the following command:

```
cd existing_repo
git remote add origin https://gitlab.aws.dev/personal/network_firewall_transit_gateway_cloudformation.git
git branch -M main
git push -uf origin main
```

***

## Contributing
State if you are open to contributions and what your requirements are for accepting them.

For people who want to make changes to your project, it's helpful to have some documentation on how to get started. Perhaps there is a script that they should run or some environment variables that they need to set. Make these steps explicit. These instructions could also be useful to your future self.

You can also document commands to lint the code or run tests. These steps help to ensure high code quality and reduce the likelihood that the changes inadvertently break something. Having instructions for running tests is especially helpful if it requires external setup, such as starting a Selenium server for testing in a browser.

## Authors and acknowledgment
Show your appreciation to those who have contributed to the project.

## License
MIT license 2.0
