The XKT format compresses large, double-precision models to a compact payload that loads quickly over the Web into 
a xeokit viewer running in the browser. 

We use xeokit-xkt-utils to convert various formats into XKT, and to generate XKT with JavaScript on Nodejs.

Listed below are the various versions of the XKT format that we have used with xeokit so far. The topmost XKT version 
is the one that's used in the most recent xeokit release, while versions below that are considered legacy. The xeokit SDK is backwardly-compatible with all legacy 
XKT versions, but it's a good idea to always migrate our data to the latest version to get the latest benefits.
<br><br>

| XKT Version | Features | Specification |
| --- | --- | --- |
| v9 | Triangles, lines and points<br>Geometry reuse<br>Quantized geometry<br>Per-instance geometry colors<br>Double-precision geometry<br>Vertex colors<br>Improved meta objects<br>PBR materials<br>Vertex normals optional<br>Vertex colors alpha channel| [xkt_v9.md](https://github.com/xeokit/xeokit-xkt-utils/tree/master/specs/xkt_v9.md) <br>[xkt_v9_metadata_schema.json](https://github.com/xeokit/xeokit-xkt-utils/blob/master/specs/xkt_v9_metadata.schema.json) |
| v8 | Triangles, lines and points<br>Geometry reuse<br>Quantized geometry<br>Per-instance geometry colors<br>Double-precision geometry<br>Vertex colors<br>Meta-objects<br>PBR materials | |
| v7 | Triangles lines and points<br>Geometry reuse<br>Quantized geometry<br>Per-instance geometry colors<br>Double-precision geometry<br>Vertex colors| |
| v6 | Triangles<br>Geometry reuse<br>Quantized geometry<br>Per-instance geometry colors<br>Double-precision geometry| |
| v5 | Triangles<br>Geometry reuse<br>Quantized geometry<br>Per-instance geometry colors| |
| v4 | Triangles<br>No geometry reuse<br>Quantized geometry<br>Per-instance geometry colors| |
| v3 | Triangles<br>No geometry reuse<br>Quantized geometry | |
| v2 | Triangles<br>No geometry reuse<br>Quantized geometry | |
| v1 | Triangles<br>No geometry reuse<br>Quantized geometry | |