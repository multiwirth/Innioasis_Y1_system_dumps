# Innioasis_Y1_system_dumps
## This system image is supposed to be flashed alongside ``https://github.com/team-slide/y1-ata-rom/releases/tag/20250801`` firmware
### Includes chainfire supersu as before, but also viper4android driver preconfigured and a working busybox binary as dependency for v4a.
#### Based on wifi enabled firmware! You can now check out cat images @web.

> Viper4Android should be installed as user app seperately ``adb install com.audlabs.viperfx.apk`` in order to be accessible through rockbox.
> After installation, v4a should work just fine.
> Settings can only be adjusted using Y1 helper or use https://play.google.com/store/apps/details?id=io.appground.blek
> I recommend creating a v4a profile on another device, then copy the ``Viper4Android`` folder from the other device onto the Y1, and load the profiles using the menu, which is >surprisingly accessible with the scrollwheel.

>Including ADW Launcher (system)

>Optionally, grab ''userdata.img'' with rockbox, viper4android, ES File Explorer, App Quarantine preloaded.
>The user can choose between ADW Launcher and Rockbox on first startup.
>After setting rockbox as default, ADW Launcher can only be accessed by launching through the android-system-settings.
