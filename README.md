POSTFIX SMARTHOST
=========

A quick role that installs postfix (if needed) and then sets the Relayhost (smarthost) to a value provided through a variable

Requirements
------------

Written against Ansible 2.4.0.0 

Role Variables
--------------

postfix_relay_host: "smarthost.domain.org"

Dependencies
------------

No existing dependencies

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles: 
        - { role: jhu-sheridan-libraries.postfix-smarthost, postfix_relay_host: "smtp.domain.org"}

License
-------

TBD

Author Information
------------------

Derek Belrose <dbelrose@jhu.edu> Johns Hopkins University,  Sheridan Libraies 
