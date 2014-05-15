Import Unity Package into unity.

IOS Specific:

Add objective C headers and implementation files to xCode project (Classes folder) exported from unity.

Add contents of MoPubSdk of mopub-ios-sdk into Classes folder of xCode project.

If you want to test mopub in iPhone Simulator, replace RegisterMonoModules.cpp file of Library/ folder with the file from this repo. (Note: for this, select Simulator SDK from Unity->File->Build Settings->Player Settings->Other Settings(in inspector) -> SDK Version.)

Android Specific:

Clone mopub-sdk-android from https://github.com/dg-no-9/mopub-android-sdk (this is modified version of original sdk)
Add classes.jar into build path of above sdk project, and build it with your favorite build tool like Eclipse.
copy mopub-sdk.jar from bin/ folder of above sdk into Unity-Project/Assets/Android/ 
