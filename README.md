# A2

1. Create the all ReverseServer.java , ReverseClient.java , ReverseImpl.java & ReverseModule.idl  files.

2. idlj -fall  ReverseModule.idl
3. javac *.java  ReverseModule/*.java
4. orbd -ORBInitialPort 1050&
5. java ReverseServer -ORBInitialPort 1050& -ORBInitialHost localhost&
6. Run the client application :
  java ReverseClient -ORBInitialPort 1050 -ORBInitialHost localhost
