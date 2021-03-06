# Audio Monitor dock and filter for OBS Studio

Plugin for OBS Studio to add Audio Monitor dock and filter.
It allows you to put the audio of a OBS source to an audio device by adding the Audio Monitor filter on the Source in OBS Studio.

![Screenshot](media/screenshot.png)

This can be useful in different use cases:

   * monitoring a source on multiple devices
   * monitoring audio without the delays of syncing to video
   * separate monitoring audio levels per source and device
   
# Download
https://obsproject.com/forum/resources/audio-monitor.1186/

# Build
- Build OBS Studio: https://obsproject.com/wiki/Install-Instructions
- Check out this repository to UI/frontend-plugins/audio-monitor
- Add `add_subdirectory(audio-monitor)` to UI/frontend-plugins/CMakeLists.txt
- Rebuild OBS Studio

# Donations
- https://github.com/sponsors/exeldro
- https://www.paypal.me/exeldro
- https://www.patreon.com/exeldro
