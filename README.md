k8s-master 
=========

Installs  - Kubernetes Stack (kubeadm,kubectl,kubelet)
          - Containerd
          - Helm3 
      

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

    - hosts: k8s-masters
      roles:
     - { role: kubernetes/k8s-master }

License
-------

GNU

See also
------------------

* https://www.linuxsysadmins.com/install-kubernetes-cluster-with-ansible/
