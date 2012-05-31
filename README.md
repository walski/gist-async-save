# Gist Async Save

This makes it possible to save Gists ansychronously without even leaving the edit mode. It is a user script that can run in Chrome and might run in Firefox using Greasemonkey.

## Why?

I took a lot of notes in a Gist and wanted to save it every now and then which is a pain in the ass for long Gists with the whole save/view/edit/find place of last edit rountrip you have to take normally.

## Install

### The Clicky Clicky Way

* Click [here](https://github.com/walski/gist-async-save/raw/master/gist-async-save.user.js) 
* Click on ``Continue`` at the bottom of your browser
* Confirm that the script is allowed to access data from any page you surf at https://gist.github.com/ by clicking ``Add``

### Manually

* Download the gist-async.save.user.js
* Drag the downloaded file to your Chrome browser
* Click on ``Continue`` at the bottom of the browser
* Confirm that the script is allowed to access data from any page you surf at https://gist.github.com/ by clicking ``Add``

## Usage

The scripts adds another save button to each Gist's edit page. You can also save with the keyboard shortcuts:

* ⌘ + s
* Ctrl + s

## Thanks!

The script uses [jQuery UI](http://jqueryui.com/) and [keymaster.js](https://github.com/madrobby/keymaster) which both gets injected into the page by an awesome script I found on [Stack Overflow](http://stackoverflow.com/questions/2588513/why-doesnt-jquery-work-in-chrome-user-scripts-greasemonkey).

**Thank you guys!** :clap: