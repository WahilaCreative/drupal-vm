## Overview
This is the README for the Wahila Creative folks. This contains some of the basic steps to follow to get going and some of the basic things to be aware of.


## Getting started

You will need/want to adjust the following parameters in the  `default.config.yml`:

 * `vagrant_hostname` (change to whatever hostname you want)
 * `vagrant_ip` (change to something different than your other VMs)
 
 Once you have made those changes, you should be able to just type `vagrant up` and be on your merry way.
 
 That should be it.
 
 
 ## Notes
 
 To get backup_migrate to work, you will need to set a "Private file system path" directory in. You need to do this in  the `Configuration -> File System`. A directory, `/home/vagrant/supersecret` will have been created with the correct permissions to be used as this "private" storage place, feel free to use it.
