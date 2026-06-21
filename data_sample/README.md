# Controlled Data Sample

This folder provides a small, public, de-identified preview of the controlled data structure. It is intended to help requesters understand what approved controlled access can provide.

Each sample contains:

- `metadata.json`: representative record-level fields and model/label metadata with sensitive values removed or replaced.
- `aoi_local.geojson`: AOI geometry in local normalized tile coordinates, not real-world coordinates.
- `remote_sensing_tile.png`: low-resolution, stripped remote-sensing thumbnail for format preview only.

The public samples do **not** include real AOI IDs, community names, addresses, provider IDs, real geographic coordinates, raw provider metadata, or full-resolution imagery. Approved controlled archives may include source CRS geometries, image chips, provider-derived metadata, Guangzhou human labels, and diagnostic transfer components only under the signed DUA.

For controlled access requests, contact `m.zhao@connect.hkust-gz.edu.cn`.
