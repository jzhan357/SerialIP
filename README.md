# SerialIP
Expose a serial port over IP

# Requirements
* Python 3
* Pyserial `python3 -m pip install pyserial`

# Running
SerialIP can be run in server or client mode. Running in server mode requires the port 5000 to be open.
If need be, you can change the port variable to change which port SerialIP uses.

Depending on your system, you may need root/admin privileges to access serial ports.

`python3 serialIP.py`

On Windows, serial ports should be in the form of `COM#`.

On Linux, serial ports are usually in the form of `/dev/tty#`.
