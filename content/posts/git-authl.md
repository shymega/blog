---
title: "git-authl: what is it?"
date: 2019-08-09T00:00:00Z
---

I've started a new project which I've called `git-authl`. It's an abbreviation
of `Git-AuthorisationLayer`. Its written in Go, and it aims to be a
single-binary replacement for the clunky Gitolite, which is written in Perl.

The idea, basically, is for a simple, but powerful Git authorisation layer
(although it'd be nice to add support for other VCS systems!) to control
permissions, and hooks. It will also allow Git web UIs to hook into it to
extract metadata, and serve up repositories.
