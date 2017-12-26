The following is a list of tasks I've done to setup a new development environment on OS X. This is of course specific to my needs which are primarily focused on setting up a Java development environment but could include other languages over time.

# Common OS X Tasks
Download and install the following:
* iTerm2 - terminal replacement
** There are some important OS X escape keys that do not work out of the box in iterm2. However nothing like a little bit of customization to fix that - thank you to [elweb](https://elweb.co/making-iterm-2-work-with-normal-mac-osx-keyboard-shortcuts/)
* XCode from the App Store
* XCode command line utilities
* Java 8 from Oracle
* Homebrew
* git

# Setup Vagrant and VirtualBox
* Install VirtualBox
* Install Vagrant
* Install the Guest Plugin:

```vagrant plugin install vagrant-vbguest```

* Setup your own box - there are plenty. I use a [CentOS box](https://app.vagrantup.com/centos/boxes/7) but you can find [more here](https://app.vagrantup.com/boxes/search)


