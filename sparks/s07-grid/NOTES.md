# NOTES — S07 Grid

## Intent
I am creating a page of hiking trail information for students who want to find trails near BYU campus. I'm creating it for people to view on their laptop.

Prediction: 
I'm predicting the display: grid property will the header, main content, sidebar, and footer into different parts of the grid. 
I'm predicting the auto-fit property will make the cards all fit next to each other without me specifying how many.

What it used:
The page-layout used display: grid and grid-template-areas to put those sections in place. Each one has a grid-area value (header, main, aside, footer) so it goes in the matching spot. I was right in guessing about the display: grid property being used, but I didn't get very specific with the way the grid-area value actually assigns each element (header, main, etc.) to an area. 
To make the cards fit next to each other without my specifying how many, it used display: grid and grid-template-columns with repeat with auto-fit, minmax, and fr. The auto-fit property lets the browser fit as many columns as possible. I was right about the auto-fit aspect, but I didn't get into detail with the minmax, grid-template, and fr properties, which are also really important. 

## AI use
I am using AI Copilot on VS Code. I gave it my intent and told it to create a new folder for this spark and a NOTES.md file, an index.html, and a style.css. I gave it the done list and told it to help me create a page that followed the guidelines of the done list.
I described my desired layout to the agent of a header, four cards next to an aside section, and a footer at the bottom.
## Accepted / changed / rejected
I changed the color palette and font because it looked a little plain the way it was. I kept the overall information but changed the aside to go next to the cards rather than below them. I also added an extra card because the AI only put three on the layout.
## Dig deeper
I dug deeper on minmax() and learned that it sets a minimum and maximum size for columns. It won't be able to shrink below its minimum size. Within this feature, you can put 1fr, which makes it grow to a fraction of the leftover space. 

## Open questions
N/A