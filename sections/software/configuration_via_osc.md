$order=3
$title=Configuring MiniBees via OSC

If you are using the minihiveosc interface, you can configure a MiniBee via OSC, by sending a message with the tag

```/minibee/configuration``` with two arguments: the number of the minibee (which is automatically generated) and the number of the configuration – as defined in the configuration file, e.g. from SuperCollider you would do:


    // create a target OSC address corresponding to minihiveosc:
    n = NetAddr.new( "127.0.0.1" , 57600 );

    // set configuration to a minibee:
    n.sendMsg( "/minibee/configuration", 1, 1 ); // minibee id, config id

You can save the configuration to a file by sending a message:

```/minihive/configuration/save``` with as argument the filename for the configuration, e.g. from SuperCollider you would do:

    /// save the configuration to a file "rmhiveconfig.xml":
    n.sendMsg( "/minihive/configuration/save", "rmhiveconfig.xml");