hit : ctrl + r TO INVOKE THE TEMPLATER
ctrl + p == OPEN THE COMMAND PALATTEE
CTRL + L == to toggle the stupid side bar shit 
Ctrl + d  == delete a note, ctrl + 0 =  use the stupid ass open switcher
CTRL D == daily note 
CTRL + G == GIT SAVE THE SHIT 
-----------------------------------------------------



here is the syntax : 

// Date now <% tp.date.now() %> 
// Date now with format <% tp.date.now("Do MMMM YYYY") %> 
// Last week <% tp.date.now("YYYY-MM-DD", -7) %> 
// Next week <% tp.date.now("YYYY-MM-DD", 7) %> 
// Last month <% tp.date.now("YYYY-MM-DD", "P-1M") %> 
// Next year <% tp.date.now("YYYY-MM-DD", "P1Y") %> 
// File's title date + 1 day (tomorrow) <% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %> 
// File's title date - 1 day (yesterday) <% tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM-DD") %>




> [!tldr] 
> so whats up boss



|Variable|Description|
|---|---|
|`{{title}}`|Title of the active note.|
|`{{date}}`|Today's date. **Default format:** `YYYY-MM-DD`.|
|`{{time}}`|Current time. **Default format:** `HH:mm`.|
#uniquenote/friday
[[20240425]]


### Supported Markdown extensions

| Syntax          | Description                                                                                                   |
| --------------- | ------------------------------------------------------------------------------------------------------------- |
| `[[Link]]`      | [Internal links](https://help.obsidian.md/Linking+notes+and+files/Internal+links)                             |
| `![[Link]]`     | [Embed files](https://help.obsidian.md/Linking+notes+and+files/Embed+files)                                   |
| `![[Link#^id]]` | [Block references](https://help.obsidian.md/Linking+notes+and+files/Internal+links#Link to a block in a note) |
| `^id`           | [Defining a block](https://help.obsidian.md/Linking+notes+and+files/Internal+links#Link to a block in a note) |
| `%%Text%%`      | [Comments](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax#Comments)                  |
| `~~Text~~`      | [Strikethroughs](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax#Styling text)        |
| `==Text==`      | [Highlights](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax#Styling text)            |
| ` ``` `         | [Code blocks](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax#Code blocks)            |
| `- [ ]`         | [Incomplete task](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax#Task lists)         |
| `- [x]`         | [Completed task](https://help.obsidian.md/Editing+and+formatting/Basic+formatting+syntax#Task lists)          |
| `> [!note]`     | [Callouts](https://help.obsidian.md/Editing+and+formatting/Callouts)                                          |
| (see link)      | [Tables](https://help.obsidian.md/Editing+and+formatting/Advanced+formatting+syntax#Tables)                   |