---
type: sessNote
sessionNum: 
date: <% tp.data.now("MM-DD-YYYY") %>
endLoc:
---

<% tp.file.title %>
<% await tp.file.move("/Session-Notes/" + tp.file.title) %>

<%*
let title;

title = await tp.system.prompt("Enter Session Number");
await tp.file.rename(title);
_%>

## Session Notes

