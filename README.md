# Smart Plant Pot
Manage your plants from your phone and keep them alive.

## The Project
Smart Plant Pot was developed during the lecture Free and Open Technologies at the TU Vienna. The goal of the lecture is to sensibilise and promote the use and production of free and open technologies. Our contribution to the open source community is a do it yourself guidance to create a Smart Plant Pot. It lets you keep track of the soil moisture, air humidity, temperature of your plant and also lets you take pictures from it. It consist of three main parts:

1. **The Hardware:** The hardware setup consists of two sensors (soil moisture, temperature and air humidity) an a webcam, all connected to one Arduino and one Raspberry PI communicating with the back-end.
2. **The IOS APP:** Add and manage your plants, see whether they need watering or take a look at live pictures. It also lets you display all data in a histogram.
3. **The Back-End:** A mySQL database and a REST API allow communication between your app and your plants and keep your data accessible at any time.

## Let's get started
To build a Smart Plant Pot for yourself you need to follow all the instructions provided in the documentations below:

### 1 - The Hardware
[Setting up and configuring the Hardware](https://github.com/FeliziusV/SmartPod-Hardware-Side)

### 2 - The iOS App
[Implementing the iOS App](https://github.com/antizwiebel/SmartPot_iOS)

### 3 - The Back-End
[Implementing the REST API and configuring the Database](https://github.com/Snuu101/Smart-Plant-Pot-Back-End)

## Future Development
- **User Management:** The abillity to create and manage multiple users. 
- **Design a plant pot:** A 3D printable plant pot that includes all the hardware.
- **More Sensors:** Extend the hardware implementation to support more sensors (brightness sensor, etc.)

## Known Issues
