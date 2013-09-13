# Pivotal Tracker Mac App

I've been using this mac app on my own to browse Pivotal. It's
especially useful if you're managing a project, because you can see
everything at a glance.

Made with [MacGap][mg].

## Features

- Runs the PT site in a Mac app
- Full-screen mode

### Roadmap

- Hotkeys for adding a story and tab-switching for projects.
- Minimal menu system
- Notifications for new story assignments

## Setup

Download this repo:

    $ git clone https://github.com/tubbo/PivotalTracker.app.git

Install dependencies:

    $ bundle install

Install the app to ~/Applications:

    $ rake install

You can `mv` the app to `/Applications` to share it with other users on
your machine, or just leave it where it is. OS X will pick up `.app`s in
**~/Applications** by default.

## Contributing

Please submit a Git or Github pull request.

[mg]: http://github.com/maccman/macgap
