# Qolor Tyme

This is a Toastmasters-inspired speech timer for use during online daily scrum meeting updates.

It is based on PyQt, which is Python API for Qt (pronounced "cute") cross-platform GUI framework, hence the name Qolor Tyme.

I honestly don't know why they called it PyQt instead of QtPy, which would have made it "cutie-pie" `¯\_(ツ)_/¯`

## Pre-requisites

Install **pyqt5**:

```shell
pip install pyqt5
```

## Running

This is just a single Python script, so to run it you invoke it with the python interpreter on the command line. It accepts an optional timeout interval (default is 90 seconds per Agile guidelines)

```shell
python qolor_tyme.py 120
```

This will configure it for 2 minutes timeout. The other optional parameters can be changed in code. The default behavior is that 20 seconds before the timeout the color will change to yellow, 5 seconds before the timeout it will change to red, and when it times out it will blink red.

