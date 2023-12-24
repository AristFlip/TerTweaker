# Chunky
Pre-generates chunks, quickly, efficiently, and safely
A better alternative to WorldBorder fill and similar features in other plugins

# Features
- Start one or several chunk generation tasks at the same time (if you want to leverage your CPU more)
- Pause chunk generation tasks, saving them for later
- Shows detailed information such as chunks processed, percent to completion, ETA, chunk processing rate, etc
- Custom world shapes, and optional world border support with ChunkyBorder installed

# Commands

Task Management
chunky start Starts a new chunk generation task from the current selection
chunky pause Pauses the current chunk generation tasks, and saves progress
chunky continue Continues running current or saved chunk generation tasks
chunky cancel Stops the current chunk generation tasks, and cancels progress
Selection
chunky world [world] Sets the currently selected world
chunky shape <shape> Set the shape to generate
chunky center [<x> <z>] Sets the current center block location
chunky radius <radius> Sets the current radius
chunky worldborder Set the center and radius to match the vanilla world border in the selected world
chunky spawn Set the center to the spawn point
chunky corners <x1> <z1> <x2> <z2> Set the selection by corner coordinates
chunky pattern <pattern> Set the preferred generation pattern
chunky selection Display the current selection
Miscellaneous
chunky silent Toggle displaying update messages
chunky quiet <interval> Set the quiet interval in seconds for update messages
chunky progress Display pre-generation progress in-game for all tasks
chunky reload Reloads the configuration
chunky trim Delete chunks outside selection
