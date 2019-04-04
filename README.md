# BootSass

A simple Bootstrap Sass framework using Gulp 4, JavaScript, task automation and linting. With thanks to [Ben Spencer](https://github.com/spenno).


## Installing

### Step One: Windows

1. On a Windows computer, visit the [Node JS website](https://nodejs.org/en/download/) and download the "Windows Installer".

2. Run the installer, accepting the licence agreement, keeping all the default options.

3. Restart your Computer.

4. Click the Start Button, type "cmd" to search your applications and open "Command Prompt".

5. Proceed to Step Two.

6. Issues? [Visit this website](https://www.tutorialspoint.com/gulp/gulp_installation.htm)

### Step One: Mac

1. On a Mac, open your app launcher and type "Terminal" to search your applications and open "Terminal".

2. Install the Xcode Command Line Tools by entering the following code into the terminal and press enter:

```
$ xcode-select --install
```

3. If you've recently installed Xcode you might need to launch it and accept the terms and conditions.

4. Install Node.js by running the Node Version Manager (NVM) install script (ff you're using [Z shell](https://www.zsh.org/), replace `bash` with `zsh` in the above install script):

```
$ curl -o- https://raw.githubusercontent.com/creationix/nvm/master/install.sh | bash
```

5. Restart your Mac.

6. Proceed to Step Two.

### Step Two (Windows and Mac)

1. Using the Terminal/Command Prompt type the following code and press enter to check what version of Node.js is installed:

```
$ nvm list
```

2. Check what the latest stable version of Node.js available for download:

```
$ nvm ls-remote --lts | grep Latest
```

3. If the versions differ, type the following code to install to the latest version:

```
$ nvm install --lts
```

4. Now that you've installed the latest version, check that the latest version is being used:

```
$ node -v
```

5. Now update the Node.js Package Manager, NPM:

```
$ npm install -g npm
```

6. Install the Gulp command line utility:

```
$ npm install --g gulp-cli
```

7. Install all of BootSass's required packages:

```
$ npm install
```


## Usage

1. Run 'gulp' to start in development mode and watch for Sass and JavaScript changes.

```
$ gulp
```

2. Run 'gulp prod' to minify CSS and JavaScript ready for production.

```
$ gulp prod
```


## Built with

* [Plinth](https://github.com/spenno/plinth) - A solid and simple base for front-end web projects using Sass, JavaScript, task automation and linting
* [Sass Boilerplate](https://github.com/HugoGiraudel/sass-boilerplate) - A boilerplate for Sass projects
* [include-media](http://include-media.com/) - Simple, elegant and maintainable media queries in Sass
* [Gulp](http://gulpjs.com/) - Automate and enhance your workflow
* [Stylelint](https://stylelint.io/) - A mighty, modern linter that helps you avoid errors and enforce conventions in your styles.
* [JSHint](https://jshint.com/) - Community-driven tool that detects errors and potential problems in JavaScript code
