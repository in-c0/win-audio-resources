# win-audio-resources

We're following https://learn.microsoft.com/en-us/samples/microsoft/windows-driver-samples/sysvad-virtual-audio-device-driver-sample/

Download driver samples from the [repo](https://github.com/microsoft/Windows-driver-samples/tree/main/audio/sysvad)
Install the driver samples:
Download [WDK](https://learn.microsoft.com/en-us/windows-hardware/drivers/download-the-wdk) and execute devcon.exe on the driver package ( Driver package path: D:\Projects\WASAPI\Windows-driver-samples\audio\sysvad\x64\Release\package )
& "C:\Program Files (x86)\Windows Kits\10\Tools\10.0.26100.0\x64\devcon.exe" install ComponentizedAudioSample.inf Root\Sysvad_ComponentizedAudioSample 

You may need to rightclick driver certificate (package.cer) and install it prior to the driver installation


Bug notes:
https://techcommunity.microsoft.com/discussions/windows11/volume-mixer-doesnt-go-below-1-even-if-youre-on-0-it-still-has-noise/4034333

Check Win+R -> sndvol as it is different from the Win11 volume mixer UI



list to come back to

- https://learn.microsoft.com/en-us/samples/microsoft/windows-driver-samples/sysvad-virtual-audio-device-driver-sample/
- https://learn.microsoft.com/en-us/windows-hardware/drivers/audio/wavert-miniport-driver
- https://learn.microsoft.com/en-us/windows-hardware/drivers/audio/hardware-offloaded-audio-processing
- https://learn.microsoft.com/en-us/windows-hardware/drivers/audio/audio-processing-object-architecture
- https://learn.microsoft.com/en-au/windows/win32/coreaudio/wasapi?redirectedfrom=MSDN
- https://learn.microsoft.com/en-au/windows/win32/coreaudio/stream-management
- https://learn.microsoft.com/en-au/windows/win32/coreaudio/audio-endpoint-devices


Kernel mode driver debugging
https://learn.microsoft.com/en-us/windows-hardware/drivers/debugger/debug-universal-drivers--kernel-mode-


nice layout https://basicpitch.spotify.com/about
