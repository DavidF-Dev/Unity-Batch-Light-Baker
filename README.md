# Unity Batch Light Baker
A tool that bakes the lighting for multiple scenes, and automatically compresses the assets.

Download the Unity Package from [**Releases**](https://github.com/DavidF-Dev/Unity-Batch-Light-Baker/releases) tab.

## Instructions
To begin, open the tool window in *Tools > DavidFDev > Batch Bake Lighting*.
Enter in the range of scenes that you would like to operate on. This requires the scenes to be part of the Build Settings.

**Ignore read-only scenes**: If this is enabled, the tool will only affect scenes that are editable (i.e. checked out in version control). You can use this to filter which scenes you would like to operate on.

**Compression texture reference**: You can either use an existing texture, or simply create one (by pressing the *Create new reference texture* button). When the tool compresses the light texture assets, it will apply the settings from the compression texture reference automatically.

**Start Baking**: Use the *Start Baking* button to begin baking the lighting for all the scenes in the range specified. This operation can take a long time for a large quantity of scenes, but will save time in the long run!

**Start Compressing**: Use the *Start Compressing* button to begin compressing the light texture assets for all the scenes in the range specified.
