# NOTES — <assignment name>

## Intent
I built a farmers market site to show what's in season and the hours and location and a table of the vendors for each day. This is for people wanting to visit a farmers market and who are accessing the page on their phone. I built it to make this information more clear and organized on a phone.

Prediction: 
For making the page one column on a phone, I predict that using the base CSS without media queries is how this could be accomplished.

For bringing the sidebar back on a wide screen, I predict that @media (min-width:...) would be the property used to do this.

For keeping the table from pushing the page sideways, I predict that minmax(0, 1fr) will be the way to accomplish this.

What it used: 
It used no media queries and the base layout with grid-template-columns: minmax(0, 1fr) with everything stacked into one column. I was right because I guessed that there would be no media queries used because media queries are better used for changing the layout to a larger width rather than a smaller width.

It used @media (min-width: 45em) I was right with this. The media query gave instructions for how to properly format it at a larger width. The provided minimum width establishes the minimum width that format should be applied at.

I was kind of right for the third one. It did use minmax(0, 1fr), which was what I guessed, but the main reason it didn't push the page sideways was because of the table-scroll{overflow-x: auto;} feature. The table's minimum width lets it be wider than that box when it needs to be.

## AI use
I used the free copilot in VS code. I gave it my intenet of creating a page with information about a farmer's market for people wanting to access the info on their phone. I gave it the "done" list and asked for a plan before having it create the index.html and style.css

## Accepted / changed / rejected
I kept the overall design and layout the agent gave me because it seemed to align with the goal of the assignemnt.
## Dig deeper
I looked deeper into media queries and learned that media queries are used to apply different styles with conditions. They can also target specific media for different HTML elements like <style>, <link>, or <source>
https://developer.mozilla.org/en-US/docs/Web/CSS/Guides/Media_queries/Using

## Open questions

N/A
