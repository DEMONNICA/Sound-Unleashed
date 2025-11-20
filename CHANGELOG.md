> `Changelog:`
> - All significant changes to this project will be documented here.
---

> [5.0.0] `FINAL`
> 
> - `verify.sh`: Upgraded to multi-algorithm hash fallback (SHA512→384→256→224→1)
> - `verify.sh`: Added TMPDIR support + trap-based automatic cleanup
> - `verify.sh`: Precise checksum mismatch reporting with expected/got values
> - `customize.sh`: Complete rewrite with advanced root detection for all Magisk variants (Stable/Canary/Kitsune/Alpha)
> - `customize.sh`: Full APatch support + dynamic KernelPatch version fetching from GitHub
> - `customize.sh`: Formatted English timestamps + enhanced chipset auto-detection (Snapdragon/MediaTek/Exynos)
> - Safer file extraction with repeated existence verification + mandatory `module.prop` integrity check
> - Refined permission handling + expanded random Black Clover devil-themed messages (15 variants)
> - `post-fs-data.sh`: Forced `ro.audio.high_res_enabled` + USB DAC 96kHz & 16ms buffer
> - `post-fs-data.sh`: Stereo speaker enforcement + speaker calibration + Fluence & SSR tunnel activation
> - `post-fs-data.sh`: Ringtone/alarm volume steps increased to 20 + vendor Hi-Fi mode enabled
> - `post-fs-data.sh`: Multiple new `ro.vendor.audio.*` flags unlocked for maximum Qualcomm features
> - `service.sh`: Full Dirac Audio (music + speaker) + Dolby Atmos DS2 + TFA calibration + SFX HD Music
> - `service.sh`: All enhancements now persisted at `persist.vendor` level for full reboot survival
> - Automatic `[FINAL]` tag injection + random emoji author branding in `module.prop`
> - Preserved `audioserver` + `mediaserver` restart for instant effect + cleaner post-install messages
---

> [4.0.0]
>
> - Headset auto volume set to maximum for fuller experience.  
> - Speaker auto volume set to maximum for louder, clearer sound.  
> - Eliminated automatic volume drop issue.  
> - Increased heap buffer for more reliable audio processing.  
> - Increased audio buffer size for stable playback.  
> - Disabled surround sound recording (rarely used).  
> - Forced software AAC encoder for improved quality.  
> - Enabled Qualcomm Fluence noise cancellation.  
> - Enabled Dolby DS2 / Dolby Atmos system-wide.  
> - Restored system audio effects compatibility (no longer bypassing other effects, ensures Dolby stability).  
> - Disabled Reactive Audio Scene for consistent sound, suitable for Dolby & manual EQ use.  
> - Applied default music profile with EQ tuned for deeper, cleaner bass without distortion.  
> - Disabled speaker calibration for raw, more powerful output.  
> - Improved `verify.sh` hash and applied minor updates.  
> - Updated `customize.sh` for better installation flow.  
> - Dropped Android 9 support for improved stability.  
> - Updated installation message with more professional wording.  
> - Added `post-fs-data.sh` for more optimal results.
> - Removed `system.prop` in favor of runtime `resetprop`.  
> - Updated `module.prop` and `README.md` descriptions.  
---

> [3.0.0]
>
> - Magisk structure update to be more competitive.
> - Added `uninstall.sh`.
> - Add `verify.sh` to automate the `integrity` check.
> - Add module banner for KernelSU Next.
> - Fixed the code in service.sh and updated it to be more optimal.
> - Added Enable gapless playback.
> - Offload if the duration is sufficient.
> - Enable PCM 24-bit offload.
> - Allow offload for videos.
> - Multi-AAC support & AAC 5.1 output active.
> - Offload individual tracks.
> - Make sure offload is not turned off.
> - Add media volume steps & Add general volume steps.
> - Bypassing system DSP effects.
> - Increase phone volume steps.
> - Disable the default silent audio mode.
> - Enable Ultra Hi-Quality Audio `samsung only`.
> - Let the hardware DSP take care of the decoding.
> - More stream offload & for 3D/spatial content.
> - Better USB DAC support.
---

> [2.0.0]
>
> - Updated `customize` and `functions`.
> - Write `system.prop` automatically.
> - Added properties for high-resolution audio with a sample rate of `96000` Hz and a bit depth of `24-bit`.
> - Optimize the audio buffer by setting the buffer size and buffer depth.
> - Ensure audio offloading is enabled.
> - Enable HiFi mode `if supported by device`.
> - Optimize audio latency.
---

> [1.0.0]
>
> - Initial release.
---