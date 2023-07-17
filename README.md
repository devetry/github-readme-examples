# Making READMEs more pleasing to... read.

I've recently been cycling through updating README.md to multiple projects of my own and my client, and found a few updates to Github's
version of Markdown that have, at least aesthetically, made reading a readme more informative and enjoyable, for myself.

The first, is being able to block notes and warnings in their own blocks

## Note and Warning Blockquotes

To accomplish these, you begin a new Blockquote `>` with either **Note** or **Warning**
the complete the contents of your block quote. Github's Markdown will then style them to the following

> **Note**
> 
> If you're experiencing problems with A, do B

> **Warning**
> 
> Please be careful when you run process X. It runs against production and you might accidentally delete the whole SQL databse.

As of the latest revision, only Note and Warning are supported.

## Copy to clipboard from code snippets

Another item they added back in 2021, is the ability to copy contents of a codeblock to your clipboard.

There are no changes in how you write your code snippet, it just adds it below, like shown:

```bash
npm install @doman/library-name
```

> **Note**
> Because we can now copy the contents of the above, some directives had authors adding `$` to indicate this was a command.
> Now that we can copy and paste, we should just write the command we would write it to execute in our terminal instances so anyone
> copying the command will be able to run it just by pasting it in.

These have been the two I've most recently found and really enjoyed using to enhance the experience of reading a repository's reaadme file. If you know of any others, feel free to let me know and I can add them to this file.
