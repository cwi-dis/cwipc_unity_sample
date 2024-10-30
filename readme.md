# Sample Unity project for CWI Pointcloud Unity package

This repository contains a sample Unity project showing how to use the Unity package `nl.cwi.dis.cwipc` that allows capture and display of
point clouds and various operations such as compression for transmission, reading and writing to disk, etc.

The `nl.cwi.dis.cwipc` is imported through the Unity Package Manager.

There is usually no need to clone <https://github.com/cwi-dis/cwipc_unity>, where the package lives, unless you want to make changes to the package itself.

The Unity project should build for desktop (Windows, Mac, Linux) and for  Meta Quest (running on the headset itself).

## Usage for desktop

First you need to install the native _cwipc_ point cloud suite on your computer. See <https://github.com/cwi -dis/cwipc> for instructions.

Now you open the project in Unity. In `Assets/Samples/CWIPC Point Cloud Suite` there are various example scenes. Try them.

## Usage for Quest

You do not have to install the native _cwipc_ suite: the native libraries you need for Quest/Android are included in the package.

Set your platform to Android in the player settings, select the scene you want, build, run.

## Updating the package

You can always update the `nl.cwi.dis.cwipc` package through the Unity Package Manager. You should probably update the essential cwipc samples at the same time.
