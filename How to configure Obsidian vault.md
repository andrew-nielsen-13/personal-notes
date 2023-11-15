1. Clone to main repo "~/obsidian notes".
2. Change the default view from dark mode to light mode. 
3. Make these changes:
![](images/Default%20location%20screenshot.png)
![](images/Wikilinks%20screenshot.png)
4. Install "Obsidian Git" from the settings menu.

## GitHub
You must follow [these instructions](https://github.com/dy-sh/obsidian-consistent-attachments-and-links) for images to display on GitHub. 

**Required Obsidian settings for the plugin to work properly:**

- **"Files & Links > Automatically update internal links": disabled.** The plugin itself is responsible for updating the links. When Obsidian shows a dialog asking to update links, refuse.
    
- **"New link format": Relative path to file.** Otherwise, strict compliance of the links cannot be guaranteed.
    
- **"Use [[Wikilinks]]": disabled**. Wikilinks are not a markdown standard.
    

Recommended additional settings (not required for the plugin to work):

- **"Default location for new attachments":In subfolder under current folder**. This is not required, but this ensures that attachments are always next to your notes. The option "Same folder as current file" is also suitable.
    
- **"Subfolder name": "_attachments"**. Or any other.