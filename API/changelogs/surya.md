# 26-Jan-2023
- Added Refresh rate per-app
- Added Mi sound Enhancer
- Added Clear Speaker
- Added gcam to aux Allowlist

# 22-Jan-2023
- Rebased on kenny Trees
- Inherit several Android Go configurations
- Don't limit inodes on /system_ext
- Update FPs to latest available
- Update blobs from V13.0.4.0.SJGEUXM
- Switch and configure Aperture
- Address MiuiCamera sepolicy denials
- Optimize dex flags

# 16-Nov-2022
- Cleanup unused overlays
- Rebase kernel on Quicksilver
- Add llvm support
- Included qcom FM
- Added 140mhz GPU frequency
- Enable UXE in perfconfigstore 
- Update media configs from V13.0.4.0.SJGIDXM
- Update stock blobs from V13.0.3.0.SJGEUXM

# 31-Oct-2022
- Set fingerprint separately for surya and karna
- Bring back min/max Refresh Rate
- Fix green tint on camera

# 25-Oct-2022
- Bump dex2oat threads
- Improve SystemUI dimensions
- Fixed status bar glitch for apps
- Update power profiles
- Boost GPU to max on expensive rendering
- Kang runtime cpusets from coral
- Switch to FBEv2
- Set stock fingerprint
- Switch to Smooth Display toggle
- Import xiaomi UFS changes
- UFS: Increase power control and query timeout
- Wake CPUs explicitly when resuming UFS chip
- Remove 10 ms CPU idle latency unvote timeout
- work-simple: Rewrite for clarity and performance

# 16-Aug-2022
- Use wpa_supplicant.conf from V13.0.1.0.SJGMIXM
- Pull vendor.qti.hardware.camera.device@3.5 from stock
- Add XiaoMi bluetooth boost
- Import powerhint from V13.0.1.0.SJGMIXM
- Import Missing FM blobs
- Build Qualcomm common audio overlay
- Fixed Recovery encryption problem (needs Format Data)
- Do not allow restricted tasks to run on big cores
- Use max frequency for main 2 second app launch boost
- Added back Refresh rate settings
- Added back Mi sound enhancer
- Added Vibration settings
- Added Clear speaker
- Added Refresh rate per app

# 14-Aug-2022
- Fixed Bluetooth crash on phone calls
- Fixed FM radio crash when inserting Headphone jack
- Add OpenGL ES and update Vulkan dEQP feature flags
- Add offline charging LED indicator
- Enable usage of dex2oat64
- Update Blobs From MIUI 13.0.1.0 SJGMIXM
- Tuned speaker volumes
- Adjust statusbar paddings
- Removed prebuilt firmware
- Other Fixes & Improvements

# 12-Aug-2022
- Adjust Display calibration data 
- Fixed FP indicator location 
- Set Arch variant armv8-2a-dotprod 
- Added GcamGO
- Other optimization & fixes
