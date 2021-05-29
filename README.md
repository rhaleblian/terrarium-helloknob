[![CI](https://github.com/rhaleblian/terrarium-helloknob/actions/workflows/CI.yml/badge.svg)](https://github.com/rhaleblian/terrarium-helloknob/actions/workflows/CI.yml)

# terrarium-helloknob

A PedalPCB Terrarium PureData patch that plays a Cmaj7+ chord
controlled by knobs. Use it to test that all knobs respond.

Want to get the binary file immediately? See the Releases.


## Prerequisites

Your local machine needs:

* Python 3
* The `gcc-arm-none-eabi` compiler toolchain

On WSL or Ubuntu you might:

    sudo apt install python3 gcc-arm-none-eabi

On macOS you can do same if you have Homebrew installed:

    brew install python3 gcc-arm-none-eabi


## Setup

    make bootstrap

The process may want your input to install additional Python
packages.


## Building the binary

    make
    
`helloknob.bin` will be next to `helloknob.pd`.


# Resources

[Pure Data Manual](http://write.flossmanuals.net/pure-data/introduction2/)
