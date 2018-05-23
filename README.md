# MSSerialPortExamplesCombined
Combined two sets of Microsoft Code Snippet Examples for the System.IO.Ports Namespace.

The larger Microsoft provided Serial Port Code Example threw TimeOutException errors and just surpressed them.  However, they also had a second snippet that wired up an event handler.  This just effectively listens to the port for incoming data.

You can run multiple instances of this application.  Run two instances each connected to their own COM port.  Connect the two ports together with a Null Modem Cable.  You could also use Putty to replace one of the instances.

This was tested using a Moxa NPort 5410 serial server for the physical COM ports.
