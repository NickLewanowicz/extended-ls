# ls-additions-X

This repo contains some modifications to ls inside of coreUtils-8.26 and is known to work on Ubuntu 16.04 LTS 32 bit. The objective of these modifications were to gain a better understanding of the linux operating system (in particular coreUtils) and use that knowledge to build a new feature into the known and loved package.

The feature we made is in the form of an ls flag -N which has a --d `X` flag that will recurse your ls command X times. The installation of which follows.


## Installation

* `git clone <repository-url>` this repository
* `cd improved-ls-linux/coreutils-8.26`
* `./configure prefix=/home/{username}/coreutils`
* `PATH="$HOME/coreutils/bin:$PATH"`
* `make`
* `sudo make install`

<i>Thankyou to Patches on [SuperUser](https://superuser.com/questions/304943/how-can-i-install-a-more-modern-version-of-gnu-utils-coreutils-on-debian-linux) for describing this process for us.<i/>


## Further Reading / Useful Links

* [What is LS](http://linuxcommand.org/lc3_man_pages/ls1.html)
* [GNU CoreUtils](https://www.gnu.org/software/coreutils/coreutils.html)
* [How does LS work? by: amitsaha on github](https://gist.github.com/amitsaha/8169242)


