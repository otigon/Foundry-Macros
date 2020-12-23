# Foundry-Macros

Update: I've updated all macros to work with the JB2A version 0.1 to account for the new naming structure and file widths. I've also added all the new attack spell macros, as well as some special effect arrows. 

Note that the file paths are set for the PATREON version. Simply edit the file location in the macro if using the free version. The proper location to edit is anywhere the animation file location is referenced in the macro, 95% that will be towards the top of the code. Some simpler codes call it directly towards the middle in the spell animation definition.

Here are a few examples of how the file is named in these macros:

1. Part of a "random call"
   /n let file = "modules/jb2a_patreon/Library/........"
   let a = .......
   let b = ......
   
   In this line you'll change jb2a_patreon to JB2A_DnD5e, or whatever your module folder is called.
   
2. Part of the spellAnim definition:
   
   let spellAnim = 
      {
       file: "modules/jb2a_patreon/Library/....."
       
   Again, change jb2a_patreon to your file location folder name
   
Simple Macros designed for use with FXMaster and MIDI-QOL Modules in Foundry VTT, and some for Token Magic Effects application. Some of these are not mine, I've just scavenged and modified others code work. Scaling could use some tweaks, but they'll play nice on most normal grid sizes in Foundry VTT. 

As written they are designed for use with the On-Use Macro function for spells/items as part of Midi-QOL (or use with the Item Macro module), and leverage FXMaster to play the spell animations. These are works of the Foundry VTT community that I have compiled and tweaked, and were created to leverage spell animations from modules/creators like JB2A. Using the "On-Use" macro field from Midi-QOL, the macro will execute when DAMAGE is rolled. If you have speed rolls active and always roll damage, it will play everytime.

Special thanks to Lazytron and MagoRaion on the JB2A discord for compiling and testing the bulk of these codes and Kandashi for offering guidance on how to clean up the messy code.

