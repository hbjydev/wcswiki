# Adding armbands to a loadout

1. Edit your loadout prefab by double clicking on it in the workbench, then pressing the edit button on the far right side.

   ![How to edit the prefab](/img/mods/armbands/loadout_tut_0.png)

2. In your main prefab object (the character), scroll down in the components list until you find `BaseLoadoutManagerComponent`.

   ![A view of the components list showing `BaseLoadoutManagerComponent` selected](/img/mods/armbands/loadout_tut_1.png)

3. Expand the `Slots` tree and look for the slot named `Armband`.

   ![The armband slot](/img/mods/armbands/loadout_tut_2.png)

4. In the Resource Browser, find `WCS_Armbands/Prefabs/Characters/Armbands`.

   ![The resource browser, navigated to the Armbands directory](/img/mods/armbands/loadout_tut_3.png)

5. Drag the desired armband into the `Prefab` attribute in the Armband slot in your character's loadout.

   ![A user dragging an armband into the Prefab attribute on the Armband slot](/img/mods/armbands/loadout_tut_4.gif)