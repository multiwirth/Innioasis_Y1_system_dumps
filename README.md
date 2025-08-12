# Innioasis_Y1_system_dumps
## This system image is supposed to be flashed alongside ``https://github.com/team-slide/y1-stock-rom-type-b/releases/tag/1.7.6`` firmware
### Includes chainfire supersu as before, but also viper4android driver preconfigured and a working busybox binary as dependency for v4a.
#### Based on old firmware without wifi! You can't check out cat images @web.
##### Highly experimental, i don't have hardware to test the changes to the scrollwheel key behaviour (keylayouts)!!

> Viper4Android should be installed as user app seperately ``adb install com.audlabs.viperfx.apk`` in order to be accessible through rockbox.
> After installation, v4a should work just fine.
> Settings can only be adjusted using Y1 helper or use https://play.google.com/store/apps/details?id=io.appground.blek
> I recommend creating a v4a profile on another device, then copy the ``Viper4Android`` folder from the other device onto the Y1, and load the profiles using the menu, which is >surprisingly accessible with the scrollwheel.

>Including ADW Launcher (system)

>Optionally, grab ''userdata.img'' with rockbox, viper4android, ES File Explorer, App Quarantine preloaded.
>The user can choose between ADW Launcher and Rockbox on first startup.
>After setting rockbox as default, ADW Launcher can only be accessed by launching through the android-system-settings.
