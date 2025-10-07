# 3D-printing guide
A simple guide of how to use the 3D-printers located in the 3D-printer room. The 3D-printers are free to use for no cost for all who have access to the workspace. The 3D-printers may not be moved. Use the sections below to get started.

> ### Look things up! 🔎
> - This is not a comprehensive guide on how to do every step. If you are new to 3D-printing, please look at a couple of 3D-printer tutorials.
> - You may see the [keywords](#keywords-) chapter for a guide of what the different **words marked in bold** means.


> ### Safety notice 🚨
> - Keep hands and fingers away from the printer while it's operating; the device will not stop for you and can cause injury.
> - Keep away from the **nozzle** and **print bed** while hot. Freshly extruded **filament** can also be hot. They can cause burns.

# About 3D printing 📖
3D printing (FDM) is the process of a machine depositing material to create an object. Usually done layer by layer. The printer heats up and liquefies the material in the **nozzle** and pushes it though, forming the material into a small tube that gets deposited onto the object, slowly creating a 3D-printed object as the **tool head** is moving the **nozzle** around. [Learn more](https://www.youtube.com/watch?v=f94CnlQ0eq4)

# General information 📌
- Places to find models: [thingiverse](https://www.thingiverse.com/), [printables](https://www.printables.com/), [makerworld](https://makerworld.com/en)
- Make your own models in any CAD program. For example [Onshape](https://www.onshape.com/en/).
- For help, please contact a 3D-printer manager in person or in the *Discord* server. (see qr-code on the wall)
- We recommend the [OrcaSlicer](https://github.com/SoftFever/OrcaSlicer) **slicer** for all the [printers](#printers-️) that it works with.
- Calibrated slicer profiles can be found on *Mac* computer located in the 3D-printer room.
- If you wish to use a **filament** other than *PLA* or *PETG* please contact a 3D-printer manager.


# How to print an object 📜
- Make sure that the printer you are planning to use is not occupied. If it is, then choose another printer or wait for your turn.
- Use the on site *Mac* computer or your own computer and start the **slicer** that matches the printer. (*see* [*printers*](#printers-️))
    - When using your own computer you need to configure the **slicer** for the [printer](#printers-️) and **filament** you are using. Ask for help if unsure how to do this.
- Load your model file. (*.step or .stl* format is recommended)
- Choose an already existing print quality setting profile or customize your own.
    - Don't change printer settings unless you know what you are doing. especially g-start code.
    - Add supports and other modifications if needed.
- Once satisfied click "*slice*"
- Make sure there are no floating regions (unsupported from bellow) or artifacts (holes or extra bits that are unintentional).
- Export the **sliced** file to a SD card. Remember the name of the file.
    - When using the [*bambu x1c*](#bambu-x1c) and **slicing** with the *Mac* computer, send the **sliced** file wirelessly via the **slicer**. The print should start automatically. (skip the next step)
- Eject the SD card. Then insert it into the printer.
- Make sure the correct filament is loaded and is enough for the print.
- [Clear the *sheet*](#removing-printed-objects-) from potential old **prints**.
- Turn on the printer if off. Select your file from the print menu and press print. (it will take a minute until the printer starts printing)
- It is recommended to supervise the printer at least until it has completed a few layers.
    - If issues occur, stop the printer and [clear the *print bed*](#removing-printed-objects-). Fix the cause of the issue before attempting to print again.
- If nothing went wrong and the printer is done printing then **Hurray!** You have successfully printed something. [*Clear the print bed*](#removing-printed-objects-)  to retrieve your print. Done!


# Removing printed objects 🧹
> When removing a printed object from the printer please be aware that the **sheet** and **nozzle** may still be hot.
> Do not try to remove the  **print** from the **sheet** while it is still on the **print bed**! With the exception of glass **sheets**. Be gentle!
> **Never!** touch the print surface. You may only touch the edges of the **sheet** as well as the tab that sticks out!


- Gently remove the **sheet** from the **print bed** by pulling up on the tab sticking out. **Don't touch the print surface!** If the **sheet** is glass then you may remove the print whilst on the print bed. Use as little force as possible.
- If the sheet is flexible, bend the sheet to expose a gap between the sheet and print. Firmly attempt to twist off the print. If still stuck, use the **spatula** to gently pry at the gap created by bending the **sheet** at the base of the **print** until the **print** loosens. Do not bend the sheet excessively! Do not touch the sheet on the print side with your fingers!
- Once the  **print** is free. [*Clear the print bed of any residue*](#removing-printed-objects-).
- Return the sheet. Make sure to properly align the sheet with the **print bed** corners.

# Keywords ❓
- **print**: The 3D-printed object, not to confuse with to "print something", the process of making the printed object (**print**).
- **print bed**: Surface where objects are printed.
- **sheet**: Removable magnetic sheet placed on the **print bed**.
- **filament**: Material used in the printing process.
- **tool head**: Moving part that extrudes filament.
- **nozzle**: ****Hot**** metal piece at the end of the **tool head**.
- **spatula**: Tool for removing prints.
- **slicer**: Program that prepares model files for printing.
- **slice**: The process of converting a model file *(ex .stl, .step, .obj)* into a printable file *(g-code, .3mf)*. Done in the **slicer**.
- **g-code** (file): A file containing the instructions of how to print the model for the 3D-printer to read. This is what **slicing** does, it converts model files like *.step* and *.stl* to *.gcode* that the 3D-printer understands.

# Printers ⚙️
## Bambu X1C
- Materials: any filament under that prints under 230 celsius and is not flexible. (*PLA* or *PETG*, contact a 3D-printer manager if intending to print another material)
- Sheets: Textured PEI (no glue; increase bed temperature if needed), smooth PEI (use glue if required), Cool plate (use glue if required)
 - Filament size: 1.75 mm
 - Slicer: [OrcaSlicer](https://github.com/SoftFever/OrcaSlicer)
- Max print size: 256x256x256 mm


## Ender 3-V2 Pro
- Material options: any filament under that prints under 230 celsius (*PLA* or *PETG*, contact a 3D-printer manager if intending to print another material)
 - Sheet: textured PEI (no glue; increase bed temperature if needed)
 - Filament size: 1.75 mm
 - Slicer: [OrcaSlicer](https://github.com/SoftFever/OrcaSlicer)
 - Max print size: 220x220x190 mm


## FLSUN Q5
- Material options: any filament under that prints under 230 celsius (*PLA* or *PETG*, contact a 3D-printer manager if intending to print another material)
 - Sheet: permanent glass sheet (use glue if needed)
 - Filament size: 1.75 mm
 - Slicer: [OrcaSlicer](https://github.com/SoftFever/OrcaSlicer)
 - Max print size: 200x200 mm

 ## Raise-3D E2
- Material options: any filament under that prints under 300 celsius (*PLA* or *PETG*, contact a 3D-printer manager if intending to print another material)
 - Sheet: smooth sheet (use glue if needed)
 - Filament size: 1.75 mm
 - Slicer: [IdeaMaker](https://www.raise3d.com/ideamaker/)
 - Max print size: single 330x240x240, dual 295x240x240 mm

## UltiMaker S3
- Material options: any filament under that prints under 230 celsius (*PLA* or *PETG*, contact a 3D-printer manager if intending to print another material)
 - Sheet: glass sheet (use glue if needed)
 - Filament size: 2.85 mm (**not 1.75 mm!**)
 - Slicer: [UltiMaker Cura](https://ultimaker.com/software/ultimaker-cura/)
 - Max print size: 230x190x200 mm
