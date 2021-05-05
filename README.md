
## <a name='toc'>Tools list:</a>

  1. [Vagrant](#vagrant)
  1. [LXD](LXD.md)
  1. [Nginx](#nginx)
  1. [Apache Web](#apache)
  1. [KVM](#kvm)
  1. [AutoBackupMySQL](/autobackupmysql.sh)
  1. [Rsnapshot](rsnapshot.conf)
  1. [Teleconsole](#teleconsole)



#### <a name='vagrant'>Vagrant examples:</a>

* [Vagrant + LXC plugin](/vagrant/vagrant-lxc/Vagrantfile)
* [Vagrant + libvirt plugin (KVM)](/vagrant/vagrant-kvm/Vagrantfile)
* [Vagrant + VirtualBox](/vagrant/vagrant-virtualbox/Vagrantfile)


#### [[⬆]](#toc) <a name='nginx'>Nginx examples:</a>

* [Nginx Reverse Proxy](/nginx/reverse-proxy.conf)
* [Nginx HTTP Load Balancing](/nginx/load-balancer-http.conf)
* [Nginx TCP and UDP Load Balancing](/nginx/load-balancer-tcp.conf)
* [Using PROXY Protocol for receiving IP](/nginx/proxy-protocol.conf)
* [Nginx config for Nextcloud](/nginx/nextcloud.conf)
* [Nginx + php-fpm for Mediawiki](/nginx/mediawiki.conf)
* [Nginx (mix)](/nginx/nginx.conf)


#### [[⬆]](#toc) <a name='apache'>Apache VirtualHost Examples:</a>

* [Apache Nextcloud conf](/apache/nextcloud.conf)
* [Apache Nextcloud2 conf](/apache/nextcloudSimple.conf)
* [Apache zendFramework](/apache/zendFramework.conf)


#### <a name='kvm'>libvirt(kvm) scripts:</a>

* [Simple script for backuping libvirt images + xml confs](/kvm/libvirt-backup.sh)
* [Stop all running vms](/kvm/vms-stop.sh)


#### [[⬆]](#toc) <a name='teleconsole'>Teleconsole - terminal sharing:</a>
```bash
#install:
curl https://www.teleconsole.com/get.sh | sh
#start service:
teleconsole
#client connect:
teleconsole join <session ID> 
# access through web:
https://teleconsole.com/s/ace723ba055a28c66ae22b7a13c18d44fbc5a8b8 
```
Source: https://github.com/gravitational/teleconsole
