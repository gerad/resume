# Resumatic

An open source resume you can host on github pages with a click.

![](https://cloud.githubusercontent.com/assets/27563/4994202/8f87b14a-696b-11e4-8bfd-15befcc4cef0.png)

Demo: <http://gerad.github.io/resume>

## Usage

1. Fork this repository to your github account.
2. Edit `index.html` to add your personal details at the top.
3. See your resume at http://{username}}.github.io/resume

## Why?

I just wrapped up a project. While looking for what's next I got feedback from several recruiters that pointing people at a LinkedIn profile was not enough. Everybody wanted a separate resume.

## Features

* **Modern** - Uses bootstrap and angular, so you can be one of the cool kids.
* **Mobile Friendly** - Looks great on mobile, desktop, and everything in between.
* **Print Friendly** - Prints to a two-page resume, just like the recruiters want.
* **Opinionated** - Uses a project- and skill-based approach that works great for technical resumes.
* **Tested** -  Designed based on feedback from recruiters and hiring managers.
* **Delightfully Polished** - Just look at that cool header transition.

## Developing

1. Check out the `master` branch (e.g. `git checkout master`).
2. Start an http server that servers `index.html` (e.g. `npm install -g http-server && http-server`).
3. Make tweaks to the html, css, and js files.
4. Commit them.
5. Run `./build`
6. The changes will automatically be committed to the `gh-pages` branch. (You will need to push the changes to publish them).

## Helping

As you can tell, I'm not a designer. Design feedback and advice appreciated.

Pull requests also appreciated. In particular, the build script is kinda half-baked.

## License

MIT

But if you link to <http://gerad.suyderhoud.com/> in your README, that'd be cool.
