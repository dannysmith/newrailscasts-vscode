# New RailsCasts Theme for VSCode

A theme for VS Code. The code and structure was lifted from Wes Bos' [awesome Cobalt2 theme](https://github.com/wesbos/cobalt2-vscode/), and consiquently has a lot in common. The color scheme is loosley based on [Ryan Bates](https://twitter.com/rbates)' railscasts theme for TextMate.

# Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `DannySmith`
3. Click **Install** to install it
4. Click **Reload** to reload the your editor
5. File > Preferences > Color Theme > **DannySmith**
6. Optional: Install [this plugin](https://github.com/be5invis/vscode-custom-css).
7. Optional: Create a `.vscodestyles.css` in your home directory for custom CSS.
8. Optional: Use the recommended settings below

## Recommended User Settings

```js

}
```

## CSS Hacks For a better editor
Some things in VS code can't be controlled by settings, but you can install [this plugin](https://github.com/be5invis/vscode-custom-css), then make a file on your computer that will hold your custom CSS, I've followed Wes' advice and created one in my home directory called `~/.vscodestyles.css` and then put this everything in [custom-css.css](https://github.com/wesbos/cobalt2-vscode/blob/master/./custom-css.css) in it.

Once done, open your command palette and select enable **custom CSS and JS**

Finally reload your editor and the Custom CSS should be working.

## Contributing
This is a bit weird, but to get some sort of live feedback for when editing a theme. Please let me know if you have a saner way of doing it

1. Open this repo in your terminal and type `npm install`
1. Start to watch for change on the repo with `npm start` - this runs a nodemon task for you and will automatically recompile any changes
1. Open this repo in VS Code
1. Open your command palette and hit type **VSIX**. Select the one that says **Extensions: Install from VSIX...`
1. Load the VSIX file that was created a few steps back
1. Set your editor to use _this_ Cobalt2 theme - it might help to change the name in package.json to something like "Cobalt2 Dev" so you can differentiate from the Cobalt2 you've installed from the marketplace. If you get confused, just delete all traces of Cobalt2 and then load the VSIX.
1. Go to the debug sidebar `View → Debug`
1. Press the green arrow beside "Launch Extension"
1. This will then open a second window.
1. Make a change, and then hit the refresh button on your debug toolbar - this is in your first editor - not the one that poped open.
1. Wait a sec, your changes should now be reflected!

Whew. Again, if you have an easier way to style these things, let me know!

## Thanks

Wes and Ryan, obviously.
