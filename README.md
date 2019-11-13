# Learning `axe-cli`

Just one of the things I'm learning: https://github.com/hchiam/learning

Reference and more aXe tools: a [YouTube video](https://www.youtube.com/watch?v=jC_7NnRdYb0) also found in [Google Devs docs](https://developers.google.com/web/fundamentals/accessibility/a11y-for-teams#automated_testing).

## Setup

* Install the CLI tool:

```bash
npm install axe-cli -g
axe-cli --version # just to confirm it's actually installed
```

* Get the latest `.zip` or `.tar.gz` driver binaries for your OS by following the links at <https://www.npmjs.com/package/selenium-webdriver#installation>

* Unzip into a folder like Users/your-user-name/bin

* Add this line to .bash_profile: `export PATH="$PATH:$HOME/bin"`

* Confirm driver binaries set up:

```bash
which chromedriver
which geckodriver
```

## Use

* One line. For example, to test `https://www.deque.com`:

```bash
axe https://www.deque.com
```

(It even works on things like `localhost` or `file://.../index.html`.)
