<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![Twitch][twitch-shield]][twitch-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h3 align="center">Indy HUD v1.4 by CodeInfused</h3>

  <p align="center">
    An augmented reality HUD for managing industry
    <br />
    <a href="https://youtu.be/kDHVO_DGU-k">Watch a Demo</a>
    ·
    <a href="https://github.com/codeinfused/Indy-HUD/issues">Report Bug</a>
  </p>
</div>



<!-- ABOUT INDY HUD -->
## About Indy HUD

This is an augmented reality HUD for tracking states of your industry machines for Dual Universe. This script only requires a single programming board, and can manage all the units on a single core factory. 

_What This HUD Isn't:_
* Not an automation tool; it cannot start or stop machines
* Not a recipe tool; it will not show recipe trees for items

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

_This programming board HUD is delivered by "json" import, a feature supported by Dual Universe for custom scripts. You will need to download a file as instructed below to use this HUD._

### File Install

1. Click this link to open the json file directly (it will be raw text) [json-indyhud-v1-4.json][download-url]
2. Select all of the text contents (CTRL+A to select all), and then copy (CTRL+C).
3. You'll need to place a Programming Board at your factory. This should be a fresh board (or re-placed to clear it).
4. Right-click the programming board, go to "Advanced" > "Paste Lua Configuration From Clipboard"
5. After doing "Paste Lua Config", go into build mode. 
6. Link your construct's Core to the programming board.
7. Link your construct's schematic container to the programming board also.

That's it! Run the board now and enjoy.


<!-- CHANGELOG -->
## Changelog

### v1.4
- Added support for Schematic Containers, adding available schematic counts to each industry element
- Added option in Lua Parameters for the startup mode view (0-9)
- New dynamic render range: AR automatically determines max distance to render machines based on active filters, extending the range when less matches are found, and shortening the range if needed for performance.

### v1.3
- Added DE and FR language translations for menus and machine states
- Added a 3rd mode for Containers, "full" shows all names within range
- Added a corner highlight on machines that are set to "run forever"
- Improved the foreground highlight of boxes being hovered on
- Improved maintain levels when pending
- Improved max machine load (no limit found yet)
- Minor performance improvement

### v1.2
- FIXED: initialization load bug for larger factories
- Improved position of status box
- Improved render performance when maxDist is lower and filters are applied
- Reduced hover hitbox of distant units
- Increased overall opacity
- Added visual distance scaling of mini-boxes
- Added recipe data to status detail view (optional)
- Added containers to machine list (optional)
- Added font size option (in Parameters)
- Added opacity distance option (in Parameters)

### v1.1
Improvements to performance for larger factories with hundreds of industry units to help prevent cpu shutdown errors.


<!-- USAGE -->
## Usage

Coming soon.


<!-- CONTACT -->
## Contact

_While I do love Dual Universe and its community, I also have very little free time typically. I will try to answer questions via Discord, or if you catch me online on Twitch. But keep in mind this is a free resource, and I've spent a good chunk of time on it, so please be constructive and kind :)_

Discord: [Albatross HUD on DU-OSI](https://discord.gg/EThSxMGXBg)

Twitch: [Watch CodeInfused on Twitch](https://twitch.tv/codeinfused)<br/>
_I go online at pretty random times, so if you'd like to catch my streams, just go here and hit Follow_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GNU GPLv3 license. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>




<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[download-url]: https://github.com/codeinfused/Indy-HUD/raw/main/json-indyhud-v1-4.json
[contributors-shield]: https://img.shields.io/github/contributors/codeinfused/Indy-HUD.svg?style=plastic
[contributors-url]: https://github.com/codeinfused/Indy-HUD/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/codeinfused/Indy-HUD.svg?style=plastic
[forks-url]: https://github.com/codeinfused/Indy-HUDy/network/members
[stars-shield]: https://img.shields.io/github/stars/codeinfused/Indy-HUD.svg?style=plastic
[stars-url]: https://github.com/codeinfused/Indy-HUD/stargazers
[issues-shield]: https://img.shields.io/github/issues/codeinfused/Indy-HUD.svg?style=plastic
[issues-url]: https://github.com/codeinfused/Indy-HUDy/issues
[license-shield]: https://img.shields.io/github/license/codeinfused/Indy-HUD.svg?style=plastic
[license-url]: https://github.com/codeinfused/Indy-HUD/blob/master/LICENSE.txt
[twitch-shield]: https://img.shields.io/badge/twitch-live-red?logo=twitch&style=social
[twitch-url]: https://twitch.tv/codeinfused
[product-screenshot]: images/screenshot.png
