# krita unofficial spine export Updated - 2024
This is the Unofficial Krita Python Plugin to export into the Spine JSON format - 2024
Unofficial Krita 4 Python Plugin to export into the Spine JSON format

How to install
Copy KritaToSpine.desktop and the KritaToSpine folder into the pykrita directory inside the Krita Resource directory. You can find your Resource Directory within Krita via Settings > Manage Resources > Open Resource Folder

Restart Krita and make sure the plugin is enabled, which means Settings > Configure Krita > Python Plugin manager > Krita To Spine Export Plugin should be checked.

How to use
This plugin is inspired by the official Photoshop plugin, and the Krita built-in Document Tools plugin.

You can find the script under Tools > Scripts > Export to Spine. Select a folder and all your images will be exported into it as well as spine.json

Supported in Group Layers:

(Bone)
(Slot)
(Merge)
(Ignore)
Various operations such as scaling, resizing and rotating can be applied before export, these are not applied to the original document.

Notes:

Skins and subfolders are not supported
Images will be in png format
Both () and [] can be used
Invisible layers are ignored
Be careful with filter layers. They will export as merged layer like they are shown in Krita. Consider organizing your scene with merge folders for better control.
