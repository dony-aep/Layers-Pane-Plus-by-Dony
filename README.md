# Layers Pane Plus by dony.

## Description
Layers Pane Plus is an advanced script for Adobe After Effects that provides extended functionality for layer creation and management. Designed to enhance workflow, this script offers an intuitive user interface with icon buttons for various layer operations.

## Current Version
**v1.6.5** - This is the most recent and stable version of the script.

## Installation
1. Locate the After Effects ScriptUI Panels folder:
   ```
   C:\Program Files\Adobe\Adobe After Effects [Version]\Support Files\Scripts\ScriptUI Panels
   ```
2. Place the script file (`Layers Pane Plus.jsx`) in this folder.
3. Ensure that the `LpPlusAssets` folder (containing the icons) is in the same location as the script.

## Main Features
- Quick creation of various layer types: Text, Solid, Null Object, Shape, Camera, Adjustment
- Deletion of selected layers
- Creation of layer sequences based on selection order
- Splitting of all layers at the current time indicator
- Creation of new compositions using the native After Effects dialog
- User-friendly interface with icon buttons
- Dockable panel in the workspace
- Resizable window with adaptive button alignment

## Usage
1. Open Adobe After Effects
2. Go to Window > Layers Pane Plus
3. Use the buttons to create different types of layers or perform actions
4. For layer sequencing:
   - Select layers in the desired order
   - Click the sequence button
   - The first selected layer will maintain its position, and subsequent layers will be placed one after another in the order of selection, respecting their trimmed durations
5. For creating Solid, Text, Null Object, Shape, Camera, and Adjustment layers:
   - Click the respective button
   - Use the native After Effects dialog (if applicable)
   - Choose your settings in the dialog
   - The script will ensure the name is unique in the composition
6. To split all layers at the current time indicator:
   - Click the "Crop any layer" button
   - All layers will be split at the current time
   - **Note:** If there is no active composition, you will be notified to create one first

## Version History

### v1.6.5 (Current Version)
- Restored alert for active composition in the `splitAllLayers` function
- Updated layer splitting functionality
- Fixed command ID for creating new composition
- Updated help text for the layer splitting button

### v1.6.4
- Adjusted the `splitAllLayers` function to split layers without individual notifications
- Updated version text in the user interface
- Updated help documentation

### v1.6.3
- Added button to split layers
- Added button to create new composition
- Improved help documentation

### v1.6.2
- Improved text layer creation
- Fixed error handling issues in layer naming
- Improved compatibility with various After Effects versions

### v1.6.1
- Updated layer creation to use native After Effects commands
- Improved error handling and user feedback

### v1.6
- Improved solid layer creation using native dialog
- Implemented unique naming system for layers

### v1.5
- Rewrote layer sequencing function

### v1.4
- Updated sequencing function to respect layer in and out points

### v1.3
- Added function to create layer sequences

### v1.2
- Added icons to the user interface
- Added buttons for deleting layers and help

### v1.1
- Added validations for each button
- Made panel dockable in the workspace
- Added ability to adjust window size

### v1.0
- Initial release with basic layer creation functions

## Support
If you need help or want to provide feedback, you can contact me here:
[https://linktr.ee/Dony.ae](https://linktr.ee/Dony.ae)

Enjoy this script and happy creating! :>