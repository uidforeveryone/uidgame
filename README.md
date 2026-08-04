# Unterwegs in Düsterburg - Web Version

Deutsche Version spielen:
https://uidforeveryone.github.io/uidgame/de/<br>
Play English Version:
https://uidforeveryone.github.io/uidgame/en/

## Project Overview
* Web-based version of the RPG Maker 2000 game "Unterwegs in Düsterburg".
* Purpose: Allows execution of the game directly in modern internet browsers without requiring a local installation or specific operating system.
* English Translation (v1.3) of the game by Aranael

## Notes
* **Note 1:** The total size of the game files is up to 90 MB, with 60 MB dedicated to the music. Approximately 43 MB are downloaded when you first launch the game. Downloading via mobile data without Wi-Fi (e.g., while on the go using a smartphone or tablet) is not recommended due to data usage.
*  **Note 2:** Save data cannot be transferred between the offline and online versions.
*  **Language-Cross-Compatibility:** Save data is automatically transferred between the English and German version.

## Technical Details
* **Engine:** Uses the EasyRPG Player (https://github.com/easyrpg/player) via WebAssembly (`.wasm`).
* **Execution:** Runs entirely client-side within the browser's sandbox environment. Requires no server-side processing.
* **File Handling:** Game assets (graphics, audio, maps) are loaded into the browser's temporary cache during execution.
* **Save Data:** Save states are stored locally on the user's device inside the browser's IndexedDB. Closing the tab ends the process, but saves remain intact in the browser.

## Controls
* **Arrow Keys:** Movement
* **Enter / Z:** Action / Confirm
* **Esc / X:** Menu / Cancel / Go Back

## Licenses and Copyrights
* **Game Data:** "Unterwegs in Düsterburg" All game files, story, and custom assets are the intellectual property of the original author.
* **Software:** [EasyRPG Player](https://easyrpg.org/) is open-source software licensed under the GNU General Public License v3.0 (GPLv3).
* **Audio (MIDI):** Utilizes open-source General MIDI SoundFont GeneralUser GS v2.0.3 for music playback.

## Soundfont: GeneralUser GS v2.0.3 License
```txt
* *** GeneralUser GS v2.0.3 ***
***      License v2.0     ***

** License of the complete work **
You may use GeneralUser GS without restriction for your own music creation,
private or commercial. This SoundFont bank is provided to the community free of
charge. Please feel free to use it in your software projects, and to modify the
SoundFont bank or its packaging to suit your needs.

** License of contained samples **
GeneralUser GS inherits the usage rights of the samples contained within, all of
which allow full use in music production, including the ability to make profit
from musical recordings created with GeneralUser GS.

Many of the samples are original, but some were taken from other banks freely
(and legally) available on the Internet from various SoundFont websites. Because
GeneralUser GS originated as a personal project with no intention for
publication, I cannot be 100% sure where all of the samples originated, although
I do know that none of them came from commercially published SoundFont packages
or sample CDs. Regardless, many "free" SoundFonts available on the web may
indeed contain samples of questionable origin. My understanding of the
copyrights of all samples is only as good as the information provided by the
original sources. If you become aware of any restricted samples being used in
GeneralUser GS, please let me know so I can replace them.

This uncertainty may concern you if you intend to use GeneralUser GS in a
commercial software product. That being said, I have never received any
complaint regarding sample ownership since I published the original GeneralUser
GS back in 2000, and as far as I am aware, neither have any of the companies
creating commercial software products using GeneralUser GS.

** More info **
If you plan to feature GeneralUser GS on your own website, please do not link
directly to my download files. Either link to my website, or provide your own
local copy instead.

I hope you enjoy GeneralUser GS! This SoundFont bank is the product of many
years of hard work.

You can find updates to GeneralUser GS and more of my virtual instruments at:
http://www.schristiancollins.com

I can be reached via the contact page on my website here:
https://www.schristiancollins.com/contact

Thank you!
-~Chris
```
