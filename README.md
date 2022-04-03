# GMMKPro-QMK-ISO-TR
My custom QMK keymap configuration for GMMK Pro ISO Turkish (TR) layout, especially for MacOS

## How to Upload Keymap File and See the Layout?
- Dowload the file as named "my-keymap.json"
- Go to [QMK Configuratior][qmk-config]
- Click the "Upload a QMK JSON File"
- Select the downloaded before "my-keymap.json" file
- You are gonna see the layout.

## About the Layout
- First of all this layout is for MacOS and Turkish ISO keyboard layout format.
- The Any key is a combination key for single command which is right of the F12 key. LCTL(LALT(LSFT(KC_C))) meaning is CTRL+Option+Shift+C combination. This combination is assigned for launching Calculator application on my MacOS. You can change it as yours favors.
- The double quot key is for Turkish ISO layout which is left of the 1 key. The key is replaced with <>| key.
- Home key is set for my using experience favor on the Page Up key.
- The <>| key is for Turkish ISO layout which is left of the Z key. The key is replaced with double quot key key.
- The left OS and left alt keys are switched with each other for using experience on MacOS.
- Right of the space key is arranged as follows: right OS key, right alt key and FN key. You will see the FN key as MO [1].

## Compile Keymap and Download Firmware
- Click the Compile button.
- After the baking image disappear then download firmware button is clickable. Then click it and download firmware. The downloaded firmware name will be "gmmk_pro_iso_my-keymap.bin".

## How to Flash Firmware to GMMK Pro?
- Go to [QMK Toolbox][qmk-toolbox]
- From the latest section download "QMK.Toolbox.app.zip" file.
- Unzip it and run. If MacOS security check fail then give permission to it from preferences.
- Select the downloaded before "gmmk_pro_iso_my-keymap.bin" file
- Unplug cable of GMMK Pro and while holding Space+B key then plug again. This will connect your keyboard on bootloader mode. After that you will see the yellow colored device connected command.
- Click the Flash button. After it complete then it is ready for use your GMMK Pro.
- If you want to return original then press the FN+Backspace.

## Additional Notes
- I don't have ANSI layout GMMK Pro so I don't have any idea about QMK ANSI layout configuration.
- For all documentations about go to [QMK Firmware][qmk-docs]

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [qmk-config]: <https://config.qmk.fm/>
   [qmk-toolbox]: <https://github.com/qmk/qmk_toolbox/releases>
   [qmk-docs]: <https://docs.qmk.fm/#/>
   [git-repo-url]: <https://github.com/tunahanaltintop/GMMKPro-QMK-ISO-TR>
