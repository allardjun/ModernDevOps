# Modern DevOps for Systems Biologists

Course materials for a graduate course in the Mathematical, Computational and Systems Biology program.

**[Open the course website →](https://allardjun.github.io/ModernDevOps/)**

The website is the place to read the course.
This repository is the place to *work* in it.

## Activities

Click one to open it as a notebook you can type in.
Every activity is also on the website as html, pdf, tex and markdown.

- [Activity 1: Working with your past and future self](docs/PS1_working-with-yourself.ipynb)
- [Activity 2: Let’s write a story!](docs/PS2_working-with-a-team.ipynb)
- [Activity 3: Who killed Suzy?](docs/PS3_talking-with-the-machine.ipynb)
- [Activity 4: Working with the world](docs/PS4_working-with-the-world.ipynb)

Two of the activities do not live here at all.
They have repositories of their own, because working in someone else's repository is the thing they are teaching — the website links to those directly.

## Somewhere to work

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/allardjun/ModernDevOps)

That button builds a Linux machine in the cloud with git and a shell already on it, and opens it in your browser.
Give it a few minutes the first time.

This is not a convenience — for most of this course it *is* the material.
Units 1 to 3 are about talking to a machine like that one: committing, branching, pushing, and getting around a filesystem from a prompt.
A Codespace is a real one you cannot break in any way that matters, and throwing it away and starting again costs nothing.

Open a terminal in it with **Terminal → New Terminal**, or `` Ctrl-` ``.

### On your own machine instead

Everything in this course runs on a laptop, and by the end you should prefer it that way.
You need `git` and a terminal:

```sh
git clone https://github.com/allardjun/ModernDevOps.git
cd ModernDevOps
```

macOS and Linux have a terminal already.
On Windows, use [Git for Windows](https://gitforwindows.org/) or WSL — not PowerShell, since the course's transcripts are bash.

### By downloading a single activity

Every activity page on the website has an **ipynb** link.
Download it and open it in whatever you already use.

## The course is language-agnostic

Where an activity says "write code", write it in whatever language you intend to use for the rest of your degree — Matlab, Python, R, Julia — and be ready to explain your choice to someone who picked differently.
Nothing here installs a language for you, and nothing here runs your code for you.
That is deliberate: choosing and installing your own environment is Unit 4.

---

*This repository is generated.
Its source lives in a separate repository and everything here is rebuilt from that, so edits made here are overwritten on the next publish.
Anything you change while working is yours locally, but do not expect it to survive a `git pull`.*
