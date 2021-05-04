![Community A-4E-C for DCS World](https://user-images.githubusercontent.com/46121009/57830942-41b3da00-77e6-11e9-8e8c-1b7274927bb0.jpg)

The Community A-4E-C represents more than three years of work on behalf of the development team. We’re proud to present the most comprehensive DCS World module to date, boasting such capabilities as air-to-ground radar and carrier operations. The A-4 was a cold war workhorse, providing a capable, reliable light attack aircraft to dozens of nations around the world. From the Sinai Desert to the Jungles of Vietnam, the A-4 was a common sight above cold war battlefields.

After severel years of development, we are pleased to announce version 2.0 of the module, with a realistic flight model, the addition of a CP-741/a CCRP bombing computer, increased DCS functionality, increased carrier compatibility, and myriad new sounds and keybinds to increase your ease of use and immersion when flying this now-venerable module.

We thank the DCS World community for their support over the years, and dedicate the module to our friend, mentor and lead coder, Eric “Gospadin” Mudama. His passion and brilliance left a mark on us all, and this labor of love which would not have been possible without him.

**Please DO NOT redistribute this mod without permission!**

## Contributing Developers

Gospadin, Heclak, Joshua Nelson, plusnine, Farlander, gyrovague, kryb / Archimaede, Merker, Jones, Nero

## Special Thanks

SkateZilla, uboats, Dr. Manius, LevelPulse, Cubeboy, Sidekick65, Talo, Gvad, HellesBelles, SPINEG, Sport, rudel-chw, Luciano, Malamem, ataribaby, The Original HoggitDev Team, [Eric Haugen](http://erichaugen.bandcamp.com)

## Features

- Realistic external flight model and engine simulation
- Clickable cockpit
- Air-to-ground radar
- Shrike anti-radiation missile
- CP-741/a Bombing computer (CCRP)
- Carrier landing and takeoff
- Air-to-air refueling
- New weapons:
  - AN- series WWII munitions: M66, M81, M88
  - MK4 HIPEG 20 mm gunpod
  - Mk-77 napalm canister
  - SUU-7 bomblet dispenser
- Custom sounds

### Version 2.0 Changelog: Featured Items

- Features: External Flight Model (EFM) with flight dynamics, suspension, slat simulation, cockpit shake, wing vapour and more.
- Features: Realistic engine simulation (jnels, please add detail here!)
- Features: Added radio functions (jnels, please add detail here! - thanks, Harald?)
- Features: Added ILS for ground stations
- Features: Added SuperCarrier compatibility
- Features: Added CP-741/a bombing computer (set CMPTR on weapon selector and use slick bombs)
- Features: Added air-to-air refueling capabilities
- Features: Added nosewheel steering and differential braking (be sure to reset your user inputs)
- Features: Added SUU-25 Parachute illumination pod for night ops
- Systems: AFCS Added stability augmentation (be sure to enable this yaw-dampening system on the AFCS panel before takeoff!)
- Systems: Added sidewinders to loadout options on outer pylons
- Systems: Added SUU-25 parachute illumination pod to loadout options
- Systems: Added empty fuel tanks to loadout options
- Systems: Added fuel flow system
- Systems: Added oxygen system (pilots must now beware of hypooxia!)
- Misions: Added instant action missions (thanks Sidekick65, Cubeboy)
- Textures: Exterior texture improvements, added normal map (thanks HellesBelles)
- Textures: Cockpit improvements (thanks Sport, for the new gunsight mapping)
- Liveries: Added Argentina and Chile as available countries for the A-4E-C
- Liveries: Added Argentine Brigada (thanks GVad, for these paints and much more)
- Liveries: Reformatted livery description.lua templates (livery creators, see our updated paintkit)
- Liveries: Inaccuracies corrected (within the available modex systems, with great apologies to the non-USN/USMC operators)
- Quality of Life: Added new keybinds (thanks to the userbase for documenting many of these)
- Quality of Life: Added in-cockpit sounds and improved user feedback
- Quality of Life: Revised special menu options (like screen shake)
- Quality of Life: Fixed FFB stick support
- Quality of Life: Slats locking option for aerobatic performance teams
- Quality of Life: Smokewinder pod easier to operate (weapon select independent)
- Quality of Life: Lots, and lots, and we mean LOTS of bug fixes

[See full changelog](https://github.com/heclak/community-a4e-c/blob/master/CHANGELOG.md)

### Known Bugs

- Fuel system cuts off if auto pause is left on for too long
- Pilot blacks out when hooking into SuperCarrier (throttle up hard to cat-in!)
- Wheel chocks do not stop the aircraft 
- APC underresponsive
- AN/ASN-41 navigation BDHI needle animations swapped in test mode
- IN RANGE lamp flickers when TEST is pressed
- TEST press can cause ECM panel lights to stick on
- Throttle position occasionally stuck in OFF position after rearm

[see full issue list](https://github.com/heclak/community-a4e-c/issues/) 

#### Dispensing high volumes of bomblets (40+) from SUU-7/CBU-1/CBU-2 causes serious performance dip and/or crashes to desktop

- Drop bomblets in lower release settings via the kneeboard (RShift+K by default), mission editor, or the Automatic Weapons Release System (AWRS).

## Installation

Failure to perform these steps will result in DCS World not recognizing the module, inability to use the module, input errors when using the module, or client integrity check failures on multiplayer servers that require them. Never install the A-4E-C files directly into your DCS World installation files!

### STEP 1: Upgrading from an older release

If you are upgrading from an older version of the A-4E-C, perform these following actions. You must completely delete the currently installed A-4E-C files before installing the new version, as some important files have been removed for this. 

Additionally your input bindings must be reset and rebound in order to accommodate this release’s enhanced control scheme. If this is a new installation, you can skip this step and move on to Step 2.

- Delete the contents of your old A-4E-C installation folder: `C:\Users\username\Saved Games\DCS\Mods\aircraft\A-4E-C`
- Delete your A-4E-C input settings by opening the following folder: `C:\Users\username\Saved Games\DCS\Config\Input\A-4E-C`
- Delete the joystick, keyboard, mouse and trackir folders.

### STEP 2: Installing the module files.

- Download the latest official A-4E-C release package. Do not download directly from the Github repository.
- Place the included `Mods\aircraft\A-4E-C` folder in into your `C:\Users\username\Saved Games\DCS` folder.
- If you have installed other DCS World mods, you might already have the `Mods` and `aircraft` folders indicated in the file path. If this is the case, merge the new A-4E-C folder into the existing folders.

Your correctly installed files should look something like the following image, substituting your Windows account name where the image displays Partario. If you're using the release branch of DCS World, the folder is `DCS` instead of `DCS.openbeta`.

![Image of A-4E-C installation](https://user-images.githubusercontent.com/46121009/84217257-3b358600-aafe-11ea-9203-20d787b09662.png)

### STEP 3: Launch DCS World and verify installation

When you are confident your files are correctly installed, launch DCS World. If your installation was successful, the A-4E-C theme icon appears as a option in the main menu:

![Image of DCS World Menu with A-4E installed](https://cdn.discordapp.com/attachments/518815071858589697/720094260699070464/unknown.png)

## Installation Troubleshooting

- Never, ever install the A-4E-C files directly into your DCS World installation files! This will cause your DCS World to not locate the module, create conflicts with other modules, and other problems.

- If you have multiple DCS-related folders in your `C:\Users\username\Saved Games`, for example, `DCS`, or `DCS.openbeta`. If you are unsure which folder your DCS World installation is using, locate the `dcs_variant.txt` file in the game files. If this file is present, its contents determines the folder structure your DCS World installation is using.

- If you are recieving an authorization error, you have installed the module incorrectly. Double check the installation instructions above, ensure you have have installed the module to the correct folder, and do not have any improperly installed files remaining in your DCS world game files. Any conflicts will result in the persistence of this this error.

- If you find you can't take control of the aircraft, ensure you have installed Microsoft's Visual Studio 2015, 2017 and 2019 Redistributable libraries. Windows users running DCS world are typically running x64, so you will want to download and install vc_redist.x64.exe (~15 MB) from the following page, install the library, and then restart your computer: (https://support.microsoft.com/en-us/topic/the-latest-supported-visual-c-downloads-2647da03-1eea-4433-9aff-95f26a218cc0)

- If you cannot find the A-4E-C as a unit option in the Mission Editor, Ensure the historical mode filter is disabled in the mission editor by toggling the clock icon at the bottom of the screen, as shown in the following screenshot:

![Image of the Mission Editor pointing out the location of the Historical Filter](https://cdn.discordapp.com/attachments/518814186739073024/759230033960763422/unknown.png)

## Frequently Asked Questions and Troubleshooting

**Q: Is it really free?**

- Yes, it’s really free!

**Q: How large is the module?**

- The download file is ~700 MB. Installation size is ~800 MB.

**Q: Can I donate to the A-4E-C project?**

- We cannot accept donations, but we appreciate your words of support! There are so many good causes out there. Consider donating to one of those instead!

**Q: Can I get involved with the A-4E-C project?**

- Yes! Join our Discord server and introduce yourself! We can always use a hand from game artists, programmers or reliable testers as we continue to move the project forward. If you think you have something to contribute, don’t hesitate!

**Q: Is there a user manual or tutorials available?**

- [Heclak's Community A-4E Guide](https://docs.google.com/presentation/d/1cUH7jpAoGHm-IzUDnv_NDhiZlvX55Q9WvpgR1d9ksYY/edit?usp=sharing) is a great resource, and [Sidekick65's YouTube Channel](https://www.youtube.com/channel/UC4kJt_8Jw9ByL10ar6b8rQg) features many good tutorials on systems and weaponry.

**Q: Is there a paint kit I can use to create my own A-4E-C liveries?**

- Yes! This [A-4E-C Paintkit](https://drive.google.com/open?id=19w_bD8xHJiZpAi1JbA2xyPDJpl9dje-4) includes the aircraft’s top, bottom and fuel tanks. See the included liveries for lua examples. If you created liveries for older versions of the A-4E-C, you might want to update them to accommodate new changes in the external model in the newer version.

**Q: Can I use radio functions?**

- Limited radio functions are available. Additional functions might require time, and may never be able ot be implemented.

**Q: Why can't I use the TACAN and BDHI or ILS my favorite carrier?**

- In order to TACAN to a carrier, the mission file must be set up correctly, allowing the A-4E-C to interpret the carrier's position from the mission file's settings. 
- In the mission file, the following conditions should be met:
  - The carrier must be the Stennis
  - The Stennis must have one (and only one) waypoint
  - The start and end speeds for eacg waypoint must be equal
  - The TACAN channel is set to the X frequency
  - Drift, damage, or other server strain can still throw the calculation off course, but in a properly set up mission, the TACAN signal should remain in visual range of the carrier. 
  - ILS does not function for carrier units.

**Q: Can I fly the A-4E-C as a tanker?**

- The A-4E-C serving as a player-piloted tanker would also require access to the SDK.

**Q: What about the AGM-12 Bullpup or AGM-62 Walleye?**

- Implementing guided weapons would also require access to the SDK. Additionally, the specific airframe/cockpit that we have modelled is not equipped to accommodate the AGM-62 Walleye. A-4Es that were able to carry the AGM-62 Walleye had the ground radar display replaced with a TV monitor for use with the AGM-62 Walleye.

**Q: Are there any plans to make the module official, obtain the Eagle Dynamics SDK, or make the module a part of the default DCS install package?**

- No, there are no plans nor keen interest to pursue this. The project will continue as a free and open-source resource you can download and install to enjoy.

**Q: Why doesn't the A-4E-C work with my favorite mission or multiplayer scripting system?**

- Some scripts or other utilities need to be informed of the A-4E-C's existence in order to accomodate it. If you have a favorite popular mod, script that should accomodate it, be sure to let the author know!

**Q: What's the song in the menu?**
- Crow, by [Eric Haugen](https://erichaugen.bandcamp.com/releases)
