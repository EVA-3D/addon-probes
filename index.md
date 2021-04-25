---
title: Bed Probing
uid: EVA / Addons / Probes
type: addon
badges:
    - Official
contributors: 
    - pkucmus
repo_url: https://github.com/EVA-3D/addon-probes
cad_url: https://cad.onshape.com/documents/94cafeab52e3dfa0a28bae89/w/99794094315556b24b5664ec/e/e50692a479f24cc5bf03727a
satisfies:
    - bed_probe
---

# Bed Probing

![preview](assets/__ALL__.png)

This EVA Addon is supposed to contain different mounting solutions for different bed probe options. In some cases it might make more sense to mirror the mount in the slicer to move the probe to the right side of the carriage.

## Offsets

=== "Inductive Probe"
    === "8mm"

        <img src="assets/LJ8_probe_mount.png" width="300"/>

        - Hemera: `X31.48`, `Y-41.69`
        - Aero: `X-50.35`, `Y8` or `X-14`, `Y-44.9`
        - Others: `X-27.8`, `Y-12`

        <add-bom-button name="{{ meta.uid }} (LJ8)">
            {{ bom_to_json("inductive_8mm.csv") }}
        </add-bom-button>
        
        {{ bom_to_md_table("inductive_8mm.csv", 8) }}

    === "12mm"

        <img src="assets/LJ12_probe_mount.png" width="300"/>

        - Hemera: `X32.98`, `Y-43.69`
        - Aero: `X-52.35`, `Y6.5` or `X-12.5`, `Y-46.9`
        - Others: `X-29.8`, `Y-13.5`

        <add-bom-button name="{{ meta.uid }} (LJ12)">
            {{ bom_to_json("inductive_12mm.csv") }}
        </add-bom-button>
        
        {{ bom_to_md_table("inductive_12mm.csv", 8) }}

    === "18mm"

        <img src="assets/LJ18_probe_mount.png" width="300"/>

        - Hemera: `X36.98`, `Y-46.69`
        - Aero: `X-55.35`, `Y2.5` or `X-8.5`, `Y-49.9`
        - Others: `X-32.8`, `Y-17.5`

        <add-bom-button name="{{ meta.uid }} (LJ18)">
            {{ bom_to_json("inductive_18mm.csv") }}
        </add-bom-button>
        
        {{ bom_to_md_table("inductive_18mm.csv", 8) }}

=== "BLTouch"
    === "Standard"

        <img src="assets/bl_touch_mount.png" width="300"/>

        - Hemera: `X32.5`, `Y-42`
        - Aero: `X-50.55`, `Y7` or `X-13`, `Y-45.1`
        - Others: `X-28`, `Y-13`

        <add-bom-button name="{{ meta.uid }} (BL)">
            {{ bom_to_json("bltouch.csv") }}
        </add-bom-button>
        
        {{ bom_to_md_table("bltouch.csv", 8) }}

    === "Alternative"

        <img src="assets/bl_touch_mount_alt.png" width="300"/>

        - Hemera: `X24.5`, `Y-46.84`
        - Aero: `X-58`, `Y15` or `X-21`, `Y-50.6`
        - Others: `X-33.48`, `Y-5`

        <add-bom-button name="{{ meta.uid }} (BL-alt)">
            {{ bom_to_json("bltouch_alt.csv") }}
        </add-bom-button>
        
        {{ bom_to_md_table("bltouch_alt.csv", 8) }}
