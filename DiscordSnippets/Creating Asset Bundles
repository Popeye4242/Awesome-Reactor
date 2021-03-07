### Creating Asset Bundles

1. Install Unity from the archives (Unity 2019.4.9) https://unity3d.com/get-unity/download/archive
2. In Unity install the package AssetBundle Browser from `Window > Package Manager`
3. Drag your assets into the assets folder in Unity
4. Click each asset you want to include in the bundle. In the lower right corner set the bundle you want the selected asset to be bundled in.
5. Go to `Window > AssetBundle Browser`, go to the build tab and Build the bundle
6. Load the bundle in your mod

```
            string path = Path.Combine(Environment.CurrentDirectory, "Assets", "morerolesmod");
            Assets.Bundle = AssetBundle.LoadFromFile(path);
            Assets.Popeye = Assets.Bundle.LoadAsset<Sprite>("Popeye").DontUnload();
```
