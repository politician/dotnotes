# .notes

Finally, you can commit the uncommitable 😱

## Why?
The life of a programmer is full of **interruptions**: You have to jump from urgent projects to even more urgent projects and your side projects had 3 weekends of commits over the last 4 years.
When you come back to your code, wether it's a work project or a side project, it takes you 1/2 a day to even find out where you left it and another 1/2 a day to understand where you were going with that logic of yours. If this isn't your code, double those numbers.

## Solutions
- Try to immerse yourself in the logic you or someone else had at the time
- Look at code comments (if there are any)
- Look at previous commits to understand the evolution of the code
- Use .notes

## What are .notes?
They are developer notes, as close to the code as possible so they're easily accessible when you come back to a project after a few days, months, years.
You shouldn't care about styling your notes, they are meant to be a raw dump of your mind. They are here to help you, not get in your way! Although, try to write intelligible notes as much as possible, your future self will thank you for that!

- Got an idea to refactor your code but don't have time to implement it? Add it to your notes
- Got a piece of code you worked on but finally didn't commit and you might need it for later? Add it to your notes
- Got a small todo list for yourself to implement your logic? Add it to your notes
- Got to jump on another project or got to leave work right now? Add to your notes what you were doing and about to do

.notes evolve with your code, you can keep adding them but it is recommended to delete notes not relevant anymore so they are easier to ingest when you come back to your code.

You can use whatever format you want to store and write your notes. 

It is important to understand that your notes are primarily meant for you. You are totally allowed to write stupid stuff in your notes. **No other developer should criticize/judge/comment what is inside .notes and no coding style apply to .notes.**. And remember: **What happens in .notes stays in .notes!**

That said, if someone else has to work on your code, your notes might be of great help for them too.

## How to use .notes?
- Create a `.notes` folder at the root of your repository
- Each developer who wants to write notes can either create a folder or a file (of any extension) in the `.notes` folder. It is best practice to use the username used for commit messages as the name of the file/folder.
- Commit the `.notes` folder (don't add it to .gitignore)

### Example
My username on GitHub is `incorrupt`. So for a given GitHub repository, the structure would be:

```
root
│ README.md 
└─.notes
  │ incorrupt.txt
```

If another developer works on the project, s?he could decide to use the folder structure for h(is|er) notes

```
root
│ README.md 
└─.notes
  │ incorrupt.txt
  └─otherdev
    │ todo.md
    | somefile.csv
```
