Role
=========

Automated monitoring for distributed SQS queues using Ansible

Requirements
------------

* AWS CLI installed, Configure a named profile with AWS Credentials. Refer https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-configure.html#cli-quick-configuration
* Complete variable `sqs_base_url` with ***AWS Account ID***

Role Variables
--------------

* Definition for the queues.
* Defintion for team alert groups


Run Playbook
----------------

    ansible-playbook install.yml



