# wikipedia-random-to-facebook
Using Mac's automator to comment random pages from wikipedia on facebook.

# Rationale

A friend told me she would start doing one ab for every comment posted on
her facebook post. I want to see those abs burning.

## How does it work?

- It opens https://en.m.wikipedia.org/wiki/Special:Random - a special page
which always points to a random article.
- Removes some text to make it easier to paste
- Chews the text a bit (applescript magic)
- Types the text into the comment
- Press shift-tab (my safari ends up somewhat in the avatar shit after pasting text)
- Presses enter
- Closes tab


## How to use

Clone this repo, open the folder on automator, and change the "Get specified URLS" to the url of a comment: something like this: https://www.facebook.com/user/posts/NUMBER?comment_id=NUMBER&reply_comment_id=NUMBER&notif_id=NUMBER&notif_t=comment_mention&ref=notif

- You have to obviosuly figure the comment url yourself.
