# Random GIF Activity

The purpose of this activity is to write a small web application
that displays a random GIF. The user stories are as a follow.

```
As a user, I can visit the "/" URL and see a button that says
"display gif" on an otherwise empty webpage.

As a user, I can click the button and it takes me to the same page
and shows me a random GIF along with the same button as before.
```

## Getting started

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

5. ....umm...class is starting, you're on your own.
6. Look at [this example](http://polyglot.ninja/golang-making-http-requests/) for how to
   make HTTP get requests. Get your random Gif from my API at
   [http://giphy-proxy.solutions.656.mba](http://giphy-proxy.solutions.656.mba)
