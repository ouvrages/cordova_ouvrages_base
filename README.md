Requirements
============

* Apache Cordova
* Ruby
* Bundler
* npm

Setup
=====

Clone the application:

    git clone https://github.com/ouvrages/cordova_ouvrages_base.git your_app_name

Install the gems:

    cd your_app_name
    bundle install --jobs 4

Install the emulator:

    npm install -g ripple-emulator

Development
===========

Run the middleman server:

    bundle exec middleman

Run the emulator:

    ripple emulate --remote http://localhost:4567/
