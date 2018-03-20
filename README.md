# _Common


## Necessary settings for version control 
## Under Project Settings/Editor:

### 1. Set Asset Serialization Mode to "Force Text"
*Unity uses serialization to load and save Assets and AssetBundles to and from your computer’s hard drive. 
To help with version control merges, Unity can store Scene files in a text-based format 
(see documentation on text scene format for further details). 
If Scene merges are not performed, Unity can store Scenes in a more space-efficient binary format, 
or allow both text and binary Scene files to exist at the same time.
Use the drop-down to select which format Unity should use to store serialized Assets. 
This is set to Force Text by default.*

### 2. Version Control to "Visible Meta Files"
*Set Unity to display meta files. This is useful when using version control, 
because it allows other users and machines to view these meta files.*