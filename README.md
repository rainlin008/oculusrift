oculusrift
==========

Utilities and examples using Unity and the Oculus Rift VR head mounted display (HMD)

Examples
--------

Oculandia

This is a Unity Pro (4.2.2) project that includes a prebuilt "Construct" scene for placing objects. The OVRPlayerController is placed in the heirarchy to give full OVR and navigation support. The example object and all future objects should be placed in Assets/Objects.

To build a OVR application select File > Build Settings. Select PC, Mac & Linux Standalone, then pick Mac OSX followed by Build And Run. This will generate a standalone application which can be run with the HMD.

You can also set the Mac Screen Mode to "FullWindow" in the Build Settings > Player Settings view to always show the application full screen when launched.

The HMD resolution should be set to 1280 x 800 and you should mirror your display.

Oculus SDK v0.2.5 is used. For future SDK updates, sign up at https://developer.oculusvr.com.


--

OSCTest

This is a Unity Pro (4.2.2) project that includes a prebuilt scene for placing objects. It uses the UnityOSC (https://github.com/jorgegarcia/UnityOSC) code to add OSC functionality to the world. The unityOSC.maxpat patcher brings in tracking data from the transLAB and sends it out over OSC.