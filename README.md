# VirtualDoubleMount

ASCOM driver for a Virtual telescope mount connected to 2 mounts
ASCOM platform does not allow to use a second telescope mount, only one mount can be connected at a time. This virtual double mount will cover two mounts at a time by using existing ASCOM drivers for specific hardware and providing one ASCOM driver to connect with to work with both telescope mounts.
Needed to use with panoramic set-up to have one mount performing only tracking and guiding and second one to perform move-shoot-move procedure
For ASCOM, please see https://ascom-standards.org/
here is implemented ITelescopeV4 interface of the ASCOM driver
