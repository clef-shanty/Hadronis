<%*
const firstName = tp.frontmatter["first-name"]; // Access the "first name"
const lastName = tp.frontmatter["last-name"]; // Access the "last name"
// Combine the last name and first name to create the new note name
const newFileName = `${firstName} ${lastName}`;
// Rename the current note
await tp.file.rename(newFileName);
%>