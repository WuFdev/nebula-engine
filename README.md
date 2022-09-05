# the Nebula engine

## About
the Nebula engine is engine that is based off of the VYGE engine heres a example from that engine:
<p align="center"><img src="res/FPS.png"></p>

## Development
* **Platform**: Windows 10 32 Bit (Windows API + DirectX 9)

**Note**: Building the code for 64 Bit results in some pointer conversions between 32 Bit primitives and 64 Bit pointers which is dangerous. To avoid these issues and since I do not want to modify the original code (to keep it as a reference), I removed the 64 Bit build completely from the solution.

## Before building
1. Install [Microsoft DirectX SDK (June 2010)](https://www.microsoft.com/en-us/download/details.aspx?id=6812). I tested using Microsoft DirectX 9.0 SDK (October 2004) which does not seem to be directly available from Microsoft anymore.
2. Set the environment variable `DXSDK_DIR9` to the installation directory of the DirectX SDK.
  1. Go to `This PC`
  2. Right click
  3. Select `Properties`
  4. Select `Advanced system settings`
  5. Click on the `Environment Variables` button
  6. Add `DXSDK_DIR9` in the list of `System Variables` and set it to the installation directory of the DirectX SDK.
  
**Note**: you need to position the *Assets* directory in your execution directory to be able to play the game. Make sure the .txt files have `CRLF` (Windows) instead of `LF` (Unix) line endings!

## note
ive always what to make a game engine that you know works so heres a engine that you know you can use and mod to your liking
