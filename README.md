# mqtt-PubSub-python
MQTT Client and Server code using Python

MQTT - Message queuing telemetry transport
Client publishes the code to server (called as broker). MQTT runs on cloud server. Therefore it always runs over TCP/IP.

We have two codes, mqtt_pub.py to publish data from public API: https://home.openweathermap.org/ . Signup for getting API key. Temperature, humidity, pressure data for different cities are obtained from the API, and are published on 4 channels. mqtt_sub.py connects to the MQTT broker, and gets the data published on those 4 different channels.

This concept is used widely in IoT.

