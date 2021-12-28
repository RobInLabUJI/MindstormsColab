# MindstormsColab

[Google Colab notebooks](https://research.google.com/colaboratory/faq.html) 
with examples and exercises for LEGO&reg; Mindstorms NXT and EV3 mobile robots.

The code consists of [Jupyter notebooks](http://jupyter.org/) 
running in a laptop or desktop computer with Ubuntu Linux 20.04, 
which communicates with the robots via Bluetooth.

The NXT runs its standard firmware, and so does the EV3 (there is no need
to use an SD card).

## Prerequisites - Ubuntu 20.04

* [PyBluez](https://github.com/karulis/pybluez)
* NXT
  * [NXT-Python](https://github.com/Eelviny/nxt-python)
* EV3
  * [ev3-python3](https://github.com/ChristophGaukel/ev3-python3)
* Computer
  * Python 3.x
  * [Jupyter notebook](http://jupyter.readthedocs.io/en/latest/install.html)

## Setup

### NXT / EV3

Activate Bluetooth and pair your robot and computer.

Run the pairing script:

`./script/pair.bash`

The script launches [`bluetoothctl`](https://www.makeuseof.com/manage-bluetooth-linux-with-bluetoothctl/).
Use the command `scan on` for finding your device, then use `pair <mac_address>` for pairing it.

### Computer

Run the install script:

`./script/install.bash`

## Usage

### NXT / EV3

Switch it on, that's all!

### Computer

Run the script `./script/run.bash` in the root folder, and enjoy!
