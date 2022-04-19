# IoT_Simulation
Temperature and Humidity microcontroller ESP32 on Python (Wokwi Simulation + Hivemq Broker Client)

Project on Wokwi (Micropython on ESP32): https://wokwi.com/projects/328777740948865619

Where to see the messages on broker -> Hivemq Broker Client: http://www.hivemq.com/demos/websocket-client/

Host - broker.mqttdashboard.com
Port - 8000
KeepAlive - 60
Click on 'Connect'

Subsciptions -> Add new Topic
Topic: sala306/umidade
QoS: 0
- Subscribe -

Subsciptions -> Add new Topic
Topic: sala306/temp
QoS: 0
- Subscribe -

Run the simulation Wokwi and see the messages on Broker.