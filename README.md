# asdf-sml

[Standard ML](https://smlnj.org) plugin for asdf version manager

## Build History

[![Build history](https://buildstats.info/github/chart/asdf-community/asdf-sml?branch=master)](https://github.com/asdf-community/asdf-sml/actions)

## Installation

```bash
asdf plugin-add sml https://github.com/asdf-community/asdf-sml.git
```

## Usage

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to
install & manage versions.

## Notes

Before version 110.94, SML is 32bit. On 64bit Ubuntu, to get required 32bit
libs:

```bash
apt-get install gcc-multilib g++-multilib lib32ncurses5 lib32z1
```

## License

Licensed under the
[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
