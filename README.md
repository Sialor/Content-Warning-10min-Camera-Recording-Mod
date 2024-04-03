# Content-Warning-10min-Camera-Recording-Mod
If you want to reproduce this mod for your game version, then you should use [dnSpy software][dnSpy] and replace two 90f values in the "Content Warning_Data\Managed\Assembly-CSharp.dll" in the "ConfigItem" method of the VideoCamera class.
## Steps to reproduce:
1. Download and unzip dnSpy.
2. Create the backups of original files, create the working directory and copy all .dll files from "Managed" folder in it.
3. Run "dnSpy" and open all of .dll files that contained in your wokring dir.
4. Find VideoCamera class and change 90f values to any values in ConfigItem method by clicking RMB on the method and selecting "Edit Method (C#)".
5. Compile file after changing values. After compilation you need to save the module "File->Save module..". Then you can replace original Assembly-CSharp.dll by modified file.

[dnSpy]: https://github.com/dnSpy/dnSpy
