<p align="center">
  <a href="https://github.com/BennyExtreme/WAIUA">
    <img src="Screenshots/logo.png" alt="Logo" width="80" height="80">
  </a>
</p>
<h3 align="center">WAIUA</h3>
<h4 align="center">Who Am I Up Against?</h4>
<a href="https://waiua.bennyextreme.tk"><h1 align="center">waiua.bennyextreme.tk</h1></a>

  <p align="center">
    A Windows application to view player ranks and other info in a live Valorant Match</p>
    <p align="center">
    <img alt="GitHub" src="https://img.shields.io/github/license/BennyExtreme/WAIUA?color=blue">
    <a href="https://github.com/Soneliem/WAIUA/releases/latest/download/WAIUA.exe">
	  <img alt="GitHub downloads counter" src="https://img.shields.io/github/downloads/BennyExtreme/WAIUA/total?color=blue">
      <img alt="GitHub latest release" src="https://img.shields.io/github/v/release/BennyExtreme/WAIUA">
    </a>
    </p>
  <br />

![Screenshot](Screenshots/main.png)

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
      <li><a href="#current-features">Current Features</a></li>
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
    <li><a href="#roadmap-and-known-bugs">Roadmap And Known Bugs</a></li>
    <li>
	  <a href="#built-with">Built With</a>
	  <ul>
	    <li><a href="#packages">Packages</a></li>
	  </ul>
	</li>
	<li><a href="#why-this-app-exists">Why This App Exists</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#translations">Translations</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
    <li><a href="#disclaimer">Disclaimer</a></li>
  </ol>
</details>

## About The Project

"Who Am I Up Against?" (WAIUA) is simple Windows app that lets you see the ranks, recent game stats and other info of players in a live Valorant match while you're still playing it. Below are the current features that are in the app.

### Current Features

|Current Rank and Rank Progress|Past three ranks (from last 3 acts)|RR lost or gained in last three competitive games|Account Level and Agent Image|
|:---:|:---:|:---:|:---:|
|![rank](Screenshots/rank.png)|![rank](Screenshots/pranks.png)|![rank](Screenshots/history.png)|![card](Screenshots/card.png)|

|In-game and Agent Name|Vandal And Phantom Skin|Party Indicators|Fully translated into 15+ languages|
|:---:|:---:|:---:|:---:|
|![name](Screenshots/name.png)|![skin](Screenshots/skin.png)|![party](Screenshots/party.png)|![translation](Screenshots/language.png)|

|Tracker.gg Intergration|Mini-Aim Trainer|Support For all Game Modes|Auto Refresh and Updates|
|:---:|:---:|:---:|:---:|
|![tracker](Screenshots/tracker.png)|![trainer](Screenshots/trainer.png)|![mode](Screenshots/mode.png)|![refresh](Screenshots/refresh.png)|

## Getting Started

To get the app up and running follow these simple steps.

### Prerequisites

* Windows 64-bit (If you're able to run Valorant on it you'll be fine)
* .NET (will be automatically installed during installation)

### Installation

1. Download [the latest installer](https://github.com/BennyExtreme/WAIUA/releases/latest/download/WAIUA.exe)
2. Run the .exe (If a blue box saying "Windows protected your PC" shows up, click `More Info` and then `Run Anyway`)
3. Follow the steps to install WAIUA

## Usage

1. Open the app
2. WAIUA will automatically check for a match and give you the info of it

## Roadmap and Known Bugs

Please check the [issues tab](https://github.com/BennyExtreme/WAIUA/issues) before making a new issue.

## Built With

* [WPF](https://docs.microsoft.com/en-us/dotnet/desktop/wpf/?view=netdesktop-6.0)
* [C#](https://docs.microsoft.com/en-us/dotnet/csharp/)
* [.NET 6.0](https://dotnet.microsoft.com/)

#### Packages

* [RestSharp](https://restsharp.dev/) for API requests
* [System.Text.Json](https://docs.microsoft.com/en-us/dotnet/api/system.text.json) to deserialise JSON.
* [Windows Community Toolkit MVVM](https://docs.microsoft.com/en-us/windows/communitytoolkit/mvvm/introduction) for MVVM.
* [AutoUpdater.NET](https://github.com/ravibpatel/AutoUpdater.NET) for auto updates
* [Inno Setup](https://jrsoftware.org/isinfo.php) to install WAIUA
* [FontAwesome](https://fontawesome.com/license) for icons.

## Why This App Exists

The main reason was to detect smurfs. The set of available features was chosen carefully to maintain the competitive integrity of the game.

## Contributing

I welcome any sort of contribution. Please remember that translations are managed externally as mentioned below.

## Translations

WAIUA Supports full localization and instructions to help with translations can be found in [Localization](https://github.com/BennyExtreme/WAIUA/blob/master/Localization.md)

## Contact

**Official Website:** [waiua.bennyextreme.tk](https://waiua.bennyextreme.tk)
**Discord:** BennyExtreme_
**Email:** [bennygames.yt@gmail.com](mailto:bennygames.yt@gmail.com)
**Project Link:** [https://github.com/BennyExtreme/WAIUA](https://github.com/BennyExtreme/WAIUA)

## Acknowledgements

* [techchrism for work on documenting Valorant endpoints](https://github.com/techchrism/valorant-api-docs)
* [Valorant-API.com for all images, etc](https://valorant-api.com/)
* [The guys on the Valorant App Developers Discord Server](https://discord.gg/a9yzrw3KAm)
* This project uses Riot's in-game API for most of the information

## DISCLAIMER

THIS PROJECT IS NOT ASSOCIATED OR ENDORSED BY RIOT GAMES. Riot Games, and all associated properties are trademarks or registered trademarks of Riot Games, Inc.
By using this application, you agree that you, the individual, are knowingly accessing all information required to be displayed.
