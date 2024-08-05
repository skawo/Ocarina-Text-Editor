<h1>Zelda 64 Text Editor</h1>

This fork of Sage of Mirror's Ocarina Text Editor adds a bunch of extra features:

* A message previewer
* Support for custom fonts
* Support for staff roll messages (hold CTRL while opening a ROM)
* Support for opening ZZRTL, ZZRT and Z64ROM-exported filesystems directly
* Support for Ocarina of Time versions: PAL1.0, PAL1.1, PAL Gamecube, PAL Master Quest, PAL Beta Master Quest, Debug, NTSC0.9, NTSC1.0, NTSC1.1, NTSC1.2, NTSC GameCube, NTSC Master Quest, NTSC Lodgenet
* Support for Majora's Mask versions: PAL1.0, PAL1.1, PAL Gamecube, PAL Debug ROM, NTSC1.0, NTSC Kiosk Demo, NTSC GameCube
* Support for remapping characters 

<h2>Usage:</h2>
To load a ROM, first decompress it using <a href="https://github.com/z64tools/z64decompress">Z64Decompress</a>. Otherwise, just point to a ZZRTL/ZZRT/Z64ROM filesystem or extracted data files.
<br><br>
To open credits messages, hold left CTRL while opening a ROM or Z64ROM filesystem. For ZZRT and ZZRTL, edit the credits messages by opening the base ROM (as they don't extract the credits messages from it).
<br><br>
You can search through the messages by typing in the top-left corner textbox. You can also filter messages with a regex pattern by encasing it with "REGEX:{}".
<br><br>
Right click the message input textbox to open a context menu containing all the control codes available. Hover over one to receive an explanation.
<br><br>
Supports custom fonts as exported from <a href="https://github.com/z64me/z64font">z64font</a>. Simply put both files exported from the program in the same directory as the text editor - named <i>font.font_static</i> and <i>font.width_table</i> - and they will be automatically loaded and used for the preview.
<br><br>
By placing a <i>codepoint.txt</i> file in the same folder as the editor, you can remap the OoT/MM character set, allowing for fonts suited to other languages. More information <a href="https://github.com/skawo/Zelda64-Text-Editor/releases/tag/v.3.32">here</a>.
<br><br>

![image](https://github.com/skawo/Zelda64-Text-Editor/assets/43761362/57cc981d-0b8c-42d1-91ef-90d45fbf89e3)

