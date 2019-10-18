# Animarr

Animarr is an **independent** fork of Sonarr for automatically downloading Anime via Usenet and BitTorrent.
The project was made due to lack of proper support for Anime through Sonarr.

## Configuring Development Environment:

### Requirements

* [Visual Studio 2017](https://www.visualstudio.com/vs/)
* [Git](https://git-scm.com/downloads)
* [NodeJS](https://nodejs.org/en/download/)
* [Yarn](https://yarnpkg.com/)

### Setup

* Make sure all the required software mentioned above are installed
* Clone the repository into your development machine. [*info*](https://help.github.com/en/articles/working-with-forks)
* Grab the submodules `git submodule init && git submodule update`
* Install the required Node Packages `yarn`

### Backend Development

* Run `yarn build` to build the UI
* Open `Sonarr.sln` in Visual Studio
* Make sure `NzbDrone.Console` is set as the startup project
* Build `NzbDrone.Windows` and `NzbDrone.Mono` projects
* Build Solution

### UI Development

* Run `yarn watch` to build UI and rebuild automatically when changes are detected
* Run Sonarr.Console.exe (or debug in Visual Studio)

### License

* [GNU GPL v3](http://www.gnu.org/licenses/gpl.html)
* Copyright 2010-2019
