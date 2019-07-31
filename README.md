# ground-bnb-rails

A clone of air-bnb, built in Rails. test.

Initial Installation
--------------------
Following - https://gorails.com/setup/osx/10.14-mojave#overview

1) run $(gem install rails -v 6.0.0.rc1)    // installs Rails, version 6.0.0.rc1
2a) run $(brew install rbenv ruby-build)    // installs rbenv
2b) run $(rbenv rehash)                     // tells rbenv to see rails executable
2c) run $(rails -v)                         // confirms that rails is installed, with the right version
3) run $(brew install sqlite3)              // installs sqlite3
4) run $(brew install postgresql)           // installs postgres
5) run $(sudo installer -pkg /Library/Developer/CommandLineTools/Packages/macOS_SDK_headers_for_macOS_10.14.pkg -target /) // Possibly needed to install gems requiring C extensions, such as pg and nokogiri
6) run $(rails new groundbnb -d postgresql) // creates the rails app folder
7) run $(cd groundbnb)                      // move into application folder
8) run $(rake db:create)                    // creates the databases
9) run $(rails server)                      // starts server
