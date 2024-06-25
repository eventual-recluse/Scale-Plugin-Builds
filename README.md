# ScaleSequence and ScaleSpace Plugin Builds

[ScaleSequence](https://github.com/eventual-recluse/ScaleSequence), [ScaleSpace](https://github.com/eventual-recluse/ScaleSpace) and [ScaleSpace 3D](https://github.com/eventual-recluse/ScaleSpace-3D) are [MTS-ESP](https://github.com/ODDSound/MTS-ESP) master plugins, which allow the dynamic manipulation of the current scale in a Digital Audio Workstation.

This repository contains builds in CLAP and VST3 formats.

# Updates

**25 Jun 2024:** GUI issues should be fixed on Mac. Mac versions now built with macOS 12.

24 Jun 2024: Added ScaleSpace-3D builds and linux builds for all plugins. Fixed sticky Y axis in ScaleSpace.

23 Jun 2024: Both plugins are now categorised as instrument plugins. Added popup notifications if the tuning or keymapping is reset. MIDI Ports and MIDI pass-through removed from ScaleSpace.

# Notes

To use these plugins, you will need Scala scale files (.scl) and / or keymapping files (.kbm). You will also need to install [libMTS.](https://github.com/ODDSound/MTS-ESP)

There is a large collection of .scl files at the [Scala Scale Archive.](https://huygens-fokker.org/microtonality/scales.html)

A collection of .scl and .kbm files can be found in the [Sevish Tuning Pack.](https://sevish.com/music-resources/#tuning-files)

If you wish to automate the ScaleSequence parameters in Ardour DAW, you should first go to Edit -> Preferences -> Performance,  and set Automatables to 'unlimited', then reload the plugin. This issue should be fixed in an upcoming version of Ardour.

A full workflow for building these plugins from source with Github Actions can be found in full_workflow.txt. Used with the source repositories, this workflow will build more formats on more platforms than are available here.

# Credits and attribution
[DISTRHO Plugin Framework.](https://github.com/DISTRHO/DPF) Copyright (C) 2012-2024 Filipe Coelho <falktx@falktx.com>. ISC license.

[MTS-ESP.](https://github.com/ODDSound/MTS-ESP) Copyright (C) 2021 by ODDSound Ltd. info@oddsound.com. 0BSD license.

[Surge Synthesizer Tuning Library.](https://github.com/surge-synthesizer/tuning-library) Copyright 2019-2020, Paul Walker. MIT license.

[Dear ImGui.](https://github.com/ocornut/imgui) Copyright (c) 2014-2024 Omar Cornut. MIT license.

[DearWidgets](https://github.com/soufianekhiat/DearWidgets) for the XY slider widget. CC0-1.0 license.

[Bruno Ace Font](https://fonts.google.com/specimen/Bruno+Ace) designed by Astigmatic. [Open Font License.](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)

[Bruno Ace SC Font](https://fonts.google.com/specimen/Bruno+Ace+SC) designed by Astigmatic. [Open Font License.](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)

[Lekton Font](https://fonts.google.com/specimen/Lekton) designed by ISIA Urbino. [Open Font License.](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)

CLAP. Copyright 2014-2022 Alexandre Bique.
