# Theory of Computation

This repository contains my notes on the subject `Theory of Computation` and will
revolve around languages and grammars.

## Introduction to TOC

- **Automata Theory** also known as TOC is a branch of CS and Maths

- It deals with the logic of computation w.r.t. simple machines, referred to as
`automata`

- `Automata` enables scientists to understand how machines compute functions and
solve problems

- Computers have their own languages to communicate and do various tasks

- To understand how they operate, we need to first understand their languages

- TOC focuses on the concept of language rather than a language in particular

- Therefore, this repo will mainly revolve around languages and how they bridge
to different types of machines

## Commit Message Tags

### Topic

If a commit introduces a new topic to the master branch, it will be marked
by this tag

### Add

New files are added (as maybe additional information) but do not represent a
new topic/chapter

### Addendum

Additions to existing files

### Delete

Deletions made to existing files

### Rename

Existing files are renamed

### Correction

Lines in existing files are changed; Corrections similar in nature should be grouped
in a single commit under this tag. For ex. spelling mistakes, logical mistakes
in a topic, etc.

### Update

More than one type of change is made to existing files; An update should contain
a logical change made over file(s) that involves more than one of the above operations.
The individual changes referring to the above tags, if need be, can added to the
body.

### Finish

Marks the completion of the intent of a branch. A pull request for a topic branch
must not be accepted unless one of its commits has this tag. A topic branch is made
to add a topic. A branch made for any other purpose need not contain this tag to
be merged.

### Refactor

Files are internally unchanged but their locations are changed. This can include
renaming parent directories and/or rearranging files into new or existing directories

## Known Issues

## LaTeX

LaTeX doesn't work on GitHub mobile and its syntax in GitHub works differently
than VS Code's built-in preview mechanism. Sometimes, they're outright opposite
of each other. In such cases, VS Code will bear precedence. Therefore, whoever
wishes to use this repository is recommended to clone it locally and use VS Code's
built-in preview feature to read the correct syntax. Alternatively, you can check
out the file in raw form to understand the intended results.
