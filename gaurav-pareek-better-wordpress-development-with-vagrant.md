# 2015
Speaker Notes Template for WordCamp Mumbai 2015

##Gaurav Pareek
###Better WordPress development with Vagrant

The 'Works on My Machine' syndrome is a very common problem in scenarios where more than one developer is involved. More often than not, this can be blamed on undocumented, half-baked, or unstable development environments.

###Some common problem scenarios

- Lone developer with a dev environment vastly different from production.
- Multiple people with different computers, and incomplete knowledge about reproducing their dev environment.
- Multiple people with different OS, platform etc.
- Designers/Frontend developers not willing to delve in server software.

All this usually results in code not working. In cases where software such as WordPress, which has a huge history of *cowboy coding* is involved, the situation is even more out of control. This is where Vagrant comes in, as it allows packaging a development environment into a portable container with the help of virtualization technologies, paired with powerful provisioning tools such as Chef and Puppet.

Vagrant allows developers/teams to keep their development environment in simple text files, which can be prepared and run using one simple command. This makes development by various people, working on different platforms, much easier and cleaner.

This talk deals with how Vagrant can be implemented by all sorts of people, both developers and designers/theme reviewers, to make their lives easier by using it for creating and maintaining portable, reusable, and sandboxed development environments.

------------------------------------------------------------

###Benefits

####For developers
- Same versions of software.
- Easily replicate production environment with the same configs.
- Same environment even on different host platforms. Works on Linux, Mac, Windows.

####For Designers/Frontend devs
- No messing with server software.
- No need to worry about configuration.
- Largely automated with pre-built config. One command sets it all up.

####For testers
- Easy to build a sandboxed server environment which is exactly the same as dev and production.
- No messing with server software, easy to get to the actual work.
- Platform independent, test multiple projects with different requirement on the same host machine.

###My slides
[Speakerdeck](https://speakerdeck.com/grvrulz/better-wordpress-development-with-vagrant-at-wordcamp-mumbai-2015)

###Useful tools (to help build your vagrant config)
- [Puphet](http://puphpet.com/)
- [Rove](http://rove.io/)
- [ProtoBox](http://getprotobox.com/)

###Resources
- [Vagrant website](http://vagrantup.com)
- [VVV on github](https://github.com/Varying-Vagrant-Vagrants/VVV)
- [Example easyengine vagrant on github](https://github.com/gau1991/easyengine-vagrant/) (use only if familier with EE already)
- [Vagrant base box site](https://atlas.hashicorp.com/boxes/search?vagrantcloud=1)
- [Link to my github](https://github.com/grvrulz/WCMum2015)
