填充走线宽度
====
The width of every line of infill being drawn. The width of a line can be different from the nozzle size simply by extruding more or less material than needed. If more material is extruded, the plastic will flow towards the sides, making the line thicker. If less material is extruded, the surface tension of the material tends to pull the material towards the centre line of the nozzle's path.
打印填充线的宽度。这个线宽是由不同尺寸的喷嘴来挤出或多或少的材料所形成的。如果挤出较多的材料，塑料将向两侧流动，线条变得更宽，如果挤出较少的材料，由于材料的表面张力，将挤出的材料拉向喷嘴路径的中心线。

![填充走线明显比其他的线宽](../../../articles/images/infill_line_width.png)

Making the infill lines wider can make your print stronger and reduce printing time as well. However, increasing it too much can cause great extrusion fluctuations. This will cause underextrusion when printing the infill and overextrusion when printing whatever comes after infill, because the flow through the nozzle cannot adjust fast enough.


**The actual infill lines may come out wider than what this setting says, if you've adjusted the [Infill Layer Thickness](../infill/infill_sparse_thickness.md) setting.**