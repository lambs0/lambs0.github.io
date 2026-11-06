# NOTES — <Spark 6>

## Intent
I built a site with a collection of recipes on cards: drinks, main courses, and desserts. This is for people who want some recipe ideas. The cards provide people a quick overview of the information so they don't have to scroll down a whole page to find one recipe they're looking for.
## AI use
I used the free Copilot within VS Code. I told it to create a new spark folder with a NOTES.MD and an index.html along with a styles.css document. I gave it my intent of making a page of recipes and the "done" list and then told it to propose a plan for the page. I also told it to add a little more detail to each recipe because they seemed too brief.
## Accepted / changed / rejected
I kept the flex-wrap: wrap the agent used because it helped the cards wrap the way I wanted them to so nothing overlapped or got cut off. I changed the content in the recipes to make them longer because there seemed to be no point "jumping" to a recipe further down the page if all of them are so close together anyway. I changed the color palette because I didn't like the plainness of the one it first proposed.
## Dig deeper
I dug deeper on flex-wrap and learned that it controls the wrap on flex items and you can choose the direction that they're stacked. You can do nowrap (single line), wrap (it can break into multiple lines), or wrap-reverse (the lines are the same as wrap but reverse order). https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/Properties/flex-wrap 
## Open questions
N/A
