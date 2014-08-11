# How to Learn Ruby on Rails

## Welcome

People come into learning Rails for all sorts of reasons.  Whether you have been programming for years and want to give development in Ruby a try, or you are a complete coding newbie wanting to see if programming is for you, Rails is a great tool to learn.  Most of the resources in this guide assume no programming knowledge, so more advanced readers may choose to skim the introductory sections of each to learn the particulars of Ruby and Rails.

Before getting started, you should **pick a goal**.  These tutorials will walk you though creating sample applications, but the real test is when you apply the concepts to something unique.  This could be a personal blog, or a site for your dog walking business... whatever!  "Building a better Facebook" is probably a bit ambitious for a first project – keep it simple.  Having a real problem to solve in the back of your mind will help keep you motivated, and allow you to ask yourself "how would this apply to my project?" as you cover each concept.

### For beginners

It's [been said](http://en.wikipedia.org/wiki/Outliers_(book)) that it takes 10,000 hours of practice to master a skill, and programming is a particularly difficult one – if it were easy, there would be a lot more programmers in the world.  There's a quote

> Give someone a program, you frustrate them for a day; teach them how to program, you frustrate them for a lifetime.

Don't be discouraged if it isn't making sense.  There are [*tons* of resources](http://hackerhours.org/resources.html), online and in-person, that can help you get unstuck.

## Introduction

Rails is a framework written in Ruby that helps you build web applications.  There are a lot of concepts packed into that one sentence that may be new to you, but don't worry, we'll get you feeling cozy.

**Ruby** is a programming language.  While there are many others (e.g. Python and Java) and they can mostly accomplish the same tasks, Ruby is a particularly readable and fun one, so you've made a good choice.  If we were building a house, Ruby would be the raw materials: plywood, nails, etc.  **Rails** is a **framework** written in (and for) Ruby – think of this as the frame for the house.  It gives you certain parameters to work within, but you have a lot of flexibility about how the final product turns out.  Just like the frame is built from the same raw materials that will be used to fill in the details of the house, Rails is written in Ruby, and you will add all of your application-specific features using Ruby (and HTML, and CSS, etc.)

Through your instructions in Ruby, Rails will take information stored in a database and send HTML to be displayed to the user in a browser.  Let's get going!

## Installation

* Resources
  * [Install Rails](http://installrails.com)

## Ruby

* Concepts
  * REPL
    * IRB
  * Programming fundamentals
  * How to run scripts
  * Gems
  * `require`
  * Debugging
    * `puts`
    * [Byebug](https://github.com/deivid-rodriguez/byebug)
* Resources
  * [Try Ruby](https://www.codeschool.com/courses/try-ruby)
  * [Ruby Bits](https://www.codeschool.com/courses/ruby-bits)
  * [Programming Ruby (the "Pickaxe" book)](http://pragprog.com/book/ruby/programming-ruby)
  * [Codecademy](http://www.codecademy.com/tracks/ruby)

## Rails

* Concepts
  * Routing
  * Helpers
  * Templating
  * Controller actions
  * Controller filters
  * ActiveRecord->SQL
  * Debugging
    * Rails console
    * Server log
    * Database exploration tools
    * [better_errors](https://github.com/charliesome/better_errors)
  * Asset pipeline
  * Bundler
  * Deployment
    * [Heroku](https://devcenter.heroku.com/articles/getting-started-with-rails4)
  * Authentication
    * OAuth
  * Basic security
    * Not putting sensitive information (e.g. keys) in repository
    * Limiting access to resources
* Resources
  * [The Hartl Rails Tutorial](http://www.railstutorial.org)
  * [The Rails 4 Way](https://leanpub.com/tr4w)
  * [Agile Web Development with Rails 4](http://pragprog.com/book/rails4/agile-web-development-with-rails-4)
  * [Rails for Zombies](http://railsforzombies.org)
