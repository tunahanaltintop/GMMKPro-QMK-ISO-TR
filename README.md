# GMMKPro-QMK-ISO-TR
My custom QMK keymap configuration for GMMK Pro ISO Turkish (TR) layout, especially for MacOS

## How to Upload Keymap File and See the Layout?
- Dowload the file as named "my-keymap.json"
- Go to [QMK Configuratior][qmk-config]
- Click the "Upload a QMK JSON File"
- Select the downloaded before "my-keymap.json" file
- You are gonna see the layout. Additionally you are gonna see gmmk/pro/rev1/iso value in keyboard combobox. The value is rev1 because my version is rev1 and it's very important. If you choose rev2 for rev1 version you are probably stuck.

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
- After the baking image disappear then download firmware button is clickable. Then click it and download firmware. The downloaded firmware name will be "gmmk_pro_rev1_iso_my-keymap.bin".

## How to Flash Firmware to GMMK Pro?
- Go to [QMK Toolbox][qmk-toolbox]
- From the latest section download "QMK.Toolbox.app.zip" file.
- Unzip it and run. If MacOS security check fail then give permission to it from preferences.
- Select the downloaded before "gmmk_pro_iso_my-keymap.bin" file
- Unplug cable of GMMK Pro and while holding Space+B (if you flashed it to QMK before then the shortcut is F+Backspace) key then plug again. This will connect your keyboard on bootloader mode. After that you will see the yellow colored device connected command.
- Click the Flash button. After it complete then it is ready for use your GMMK Pro.
- If you want to return original then press the FN+Backspace.

## Additional Notes
- I don't have ANSI layout GMMK Pro so I don't have any idea about QMK ANSI layout configuration.
- I don't have any trouble with rotary knob and RGB lighting. Everything works as well.
- You can view ANSI layout video on Youtube account which belongs to @yozak. [How to Install QMK on your GMMK Pro][youtube-yozak]
- For all documentations about go to [QMK Firmware][qmk-docs]
- GMMK Pro default stabilizers are GOAT (Greatest of All Time). The stabs are factory lubed much and have some rattle problems. So for GMMK Pro stabilizers guide and aluminum plate filing configuration then go to @ZinanPoh [GMMK Pro Stabilizers Guide and Aluminum Plate Filing (GOAT, C3, Zeal, GMK, Durock V2)
][youtube-ZinanPoh] video which is great for ANSI layout. Good news about my ISO layout GMMK Pro there is no need extra modification for Durock V2. It just fit exactly.
- For GMMK Pro Full Review then I advice to watch videos on Youtube accounts which belongs to @Romsicle [GMMK Pro Full Review - Everything You Need to Know in 13 Minutes][youtube-Romsicle] and @IOSam [GMMK Pro: The ultimate guide (in-depth review + modding tutorial)][youtube-IOSam].
- I preferred [Akko V3 Pro Cream Yellow][akko-v3-pro-cream-yellow] switches on my GMMK Pro which are durable and in appropriate price. This switches are in linear form. I lubed them. You must buy south facing (SMD-LED) switches for GMMK Pro. You can watch for lubing switches video on Youtube account which belongs to @NiftyKeyboards [RUMI61 Lubed Gateron Brown, Typing Sound | Chill Music][youtube-NiftyKeyboards]
- I preferred [Ranked Premium Blanks PBT Keycaps][ranked-blank-pbt-9009] on my GMMK Pro which are in appropriate price and have thock sound. This keycaps have ANSI+ISO layaout support and which are 139 keys and cherry profile. It has also 9009 retro color which is super cool :)
- Additionally, you can download the MacOS ISO Turkish (TR) layout legend design (which is with my IntellijIdea keymap configuration icons) for your cherry profile keycaps from the "MacOS_ISO_TR.pdf" file. You can print this design in A4 format. You can check out [@YOHON!'s][youtube-yohon] video for water slide decal.

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [qmk-config]: <https://config.qmk.fm/>
   [qmk-toolbox]: <https://github.com/qmk/qmk_toolbox/releases>
   [qmk-docs]: <https://docs.qmk.fm/#/>
   [youtube-yozak]: <https://www.youtube.com/watch?v=MxQeQoUHvEY>
   [youtube-ZinanPoh]: <https://www.youtube.com/watch?v=qkyl5c4EdXg>
   [youtube-Romsicle]: <https://www.youtube.com/watch?v=qiXV0DODAZ0>
   [youtube-IOSam]: <https://www.youtube.com/watch?v=J_axv-TkjkE>
   [youtube-NiftyKeyboards]: <https://www.youtube.com/watch?v=wWjsXOUdQpE>
   [youtube-yohon]: <https://www.youtube.com/watch?v=bnU0FQforaw>
   [akko-v3-pro-cream-yellow]: <https://en.akkogear.com/product/akko-v3-cream-yellow-pro-switch-45pcs>
   [ranked-blank-pbt-9009]: <https://ranked.gg/products/premium-blanks-pbt-keycaps?variant=42689385496797>

   
