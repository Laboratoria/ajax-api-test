# Music Database Exercise - Web API

## Overview

Your company runs an extensive music database and is in the process of improving the user experience.

The system currently supports adding and deleting music records (songs) via a front-end UI controlled by JavaScript (jQuery). The system is built using a web framework (Rails) + SQLite3 DB + Ruby enabling a db-driven webserver.

## Running application

To run this project you must be sure you have [ruby](https://www.ruby-lang.org) installed on your OS. In order to test whether you have it installed or no, you can run ```ruby -v``` from your terminal and you should see your ruby version, if you get an error it means you haven't installed or haven't installed correctly.

To install all dependencies this project uses, you should run ```bundle install``` command from your terminal on the root of your project.

This project has a model to store music records. In order to start rails webserver without getting errors, you should run ```rake db:migrate``` command, this will create a SQLite database on your development environment.

Finally, you should run ```rails server``` or ```rails s``` command.
