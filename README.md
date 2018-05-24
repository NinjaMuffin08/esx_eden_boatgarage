# esx_eden_boatgarage
Private Boat Garage based on ESX

This Garage Script only takes into account the Boats Purchased in the Boat Shop. Players can also go to the Boat Pound to retrieve their Boat if its lost or Destroyed for a Fee. During a reboot all Vehicles go back home.

# Requirement:

* Boat Shop
  * esx_eden_boatgarage => https://github.com/HumanTree92/esx_eden_boatgarage

# Installation

1) CD in your resources/[esx] folder
2) Clone the repository
3) Import eden_boatgarage.sql in your database

4) Add this in your server.cfg :

```
start esx_eden_boatgarage
```

# KNOWN BUG:

- It is Possible to Duplicate Vehicles but do note that if said Person Duplicates a Vehicle & takes 1 of them & sell thems the other one is useless & can NOT be stored or sold.

# How to use my version
To put the vehicle in the garage:
- Pull into the red dot
- Open the menu
- Select Return vehicle

To take it back out
- Walk into the green dot
- Open the menu
- Select View Vehicle List
