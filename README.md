# Mothership Warden Assistant

## Introduction

The Warden Assistant is designed to help run Mothership scenarios, providing images, music, and maps, as well as a way to track player status and present it to the players in a second monitor. This is primarily designed as an in-person experience, but screen sharing should allow use over the internet.

Currently it only includes the Haunting of Ypsilon 14 scenario, but could be expanded to more. It could likely be adapted to run an Aliens style game by changing wounds to 1 and adjusting health and stress as needed.

Demo: [https://adamgmiller.github.io/mothership-warden-assistant/](https://adamgmiller.github.io/mothership-warden-assistant/)

## Setup

You'll need to either copy the files to a web server, host the files locally (e.g. [IIS on Windows](<https://learn.microsoft.com/en-us/previous-versions/aspnet/ckk1e6z4(v=vs.100)>) ), or host the files on github.

The sound files for the Ypsilon casette tapes aren't included in the repo, so you'll need to copy those into the sounds directory yourself.

## How to Use

### Your First Player

- Click "Open Player Page" to open a second, child window. This can be dragged to a second monitor for players to view.
- Edit the default "Player 1" character by clicking on the text below the portrait. Clicking on the portrait sends the picture to to player screen.
- Enter a name (e.g. VASQUEZ, J)
- Click the down arrow to pick a portrait.
- For androids and marines, change the max wounds to 3
- Adjust the current and max health accordingly.
- Click Update
- Changes will be sent to the player window - things like status and the health and stress EKG are updated immediately
- Changes will be saved in local storage in case you need to close the browser

### Adding New Players

- After the edit screen is closed (by clicking Update), click the Add Player button
- Edit as needed and click Update

### Miscellaneous Player Management

- Clicking the portrait sends the large image to the player screen
- Remove a player by clicking the text beneath the portrait, clicking Remove, and saying yes to the confirmation dialog
- After updating, changes to vitals, names, portrait, and other statistics will be updated on the player screen
- Clicking Show portraits to player shows a full list of headshots to players to help them choose one when creating a character

### Scenes

- Expand and collapse the different scenes by clicking on the scene title
- Click on the image to send the image to the player screen
- Click the sound link to play the music or sound

### Maps

- Clicking the link next to "Show map" will send the map of the area to the player
- Clicking "(open map locally)" opens it in a new window so the warden can zoom in and examine the map more closely

### Systems

- Clicking the "Show system" button sends an animated map of the system to the player screen
- Entering a number in the box (e.g. "14" for the Ypsion system) will zoom the map on the player screen to that astronomical body

## Attribution

While the contents of maps, scenes, project, and the html and javascript are licensed as CC0.

Some maps used content from the [Starship Geomorphs book](https://travellerrpgblog.blogspot.com/2018/10/the-starship-geomorphs-book-if-finally.html) which is licensed with [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

Sound attribution is included with each scenario, but currently includes [Table Top Audio](https://tabletopaudio.com/) which is licensed with [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
