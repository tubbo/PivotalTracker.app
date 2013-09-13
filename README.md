# Pivotal Tracker Mac App

I've been using this mac app on my own to browse Pivotal. It's
especially useful if you're managing a project, because you can see
everything at a glance.

Made with [MacGap][mg].

## Features

- Runs the PT site in a Mac app

## Quick Install

Don't feel like building from source? You don't have to! Run this little
command:

```bash
$ mkdir -p ~/Applications && \
  curl 'http://f.psychedeli.ca/PivotalTracker.app.tar.gz' -o pt.tar.gz && \
  tar -zxvf PivotalTracker.app.tar.gz ~/Applications
```

## Setup

Download this repo:

    $ git clone https://github.com/tubbo/PivotalTracker.app.git PivotalTracker

Install dependencies:

    $ cd PivotalTracker && bundle install

Install the app to ~/Applications:

    $ bundle exec rake install

You can `mv` the app to `/Applications` to share it with other users on
your machine, or just leave it where it is. OS X will pick up `.app`s in
**~/Applications** by default.

## Contributing

Please submit a Git or Github pull request.

### Roadmap

- Hotkeys for adding a story and tab-switching for projects.
- Minimal menu system
- Notifications for new story assignments


[mg]: http://github.com/maccman/macgap
