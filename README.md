# Sublime Galen

Basic syntax highlighting for the [Galen Framework][galen], a Selenium based e2e testing solution with JavaScript compatibility.

## Installation

### Using [Package Control][pkgcontrol] (*Recommended*)

For all Sublime Text 2/3 users we recommend install via [Package Control][pkgcontrol].

1. [Install][pkgcontrol-install] Package Control if you haven't already
2. Use `cmd+shift+P` (or `ctrl+shift+P` for Windows) then select `Package Control: Install Package`
3. Search for `Galen` and select to install

### Manual Install

1. Click the `Preferences > Browse Packages…` menu
2. Browse up a folder and then into the `Installed Packages/` folder
3. Download the [zip archive][zip], rename it to `Galen.sublime-package` and copy it into the `Installed Packages/` directory
4. Restart Sublime Text

## Usage

Highlighting is automatically enabled for `.spec` files, assuming no other syntax highlighting plugin is installed for that file extension. You should now see "Galen" in the lower right hand corner of Sublime Text when a `.spec` file is open, but in case of a conflict, click whatever syntax label you see there and select "Galen" from the resulting menu.

If you need highlighting for non-js test suites (`.test`), open an issue.

## Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## Credits

**Shawn Erquhart**

- <https://twitter.com/erquhart>
- <https://github.com/erquhart>

## License

Code copyright 2014 Professant LLC. Code released under [the MIT License].

[galen]: http://galenframework.com
[pkgcontrol]: https://sublime.wbond.net
[pkgcontrol-install]: https://sublime.wbond.net/installation
[zip]: https://github.com/professant/sublime-galen/archive/master.zip
