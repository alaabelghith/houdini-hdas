# houdini-hdas

Houdini digital assets I built and published. Each one is a procedural tool with exposed
parameters — drop it in a SOP network and drive it. Written with VEX inside, no Python
dependency.

All six are also on [Gumroad](https://belguithala.gumroad.com) with a video demo each.
47 downloads to date.

| Asset | What it does | Demo | Gumroad |
|---|---|---|---|
| `alaa_greeble` | Greebling — recursive panel detail across any surface | [video](https://www.youtube.com/watch?v=M21rUnqC2BE) | [get](https://belguithala.gumroad.com/l/mfdsj) |
| `alaa.scattered_effect` | Controlled scatter / disintegration of geometry | [video](https://www.youtube.com/watch?v=A7yQEYU_clM) | [get](https://belguithala.gumroad.com/l/mcrha) |
| `alaa.reaction_diffusion_growth` | Gray-Scott reaction diffusion driving surface growth | [video](https://www.youtube.com/watch?v=nc0F1iwYiyc) | [get](https://belguithala.gumroad.com/l/flszgv) |
| `alaa.curve_flow` | Flow and animation along arbitrary curves | [video](https://www.youtube.com/watch?v=V3V1r1GGlsM) | [get](https://belguithala.gumroad.com/l/uhovo) |
| `alaa.adaptive_subdivision_along_curve` | Adaptive subdivision driven by a curve | [video](https://www.youtube.com/watch?v=oWohBEz2QqI) | [get](https://belguithala.gumroad.com/l/rzuax) |
| `alaa.pinArt_ray` | Pin-art displacement by raycast against a target | [video](https://www.youtube.com/watch?v=_dMXA6TjH3E) | [get](https://belguithala.gumroad.com/l/vafbc) |

## Install

Copy the `.hda` files into your Houdini otls directory:

- Windows — `C:\Users\<you>\Documents\houdini<version>\otls\`
- macOS — `~/Library/Preferences/houdini/<version>/otls/`
- Linux — `~/houdini<version>/otls/`

Restart Houdini, or **Assets → Install Asset Library** and point at the file. The nodes
appear in the SOP tab menu.

Built in Houdini 20.5. Licensed MIT — use them in commercial work.

---
Alaa Belghith — Houdini FX / 3D generalist. [Portfolio](https://alaabelghith.github.io) ·
[ArtStation](https://artstation.com/alabelguith)
