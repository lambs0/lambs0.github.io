# NOTES — <assignment name>

## Intent
I built a site for a book club meeting where people can enter their information and what they'll bring. This would be for people in a book club who need to know how to RSVP to a meeting on a laptop. This site would give them an easy way to RVSP.
Prediction: 
The vanishing labels: I think <label for> will help the labels stay visible.

The radio buttons with no question: I think <fieldset> and <legend> will be the way radio buttons are grouped under questions.

The red-from-the-start fields: I think :user-invalid will fix this.

The color-only error: I think :user-invalid and .hint::before will make it so the color isn't the only error. (There will be a hint as well.)

What it used: 
I was right that the <label for> element helped the labels stay visible because it provides text and each label matches its section.

I was right that <fieldset> and <legend> put radio buttons with their questions because they group them together.

I was right that :user-invalid makes the boxes not be red because it makes it so they only turn red once the user has interacted with them and failed to enter the necessary information or the information is in the wrong format.

I was kind of right about :user-invalid and .hint::before not being the only sign of an error. It actually uses aria-describedby, which tells a screen reader which hint text will go with which field. This way it's able to switch between the normal text "use an address like reader@example.com" and "check this: enter an email address like reader@example.com"

## AI use
I used the free AI copilot in VS code. I gave it my intent and the done list and asked for a plan. I then told it to go ahead with the plan.

## Accepted / changed / rejected
I accepted the overall format because it was simple an had the required elements to make the page understandable to users. The radio buttons and checkboxes seemed to work for the items in their lists, so I kept those as well. I changed some of the wording on the form to make it a little less formal.

## Dig deeper
I looked up <legend> and basically learned that it's a caption for the content of its parent, which is <fieldset>
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/legend
## Open questions
Where would the answers for the form go if this were actually set up and how would that work?
