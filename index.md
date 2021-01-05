---
badges:
    - Official
---

# Bed Probing

![preview](assets/__ALL__.png)

This EVA Addon is supposed to contain different mounting solutions for different bed probe options. In some cases it might make more sense to mirror the mount in the slicer to 

{{ eva_link("probes") }}

{{ onshape_link("probes") }}

## Offsets

=== "Inductive Probe"
    === "8mm"

        <img src="assets/LJ8_probe_mount.png" width="300"/>

        - Hemera: `X31.48`, `Y-41.69`
        - Aero: `X-50.35`, `Y8` or `X-14`, `Y-44.9`
        - Others: `X-27.8`, `Y-12`

{{ bom("addons/probes/bom/inductive_8mm.csv", 8) }}

    === "12mm"

        <img src="assets/LJ12_probe_mount.png" width="300"/>

        - Hemera: `X32.98`, `Y-43.69`
        - Aero: `X-52.35`, `Y6.5` or `X-12.5`, `Y-46.9`
        - Others: `X-29.8`, `Y-13.5`

{{ bom("addons/probes/bom/inductive_12mm.csv", 8) }}

    === "18mm"

        <img src="assets/LJ18_probe_mount.png" width="300"/>

        - Hemera: `X36.98`, `Y-46.69`
        - Aero: `X-55.35`, `Y2.5` or `X-8.5`, `Y-49.9`
        - Others: `X-32.8`, `Y-17.5`

{{ bom("addons/probes/bom/inductive_18mm.csv", 8) }}

=== "BLTouch"
    === "Standard"

        <img src="assets/bl_touch_mount.png" width="300"/>

        - Hemera: `X32.5`, `Y-42`
        - Aero: `X-50.55`, `Y7` or `X-13`, `Y-45.1`
        - Others: `X-28`, `Y-13`

{{ bom("addons/probes/bom/bltouch.csv", 8) }}

    === "Alternative"

        <img src="assets/bl_touch_mount_alt.png" width="300"/>

        - Hemera: `X24.5`, `Y-46.84`
        - Aero: `X-58`, `Y15` or `X-21`, `Y-50.6`
        - Others: `X-33.48`, `Y-5`

{{ bom("addons/probes/bom/bltouch_alt.csv", 8) }}
