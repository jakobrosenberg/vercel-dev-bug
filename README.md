Structure

```
dist/
  index.html
  hello.html
  folder/
    index.html
    hello.html
```

When visiting the files in the browser
```
/                     // works
/hello.html           // works
/folder               // works
/folder/hello.html    // works when deployed, but is 404 with "vercel dev"
```
