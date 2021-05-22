[![CI](https://github.com/rhaleblian/terrarium-puredaisy/actions/workflows/CI.yml/badge.svg)](https://github.com/rhaleblian/terrarium-puredaisy/actions/workflows/CI.yml)

# terrarium-puredaisy

A PedalPCB Terrarium/Daisy PureData patch that plays a Cmaj7+ chord
controlled by knobs. Use it to test that all knobs respond.


# Prerequisites

Your local machine needs:

* Python 3
* The `gcc-arm-none-eabi` compiler toolchain

On WSL or Ubuntu you might:

    sudo apt install python3 gcc-arm-none-eabi

On macOS you can do same if you have Homebrew installed:

    brew install python3 gcc-arm-none-eabi


# Setup

Create a new GitHub repository using this one as a template.

Clone your new repository locally and do a one time bootstrap:

    make bootstrap

The process may want your input to install additional Python
packages.


# Building the binary

    make
    
`helloknob.bin` will be next to `helloknob.pd`.


# Resources

[Pure Data Manual](http://write.flossmanuals.net/pure-data/introduction2/)

