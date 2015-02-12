# Lab Rules and Hints 

  This is a collection of rules and hints (on various different subjects) for members of the COMBINE lab. Others may also find them useful.
  
Making use of version control
=============================

GitHub has generously provided the COMBINE lab with an organization account.  This gives us the ability to create a significant number of private repositories as well as an unlimited number of public repositories.  This is a tremendous resource, and I am adamant that we make use of it.  This means that every project you work on should have a GitHub repository under the COMBINE lab origanization.  This repository should contain all of the code (main source code, scripts, etc. --- but not data) for the project.  Git is built around a commit-early / commit-often philosophy, and you should adhere to that.

Useful Languages, Libraries and Packages
========================================

Whenever possible, avoid re-inventing the wheel (the argument, for another day, about minimizing dependencies aside). To help achieve this end, I'd like to keep a list of languages, libraries, tools and packages that we find *useful* and *efficient*.  I propose to categorize these first by their function, and then by the language in which they're made available (if e.g. they are libraries).

General genomics tools
----------------------
 * K-mer counting & de Bruijn graph construction
  + [Genome Assembly & Analysis Tool Box (GATB)](http://gatb.inria.fr/tutorials/) --- a very nice C++ library for        general tasks such as k-mer counting and de Bruijn graph construction and traversal.
