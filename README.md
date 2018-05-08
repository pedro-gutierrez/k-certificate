# k-certificate

A simple ansible role to manage Kubernetes CSR approvals

Example Playbook
----------------

Deleting existing CSRs

    - hosts: servers
      roles:
         - role: pedro-gutierrez/k-certificate
           pattern: "some.name"
           action: delete
           
         - role: pedro-gutierrez/k-certificate
           pattern: "some.name"
           action: approve
         

License
-------

BSD
