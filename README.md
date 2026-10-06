Introduction

The hashslot system is a modular way of connecting assemblies that contain ASICs and control modules or combinations thereof 
using industrial computing riser card plugs to connect them to a main board, back plane or main frame that will contain the voltage regulators and optionally the microcontroller. 
The ASIC riser card shall contain ASICs, microcontroller or connector pass through, adaption, expansion, and connector break out depending on the function of the card. 
This system is broken down into four types for different sizes of systems that can be configured With them.

There are two types of riser plugs used in this system. They are the main riser plus and secondary power plug. 
These connector types can either be into one connector or broken up across several connectors depending on the OEMs choice.
Harting, Molex, and Samtec offer combination connectors as well as individual subsections of the hashslot riser plug types.


The main riser plug

The main riser plug shall have eight power pins or blades for carrying up to 200W as well as small signal 24 pins for low current supplementary voltages and small signal communication.
The main riser plug power section shall contain four power pins or blade contacts for riser card ASIC voltage and four power pins or blades contacts for riser card ASIC ground return. 
The main riser signal section shall contain small current power pins and their ground returns
as well as pins assign for microcontroller communication in the form of I2C, SPI, I3C, and GPIO
for communication to the main board and other main riser plugs located on the main board or on extension cards.    

The secondary power plug.
The secondary power plug shall be a plug containing eight pins or blades for additional 200W of power delivery to the ASIC riser card. 
This secondary power plug shall contain four power pins or blade contacts for riser card ASIC voltage and four power pins or blades contacts for riser card ASIC ground return. 

Small setup  types:

Type A Hashslot
Type A Hashslot is the hashslot connector convention where it will contain just a main riser plug. 

Type B Hashslot 
Type B hashslot is the connector convention where it will contain a main riser plug and a secondary power plug.

Motherboard types:

Type C Hashslot 
Type C hashslot is the connector convention where it will contain a main riser plug and two secondary power plugs.

Type D Hashslot 
Type D hashslot is the connector convention where it will contain a main riser plug and three secondary power plugs.

Type E Hashslot 
Type E hashslot is the connector convention where it will contain a main riser plug and four secondary power plugs.

Back-plane types:

Type F Hashslot 
Type F hashslot is the connector convention where it will contain a main riser plug and five secondary power plugs.

Type G Hashslot 
Type G hashslot is the connector convention where it will contain a main riser plug and six secondary power plugs.

Mainframe types:

Type H Hashslot 
Type H hashslot is the connector convention where it will contain a main riser plug and seven secondary power plugs.


Type I Hashslot 
Type I hashslot is the connector convention where it will contain a main riser plug and eight secondary power plugs.

Type J Hashslot 
Type J hashslot is the connector convention where it will contain a main riser plug and nine secondary power plugs.

Type K Hashslot 
Type K hashslot is the connector convention where it will contain a main riser plug and ten secondary power plugs.

Type L Hashslot 
Type L hashslot is the connector convention where it will contain a main riser plug and eleven secondary power plugs.

Type M Hashslot 
Type M hashslot is the connector convention where it will contain a main riser plug and twelve secondary power plugs.

Type N Hashslot 
Type N hashslot is the connector convention where it will contain a main riser plug and thirteen secondary power plugs.

Type O Hashslot 
Type O hashslot is the connector convention where it will contain a main riser plug and fourteen secondary power plugs.

Type P Hashslot 
Type P hashslot is the connector convention where it will contain a main riser plug and fifteen secondary power plugs.

Type Q Hashslot 
Type Q hashslot is the connector convention where it will contain a main riser plug and sixteen secondary power plugs.

Type R Hashslot 
Type R hashslot is the connector convention where it will contain a main riser plug and seventeen secondary power plugs.

Type S Hashslot 
Type S hashslot is the connector convention where it will contain a main riser plug and eighteen secondary power plugs.

Type T Hashslot 
Type T hashslot is the connector convention where it will contain a main riser plug and nineteen secondary power plugs.

Type U Hashslot 
Type U hashslot is the connector convention where it will contain a main riser plug and twenty secondary power plugs.

Type V Hashslot 
Type V hashslot is the connector convention where it will contain a main riser plug and twenty-two secondary power plugs.

Type W Hashslot 
Type W hashslot is the connector convention where it will contain a main riser plug and twenty-three secondary power plugs.

Type X Hashslot 
Type X hashslot is the connector convention where it will contain a main riser plug and twenty-four secondary power plugs.

Type Y Hashslot 
Type Y hashslot is the connector convention where it will contain a main riser plug and twenty-five secondary power plugs.

Type Z Hashslot 
Type Z hashslot is the connector convention where it will contain a main riser plug and twenty-six secondary power plugs.


Written by David Mikeska of Oconical. Everyone (as listed as 'OEM' below) is free to use this connection system for their system architecture as long they agree on the fallowing terms:

1. If the OEM use this connection system, the logo shall be placed onto the main board and riser cards to identify convention standards.
2. Underneath the logo, the OEM agrees to list the hashslot type used in the system.
3. Underneath the hashslot type listed, the OEM agrees to state the OEM's Model Number and optionally,  serial number, manufacturing lot and date.


Contents of this Github:


logo folder:
The logo will be supplied in this github that will contain logo formats.

Connector_Types folder:
This folder will contain the physical connectors suggested for use in the hashslot system by Oconical. 
People can submit connectors to be added to this folder freely to give others ideas to build with the hashslot system.

OEM folder:
OEM folder will contain sub-folders of OEMs that have decided to use the hashslot architecture. 
OEM's data on what connector is used by part number and a simple pinout diagram will be in their corresponding sub-folder.
OEMs and their representatives are allowed to officially submit their data to this Github. 
