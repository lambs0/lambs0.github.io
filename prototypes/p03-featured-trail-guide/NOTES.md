# NOTES — P03 · Featured trail guide

## Intent
I'm building another site for trails near BYU campus for poeple wanting to go on hikes. The page is meant to give them basic information about the different trails. 
## AI use
I used the free Copilot in VS Code. I gave it the overall goal of the assignment and the done list. I also told it I wanted to stick with the same topic as spark seven, the trails in Provo. I also asked it for suggestions on how to accomplish the third part of the assignment of helping people spot the one thing that's worth starting with. I had it give me ideas.
## Accepted / changed / rejected
I accepted the agent's suggestion of trying grid-column: 1/-1 because it made the top card stand out without breaking the page. I changed the cards by adding a link in each of the cards to help users find a location on google maps because it was in the assignment requirements to have links. I also accepted the change in color the AI gave me for the card meant to stand out because I think it draws your eyes to it well, in addition to having it take up more space on the page.
## Dig deeper

I learned more about grid-column: 1/-1 and learned that it tells an element where to begin and where to end on the horizontal part of the grid. 1 is the first defined grid line, and -1 is the last grid line from the end. This is different from just grid-column: span 2, which just takes up two columns rather than stretching all the way to the edge of the grid.
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/grid-column 

## Open questions
I am a little interested to know more about what dense does in grid-auto-flow: dense.

## Beyond: What I tried
I got the suggestion from the AI to try grid-column: 1/-1 and it made the top card take up only one column where it normally took up two in the normal spread out view. In 200% it looked fine and still took up two columns. I thought this was still a pretty good option because it made the top card stand out and the page didn't break. It all looked normal and the main top card stood out even better in the normal full view because it took up two columns. I think I would try the grid-auto-flow: dense. 