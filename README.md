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
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/OPUM-LABS/ADUser-Amuser/">
    <img src="/.screenshots/Logo.png" alt="Logo" width="100" height="100">
  </a>

<h3 align="center">ADUser-Amuser</h3>

  <p align="center">
    A tool for easy interactions wit ADUsers based on PowerShell.
    <br />
    <br />
    <a href="https://github.com/OPUM-LABS/ADUser-Amuser/issues">Report Bug</a>
    ·
    <a href="https://github.com/OPUM-LABS/ADUser-Amuser/pulls">Request Feature</a>
  </p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#features">Features</a></li>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://github.com/OPUM-LABS/ADUser-Amuser/blob/main/.screenshots/ADUser-Amuser_b%26w.png)

This program allows you to perform actions on multiple AD User objects at the same time easily and efficiently without having to know any PowerShell command.  
"Amuser" stands for the fact that the processing of repetitive tasks with ADUsers can also be fun.

### Features
You can do for all selectet users at once:  
✨ Write all groups to the info-attribute  
✨ Write all groups as a list to a TXT-File  
✨ Remove all assigned groups  
✨ Move user to a desired OU  
✨ Remove from the global adressbook (Exchange)  
✨ Disable user  
✨ Delete user (with a "high security" confirmation mechanism)  
✨ Set up to five attribute-values at once  
✨ Toggle between simple and verbose output  
✨ Toggle between dark and bright theme

Bonus:  
✨ Check inside the program if a new version is available

### Built With

* [PowerShell Studio 2022](https://www.sapien.com/software/powershell_studio)
* [Windows PowerShell](https://docs.microsoft.com/en-us/powershell/)
* [Windows PowerShell ISE](https://docs.microsoft.com/en-us/powershell/scripting/windows-powershell/ise/introducing-the-windows-powershell-ise?view=powershell-7.1)
* [Notepad++](https://notepad-plus-plus.org/)
<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

Just download the latest ADUser-Amuser.exe or ADUser-Amuser.ps1 and run it on a domain-joined computer.  
(Note that neither the EXE nor the PS1 file is signed.  
A warning message will appear either when you download the file(s) or most likely later when you try to open it!)

### Prerequisites

The following prerequisites must be met:
* PowerShell 5 and up
* domain-joined computer

### Installation

This is a program that can be easily run without installation.
<p align="right">(<a href="#top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
## Usage

Users can be searched globally or filtered by OU if desired, based on their SamAccountName or UserPrincipalName and. Several options are then available for interacting with them.  
(Keep in mind that the program must be opened with a user who has the necessary AD permissions!)
<p align="right">(<a href="#top">back to top</a>)</p>


<!-- LICENSE -->
## License

Distributed under the GNU General Public License v3.0. See `LICENSE` for more information.
<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/OPUM-LABS/ADUser-Amuser.svg?style=for-the-badge
[contributors-url]: https://github.com/OPUM-LABS/ADUser-Amuser/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/OPUM-LABS/ADUser-Amuser.svg?style=for-the-badge
[forks-url]: https://github.com/OPUM-LABS/ADUser-Amuser/network/members
[stars-shield]: https://img.shields.io/github/stars/OPUM-LABS/ADUser-Amuser.svg?style=for-the-badge
[stars-url]: https://github.com/OPUM-LABS/ADUser-Amuser/stargazers
[issues-shield]: https://img.shields.io/github/issues/OPUM-LABS/ADUser-Amuser.svg?style=for-the-badge
[issues-url]: https://github.com/OPUM-LABS/ADUser-Amuser/issues
[license-shield]: https://img.shields.io/github/license/OPUM-LABS/ADUser-Amuser.svg?style=for-the-badge
[license-url]: https://github.com/MitchPatch/MitchPatch/blob/master/LICENSE.txt
[product-screenshot]: .screenshots/ADUser-Amuser_b%26w.png
