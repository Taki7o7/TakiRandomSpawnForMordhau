# Taki Random Spawn System for Mordhau
### Easy to use Random Spawn System for Custom/Modded Mordhau Map Creators. You can set a range with a Sphere around a SpawnPoint. If somebody stays inside this Sphere the Spawn Controller will check for another SpawnPoint.

# ! IMPORTANT NOTE !
## Do not rename/move the folder structure or any files before the import process has finished successfully. And also afterwards, only do such stuff in the UE4 ContentBrowser!




> **1.** Download the newest version of this [**\> HERE <**](https://github.com/WaGi-Coding/TakiRandomSpawnForMordhau/releases)


> **2.** Unpack **`TakiUtility.zip`** into `\Content\Mordhau\Maps\` so the full path where the 2 Blueprints are is `\Content\Mordhau\Maps\TakiUtility\` containing TakiSpawnController.uasset & TakiSpawnPoint.uasset
![Guide-Image-2](https://i.imgur.com/FJ45KYl.jpg)

> **3.** Open your Project and open your Maps LevelBlueprint

> **4.** Drag **`TakiSpawnController`** into the LevelBlueprint and connect the Event BeginPlay with it.
![Guide-Image-4](https://i.imgur.com/4zMmaBM.jpg)

> **5.** Hit `Compile` & `Save` afterwards

> **6** Go into your Level Scene/Viewport and drag in some **`TakiSpawnPoint`**'s
![Guide-Image-6](https://i.imgur.com/vOCSpNQ.jpg)

## Thats it!

For sure you need the cooked blueprints in same location as in your editor on your client then

You maybe want to adjust the Spheres Radius.
You can find that in the Component Hierachy
![ChangeSphereSize-Explanation](https://i.imgur.com/N9shS0T.jpg)

Aswell you can now switch between Box or Sphere for the detection
[Sphere-or-Box](https://i.imgur.com/yu1xCrg.jpg)
