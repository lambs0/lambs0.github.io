# NOTES — Prototype 4: Responsive + Forms

## Intent
I'm building a form for people who want to audition for a musical. The page will give them a way to provide basic information like contact information and their prior experience before going into the audition. They will access this page on a phone.

## AI use
I used the free Copilot in VS Code. I gave it my intent and the "done" list. I also told it to change some of the elements on the page I didn't like. I had it add in an extra question about which character the user is auditioning for as well.

## Accepted / changed / rejected
I kept the basic layout of what the agent gave me because it matched the requirements of the assignment. I added more questions to the form because it was pretty empty. The agent only gave me a few basic questions to begin with, and it didn't feel much like an audition form because of that. The agent added autocomplete, but I wanted to add a few more values than what it provided because I wanted more information to be able to be filled in automatically. I also changed the color to green to fit the vibe of Into the Woods better.

## Dig deeper
I looked deeper into autocomplete and learned that it's basically a way to allow a user agent to fill in information on a site so the user doesn't need to do as much work filling something out.
https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/autocomplete
## Open questions
I don't have any for now.


## Next step: what I tried: 
I tried autocomplete with a bunch of values like given-name, family-name, phone, and email since this would make it so the user wouldn't need to type as much in and make sure everything is more accurate. When I tried it on my phone, it only autofilled my first and last name, not my phone number or email. I realized it was because I had never updated that information in my contact card in my contacts app. Once I added my phone number and email, the autocomplete worked for every possible field in my form. Even though it might not be the perfect solution for every user, I think autocomplete worked well enough for what I wanted to accomplish. I think I'd try the enterkeyhint next. 