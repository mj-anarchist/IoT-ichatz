# Hardware and software architecture

Conceptual Architecture Of Software
--

With every device we manufacture, we add the device ID to our database and expect our web server to receive data from that ID. Whenever someone powers on the device and connects it to the network, the device starts sending us the data. We can store data, no storage limit. User can register with email and his device ID. Once he's registered, he can sign in to the dashboard and see the data with visual analytics. I have not tried MQTT protocol yet so I'll abstain from writing further but we're working on it. Had it been an HTTP request, we'd accept POST data at a certain endpoint and work with it. We're unsure about certain things and will be improving this markdown readme again in near future. 

Conceptual Architecture Of Hardware
--

We 3d print a device structure with places alloted for sensors. We have our STM board in the middle and sensors connected to it. We use powerbank for powering the board and sensors/actuators. We have a WiFi station nearby and can send and receive data.

We're expecting numerical data but we're in the process so we'll be updating this file with all the details of every sensor/hardware component.
