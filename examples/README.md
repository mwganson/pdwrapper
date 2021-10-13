# Examples folder

The draft array of sketches example wraps a draft array of sketches inside a None type.  Any non-solids should be wrapped in None types and there should be at least one solid feature ahead of the PDWrapper None type in the tree.  The PDWrapper reflects the previous solid feature's shape as its own, so FreeCAD doesn't complain about having an empty tip shape.  Use the 2D objects (in this case the Array, since it's a 2D object, being an array of 2D sketches) directly with Pad, Pocket, etc. or you may use the wrapper object if it shows as visible when it is made visible.  You might need to toggle the PDWrapper Enabled to 0 in some cases (double click the PDWRapper in the tree to toggle Enabled property).

<img src="pdwrapper_scr7.png" alt="screenshot showing draft array of sketches and additive holes">
