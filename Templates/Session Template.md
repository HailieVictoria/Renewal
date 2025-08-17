---
type: sessNote
sessionNum: 
date: <% tp.data.now("MM-DD-YYYY") %>
endLoc:
---


<% tp.file.title %>
<% await tp.file.move("/Session-Notes/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("New Session");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter Session Date");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>


## Session Notes

