# Converting a 3D Printer Into an Automatic Spray Coater
<img alt="airbrush front view" src="https://github.com/CaliforniaCatalysts/AuroraVale/blob/12366cb5cd1042f7dc3dfcc48ff7db6821b7b6ab/Images/airbrush%20mount%20front%20view.jpg" />
<img alt="full enclosure" src=https://github.com/CaliforniaCatalysts/AuroraVale/blob/6092d9f6ab4c31537369c0baaca90436ff0ee529/Images/full%20enclosure.jpg />
<img alt="mainsail web interface" src="https://github.com/CaliforniaCatalysts/AuroraVale/blob/756c065d113d2a2143e4c6a4be886b3f38b62715/Images/mainsail.jpg" />
<img alt="comparison image" src="https://github.com/CalicatSJL/Airbrush3DPrinter/blob/603322e46b361c85c9c3b4500689975b20cbf822/Images/comparison%20image.png" />
<img alt="performance data" src="https://github.com/CalicatSJL/Airbrush3DPrinter/blob/368358dcf1d8d3601b4fd78ab42792576b68395b/Images/performance%20comparison.png" />

This project was developed at Calicat by Steven Jaffe-Lewis, Que Nhi Nguyen, and Nadia Tolouei in Summer 2025. 
All files and code are being released under MIT license. The team hopes that this project will be useful for other electrochemistry labs to standardize this manual airbrush process and improve loading uniformity of sprayed catalyst inks for making catalyst-coated membranes or related components.

inspired from Remi_Rafael's project: https://www.instructables.com/Converting-a-3D-Printer-Into-an-Automatic-Spray-Co/

Main changes by the team at Calicat:
 - improved the airbrush button actuation consistency and angle resolution by moving the servo arm rotation to be planar with the airbrush trigger.
 - updated stl files for mounting the airbrush onto a Creality K1 printer.
 - parameterized the spray area and path through klipper macros, enabling adjustments from within the mainsail interface.
 - added a laser crosshair used for sewing machines to precisely align the airbrush nozzle with the desired mask area.
 - built the web interface using Mainsail to control the equipment.
 - added a heated microporous vacuum board as the base. 


