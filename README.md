# What is it?
Ex360E is a highly experimental Xbox 360 emulator, for Xbox Live Arcade titles developed with XNA Game Studio.

It uses an extremely High-Level approach to Emulation, rely on the fact that titles developed with XNA run with the .NET framework.

In order to run games, Ex360E extracts an Xbox Live Arcade Package, decrypts the .xex files, extracts any .NET executables, and then patches them so that that can then be run by the Windows version of the .NET framework.

The result of this, is the Xbox 360 game is left in a format that can be natively run on a Windows PC. Due to these resulting assemblies being 64-bit, and Windows only has a 32-bit variant of the XNA framework, the Xbox 360 version of the framework is used.

This is achieved by writing Dynamic Link Libraries (.DLL files) that implement the missing libraries from the Xbox 360 that XNA expects to be present. (D3D, XINPUT, STORAGE, MEDIA, among others)

# Minimum System Requirements
Microsoft Windows (64-bit only, Windows 7 and 8 have been tested as working)
.NET Framework 3.5
Microsoft Visual C++ 2010 Runtime

# Current Status
The emulator is capable of booting Fez, as in, it runs the code, but crashes instantly due to an incomplete Direct3D implementation.

# Update
This emulator is on hold for an undetermined amount of time, as my development laptop has failed, leaving me with a very low end machine for the time being.