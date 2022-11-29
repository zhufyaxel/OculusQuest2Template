# Oculus Quest2 Template

This project is a template that contains Oculus Integration and all necessary setups to make things work. The `OculusQuestTemplate/Scenes/SampleScene.unity` can be used as a starting point as the following gif shows

![](template.gif)

## Why we need this

Suppose you are trying to make a Unity Project for developing Oculus Quest2 Applications and following the Meta website's tutorial. This process will take a long time if you are unfamiliar with Unity. Especially from their beginning tutorial, many components need to be clarified (i.e., the section *build your first app*, which won't work, to be honest). Meanwhile, if you want to make the project works directly in the editor instead of building into the device and testing, some setups are required but not mentioned on their developer page.

Instead of wasting extra time to figure them out, clone this project and use the sample scene to make your life easier

## How To Use

**Warning: This solution is very, very slow for the first-time setup and lacks efficiency for both storage and speed, but it will work automatically, and all you need to do is wait.**

**Warning: ~1.5GB when everything finally works**

**Warning: Only tested in Unity 2021**

0. Make sure the Oculus Link to your quest works appropriately and that all the external developer-related cases irrelevant to Unity already work as expected. Make sure your Unity Account has the Oculus Intergration Package.
1. Download or clone this project
2. Copy or move the `OculusQuestTemplate` folder to somewhere you want, and rename it to satisfy your need(not necessary but recommended)
3. Open `Unity Hub` and add that new folder from `Open/Add project from disk.` to your Unity Hub Environment.
4. Get a cup of coffee, and wait. This process takes a long time for the first-time compiling.
5. Go to `File --> Build --> Settings` and switch the platform to Android. Make sure the `Run Devices` is set to your oculus
6. Get another coffee and wait. This process also takes some time.
7. Import `Oculus Intergration` from the Assets Store. This can be found in `Package Manager --> My Assets --> Oculus Intergration`
8. Get another coffee and wait. This also takes a long time for the first-time compiling. If you worry drink too much coffee, hang around but don't waste time staring at the progress bar
9. After importing the Unity would shine several notifications, yes to all, and editor should restart itself.
10. In `Assets/Scenes/SampleScene/OVRCameraRig`, make the section `QuestFeatures` set as what you want. Recommended to make sure the `Controller and Hands` are enabled and frequency could be set as `HIGH` (Not obviously work tbh).
11. Test if the `Assets/Scenes/SampleScene.` works as expected. Make sure the `Oculus Desktop App` opens already and your headset is awake.
12. Cheers if you find the method works. If it is still not working, I would feel guilty. In such a case please delete this template, go to try the official tutorial, and follow it.

## What will be the issues here

Potentially this project won't work as well since both Unity and Oculus are changing their way continuously. It becomes better and better if we look into history but sometimes make old solutions out of date. Some setups are external to Unity, which might be the reason for not making your project work.

Meanwhile, I didn't make any Git Large File Storage solution with static assets for personal convenience. But you are already using Unity, who cares.

