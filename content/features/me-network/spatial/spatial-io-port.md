---
categories:
- ME Network/Spatial
item_ids:
  - appliedenergistics2:spatial_io_port
title: Spatial IO Port
---

![A picture of a Spatial IO
Port](../../../../public/assets/large/spatial_io_port.png)<ItemLink
id="appliedenergistics2:spatial_io_port"/> are used to capture and
deploy regions of space that are defiend by <ItemLink
id="appliedenergistics2:spatial_pylon"/>.



To Capture/Deploy a region of space you must first construct a [Spatial
Containtment Structure](spatial-containment-structure.md), once
constructed and ready your <ItemLink
id="appliedenergistics2:spatial_io_port"/> will show your required
power, and current power, the next step would be to adjust your
[SCS](spatial-containment-structure.md) design, or to build and
power your required <ItemLink id="appliedenergistics2:energy_cell"/>
or <ItemLink id="appliedenergistics2:dense_energy_cell"/> to meet
the demands of the <ItemLink
id="appliedenergistics2:spatial_io_port"/>.



Once power is available and your [SCS](../Spatial-Containment-
Structure/index.html) is valid, you need to insert a <ItemLink
id="appliedenergistics2:2_cubed_spatial_storage_cell"/>, <ItemLink
id="appliedenergistics2:16_cubed_spatial_storage_cell"/>, or
<ItemLink id="appliedenergistics2:128_cubed_spatial_storage_cell"/>
depending on the required size you may need a larger or small storage cell.



When everything is ready, and the storage cell is placed inside the <ItemLink
id="appliedenergistics2:spatial_io_port"/> applying a redstone
signal to the <ItemLink id="appliedenergistics2:spatial_io_port"/>
will trigger the capture/deployment of the cell into the [SCS](../Spatial-
Containment-Structure/index.html).



Requires a [channel](../../channels.md) to function.



 *** Note Spatial uses a white list compatibilty system, only tile entities
marked as "whitelisted" can be moved with this system, other mod authors can
opt-into this, AE2 provides support for itself, and Vanilla.**



 **Also see[Spatial IO Compat
Project](https://github.com/AlgorithmX2/SpatialIO-Compat)**

<RecipeFor id="appliedenergistics2:spatial_io_port"/>