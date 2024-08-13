# Layers Pane Plus by Dony
 This script provides advanced functionality for creating and managing layers in Adobe After Effects.  It includes features for creating various layer types, deleting layers, and sequencing layers.

## Installation
1. Navigate to the After Effects ScriptUI Panels folder:
   
   C:\Program Files\Adobe\Adobe After Effects [Version]\Support Files\Scripts\ScriptUI Panels
   
2. Place the script file in this folder.
3. Place the folder containing the icons in the same destination as the script.

## Features
- Create various layer types: Text, Solid, Null Object, Shape, Camera, Adjustment
- Delete selected layers
- Create layer sequences based on selection order
- User-friendly interface with icon buttons
- Dockable panel in the workspace
- Resizable window with responsive button alignment

## Version History

### v1.6.2 (Current)
- Updated Text layer creation to ensure the name is updated without delay
- Fixed error handling issue for layer naming
- Improved compatibility with various After Effects versions

### v1.6.1
- Updated Text, Null Object, Shape, Camera, and Adjustment layer creation to use native After Effects commands
- Fixed issues with Shape and Adjustment layer creation
- Improved error handling and user feedback for all layer creation functions
- Enhanced compatibility with different versions of After Effects

### v1.6
- Improved Solid layer creation to use the native "Solid Settings" dialog
- Enhanced layer naming logic to respect user-given names in the native dialog
- Implemented unique naming system for Solid layers to avoid duplicates
- Solid layers now retain color names chosen by users (e.g., "Red Solid")
- Improved handling of default layer names to ensure uniqueness in the composition

### v1.5
- Completely rewrote createLayerSequence function to correctly sequence selected layers
- The function now places layers sequentially one after another, respecting their trimmed durations and original positions
- The first selected layer maintains its original position in the timeline
- Subsequent layers are placed one after another in the order of selection
- Trimmed durations of each layer are preserved in the sequence

### v1.4
- Updated createLayerSequence function to respect layer in and out points

### v1.3
- Added new function to create a sequence of layers from selected layers

### v1.2
- User interface change: Added icons indicating the purpose of each button
- Added two new buttons: delete layer and help

### v1.1
- Added validations for each button in the script
- Made the panel dockable in the workspace
- Added ability to adjust the size of the window with responsive button alignment

### v1.0
- Initial release with basic layer creation functions

## Usage
1. Open Adobe After Effects
2. Go to Window > Layers Pane Plus
3. Use the buttons to create different types of layers or perform actions
4. For layer sequencing:
   - Select layers in the desired order
   - Click the sequence button
   - The first selected layer will maintain its position, and subsequent layers will be placed one after another in the order of selection, respecting their trimmed durations
5. For Solid layer creation:
   - Click the Solid layer button
   - Use the native "Solid Settings" dialog to choose color and name
   - The script will ensure the name is unique in the composition
6. For Text, Null Object, Shape, Camera, and Adjustment layer creation:
   - Click the respective button
   - The native After Effects dialog will appear (if applicable)
   - Choose your settings in the dialog
   - The script will ensure the name is unique in the composition

## Support
If you need help or want to provide feedback, you can contact me here:
https://linktr.ee/Dony.ae

Enjoy this script and happy creating! :>