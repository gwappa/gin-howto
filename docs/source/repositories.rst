Getting started with "repositories"
====================================

What is a repository?
----------------------

A "repository" refers to a tree of files and directories being managed by
(a sort of) a database. In many cases, the word also refers to a
**revision history of a directory and its contents**.

Gin (and Git) tracks the change history of every file in a repository,
as well as the history of directory structures. In doing so, Gin takes
**a snapshot of the whole tree of files and directories** whenever you order to
do so; this is called a **commit** procedure (this is similar to selecting the
"Save" menu in single files). When a commit is being performed, Gin compares
the content of each file and each directory, and stores the updated version if needed.

Why use repositories?
----------------------

One important aspect of having a repository is that both files and directory
structures are **version-controlled**. You can switch back to any of the previous
states of single files, or any previous snapshots of the repository, at any given moment.

Another advantage of using a **version-control system**, such as Gin or Git,
is that you can **have your whole repository backed up remotely**, including
the whole revision history, onto a server, or onto multiple servers.
The upload procedures can be done at the order of single commits, i.e. only to
the extent the changes are not shared in common, so single uploads do not cost
a lot of time. By having a **remote repository** synchronized with your
**local repository** on your PC, you will have a level of security:
the whole dataset and its revision history can be restored from remote any time,
even when you lose your PC, or your hard drive is broken.
