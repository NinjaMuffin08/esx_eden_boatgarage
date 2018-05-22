# esx_eden_boatgarage
Private Boat Garage based on ESX

The garage only takes into account the vehicles purchased in the dealership and also the vehicles that are outside or outside.
During a reboot all vehicles go back home.

# Requirement:
FXServer-esx_vehicleshop

# Installation

1) CD in your resources/[esx] folder
2) Clone the repository
3) Import eden_boatgarage.sql in your database

4) Add this in your server.cfg :

```
start esx_eden_boatgarage
```

# KNOWN BUG:

- Some vehicles are impossible to enter
- By looking good it is possible to duplicate vehicles
- UNABLE TO STORE VEHICLE (NEED HELP FIXING THIS ISSUE)

# How to use my version
To put the vehicle in the garage:
- Pull into the red dot
- Get out of the car, open the menu
- Select "Put Vehicle In Garage"<br />

To take it back out
- Walk into the red dot
- Open the menu
- Select "Get Vehicle From Garage"
