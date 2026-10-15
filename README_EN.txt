VisualSampler v1.0.1 FREE
for SP-404MK2
============================================================

Sample Your City. Remix Your Reality.

【1. About VisualSampler】

VisualSampler is a visual sampler for macOS that lets you perform with
still images using the Roland SP-404MKII.

Sample city scenes and everyday photos just as you sample music.
Use the 16 PADs to switch images and enjoy real-time visual expression.

Add your favorite photos and simply tap the PADs.
Turn your everyday life into visual samples.

【2. System Requirements】

・Supported OS: macOS (bundled runtime minimum: 11.0; verification across OS versions is not complete)
・Supported Mac: Mac with Apple Silicon (M series)
・Controller: Roland SP-404MKII
・Connection: USB MIDI
・Built with Processing
・The distributed app includes a Java runtime (normally no separate installation is needed)

Note: This release is exclusively for Macs with Apple Silicon. Intel Macs and Windows are not supported.

【3. App Placement and Startup】

1. Extract the distribution ZIP.
2. Connect the SP-404MKII to your Mac via USB and turn it on.
3. Check the SP-404MKII MIDI settings (see below).
4. Launch VisualSampler.app.
5. Press the SP-404MKII PADs to switch images.

Required MIDI settings on the SP-404MKII:
  SHIFT + PAD 13（UTILITY）→ SYSTEM → MIDI
  ・MIDI Mode：A
  ・PAD Note Out：ON

Note: Both settings are required to operate VisualSampler.
  With MIDI Mode set to B, the PAD MIDI note/channel assignments differ
  from those expected by VisualSampler, preventing correct operation.
  With PAD Note Out set to OFF, PAD operations do not transmit MIDI signals.
Note: VisualSampler does not require a specific setting for
  MIDI EXT Src（TOGGLE / GATE / THROUGH）.

Keeping Banks alongside VisualSampler.app makes the layout easy to understand.
If asked to locate Banks at startup, select the parent “Banks” folder containing BankA and BankB.
The selected location is saved and used on subsequent launches.
If the saved location is no longer available, the folder picker appears again.
After cancelling or choosing the wrong folder, press R in the app to try again.
Banks/BankA and Banks/BankB must each contain images numbered 01–16.

Example of the correct folder structure:

VisualSampler_v1.0.1_macOS_AppleSilicon/
├── VisualSampler.app
├── Banks/
│   ├── BankA/
│   │   ├── 01.jpg
│   │   ├── 02.jpg
│   │   └── ... 16.jpg
│   └── BankB/
│       ├── 01.jpg
│       ├── 02.jpg
│       └── ... 16.jpg
├── README_JP.txt
├── README_EN.txt
├── README_ES.txt
├── README_ZH_CN.txt
└── README_KO.txt

Note: The folder names are “Banks”, “BankA”, and “BankB”.
  Do not rename them to “BANK_A”, “BANK_B”, or other names.
Note: Do not move Banks inside the .app.
【First launch: Privacy & Security】

This release is not signed with Developer ID and has not been notarized by Apple.
macOS may therefore warn that Apple cannot verify its safety on first launch.
Follow these steps only if you trust the source and have confirmed that the file has not been altered.

1. Extract the ZIP and try opening VisualSampler.app once.
2. If Apple warns that it cannot check the app for malware, dismiss the warning.
3. Open System Settings from the Apple menu.
4. Select Privacy & Security and scroll down to Security.
5. Click Open Anyway next to the notice that VisualSampler was blocked.
6. Review any authentication or confirmation request. If you wish to continue, select Open.
7. After the app starts, select the Banks folder if prompted.

Permission is normally saved, allowing subsequent launches by double-clicking.
An updated version may require permission again.
If Open Anyway is missing, check this screen immediately after trying to open the app.
This option may be unavailable on a Mac managed by a school or employer.

For warnings saying the app is damaged, will damage your Mac, or contains detected malware,
do not proceed using these steps alone: check the official source and the downloaded file.
If the app is not responding, quit it once and check again rather than repeatedly launching it.

Apple’s official instructions:
https://support.apple.com/ja-jp/102445

【4. About BANKs】

VisualSampler v1.0.1 FREE supports only BANK A and BANK B.
You can assign 16 images to each BANK, for a total of up to 32 images.

BANK A: 16 photos of everyday scenes in Tokyo (included by default)
BANK B: 16 two-color manga-style images based on the BANK A photos (included by default)

Images placed in BANK C or later BANKs will not load or display in the FREE version.
A future VisualSampler PRO version is planned to support more BANKs.
Note: PRO specifications and release timing are undecided and may change.

【5. Using Your Own Images】

1. Quit VisualSampler.
2. Open Banks/BankA or Banks/BankB.
3. Back up the existing images and replace them with images of your choice.
4. Restart VisualSampler and check the results.

Supported image formats:
  .jpg   (priority 1)
  .jpeg  (priority 2)
  .png   (priority 3)

File extensions are case-insensitive.

File naming rules:
・Start with “01” through “16”, corresponding to PAD 01–16.
・Use the number alone, or “number_any name”.
・Examples: 01.jpg / 01_tokyo.jpg / 16_night.png
・Names without an underscore immediately after the number,
  such as “01tokyo.jpg”, are not recognized.

Priority when multiple files match the same PAD number:
  1. Extension: .jpg → .jpeg → .png
  2. With the same extension, the shorter filename excluding the extension
  3. With the same length, alphabetical filename order (case-insensitive)

Example: If 01.jpg / 01_city.jpg / 01_tokyo.png are present,
         01.jpg is loaded.

To avoid confusion, one image file per PAD number is recommended.

【6. Recommended Image Aspect Ratio and File Size】

The app's reference window size is 768 × 1024 px (width:height = 3:4).
If preparing images to match the screen ratio, use a portrait 3:4 ratio as a guide.

Suggested sizes: approximately 768 × 1024 px or 1536 × 2048 px.
Note: These are guidelines for preparing images, not requirements.
Note: Cropping, margins, and distortion may appear differently depending
  on the image display method. Check the actual display.

Larger image files or higher resolutions may increase the time needed
to load BANK images at startup.
If the transition from the startup screen to the main screen takes a long
time, resize or compress the images to an appropriate size.

【7. Changing Window Size with the Mac Keyboard】

Shift + 1 ：384 × 512 px（50%）
Shift + 2 ：576 × 768 px（75%）
Shift + 3 ：768 × 1024 px（100%）

Note: These shortcuts change the app's window size,
  not the size of the image files themselves.
Note: Behavior may vary depending on keyboard layout and input settings.

【8. Visual Effects】

Included effects:
・GLITCH    : Digital noise and visual disruption
・CRT       : CRT television-style visuals
・PIXELATE  : Coarse pixel-style visuals
・RGB SPLIT : Visuals created by offsetting RGB colors

SP-404MKII controls:
・CTRL 1: Select an effect
・CTRL 2 / CTRL 3: Adjust the selected effect
・Press EXT SOURCE twice: Reset the effects

Note: The appearance and available adjustments depend on the selected effect.

【9. Troubleshooting】

If images do not appear:
・Select the parent Banks folder, not BankA or BankB alone.
・Press R on the guidance screen to choose again.
・Check that the saved Banks location exists and is readable.
・Check that the names “Banks/BankA” and “Banks/BankB” are correct.
・Check that images follow the 01–16 naming rules and use supported formats.
・Check that images have not been placed in BANK C or later BANKs.
・Check that you restarted the app after replacing images.

If startup takes a long time:
・Reduce the image resolution or file size and try again.

If you cannot operate the app with the SP-404MKII:
・Check the USB connection and the controller's power.
・Check “MIDI Mode：A” under SYSTEM → MIDI.
・Check “PAD Note Out：ON” on the same screen.
・Restart the app and check again.

【10. Usage Notes and Trademarks】

VisualSampler is independently created software.
It may not work correctly in some environments.
To the extent permitted by law, the creator accepts no liability for
damages arising from the use of this software.

When replacing images, respect copyright, portrait rights, and other rights.
Also check the rights to your materials when livestreaming or publishing videos.

VisualSampler is an independent creation with no affiliation with Roland
Corporation. It is not developed, approved, or sponsored by Roland Corporation.
Roland and SP-404MKII are trademarks or registered trademarks of Roland Corporation.

【11. Credits / Creator Information】

VisualSampler v1.0.1 FREE
Created by：achamania
Concept / Design / Development：achamania

© 2026 achamania. All rights reserved.

YouTube：achamania
https://www.youtube.com/@achamania

X（Twitter）：@achamania
https://x.com/achamania

Visit the social media channels above for demonstrations and creative projects.

【12. Message from achamania】

Show me your creations!

If you create and publish a video using VisualSampler,
please tell me in the comments on my YouTube channel!

Live performances, music videos, visual works using city scenes—
every way of using it is welcome.

I can't wait to see what you create with VisualSampler!

Show me what you've sampled!

YouTube：https://www.youtube.com/@achamania

Sample Your City. Remix Your Reality.

【v1.0.1 changes and verification】
・Fixed external Banks lookup when macOS runs a downloaded app in isolation (App Translocation).
・Added Banks folder selection, saved locations, and reselection.
・Updated the app icon.
・Java is bundled; installing Processing or an additional Java runtime is normally unnecessary.

On October 15, 2026, on the Apple Silicon Mac used for development, we verified downloading
from GitHub, macOS launch approval, Banks loading and recovery, and physical MIDI/BANK/FX/CTRL operation.
All 32 images and PAD processing were also checked with automated tests.
Other Macs, extended operation, and every combination of parameters have not been tested.
The existing startup screen displays Ver. 1.00, but this package is v1.0.1.
