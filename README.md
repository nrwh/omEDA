# omEDA
One More Electronics Design Automation software... KiCAD, EasyEDA, OrCAD, Altium, Eagle... surely this is the one.

omEDA is just a concept and not intended to actually be a big project.

There will be two file types which this program will be working with: .omeda_lib, and .omeda_prj

.omeda_lib are omEDA library files.
- Symbols
- Footprints
- 3D Models
- Components - Brings together symbols, footprints, and 3D Models. Add additional data which 
- Design Blocks - A collection of components 
- Schematic Sheet Templates
- PCB Layout Sheet Templates
- Board Stack-ups
- Design Rules

.omeda_prj are omEDA project files.
- Internal Library - A special form of the usual omEDA library internal to the project
- Component Table
- Schematic Sheet
- PCB Layout

Ultimately the purpose of using programs is to make it easier for a user to manipulate data. For this reason, the backend (algorithms and file storage) and frontend (workflow and user interface) will be developed separately to understand how they will eventually be brought together and how features will be brought in and how the program will evolve.
