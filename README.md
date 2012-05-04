try-symfony
===========

Try Symfony with Vagrant, Puppet, Composer and Symfony2

For Windows, OSX and Linux. Any Version.

What you need installed:
  * Vagrant (vagratup.com)
  * VirtaulBox

What this does:
  * Vagrant sets up the Virtual Machine and boots up the operating system (lucid32) to the login prompt and runs then the provisioner (puppet)
  * Puppet installs
    * Apache
    * PHP
    * MySql Server
    * Apc
    * XDebug