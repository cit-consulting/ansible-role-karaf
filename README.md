Role Name
=========

Ansible role for installation and configuration Apache Karaf container.

Requirements
------------

To use this role JVM version 1.7/1.8 should be installed on host.

Role Variables
--------------

TODO

Dependencies
------------

No external dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: esb-servers
      roles:
        - karaf

Multi instance use:

    - role: "karaf"
      karaf_service_name: "tesb54"
      karaf_os_user_name: "tesb54"
      karaf_ssh_port: "8102"
      karaf_rmi_registry_port: "1100"
      karaf_rmi_server_port: "44445"
      karaf_distr_name: "TESB_SE-V5.4.2"
      karaf_downoal_url: "ftp://10.192.0.50/Public/distr/TalendESB/TESB_SE-V5.4.2.tar.gz"


License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
