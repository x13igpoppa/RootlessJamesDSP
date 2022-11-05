# Using root

If you want to use this app with the JamesDSP magisk module on a rooted device, follow these instructions:

**Important: I don't actively test root builds; therefore I won't provide stable APK files. They may be more unstable than the regular rootless version.**

1. Install the JamesDSP magisk module, if not already done

2. Uninstall the original JamesDSP app

3. Select the latest commit and download the prebuilt root APK artifact: https://github.com/ThePBone/RootlessJamesDSP/actions/workflows/build.yml

4. Install the APK, and it _should_ work

   

This app behaves differently than the original app:

* Different preset file format (.tar); you can't import old presets
* No separate configurations for speaker/bluetooth/usb/wired; there's one active category for all