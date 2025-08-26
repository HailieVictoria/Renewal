---
locType:
tags:
  - Location
---
<% tp.file.title %>
<% await tp.file.move("/Locations/" + tp.file.title) %>
<%*
const hasTitle = !tp.file.title.startsWith("New Location");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Location Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>
## Overview
- ###### Type:  
	- 
- ###### Size:
	- 
- ###### Description: 
	- 
- ###### Inhabitants:
	- 
- ###### Points of Interest:
	- 

## General Notes
- 
