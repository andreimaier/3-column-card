Hi there! 👋 First off, **great job** on implementing the design!

Here are a few _suggestions_ on how you can improve your code:

- try setting `display: flex` to your `body` element

**Syntax**

```
body {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
}
```

This will align your `div.center` vertically.

- add an `alt` description to your `img.qr-code`

For **More info** on when you should use `alt` attributes _and when not to_, check [THIS 📚](https://www.w3.org/WAI/tutorials/images/)

- try to use **Semantic HTML** as much as possible
  - for example by replacing your `div.center` with the `main` element
  - you can also add an `h1` heading, give it a `sr-only` class and _hide it_ using something like this

```
.sr-only {
    position: absolute;
    width: 1rem;
    height: 1rem;
    padding: 0;
    margin: -1rem;
    overflow: hidden;
    white-space: nowrap;
    border: 0;
}
```

I'm also new, but I learned a lot from comments and looking at others' solutions.

If you have any **questions** or **need further clarification**, feel free to reach out to me. I'll do my best to help!

**Keep up the good work!!**
