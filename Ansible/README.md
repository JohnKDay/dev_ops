#Open vStorage goes Ansible!

##Description
The Open vStorage support team has created an easy way to install your future, high-performance, highly-scalable cloud through Ansible. 

##Manual and more information...
https://openvstorage.gitbooks.io/openvstorage/content/Installation/index.html

##Compatibility
* Open vStorage HyperScale (Enterprise Level Cloud)
* Open vStorage HyperConverged (Small - Medium level Cloud)

##Known bugs
* For installing apt packages we've used the general bash command instead of the APT module of Ansible due to a bug: https://github.com/ansible/ansible/issues/13980, this has been patched (https://github.com/ansible/ansible/pull/14168) and will be released in Ansible 2.0.1
