## oncemore

A (hopefully temporary) repo for use with the [MicroPython IoT Hackathon](http://micropython-iot-hackathon.readthedocs.io/en/latest/) tutorial.

### Setup

Assuming you're successfully cloned this repo, there's just a few more steps get everything setup:

1) Both [antevents-python](https://github.com/mpi-sws-rse/antevents-python) and [mpftool](https://github.com/wendlers/mpfshell) are included as git submodules:

```
cd oncemore
git submodule init
```

2) Optional: Configure your virtualenv as appropriate, whether using virtualenv or python3 -m venv, and activate it.

3) Install the relevant packages.

```
pip install esptool colorama websocket_client 
```

2) Install mpftool:

```
cd mpftool
python setup.py install
```

### Features

The final client.py has been added for your convenience.
