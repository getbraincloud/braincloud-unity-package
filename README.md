# brainCloud Unity Custom Package

This git repo will allow you to install the brainCloud C# client library for your Unity project via the Package Manager. For more information, please see the [brainCloud C# Client Library](https://github.com/getbraincloud/braincloud-csharp#braincloud-c-client-library) repository.

---

## Installation Guide

With your Unity project open:
1. Open `Window > Package Manager`
2. In the new window, click the big **+** icon in the top-left, then click **Add package from git URL...**
3. In the **URL** field, paste, and then click **Add**, this link:
    - https://github.com/getbraincloud/braincloud-unity-package.git

After it installs you should see **Packages - bitHeads Inc** with **brainCloud** underneath it in the Package Manager.

When a new update gets pushed, you can simply hit the **Update** button in the bottom-right of the window.

## Updating

Be sure to delete your old brainCloud settings files first.

If you're using an older version of the library then the settings will be located in the `Assets > BrainCloud > Resources` folder:
- `Assets > BrainCloud > Resources > BrainCloudSettings_X_X_X`
- `Assets > BrainCloud > Resources > BrainCloudEditorSettings_X_X_X`

Newer versions of the library going forward will have the settings files under the `BrainCloud > Unity` folder:
- `Assets > BrainCloud > Unity > Resources > BrainCloudSettings_X_X_X`
- `Assets > BrainCloud > Unity > Editor > Resources > BrainCloudEditorSettings_X_X_X`

If you plan on installing brainCloud via the Package Manager you must delete the old root brainCloud library files folder under `Assets > BrainCloud` in your Unity project. You must also delete the the brainCloud plugin files. Here are all of the brainCloud library files & folders to delete:
- `Assets > BrainCloud`
- `Assets > Plugins > Android > brainCloudUnity`
- `Assets > Plugins > iOS > RegionLocaleNative`

If you do not have any additional Plugins then it is safe to delete the root `Assets > Plugins` folder.
