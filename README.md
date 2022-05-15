# HelloCorba

###### Run server and client

From HelloCorba directory on the terminal run:
```console  
$ idlj -fall Hello.idl
$ javac HelloServer.java
$ javac HelloClient.java
```

On different terminal windows run:
```console  
$ tnameserv -ORBInitialPort 2000
$ java Server -ORBInitialHost localhost -ORBInitialPort 2000
$ java Client -ORBInitialHost localhost -ORBInitialPort 2000
```
