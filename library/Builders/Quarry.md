The Quarry, unlike the other machines, is an automatic large-scale mining device. It can mine a large area (up to 64x64) layer by layer down to bedrock. However, it will be stopped by heavy liquids (such 
as lava or [oil](/Energy/Oil.md)).

By default, when placed on the ground, the quarry will define a 9x9 square as the digging area. First, the area defined by the quarry's stripes cube will be cleared (without dropping items!) to make place for the frame outline and the mechanical arm. Next, the frame outline will be built, then the mechanical arm will appear and the quarry will start digging.

![Quarry mining in a 9x9 square](/images/screenshots/quarry1.png)

The Quarry will try outputting in the following order:

* First, if there is an inventory adjacent to the Quarry, it will try inserting into it.
* Next, it will put items into adjacent transport pipes.
* Finally, failing that, it will throw the items into the air.

![Quarry auto-ejecting into a Transport Pipe](/images/screenshots/quarry2.png)

You can define the Quarry's mining area with [Land Marks](/Core/Land_Mark.md).

![Small...](/images/screenshots/quarry3.png)

![...or large!](/images/screenshots/quarry4.png)
