# Ansible
Created by AnhNV Created Date: 2/4/2018

This document provides informaion about the following:

- Overview Ansible
- Install Ansible on Window
- Required on Managed node
- Configuring Ansible file


**Reference**:

## 1. Overview
* Ansible is a redically (căn bản) simple IT automation platform that makes your application and system easier to deploy. Avoid writing scripts or custom code to deploy and update your applications - automate in a language that approaches plain English, using SSH, with no agents to install on remote systems.

## 2. Install Ansible on Window systems
* Enable Window subsystem for Linux:
  * Access: Windows > Settings > Update & Security > For Developers
  * Select **Developer mode**
  * Select Control Panel > Programs and Futures > Turn Windows feature on or off
  * Select Window Subsystem for Linux, click OK
* Open Ubuntu bash script:
  * Run these commands:
    ```
    $ sudo apt-get update
    $ sudo apt-get install software-properties-common
    $ sudo apt-add-repository ppa:ansible/ansible
    $ sudo apt-get update
    $ sudo apt-get install ansible
    ```
## 3. Required on Managed Node (node được điều khiển bởi control node)
* Install Python 2.6 or later
## 4. Configuring ansible
- Certain settings in Ansible are adjustable via a configuration file **(ansible.cfg)**
- The configure file locate at ``/etc/ansible``
