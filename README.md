# Super Robot Wars UX — English & Spanish Fan Translation

An unofficial, free English and Latin American Spanish fan translation of **Super Robot Wars UX** for the **Nintendo 3DS**, presented by **Gyasuke & Wakabayashy Workshop**.

The translation is distributed through an **offline HTML patcher**. The game itself is not included: you must provide your own clean, decrypted Japanese game dump.

**Public base-game release** — 0.8.1  
**Experimental build with optional DLC patching** — B057G26  
**README updated:** November 13, 2026  
**Languages:** English and Latin American Spanish; **English interface in both versions**

## Changes in B057G26

- Fei-Yen HD now uses **Fei** as its short name. Both of Hallelujah’s combat name labels are translated.
- Skill labels and related descriptions use **Cont. Action** and **Concentration**. This build also includes the G25 change from **Hot Blood** to **Valor**.
- Translated more route names in the intermission notice, including **Byston Well**, plus Shoko’s bonus heading and the DLC purchase and redemption prompts.
- Translated labels and help text in the pilot and unit name editors. Updated the name editor to split **Agnes Berge** into its two fields and retain **Arnie** as the nickname.

## What's included

- Translated story and battle dialogue in English and Latin American Spanish, with ongoing revisions to character voice, terminology, names, and line formatting.
- **No original-Japanese byte-length restriction for translated dialogue.** English and Spanish lines are **not limited to the number of bytes used by the Japanese text**. They can be expanded and reformatted, provided they fit within the on-screen text box and the game’s technical storage limits.
- English menus, commands, system messages, and other interface text in both language choices.
- Translated and revised tactical graphics, narrative cards, battle graphics, and other on-screen interface elements.
- **244 revised location labels**, including restored place/room information separated by `/`. Common descriptors are abbreviated where useful, while distinctive place names are preserved.
- Corrected narrative-card layouts, including the Part 2 and Part 3 introductions, with text arranged for the game's animated fragments.
- Corrected final-chapter title card in both languages, restoring black lettering against its white background.
- Revised title logo, startup series copyright graphics, battle-skill graphics, bonuses, route labels, and commands, including E-Wave.
- Cumulative name and terminology corrections, including shared terminology checks with Super Robot Wars BX, and revised pilot-skill labels such as Resolve and Predict.
- Android patcher improvements for file reading, IVFC calculation, and translation-data processing.
- Cumulative corrections based on emulator tests and reports from Nintendo 3DS hardware.
- **Offline patching:** your game file is processed locally in your browser and does not need to be uploaded to a server.

## Installation

1. **Back up** your original Japanese game dump and existing save data.
2. Download and extract the current HTML patcher ZIP.
3. Open the `.html` file in a compatible, up-to-date browser on your computer or Android device. Large game files require adequate free storage and memory.
4. Select your **clean, unmodified, decrypted Japanese Super Robot Wars UX game** (`.cia`, `.cxi`, `.cci`, or `.3ds`). Use the separate **UX DLC** field in B057G26 for a DLC CIA. The decrypted Japanese v0 CIA is the best-tested input; other supported container formats may need further testing.
5. Choose **English** or **Español latinoamericano**. The game's menus and interface will remain in English either way.
6. Select **Check files** if you want to inspect the source, then use **Rebuild translated game** and save the generated game file.
7. Run the rebuilt game on a compatible emulator or your own Nintendo 3DS setup. Keep a backup of your saves before testing.

**Important:** Always start from the **original decrypted Japanese game**, never an already modified or translated copy. Each new release is cumulative; previous patch versions do not need to be applied first.

### Patcher and output

The patcher verifies that the input contains compatible, readable game data. Encrypted game dumps are not supported.

A **complete game rebuild** is required for the expanded location-label data. Select **Rebuild translated game**; the patcher does not provide a separate Luma/LayeredFS ZIP for this build.

### Optional DLC patching (experimental in B057G26)

Select your own clean, decrypted Japanese UX DLC CIA (Title ID `0004008C00078A00`), click **Patch DLC CIA**, and save the separate output. Install the resulting DLC CIA separately from the translated game. Encrypted or incomplete DLC files and already translated copies are rejected.

This option preserves the earlier V7 work: 48 catalog entries and 138 English objective texts across 47 missions. Puzzle titles retain their Japanese prefix to preserve category recognition. Campaign Map 9 remains in Japanese. DLC catalog/objective text is English for both base-game language choices.

The DLC rebuild introduced in B057G24 was tested with a real PC-decrypted DLC CIA whose missions were sorted by filename. The patcher recognizes that layout and restores mission order when rebuilding. **Installation and gameplay still need testing.** Keep Japan/Japanese locale settings for both game and DLC, as required in earlier hardware tests. If opening Get DLC causes a connection error, close and restart UX before viewing unit statistics; the historical crash after that sequence has not been resolved by this addition.

## Testing and project status

**B057G22 is the base-game build of public release 0.8.0. B057G26 is the latest cumulative test build.**

### Gameplay testing

**Tester Marl completed a full playthrough, consistently choosing the second option at every route split.** This confirms completion along that sequence of route choices; it does not establish that every alternate route or optional scene has been tested.

The underlying translation and expanded location-label system have also run successfully on real Nintendo 3DS hardware, including correctly displayed place/room labels with `/` in the scenes checked.

### Current-build validation

The Part 3 narration corrections were checked in an emulator in English and Spanish. The final-chapter title-card correction added in G22 passed texture reconstruction and visual inspection in both languages. For B057G26, the patcher passed JavaScript syntax checks, reconstructed the changed resources in both languages, applied the executable patch, and expanded the location data. A full rebuild and in-game checks of the new fixes, including the name editor, are still pending.

Testing continues across alternate routes, optional scenes, battle combinations, emulators, and hardware configurations. A completed playthrough does not imply exhaustive coverage of all game content or validation of every later fix.

## Known limitations and bug reports

- Some small **battle action indicators** still appear in Japanese, particularly symbols used in the combat prediction interface. These are graphical assets and are being investigated separately from the already translated interface text.
- Other graphical narration cards, long labels, and interface elements may still need visual alignment or cropping adjustments.
- Some optional scenes, route variations, and late-game content have not yet been exhaustively checked. Untranslated text, terminology inconsistencies, layout issues, or hardware-specific bugs may still be encountered.
- The translation remains under editorial and visual review; a successful patch build does not mean that every line or image has received final approval.

If you encounter a crash, untranslated graphic, clipped narration, incorrect terminology, or another interface issue, please send a report to the project team. If possible, include:

- The **patch build** and selected language (**EN/ES**).
- Your Nintendo 3DS setup or emulator and its version.
- The **chapter**, route, and exact steps needed to reproduce the issue.
- The last visible dialogue line, affected graphic, or menu/screen.
- A screenshot or short video; for crashes, an error log or crash dump if available.

Please back up your save before attempting to reproduce an issue. **Do not include copyrighted game dumps in bug reports.**

## Credits

- **Project and patch presentation:** Gyasuke & Wakabayashy Workshop

### Testers

- **Theoldnile**
- **Marl** — completed a full playthrough, always choosing the second option at route splits.

A huge thank you to our testers for their time, dedication, detailed reports, and invaluable feedback. Their help identifying translation issues, graphical defects, layout problems, and hardware-specific bugs is essential to improving the project.

Thanks also to everyone who has reported issues and supported the translation.

## Legal notice and distribution

This is an **unofficial, non-commercial fan translation**. It is not affiliated with, sponsored by, or endorsed by Bandai Namco or any original rights holder. All original game content, music, trademarks, and characters remain the property of their respective owners.

**The patch is free. It must not be sold or placed behind a paywall. If you paid for this patch, you were scammed; the project does not authorize anyone to charge for it.**

No game ROM, DLC or BIOS is distributed with this patch. You are responsible for obtaining and using your own game files in accordance with applicable laws.

---

Thank you for playing **Super Robot Wars UX** in English or Spanish!
