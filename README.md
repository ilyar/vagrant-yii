# Vagrant Yii

## Requirements
* [VirtualBox](https://www.virtualbox.org)
* [Vagrant](http://vagrantup.com)
* [Berkshelf](http://berkshelf.com)
	* `gem install berkshelf`
* [vagrant-berkshelf](https://github.com/riotgames/vagrant-berkshelf)
	* `vagrant plugin install vagrant-berkshelf --plugin-version '>= 2.0.1'`
* [vagrant-hostmanager](https://github.com/smdahlen/vagrant-hostmanager)
	* `vagrant plugin install vagrant-hostmanager`
* [vagrant-omnibus](https://github.com/schisamo/vagrant-omnibus)
	* `vagrant plugin install vagrant-omnibus`

**Note:** Vagrant 1.0.x compatible stack [is also available](https://github.com/MiniCodeMonkey/Vagrant-LAMP-Stack/tree/Vagrant-1.0.x).

## Usage
Start the VM

	$ vagrant up

Check [http://yii.local/yii/requirements/](http://yii.local/yii/requirements/)

## Demos

* [blog](http://yii.local/yii/demos/blog/)
* [hangman](http://yii.local/yii/demos/hangman/)
* [helloworld](http://yii.local/yii/demos/helloworld/)
* [phonebook](http://yii.local/yii/demos/phonebook/)

## Installed software
* Apache 2
* PHP 5.4 (with mysql, curl, mcrypt, memcached, gd, sqlite)
* memcached
* postfix
* vim, git, screen, curl, composer
* Yii Framework 1.1.15

## Default credentials

### Environment variables

```bash
VM_ARCH=32
VM_MEMORY=512
VM_CORES=1
```

### Memcached
* Port: 11211
