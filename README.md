# bootfiles dotstrap

Dotfiles setup being build thanks to the Internet.

## Usage

	git clone git@github.com:LEI/dotfiles.git ~/.dotfiles
	~/.dotfiles/bootstrap install

	dot --help

### Installer

- Prompt for git credentials
- Link repository dotfiles, .vim & bin folders to home.
- Apply Terminal window settings
- Set defaults (only OS X: init/.osx)
- Install dependencies via Homebrew
- Download application via Caskroom
- Link Preferences.sublime-settings

### Add a dotfile to your home

Just move the dot at the end of the name and place it in a directory before bootstraping

## Inspiration

- Mathias Bynens [@mathiasbynens](//github.com/mathiasbynens) [OS X dotfiles](//github.com/mathiasbynens/dotfiles)
- Zach Holman [@holman](//github.com/holman) [OS X dotfiles](//github.com/holman/dotfiles)
- Nicolas Gallagher [@necolas](//github.com/necolas) [OS X dotfiles](//github.com/necolas/dotfiles)
- Ben Alman [@cowboy](//github.com/cowboy) [OS X / Linux dotfiles](//github.com/cowboy/dotfiles)
- Ryan Bates [@ryanb](//github.com/ryanb) [OS X / Linux dotfiles](//github.com/ryanb/dotfiles)
- [tejr](//github.com/tejr/dotfiles)
- [gf3](//github.com/gf3/dotfiles)
- [rtomayko](//github.com/rtomayko/dotfiles)
- [mikemcquaid](//github.com/mikemcquaid/dotfiles)
- [nicck](//github.com/nicck/dotfiles)
- [paulirish](//github.com/paulirish/dotfiles)
- [travi](//github.com/travi/dotfiles)
- [sitaktif](//github.com/sitaktif/dotfiles)
- [zenorocha](//github.com/zenorocha/dotfiles)
- [gist/zenorocha/7159780](//gist.github.com/zenorocha/7159780)

## TODO

- opts undot silent
- Sync-home (licences, ssh_config...) CLI [Dropbox](http://www.dropboxwiki.com/tips-and-tricks/using-the-official-dropbox-command-line-interface-cli)
- Ruby, compass.. http://www.npmjs.org/package/dotfiles
- https://github.com/thoughtbot/rcm
- http://dev.svetlyak.ru/dotfiler-en/
- [HomeSick](http://technicalpickles.com/posts/never-leave-your-dotfiles-behind-again-with-homesick/)
