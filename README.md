# Pet-Guide

Inspiration

If am to start with numbers, what I know is that there are over one million species of animals in the world; ranging from the smallest, shortest to the heaviest and tallest land animals on earth. . The challenge is now that these animals are going into extinction. For example: In Kenya, about 280 Elephants and almost 60 Rhinos were killed by poachers in 2013. In preserving these animals, we are sure IoT has a role to play. Therefore, in case of wildfire, pouching, or any other danger, help can be quickly deployed to save the life of our Animals.

What it does

It is an IoT-based collar that can be used to monitor animals. It can monitor:

Animal's Health Animals' location Animals' environment

Market Use

Domestic Use Commercial Use Game Reserves Scientific Research Laboratories

How we built it

In order to fully achieve what we proposed in the fastest time possible, we made use of different technologies. The Solution is majorly three parts:

The Hardware The Software Cloud Platform

The Hardware

The hardware is the major IoT device, the one that gets all information on the Animal. We made use of the following in building the Hardware:

1. NodeMCU Programming platform

The NodeMCU is a low-cost microcontroller and IoT platform which can be integrated with different sensors. The NodeMCU takes data from our Health Monitoring Sensor and Location monitoring sensor and sends it to a cloud provider which in this case is Microsft Azure IoT Central. The board can be powered from a battery.

2. V.KEL GPS Module

The V.KEL GPS module is our location monitoring sensor. It gets the following data from the satalite: Longitude, Latitude, Altitude, Speed. The GPS sensor sends the data to the NodeMCU which inturn sends it to cloud. The module derives it power from the NodeMCU.

3. DHT11

DHT11 is a common IoT sensor for getting Temperature and Humidity related information. This sensor will be used in monitoring the health of the animal by constantly checking the temperature and environmental humidity. Just like the GPS module, it also sends data to NodeMCU.

The Software

The software part is the code controlling the IoT device. Because of the IoT board we are using which is NodeMCU, the programming language is written in C++ using the Arduino IDE.

Cloud Platform

IoT is incomplete without cloud, in this project, Microsoft Azure IoT Central platform was used as the cloud provider. All our data are being sent to the platform which can be monitored from the control station.

Challenges we ran into

Inplementaing this project came with lots of challenges and unforseen events. First, sending our data to Azure IoT Central really gave us lots of tough time because on a normal day, something like this is majorly done using python language but we are trying to use C++.

There are other factors that we couldn't control that gave us issues for example on a cloudy day, the GPS doesn't work perfectly, so most times, we have to wait for a clearer sky before we can work.

One major chalenge we also face is internet connectivity, we couldn't get seamless network connectivity and this really slowed down the project timeframe.

Accomplishments that we're proud of

What we are proud of is that all those challenges listed above were overcome. We gave in the time and it came out good.

What we learned

If there is anything all members of the team benefited from, it is the ability to work in a team. Not all the team members are developers but we all coordinate and achieve our aim. Technically, the team has learned a lot. Some that are new to IoT got to know lots of things and some that were new to cloud computing also benefited.

What's next for Pet Guide

Pet guide is open to lots of improvement. Our aim is to come up with an actual device to monitor and preserve the life of our animals, therefore any improvement to the La Torre collar that can make this happen will be well welcome.
