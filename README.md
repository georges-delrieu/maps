# How to use Titled to create a map

You can find the version to download here: https://thorbjorn.itch.io/tiled

Launch Tiled and open the file you want to work on it

## Tileset

To import new Tilesets

![image](https://user-images.githubusercontent.com/93337876/163482191-a9167a04-8293-46e2-bc03-374c798b9306.png)

Select the image you want to import and name it as follow:

+ 00_*InsertName* --> special effect Tileset
+ 01_*InsertName* --> package Tileset
+ 02_*InsertName* --> character Tileset
+ 03_*InsertName* --> one object Tileset

![image](https://user-images.githubusercontent.com/93337876/163482976-942c2f7c-6e34-4712-9c5a-3c6ffff954e3.png)
Do not forget to check "Embed in map"


### Special_Zones Tileset ###

To add a special tile in the Tileset, go to Figma, in the __Ingame_assets__. 

![image](https://user-images.githubusercontent.com/93337876/163486005-307d48d1-4fc7-4082-ad82-3afa6efb427a.png)

Add the new block next to the old ones and add them in the group. 
Then export the group in PNG

![image](https://user-images.githubusercontent.com/93337876/163487378-5e788829-a3de-45aa-8b18-fed3cdc5d44a.png)

![image](https://user-images.githubusercontent.com/93337876/163487444-5df91a50-0ed6-4217-ba15-cb088b750ce9.png)



## Layers

__floorLayer__ will be the layer where the characters are. The character will appear above every objects you will add below this layer.
If your character need to pass below an object, you'll need to add it on one of the layer in the __AbovePlayer__ folder.

Always add a layer in the __SpecialEffects__ when using a tile in the __Special_Zones__ Tileset.

![image](https://user-images.githubusercontent.com/93337876/163487667-808510d5-3989-49a2-90f9-bb2907009519.png)

