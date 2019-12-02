<div align="center">
<h1>asdf-sml</h1>
<span><a href="http://www.smlnj.org">Standard ML</a> plugin for asdf version manager</span>
</div>
<hr />

[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/asdf-community/asdf-sml/Main%20workflow?style=flat-square)](https://github.com/asdf-community/asdf-sml/actions)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License](https://img.shields.io/github/license/asdf-community/asdf-sml?style=flat-square&color=brightgreen)](https://github.com/asdf-community/asdf-sml/blob/master/LICENSE)

SML/NJ plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

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
