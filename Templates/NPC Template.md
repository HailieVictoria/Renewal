---
aliases:
tags:
  - NPC
---
<% tp.file.title %>
<% await tp.file.move("/NPCs/" + tp.file.title) %>
<%*
const hasTitle = !tp.file.title.startsWith("New NPC");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter NPC Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

## Overview
- ###### Name/Alias:  
	- 
- ###### Gender: 
	- 
- ###### Location: 
	- 
- ###### Appearance:
	- 
- ###### Relationships: 
	- 



## Backstory Notes

- 




## General Notes

- 
