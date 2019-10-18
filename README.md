# Building a Rails App with Valkyrie

A giuded installation and build of a Rails application using the Valkyrie gem
as its database persistence layer.

The tutorial was written on MacOS, so some of the command examples will be
for that operating system, but most of the commands will be applicable on
any Unix-type OS.

## Requirements

* Ruby 2.6 or later
* Rails 5.2 or greater (6.0 is recommended)
* Git
* bundler 2.0.2 or greater
* Postgresql 9.2 or later (for jsonb support)

## Installing Requirements

    gem install rails bundler
    brew install postgresql

## Syllabus

* an introductory overview of Valkyrie via the [command line](command-line.md)
* a 2-part walkthrough of building a simple repository-like application in Rails
    * [Part 1: Building a Book Repository](part-1-book.md)
    * [Part 2: Adding Pages to Books](part-2-pages.md)

