# OP-XY custom machines, kit 047

Download files for [foundmotive.com/opxy/](https://foundmotive.com/opxy/): the kit, the audio demos and the licenses.
Served by GitHub Pages at https://foundmotive.github.io/opxy-kit/ from the `main` branch root.
This repository hosts the files only. It is not the source of the public page.

Current kit, 047 (OS 1.2.1, open-xy SDK 1.10):

- `download/opxy-kit-047.zip` (+ `.sha256`): the kit (README, layout.json, offline opxy-builder.html, notices, SHA256SUMS). It holds no firmware; users supply their own stock os.ldr.
  SHA256 `add590df1e227304d5cafed0643323e0603cb9574fda83fba834ce7ca3c88e03`

Older kits stay in `download/` with their `.sha256` files:

- `download/opxy-kit-031.zip` SHA256 `b4ddf3391513e1d005e7ea241dd0b9d7d339def337a59560f39f7d6627990f34`
- `download/opxy-kit-030.zip` SHA256 `c85e2d38995b70576f2f57aafa6d4c4aded3294b8c6996a92e9b9e4c4425ebb5` (includes Electric guitar)
- `download/opxy-kit-029.zip` SHA256 `4b5040cd67c61a93d7cacf85746188132a6c62335d50b19a15ef17784d7e7cd1`
- `download/opxy-kit-028b.zip` SHA256 `8e8445ecdce502adccc09e5128d7d6d8cc0502d4e6fc13ded9a4723e53dcd972` (OS 1.2.0)
- `download/opxy-kit-020.zip` SHA256 `87988b56365d13ee6e0f5f0bac047fba2ae8adbad88217b15743c0c4d9cf4bc1`
- `download/opxy-visuals-030.zip` SHA256 `2d4d0a10d05db9d142dae587f8cfd3399bce70edeaddefc7c428bca37bffddd2`

- `audio/*.ogg`: demos rendered offline on a computer from each machine's own C++ source (host build), 44.1 kHz, peak-normalized, with a short fade standing in for the OP-XY amp release. Guitar demos are kit 019 renders, Shaker demos (default egg, Softegg) are kit 020 renders. The Vocal Tune demo is a placeholder.
- `licenses/`: Martin HD28 CC0 (Jeff Learman), Virtuosity Drums CC0 (Versilian Studios LLC, Karoryfer Lecolds), open-xy MIT, Vocal Tune demo voice CC0 (Dcoetzee), Braids / Macro Osc MIT (Emilie Gillet, Mutable Instruments), the STMicroelectronics notice, and the full notices embedded in opxy-builder.html.

## Credits
open-xy SDK by etcetc000 (MIT). Conductor by Max Mockett (mmockett), MIT. Screen ideas inspired by Max Mockett (https://mmockett.github.io/OP-XY/, MIT). Not affiliated with Teenage Engineering.

- Conductor groove statistics come from the Magenta Groove MIDI Dataset (Google LLC, CC BY 4.0).
- Guitar samples: Martin HD28 by Jeff Learman, Discord SFZ GM Bank, CC0 1.0.
- Groove Kit samples: Virtuosity Drums by Versilian Studios LLC and Karoryfer Lecolds, CC0 1.0.
- Vocal Tune demo input: "Twinkle Twinkle Little Star - sung with full lyrics.ogg" by Dcoetzee, Wikimedia Commons, CC0 1.0.
- Shaker reference recording, used only for analysis and not shipped: "Eggshaker_Solo.ogg" by Paddy, Wikimedia Commons (https://commons.wikimedia.org/wiki/File:Eggshaker_Solo.ogg), CC BY-SA 4.0. Shaker after Perry R. Cook's PhISEM idea.
- Macro Osc: code by Emilie Gillet (Mutable Instruments Braids), MIT.
- Code in third_party/STM is from STMicroelectronics, released under its notice.

No stock firmware, no os.ldr.
