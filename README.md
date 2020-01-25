# Smart Plant Pot
Manage your plants from your phone and keep them alive.

<p align="center">
<img src="/Images/app.JPG")
</p>

## The Project
Smart Plant Pot was developed during the lecture Free and Open Technologies at the TU Vienna. The goal of the lecture is to sensibilise and promote the use and production of free and open technologies. Our contribution to the open source community is a do it yourself guidance to create a Smart Plant Pot. 

The Smart Plant Pot provides you with an iOS app that helps you manage all your plants in your household. It lets you keep track of the soil moisture, air humidity, temperature of all your plants and also lets you take pictures from them. The necessary data is collected via sensors directly from your plant pots and gets send to a database on a server, hence making them accessible from all your mobile devices wherever you are.

## Architecture

The Smart Plant Pot architecture is split in three main parts:

1. **The hardware:** The hardware setup consists of two sensors (soil moisture, temperature and air humidity) and a webcam, all connected to an Arduino which in turn is connected to a Raspberry PI used to communicate with the back end.
2. **The front end:** The user interacts with the system via an iOS app. Add and manage your plants, see whether they need watering or take a look at live pictures. It also lets you display all data in a histogram.
3. **The back end:** The back end consists of a MySQL database and a REST API to keep your data accessible at any time. The REST API provides the necessary infrastructure for the communication between the database and your app and hardware.

<p align="center">
<img src="/Images/architecture.JPG")
</p>

## Let's get started
To build a Smart Plant Pot for yourself you need to follow all the instructions provided in the documentations below:

### 1 - The hardware
[Setting up and configuring the Hardware](https://github.com/FeliziusV/SmartPod-Hardware-Side)

### 2 - The front end
[Implementing the iOS App](https://github.com/antizwiebel/SmartPot_iOS)

### 3 - The back end
[Implementing the REST API and configuring the Database](https://github.com/Snuu101/Smart-Plant-Pot-Back-End)

## Future Development
- **User management:** The ability to create and manage multiple users. 
- **Design a plant pot:** A 3D printable plant pot that offers enough space to include all the hardware.
- **More sensors:** Extend the hardware implementation to support more sensors (brightness sensor, etc.).
- **Android app:** To make the Smart Plant Pot available for Android users as well, an Android app needs to be developed. Both iOS and Android app should share the same functionality.

## Known Issues

## Licence
All three parts of the Smart Plant Pot project are licensed under the GNU General Public License v3.0. See [LICENCE](/LICENSE) for additional information.
