VSCode (Repository)
 Copy files/vscode.repo into /etc/yum.repos.d/
 copy the gpgkey to the correct location in /etc/pki/rpm-gpg/
 ... from https://packages.microsoft.com/keys/microsoft.asc
 ... import the gpgkey: rpm --import /etc/pki/rpm-gpg/RPM...
 ... install configure vscode / extenstions and configure.

Puppet (Repository)
 Install https://yum.puppet.com/puppet-release-el-8.noarch.rpm
 ... configure puppet repository to be diabled by default
 ... import puppet rpm-gpg keys from directories in /etc/yum.repos.d/puppet.repo
... install puppet agent, bolt, and pdk 

Hosts file
Copy /etc/hosts file entries
