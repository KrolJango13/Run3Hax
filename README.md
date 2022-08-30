# Run3Hax
A simple JavaScript API to hack the popular web game, Run 3 (at least on its [own site](https://lekug.github.io/tn6pS9dCf37xAhkJv/)). 
To use this API, import it as a JavaScript module or copy and paste everything except the last line (the export line) into the chrome console.
#### [Source](https://kroljango13.github.io/Run3Hax/index.js?target=_blank)

## Documentation
#### query (selector: RegExp) => String
The Run 3 config is stored as a sort of CSV, with the delimeter as a colon. This method is used to get a config value using RegEx
Config values (there are more, but these are just the important ones):
- currentPath
- currentCharacter
- tilesDislodged
- infiniteRuns
- infiniteDistance
- mostBatteries
- softEarned

#### getCellsEarned () => Number
Get the number of power cells that the player has ever picked up

#### getCellsSpent () => Number
Get the number of power cells that the player has ever spent

#### getCellCount () => Number
Get the number of power cells that the player has

#### setCellCount (count: Number) => void
Set the number of power cells that the player has
