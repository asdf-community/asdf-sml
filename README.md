# asdf-sml

[![Build Status](https://travis-ci.org/nverno/asdf-sml.svg?branch=master)](https://travis-ci.org/nverno/asdf-sml)

SML/NJ plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

## Install

```
asdf plugin-add sml https://github.com/nverno/asdf-sml.git
```

## Use

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of SML/NJ.

## Notes

Before version 110.94, SML is 32bit.  On 64bit Ubuntu, to get required 32bit libs:
 
 `apt-get install gcc-multilib g++-multilib lib32ncurses5 lib32z1`
