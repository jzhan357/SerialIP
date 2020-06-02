# SerialIP
Expose a serial port over IP

# Requirements
* Python 3
* Pyserial `python3 -m pip install pyserial`

# Running
Depending on your system, you may need root/admin privileges to access serial ports.

`python3 serialIP.py`

On Windows, serial ports should be in the form of `COM#`.

On Linux, serial ports are usually in the form of `/dev/tty#`.
