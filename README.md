# Random GIF Activity

The purpose of this activity is to write a small web application
that displays a random GIF. We're going to do this in turn: you'll
try to complete some user stories in teams and then Kyle will walk
through completing those stories. These stories are pretty weak 😜,
there's no acceptance criteria and such, sorry.


The user stories are as follows:

1. As a user, I can visit your website and it shows "hello world"
   at the "/" URL.
2. As a user, I can visit your website and it shows "hello world"
   in HTML with a colored background.
3. As a user, I can visit your website and it shows a gif of your
   choosing along with search box and a button that says "reload"
   or similar.
4. As a user, I can put the query "cats" into the search box, and the gif
   that is displayed is changed to be equal to
   `http://giphy-proxy.solutions.656.mba/?q=cats`.

## Hints

1. Create a new, empty git repository in some directory on your computer (or Cloud9)
2. Create a `main.go` file, or similar. You could call it `foo.go`, it doesn't matter.
3. Fill that file with a basic web application like the stater code from the "server-side" homework.
4. Make the "/" URL return HTML instead of just plain text. You could, e.g. use something like
   this

   ```
   html := `<html><h1>This is my rad page!</h1>
   <div>
   <form action="">
   <button type="button>display gif</button>
   </form>
   </div>
   </html>
   `
   ```
   and write that to the HTTP response.
