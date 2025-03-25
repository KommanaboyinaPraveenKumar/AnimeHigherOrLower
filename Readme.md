# Anime Higher or Lower

## Overview
Anime Higher or Lower is a web-based game where players guess whether an anime has a higher or lower ranking than another. The game pulls anime rankings from MAL and dynamically updates the game state based on user choices.

## Features
- Displays two anime images side by side.
- Shows the current anime's rank.
- Players guess if the next anime has a higher or lower rank.
- Score increases for correct guesses.
- Game over when a wrong choice is made.
- Restart option available.
- Responsive design with a sleek UI.

## Technologies Used
- **HTML, CSS, JavaScript** for the front-end.
- **Bootstrap** for styling.

## Installation & Setup
1. Clone this repository:
   ```sh
   git clone https://github.com/KommanaboyinaPraveenKumar/AnimeHigherOrLowe.git 
   ```
2. Navigate to the project folder:
   ```sh
   cd anime-higher-lower
   ```
3. Open `index.html` in a web browser.
Or you can use this link to directly play https://kommanaboyinapraveenkumar.github.io/AnimeHigherOrLower/
## How to Play
1. The game starts by displaying two anime images.
2. The rank of the first anime is shown.
3. Click **Higher** if you think the second anime has a better rank (lower number) or **Lower** if you think it has a worse rank (higher number).
4. If correct, your score increases, and a new anime appears.
5. If wrong, the game ends, and your final score is displayed.
6. Click **Try Again** to restart.

## File Structure
```
Anime Higher or Lower/
│-- index.html       # Main game file
│-- anime_data.json  # JSON file containing anime rankings
|--photos            #the images used in the game
```

## Credits
- **Developer:** Praveen Kumar 
- **Anime Data:** The top 50 anime from the MyAnimeList website

