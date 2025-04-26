# ScaleSequence and ScaleSpace Plugin Builds

[ScaleSequence](https://github.com/eventual-recluse/ScaleSequence) and [Scale-Space](https://github.com/eventual-recluse/Scale-Space) are [MTS-ESP](https://github.com/ODDSound/MTS-ESP) master plugins, which allow the dynamic manipulation of the current scale in a Digital Audio Workstation.

# Updates

21 April 2025: Scale-Space version 0.0.2 (Bug fix: Ensure plugin editor and editor window are deleted. Poll for MIDI note changes.)
22 April 2025: Scale-Space version 0.0.3 (Setup existing tuningEditor for a new scale when opening the TuningEditor window.)
23 April 2025: Scale-Space version 0.0.4 (tuningEditor moved to PluginEditor.)
26 April 2025: Scale-Space version 0.0.5 (UI fixes.)

# Notes

To use these plugins, you will need Scala scale files (.scl) and / or keymapping files (.kbm). You will also need to install [libMTS.](https://github.com/ODDSound/MTS-ESP)

There is a large collection of .scl files at the [Scala Scale Archive.](https://huygens-fokker.org/microtonality/scales.html)

A collection of .scl and .kbm files can be found in the [Sevish Tuning Pack.](https://sevish.com/music-resources/#tuning-files)

If you wish to automate the ScaleSequence parameters in Ardour DAW, you should first go to Edit -> Preferences -> Performance,  and set Automatables to 'unlimited', then reload the plugin. This issue should be fixed in an upcoming version of Ardour.

# Credits and attribution
[DISTRHO Plugin Framework.](https://github.com/DISTRHO/DPF) Copyright (C) 2012-2024 Filipe Coelho <falktx@falktx.com>. ISC license.

[JUCE Framework.](https://github.com/juce-framework/JUCE) AGPLv3 license.

[MTS-ESP.](https://github.com/ODDSound/MTS-ESP) Copyright (C) 2021 by ODDSound Ltd. info@oddsound.com. 0BSD license.

[Surge Synthesizer Tuning Library.](https://github.com/surge-synthesizer/tuning-library) Copyright 2019-2020, Paul Walker. MIT license.

The Tuning Editor in Scale-Space, and supporting code, is adapted from [Surge XT.](https://github.com/surge-synthesizer/surge) GPL-3.0 license.

[Dear ImGui.](https://github.com/ocornut/imgui) Copyright (c) 2014-2024 Omar Cornut. MIT license.

[DearWidgets](https://github.com/soufianekhiat/DearWidgets) for the XY slider and 3D slider widgets. CC0-1.0 license.

[Bruno Ace Font](https://fonts.google.com/specimen/Bruno+Ace) designed by Astigmatic. [Open Font License.](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)

[Bruno Ace SC Font](https://fonts.google.com/specimen/Bruno+Ace+SC) designed by Astigmatic. [Open Font License.](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)

[Lekton Font](https://fonts.google.com/specimen/Lekton) designed by ISIA Urbino. [Open Font License.](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL)

[fmt.](https://github.com/fmtlib/fmt) [License.](https://github.com/fmtlib/fmt/blob/master/LICENSE)

CLAP. Copyright 2014-2022 Alexandre Bique.

[dpf-cmake-action.](https://github.com/DISTRHO/dpf-cmake-action) Copyright (C) 2022 Filipe Coelho <falktx@falktx.com>. ISC license.

Scale-Space 2D pad initally based on the XY pad from [aether.](https://github.com/Coconut-audio/aether) GPL-3.0 license.

