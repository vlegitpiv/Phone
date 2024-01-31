# Phone
Hardening guide to lock down your phone

This procedure applies to MIUI Global 14.0.8.0(TMOEUXM) with android 13
This ROM is found on xiaomi redmi note 12 pro 5G mobile phones.

It is recommended to run the scripts immediately after you get a new phone,
because the scripts might uninstall software that will break existing apps.
The script of Step2 will not allow remote device management on your mobile device.
You should install an alternative file manager app before running the scripts, so
then you can install more apps later on locally.

Step1 = remove bloatware from phone     / uninstall almost all pre-installed apps
Step2 = remove all spyware from phone   / improve your privacy and the battery runtime

Use adb to run the scripts, install it on a computer that runs your preffered O.S.
Connect your phone with USB to your computer and enable adb in developer settings.

You can install alternative apps for example from f-driod after you have run the scripts
which then replace the bloatware apps. In addition, you can consider to use the netguard app,
which will allow you to control outgoing communication of all apps to protect your privacy.

To update the phone firmware:
1. copy all personal data off the phone to your PC
2. reset the phone to factory defaults
3. update the firmware on the phone from the internet
4. re-run the scripts again on your phone
5. re-install the apps you need
6. copy all personal data back to the phone.
This approach will not leak so much personal data out.

Have fun
