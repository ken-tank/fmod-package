Convert FMOD Asset Plugin to UPM, so Project Distribution size will reduce significan, by Unity Git Importer

Use FMOD Plugin version 2.03.08

<hr>
Notes:
when using this FMOD UPM version, all path will moved to FMOD relative folder "YourProject/Library/PackageCache/com.fmod.integration@.../FMOD"
so, when add External Plugins to FMOD, you need add it manualy by copy-paste your .so/.dll in that directory, instead "Assets/Plugins/FMOD/platforms/..",
also maybe you need add .meta for each file to makesure assets metadata is correct

<hr>
For Distribution Only, All License still on FMOD Company

and sorry for my bad English