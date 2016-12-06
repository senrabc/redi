#Install

#Notes (unorganized, excuse please, taken while working broken install process)

#Vagrant

## Step 1: Prerequisites



[2016-12-06]

You need to install vagrant and virtual Box:
https://www.vagrantup.com/downloads.html




On a Mac use:

```
$ brew cask install virtualbox && brew cask install vagrant

```

Check the versions if you already have them. While trying to vagrant up chef was failing on old versions. Upgraded vagrant to:

```
12:01 $ vagrant --version
Vagrant 1.8.7

```

Upgraded Virtual Box to:

```

14:30 $ vboxmanage --version
5.1.10r112026

```

Then the vagrant up built a running REDCap version (6.16.0) as expected.

You may need to be on these versions or newer. You're milage may very.


## Step 2: Vagrant Up

TODO: COPY test project creation functions from:


 forge /vagrant_hcvtarget?utf8=✓&rev=develop
