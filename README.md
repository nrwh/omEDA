# omEDA
One More Electronics Design Automation software...

KiCAD, EasyEDA, OrCAD, Altium, Eagle... surely this is the one. Perhaps I'll find out why they are made the way they are.

I am currently unsatisfied with how part libraries of other software. I want the part to control how the symbols, footprints and 3D Model go together.
- Part
  - Modules (for external boards like raspberry pi pico headers)
- Symbol
- Footprint
- 3D Model
- Sub-circuits
  
There are very distinct workflows and they should be appropriately separated and not hidden from the user.
- General Purpose:
  - Gerber Viewer - Verify gerbers
  - 3D Viewer - Verify 3D Models (check clashes in enclosure)
  - Calculator
- Global or local library editors:
  - Part Editor - Create or edit parts and their properties. Bring symbols, footprints and 3D models together
  - Symbol Editor - Create or edit symbols
  - Footprint Editor - Create or edit footprints
  - Sub-circuit Editor - 
- Project Specific Workflows:
  - Project Editor - This is the starting window. View recent and favourite projects. Manage templates and general preferences.
  - Schematic Editor - Draft and iterate on your plans for a circuit
  - PCB Editor - Put plans into design and get ready to manufacture
  - Spice Simulator

I want to give the users just enough of what they need to work well efficiently. No intelligence
- Built-in online open-source part/library importer
- Easily reusable and repeatable sharable libraries for schematics and layouts
- Friendly, easy to use user interface and common sense hotkeys