k8s-slave
=========

     Connects k8s-slave servers to k8s-master  

Requirements
------------

CentOs 8 or later (7 may work)

Role Variables
--------------

N/A

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: k8s-slaves
      roles:
     - { role: kubernetes/k8s-slave }

License
-------

GNU

See also
------------------

* https://www.linuxsysadmins.com/install-kubernetes-cluster-with-ansible/
