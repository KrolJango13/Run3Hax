# Run3Hax
A simple JavaScript API to hack the popular web game, Run 3 (at least on its [own site](https://lekug.github.io/tn6pS9dCf37xAhkJv/))

## Documentation
#### query (selector: RegExp) => String
The Run 3 config is stored as a sort of CSV, with the delimeter as a colon. This method is used to get a config value using RegEx
Config values (there are more, but these are just the important ones):
- currentPath
- currentCharacter
- exploreRuns
- exploreprimary
- tilesDislodged
- infiniteRunsUnfiltered
- infiniteRuns
- infiniteDistance
- infinite
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
