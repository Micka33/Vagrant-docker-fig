#Vagrant-docker-fig


A Vagrant file with Ubuntu trusty64, the latest Docker release, the latest Fig release, and Git

##What's inside ?

 - Ubuntu 14.04 LTS (trusty).  
 - the latest Docker release  
 - Fig 0.4.2  
 - Git (through apt-get)  

##Network

IP [`172.17.8.100`][ip]  
Port [`8282`][port] is published.  


The Vagrantfile folder is automatically mounted ([/home/vagrant/mnt][mnt]) and is the default folder upon `vagrant ssh`.  
This folder is mounted as [NFS][nfs].  

## CPU/RAM

[2 CPU][ncpu]  
[CPU cap at 70%][cpuc]  
[1024 Mo RAM][ram]  

[mnt]: https://github.com/Micka33/Vagrant-docker-fig/blob/master/Vagrantfile#L63
[nfs]: https://github.com/Micka33/Vagrant-docker-fig/blob/master/Vagrantfile#L63
[ip]:  https://github.com/Micka33/Vagrant-docker-fig/blob/master/Vagrantfile#L61
[port]:https://github.com/Micka33/Vagrant-docker-fig/blob/master/Vagrantfile#L59
[ncpu]:https://github.com/Micka33/Vagrant-docker-fig/blob/master/Vagrantfile#L12
[cpuc]:https://github.com/Micka33/Vagrant-docker-fig/blob/master/Vagrantfile#L13
[ram]: https://github.com/Micka33/Vagrant-docker-fig/blob/master/Vagrantfile#L11
