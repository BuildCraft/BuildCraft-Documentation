# Actions

* **Filter** - filters what items/fluids the linked robot can load/unload into its inventory.
* **Filter Tool** - filters what items the linked robot can equip.

* **Go To Station** - instructs the linked robot to go to and dock on its linked station. If you specify a map location with a point selection, the robot will change its main linked station for the 
station in the point specified.
* **Wake Up** - if the linked robot is sleeping, it wakes the robot to make it check for new work.

* **Work in Area** - the linked robot will work only in the specified area.
* **Load/Unload in Area** - the linked robot will only load/unload or equip from docking stations inside the specified area.

* **Accept Items/Fluids** - robots can unload items/fluids in this docking station. Only available on item/fluid pipes. If you specify items/fluids as parameters it will allow the robot to unload only 
the specified items/fluids.
* **Provide Items/Fluids** - robots can load items/fluids from the associated inventory/tank. Only available when the gate is on a wooden or emerald pipe, and the robot can only take items/fluids from the extraction side of the pipe. If you specify items/fluids as parameters it will allow the robot to load only the specified items/fluids.

* **Forbid Robot** - prevents any robots of the specified types to dock on the docking station.
* **Force Robot** - allows only robots of the specified types to dock on the docking station.
* Both Forbid and Force Robot can use not only robot types themselves, but also wearables such as helmets.

# Triggers

* **Robot In Station** - activates when there is at least one robot docked in a docking station.
* **Station Linked** - activates when there is at least one docking station that is a main link.
* **Station Reserved** - activates when there is at least one docking station that is reserved.
* **Sleep** - activates when there is at least one robot sleeping in a docking station.

