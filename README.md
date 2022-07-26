# How to collaborate

#### Table of Content
- [Commit message](#Commit%201%20message)
  - [Format](#Format)
  - [Type](#Type)
  - [Subject](#Subject)
  - [Example](#Example)
  - [Example](#Example-1)

# Commit message
## Format 
```
ISSUE-123 {type}: {subject}

{content}

{footer} // optional
```


## Type
```
feat    : New feature
fix     : Bug fix
docs    : Edit documents
style   : Code formatting, When there is no logical change
refactor: Refactoring
test    : Adding test code, test code refactoring
chore   : Editing build script, package manager, etc..
```

## Subject
```
The length of a subject should be less than 50 (recommended)
```


## Footer
```
Resolves: The issue id that this commit fixes
See also: Related issues
... etc
```

## Example
```
feat: Summarize changes in around 50 characters or less

More detailed explanatory text, if necessary. Wrap it to about 72
characters or so. In some contexts, the first line is treated as the
subject of the commit and the rest of the text as the body. The
blank line separating the summary from the body is critical (unless
you omit the body entirely); various tools like `log`, `shortlog`
and `rebase` can get confused if you run the two together.

Explain the problem that this commit is solving. Focus on why you
are making this change as opposed to how (the code explains that).
Are there side effects or other unintuitive consequenses of this
change? Here's the place to explain them.

Further paragraphs come after blank lines.

 - Bullet points are okay, too

 - Typically a hyphen or asterisk is used for the bullet, preceded
   by a single space, with blank lines in between, but conventions
   vary here

If you use an issue tracker, put references to them at the bottom,
like this:

Resolves: ISSUE-13
See also: ISSUE-123, ISSUE-91
```

## Example
