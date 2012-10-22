vagrant on osx
==============

prerequisites
-------------
- osx lion or mountain lion

method
------
- download and install [VirtualBox for OS X hosts](https://www.virtualbox.org/wiki/Downloads), optionally download the [VirtualBox Extension Pack](https://www.virtualbox.org/wiki/Downloads)
  - open virtualbox settings, install the extension pack from there
  - if there are 'invalid settings', you have to configure a host-only nic
- install homebrew (see [here](https://github.com/elseym/recipes/blob/master/osx/homebrew.md) for instructions)
- via homebrew, install `brew-gem` by issuing  
`brew install brew-gem`
- via homebrew / gem, install `vagrant` and `vagrant-snap` by issuing  
`brew gem vagrant vagrant-snap`
- your vagrant dir will be `~/.vagrant.d`

serves one.