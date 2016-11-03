## Overview
This is the README for the Wahila Creative folks. This contains some of the basic steps to follow to get going and some of the basic things to be aware of.


## Getting started

You will need/want to adjust the following parameters in the  `default.config.yml`:

 * `vagrant_hostname` (change to whatever hostname you want)
 * `vagrant_ip` (change to something different than your other VMs)
 
 Once you have made those changes, you should be able to just type `vagrant up` and be on your merry way.
 
 That should be it.
 
 
 ## Notes
 
 You will see a directory called `ignoremefiles`, ummm, just ignore that. That is necessary consequence of file synchronization in Virtual Box. We needed certain permissions on the directory that it points to and this was the only way to get them set.
