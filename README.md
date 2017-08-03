# Serial Monitor for Atom

A simple serial monitor for Atom which allows you to e.g. connect to the serial
line of your embedded device and view debug output from that device within Atom.

Please note, that this is a monitor only which just prints what was received on
the serial line. It does not support sending data to the device!

## Prerequisites

A working Python setup (version 2.7 or 3.x) including pySerial with version >= 2.7.
If in doubt, install with:

    sudo pip install pyserial

## Install

Install from git:

    cd $HOME/.atom/packages
    git clone https://github.com/wendlers/atom-sermon sermon
    cd sermon
    apm install

## Usage

Open the settings dialog with `shift+alt+m`, select port and baudrate,
then hit connect.

The settings from the dialog are stored on a per project
basis in the the file `sermon_settings.json`.
