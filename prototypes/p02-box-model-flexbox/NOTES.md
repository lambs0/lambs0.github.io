# NOTES — <Boxmodel/flexbox Prototype>

## Intent
What I built, for whom, and why (2–3 sentences).
I built another recipe guide for people wanting to make some easy recipes to give them an easy way to access the recipes. People should be able to clikc on different links that take them places within the page to different recipes.
## AI use
I used the free Copilot in VS Code. I gave it my intent and the done list. I told it I wanted to make a new recipe page but with different recipes and six instead of four. I also asked it to provide links to a site about recipes so people could view more recipes.
## Accepted / changed / rejected
I kept the overall layout and the size the AI gave for the cards because they seemed to be big enough.
I made it so the cards will go from one coalumn on a more narrow window to three if the window is wider with flex and flex-wrap with no media queries. The browser will move a card to the next row if there isn't enough space on the row it's currently on. When there's extra space on a card's row, it will grow to fill in the space.
There are three spacing sizes that are reused: 0.5rem, 1rem, and 1.5rem. They affect things like the margins, padding, and gaps so even just changing one of them can change a lot on the page.
## Dig deeper
I dug deeper on CSS margin and learned that it sets how big the margin is for all four sides of an element.The bigger the percentage is, the larger the margin and therefore more squished the element is.
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/margin
## Open questions

I don't 