# Make a commit
When you make a commit, I want you to follow the rules shown below.

- On the first row, you should mention what was changed, and it should be short, neat, and easy to understand.
- From the second row, you should write about why was that change needed, and if you do not understand the reason, you should leave it blank for the user to write it.

The first row should be formatted like this.

```
prefix: Details
```

The prefix should be written like this.
- `feat:` A new feature
- `fix:` A bug fix
- `docs:` Documentation only changes
- `style:` Changes that do not affect the meaning of the code (formatting, missing semi-colons, etc)
- `refactor:` A code change that neither fixes a bug nor adds a feature
- `perf:` A code change that improves performance
- `test:` Adding missing or correcting existing tests
- `chore:` Changes to the build process or auxiliary tools and libraries


# Warning!
- You should generate a commit message on a file, show it up on the editor, and let me write additional information(Refer to the description below to look at how to do it).
- Never include your information.
- You should generate message only based on staged files.

Always make sure to follow the things written in warning.

# How to create a commit message file
First, execute `git commit`. That starts up the editor.

Next, write your message on `.git/COMMIT_EDITMSG`.

I will approve the changes with my hands(By doing this, you get the right to move, so you don't have to wait for me to say that I'm done writing it).

The message will be committed.

This is what you have to do.

Make sure to complete committing the changes.

DO NOT PUSH.
