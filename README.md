# robotframework-mqttlibrary-java

MQTT keyword library for RobotFramework in Java

This is an initial POC...stay tuned for updates.

## Usage

1. Use robotframework-maven-plugin
2. Add a dependency on this library (after installing locally `mvn install`)
3. Add RobotFramework style tests under src/test/robotframework/acceptance
4. Run `mvn verify`. This uses a public test broker provided by Eclipse Paho project. Alternatively, if you have a locally running broker at default port, run : `mvn verify -PUseLocalBroker`.

Detailed instructions coming soon...

##Reference
[1] https://github.com/mqtt/mqtt.github.io/wiki/servers
