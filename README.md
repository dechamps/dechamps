# Etienne Dechamps

Also known as: **dechamps**, **edechamps**, **e-t172**

I am a software engineer with ~20 years experience (~10 years professionally)
specializing in backend/systems programming targetting Linux and Windows. I also
like to spend my time on pet projects related to audio and video playback (e.g.
calibration, signal processing), and a bunch of other things.

My primary language is C++, but I also dabble in Python especially for data
crunching and signal processing projects. I'd love to write some Rust one day.

**This is my _personal_ profile describing projects I do on my free time. I am
also employed as a software engineer by Google, but none of the activity under
this GitHub profile is affiliated to my employer in any way.** My GitHub
activity on behalf of my employer can be found under the [edechamps-Google
profile][].

## Active projects

- **[FlexASIO][]**, a universal [ASIO][] driver _(C++, Windows, audio)_
  - By far the project I'm most known for, with 1k+ GitHub stars and a Wikipedia
    mention.
- **[ASIO401][]**, an [ASIO][] driver for the [QA403][] industrial-grade audio
  analyzer and earlier versions _(C++, Windows, USB, audio)_
  - Directly implementing a bespoke USB protocol using [WinUSB][].
  - Developed with the support and [blessing][] of the manufacturer.
- **[videojitter][]**, a physical light-based video frame presentation timing
  measurement system _(Python, video, signal processing)_
  - The first tool of its kind, as far as I'm aware.

## Inactive projects

- **[Loudspeaker Explorer][]**, a loudspeaker measurement visualization,
  analysis and comparison tool _(Python, Jupyter, data visualization, audio)_
  - Ever wondered what would happen if someone crammed an entire app into a
    single [Jupyter][] notebook and ran the entire thing off [Colab][]? Now you
    know.
- **[RudeWindowFixer][]**, a tool to fix Windows always-on-top taskbar issues
  _(C, Windows, binary reverse engineering)_
  - My first foray into binary reverse engineering, reversing closed-source
    Windows explorer binaries related to taskbar operation and using my findings
    to work around a particularly annoying bug Microsoft hasn't bothered to fix
    in many years.
- **[WindowInvestigator][]**, a set of Windows window management introspection
  tools _(C, Windows)_
  - I wrote these to help with the investigation that led to RudeWindowFixer.
- **[WinSoftVol][]**, a Windows driver to force software volume control _(C,
  Windows, kernel-mode driver)_
  - My first foray into Windows driver development.
  - This trivial filter driver alters the way Windows audio devices work,
    preventing Windows from using hardware volume control.
- **[kmlpipe][]**, a geographic data processing toolbox _(bash, XSLT, GIS)_
  - I wrote this to assist me in my search for the perfect London flat.
  - It's a [geographical information system][] using XML files as its internal
    representation _(I'm sorry)_, with individual processing steps written in
    [XSLT][] _(I'm very sorry)_, with the whole thing orchestrated by a pile of
    shell scripts _(I am so, so sorry)_. It also integrates with various APIs
    like Google Maps.
    - Needless to say, if you're planning to use this, you are either very
      brave, foolish, or both.
- **[AudioMeterEvent][]**, a tool to automatically call an HTTP API when a
  Windows audio device is in use _(C#, Windows, audio)_
  - My first foray into C#.
  - I use this for home automation, to automatically turn my speakers on/off
    based on audio activity.
- **[LGTVDeviceListener][]**, an LG TV remote control tool triggered by Windows
  USB device plug/unplug events _(C++, Windows)_
  - _What do you mean, "niche"?_
- **[laplock][]**, a tool to automatically lock a Windows laptop when its lid is
  closed _(C, Windows)_
  - One of these _"I can't believe Windows doesn't have that built in"_
    workarounds
  - My oldest project on GitHub: initial release was in 2013. It still works and
    I still use it to this day!
- **[APO][]**, a bunch of random docs on [Windows APOs][] _(Windows, audio)_
- **[audiotools][]**, a disparate set of docs and tools for audio measurement
  _(audio)_
  - Includes discussions of some of the relevant IEC and AES standards.
- **[HDRCompare][]**, a set of filters to compare SDR vs. [HDR][] video files
  _(ffmpeg, video)_
- **[WinIPBroadcast][]**, a tool to send network broadcasts to all Windows
  network interfaces _(C, Windows, networking)_
  - Another decade-old tool, which (as far as I know) still works to this day.
  - I wrote it to get old LAN games to work. Not nearly as useful nowadays.

## Projects I've significantly contributed to

- **[tinc][]**, a peer-to-peer mesh VPN _(C, networking)_
  - Made major contributions to the modern tinc 1.1 protocol (SPTPS), including
    redesigning the way it does NAT traversal (UDP hole punching, etc.) and MTU
    probing.
- **[ZFS On Linux]**, a feature-rich filesystem _(C, Linux, kernel)_
  - My first foray into Linux kernel development.
  - Made a number of non-trivial contributions, mostly related to performance
    and scalability, on behalf of my employer at the time, [OVH][].

[ASIO]: https://en.wikipedia.org/wiki/Audio_Stream_Input/Output
[ASIO401]: https://github.com/dechamps/ASIO401
[APO]: https://github.com/dechamps/APO
[AudioMeterEvent]: https://github.com/dechamps/AudioMeterEvent
[audiotools]: https://github.com/dechamps/audiotools
[blessing]: https://quantasylum.com/blogs/news/asio-arrives
[Colab]: https://colab.research.google.com/
[edechamps-Google profile]: https://github.com/edechamps-Google
[FlexASIO]: https://github.com/dechamps/FlexASIO
[geographical information system]:
  https://en.wikipedia.org/wiki/Geographic_information_system
[HDR]: https://en.wikipedia.org/wiki/High-dynamic-range_television
[HDRCompare]: https://github.com/dechamps/HDRCompare
[Jupyter]: https://jupyter.org/
[kmlpipe]: https://github.com/dechamps/kmlpipe
[laplock]: https://github.com/dechamps/laplock
[LGTVDeviceListener]: https://github.com/dechamps/LGTVDeviceListener
[Loudspeaker explorer]: https://github.com/dechamps/LoudspeakerExplorer
[QA403]: https://quantasylum.com/products/qa403-audio-analyzer
[RudeWindowFixer]: https://github.com/dechamps/RudeWindowFixer
[tinc]: https://github.com/gsliepen/tinc/issues?q=author%3Adechamps
[videojitter]: https://github.com/dechamps/videojitter
[OVH]: https://www.ovhcloud.com/
[WinSoftVol]: https://github.com/dechamps/WinSoftVol
[WindowInvestigator]: https://github.com/dechamps/WindowInvestigator
[Windows APOs]:
  https://learn.microsoft.com/en-us/windows-hardware/drivers/audio/audio-processing-object-architecture
[WinIPBroadcast]: https://github.com/dechamps/WinIPBroadcast
[WinUSB]:
  https://learn.microsoft.com/en-us/windows-hardware/drivers/usbcon/winusb
[World In Conflict]: https://en.wikipedia.org/wiki/World_in_Conflict
[WorldInConflict-FPM]: https://github.com/dechamps/WorldInConflict-FPM
[XSLT]: https://en.wikipedia.org/wiki/XSLT
[ZFS On Linux]: https://github.com/openzfs/zfs/issues?q=author%3Adechamps
