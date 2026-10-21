VisualSampler v2.0.0 FREE
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
5. Press a pad on the SP-404MKII to leave the startup screen and display or switch images.

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
A valid Banks folder alongside the app takes priority. If it is unavailable, version 2 checks its saved location.
The chosen location is saved separately from version 1 and used on subsequent launches.
If the saved location is no longer available, the folder picker appears again.
After cancelling or choosing the wrong folder, press R in the app to try again.
Banks/BankA and Banks/BankB must each contain images numbered 01–16.

Example of the correct folder structure:

VisualSampler_v2.0.0_macOS_AppleSilicon/
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

VisualSampler v2.0.0 FREE supports only BANK A and BANK B.
You can assign 16 images to each BANK, for a total of up to 32 images.

BANK A: 16 included images (3 HEIC + 13 JPG)
BANK B: 16 included images (PNG)

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
  .heic  (priority 4)
  .heif  (priority 5)

HEIC/HEIF images are loaded with their shooting orientation applied. Original files are not modified.
Video files and the video portion of Live Photos are not supported.

File extensions are case-insensitive.

File naming rules:
・Start with “01” through “16”, corresponding to PAD 01–16.
・Use the number alone, or “number_any name”.
・Examples: 01.jpg / 01_tokyo.jpg / 16_night.png
・Names without an underscore immediately after the number,
  such as “01tokyo.jpg”, are not recognized.

Priority when multiple files match the same PAD number:
  1. Extension: .jpg → .jpeg → .png → .heic → .heif
  2. With the same extension, the shorter filename excluding the extension
  3. With the same length, alphabetical filename order (case-insensitive)

Example: If 01.jpg / 01_city.jpg / 01_tokyo.png are present,
         01.jpg is loaded.

To avoid confusion, one image file per PAD number is recommended.

【6. Aspect Ratios and Recommended Image Sizes】

The initial aspect ratio is 3:4. Left-click the image to cycle through:
  3:4 → 4:3 → 9:16 → 16:9 → 3:4

Internal rendering dimensions:
  3:4  : 768 × 1024 px
  4:3  : 1024 × 768 px
  9:16 : 576 × 1024 px
  16:9 : 1024 × 576 px

Images retain their original proportions and fill the selected aspect ratio.
Any overflow is cropped around the center.
If the window and the visual output have different proportions, black borders fill the unused area.

When you change the aspect ratio, a green Japanese label such as “アスペクト比 4:3”
appears in the upper-right corner of the image and disappears after about two seconds.
The same controls and label are available in fullscreen mode.

Prepare images in the aspect ratio you plan to use for more predictable framing.
Examples: 768 × 1024 px for 3:4, 1024 × 576 px for 16:9, or integer multiples of these sizes.
These are guidelines, not mandatory dimensions.

Large images and many HEIC/HEIF files can take longer to preload at startup.
If startup or operation is slow, reduce image resolution and try again.

【7. Window and Fullscreen Display】

Version 2 uses a single display window from startup.
You do not need to right-click to open a separate presentation window.

• Drag a window edge or corner to adjust its display size.
• Use the green button in the upper-left corner to enter macOS fullscreen mode.
  Depending on your macOS version, choose “Enter Full Screen” from its menu.
• To leave fullscreen mode, move the pointer to the top of the screen and use the green button.
• Left-click to cycle through the four aspect ratios in either windowed or fullscreen mode.
• Use the red button to quit the app.

Changing the window size preserves the selected visual aspect ratio.
It does not stretch or distort the image to match the entire window.

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

If another image appears instead of HEIC:
• JPG/JPEG/PNG files with the same pad number take priority.
• To use HEIC, move other image formats with that number outside Banks.

If the aspect ratio or framing is unexpected:
• Left-click to select the desired aspect ratio.
• Images that do not match that format are cropped around the center.
• Black borders caused by a different window shape are normal.

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

VisualSampler v2.0.0 FREE
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

【Changes in v2.0.0】

• Added HEIC/HEIF still-image support alongside JPG/JPEG/PNG.
• Automatically applies HEIC/HEIF photo orientation.
• Left-click to switch between 3:4, 4:3, 9:16 and 16:9.
• Added a green, TV-style aspect ratio label in the upper-right corner.
• Unified the display into one window, with macOS fullscreen via the green button.
• Preserves the output aspect ratio when resizing, with black borders in unused areas.
• Stores Banks preferences separately from version 1 and prioritizes Banks alongside the app.
• Updated the startup screen to “Ver. 2.0.0”.
• Updated the included BANK A/B images; BANK A includes three HEIC photos.
• Retains BANK A/B operation, pad control and the four effects from version 1.
• Video support, new effects and Windows support are not included in this release.

The startup screen, window title, README and app information all use version number 2.0.0.

【Verification Status】

During development, HEIC display and orientation, four aspect ratios and effects were checked on the development Mac.
The single-window implementation was tested using a test copy for window count, rendering after startup,
four aspect ratios, effects, and entering and leaving macOS fullscreen mode.

On 2026-10-21, the release candidate was checked for app startup, bundled Java, code-signature validation,
loading all 32 images and detection of the SP-404MKII MIDI ports. Tests using the bundled Java also checked
HEIC loading and orientation, four aspect ratios, effects, a single window and fullscreen round trips.
A hands-on test of the downloaded build is planned before publication.
Other Macs, Windows, prolonged operation and every combination of parameter settings have not been tested.
