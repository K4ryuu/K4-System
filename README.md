<a name="readme-top"></a>

![GitHub tag (with filter)](https://img.shields.io/github/v/tag/K4ryuu/K4-System?style=for-the-badge&label=Version)
![GitHub Repo stars](https://img.shields.io/github/stars/K4ryuu/K4-System?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues/K4ryuu/K4-System?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/K4ryuu/K4-System?style=for-the-badge)
![GitHub contributors](https://img.shields.io/github/contributors/K4ryuu/K4-System?style=for-the-badge)
![GitHub all releases](https://img.shields.io/github/downloads/K4ryuu/K4-System/total?style=for-the-badge)
![GitHub last commit (branch)](https://img.shields.io/github/last-commit/K4ryuu/K4-System/dev?style=for-the-badge)

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <h1 align="center">K4ryuu</h1>
  <h3 align="center">K4-System</h3>

  <p align="center">
    An awesome CS2 server addon created with <a href="https://github.com/roflmuffin/CounterStrikeSharp"><strong>CounterStrikeSharp</strong></a>
    <br />
    <br />
    <a href="https://github.com/K4ryuu/K4-System/releases">Download</a>
    ·
    <a href="https://github.com/K4ryuu/K4-System/issues/new?assignees=K4ryuu&labels=bug&projects=&template=bug_report.md&title=%5BBUG%5D">Report Bug</a>
    ·
    <a href="https://github.com/K4ryuu/K4-System/issues/new?assignees=K4ryuu&labels=enhancement&projects=&template=feature_request.md&title=%5BREQ%5D">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#support-my-work">Support My Work</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
        <a href="#usage">Usage</a>
        <ul>
            <li><a href="#commands">Commands</a></li>
            <li><a href="#console-variables-(convars)">ConVars</a></li>
      </ul>
    </li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

K4-Systems is a plugin that enhances the server with features such as a playtime tracker, statistical records, and player ranks. Additionally, it includes VIP functions and admin commands for added functionality.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Dependencies

To use this server addon, you'll need the following dependencies installed:

- [**CounterStrikeSharp**](https://github.com/roflmuffin/CounterStrikeSharp/releases): CounterStrikeSharp allows you to write server plugins in C# for Counter-Strike 2/Source2/CS2
- **MySQL Database (Version 5.2 or higher):** This project requires a MySQL database to store and manage data. You can host your own MySQL server or use a third-party hosting service. Make sure it's at least version 5.2 or higher.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Support My Work

I offer various ways to support my journey:

- 💬 **Request Private Paid Jobs:** Got a specific project in mind? Let's chat, and I'll provide a quote.
- 🎁 **Subscribe to My Tiers:** Join one of my subscription tiers for exclusive benefits, early access to projects, and personalized support.
- ☕ **Buy Me a Coffee:** One-time donations keep me motivated and my creativity flowing.
- 💼 **Shop from My Paid Resources:** Explore and purchase resources I've crafted for private use.

Your support keeps my creative engine running and allows me to share knowledge with the community. Thanks for being part of my journey.

<p align="center">
<a href="https://www.buymeacoffee.com/k4ryuu">
<img src="https://img.buymeacoffee.com/button-api/?text=Support My Work&emoji=☕&slug=k4ryuu&button_colour=FF5F5F&font_colour=ffffff&font_family=Inter&outline_colour=000000&coffee_colour=FFDD00" />
</a>
</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## Getting Started

Follow these steps to install and use the addon:

### Prerequisites

Before you begin, ensure you have the following prerequisites:

- A working CS2 (Counter-Strike 2) server.
- CounterStrikeSharp is up to date and is running on your server.
- A compatible MySQL database (Version 5.2 or higher) set up and configured.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Installation

1. **Download the Addon:** Start by downloading the addon from the [GitHub Releases Page](https://github.com/K4ryuu/K4-System/releases). Choose the latest release version.

2. **Extract the Addon:** After downloading, extract the contents of the addon to the counterstrikesharp/plugins directory on your server. Inside the plugins folder, you should have a folder named exactly as the project dll. From the releases, you find it pre zipped with the correct name.

3. **Configuration:** The config is being generated after the first start of the plugin, to configs/plugins/K4-System/ folder.

4. **Permissions:** You can set the permissions as you need in the counterstrikesharp/configs/admins.json

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->

## Usage

The addon provides several commands and console variables (convars) to customize and interact with its features. Here is the list of the key commands and convars you can use:

### Commands

- **!rank** - Check the current rank and points
- **!ranktop, !top, !top5** - Check the top 5 players by points
- **!top10** - Check the top 10 players by points
- **!resetmyrank** - Reset the players self rank and points
- **!resetrank "SteamID64"** - Reset the rank of the target if its used by admin
- **!setpoints "SteamID64" 100** - Sets the targeted player's points to the given value if its used by admin
- **!givepoints "SteamID64" 100** - Gives points to the targeted player if its used by admin
- **!removepoints "SteamID64" 100** - Removes points from the targeted player if its used by admin
- **!stat, !statistics** - Check your statistics
- **!time, !mytime, !playtime** - Check the current playtime
- **!k4** - K4-System informational panel

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Permissions

- **@k4system/vip/points-multiplier** VIP Point Multiplier Permission
- **@k4system/admin** All K4 Admin Commands
- **@css/config** See debug prints in chat

- <p align="right">(<a href="#readme-top">back to top</a>)</p>

### Log Levels

If you set a loglevel only THAT or ABOVE logs will be printed and saved.

- **Debug (-1)** Print debug logs to people's chat with @css/config permission and into console/log files (RESOURCE EXPENSIVE)
- **Info (0)** Informational log/console messages
- **Warning (1)** Warning log/console messages
- **Error (2)** Error log/console messages

- <p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->

## Roadmap

- [x] Config to disable modules fully
- [ ] Automated Moderation System
- [ ] VIP Clan Tag
- [ ] Daily Rewards
- [ ] More VIP perks
- [ ] Point For Playtime
- [ ] WebPanel (under development)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## License

Distributed under the GPL-3.0 License. See `LICENSE.md` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->

## Contact

- **Discord:** k4ryuu
- **Email:** k4ryuu@icloud.com

<p align="right">(<a href="#readme-top">back to top</a>)</p>
