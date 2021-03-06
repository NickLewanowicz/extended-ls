# extended-ls

This repo contains some modifications to ls inside of coreUtils-8.26 and is known to work on Ubuntu 16.04 LTS 32 bit. The objective of these modifications were to gain a better understanding of the linux operating system (in particular coreUtils) and use that knowledge to build a new feature into the known and loved package.

The feature we made is in the form of an ls flag -e which has a --reach `X` flag that will recurse your ls command X times. The installation of which follows.

[Full documentation of the implementation process available here.](https://docs.google.com/document/d/100poTkgIc0kR0Jgu00ALAiLU4pzcvBpD3MihMmu3E1s/edit?usp=sharing)
## Installation

* `git clone <repository-url>` this repository
* `cd extended-ls`
* `sudo apt-get install automake autotools-dev texinfo`
* `source ./install`


## Further Reading / Useful Links

* [What is LS](http://linuxcommand.org/lc3_man_pages/ls1.html)
* [GNU CoreUtils](https://www.gnu.org/software/coreutils/coreutils.html)
* [How does LS work? by: amitsaha on github](https://gist.github.com/amitsaha/8169242)
* [Functions for ls modifiers](https://explainshell.com/)


