# Cisco-IOS-Router-Shell - modified
[![Build status](https://travis-ci.org/QualiSystems/Cisco-IOS-Router-Shell-2G.svg?branch=dev)](https://travis-ci.org/QualiSystems/Cisco-IOS-Router-Shell-2G)
[![Coverage Status](https://coveralls.io/repos/github/QualiSystems/Cisco-IOS-Router-Shell-2G/badge.svg)](https://coveralls.io/github/QualiSystems/Cisco-IOS-Router-Shell-2G)
[![Dependency Status](https://dependencyci.com/github/QualiSystems/Cisco-IOS-Router-Shell-2G/badge)](https://dependencyci.com/github/QualiSystems/Cisco-IOS-Router-Shell-2G)
[![Stories in Ready](https://badge.waffle.io/QualiSystems/Cisco-IOS-Router-Shell-2G.svg?label=ready&title=Ready)](http://waffle.io/QualiSystems/Cisco-IOS-Router-Shell-2G)

<p align="center">
<img src="https://github.com/QualiSystems/devguide_source/raw/master/logo.png"></img>
</p>

# Cisco IOS Router Shell Gen 2 - modified to create a mock resource structure
*This is not an official Quali shell. It was created for simulation purposes only and should not be used in production environments.*

This shell is based on the Cisco IOS Router Shell (2G). It's *get_inventory* function has been modified to create a mock resource structure of 16 ports. Additional modifications include **ServerName** and **NumberOfPorts** attributes, to be used by the mock autoload process.

**Note:** The number of ports can be changed by editing the shell resource's **NUMBEROFPORTS** attribute.
