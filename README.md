# Homebrew-custom

This tap provides Homebrew formulae for various packages that need to be held back or are not working in the core repository or other custom taps.

## Installing Homebrew-custom Formulae

Just `brew tap gunzy83/custom` and then `brew install <formula>`. You only need to tap the repository once.

Or, if you would like to install the latest development release:

```
brew install --HEAD <formula>
```

You can also install via fully qualified name:

```
brew install gunzy83/custom/<formula>
```

or URL:

```
brew install https://raw.githubusercontent.com/gunzy83/homebrew-custom/master/<formula>.rb
```

## Troubleshooting

First, please run `brew update` and `brew doctor`.

Second, read the [Homebrew Troubleshooting Checklist](https://github.com/Homebrew/homebrew/blob/master/share/doc/homebrew/Troubleshooting.md#troubleshooting).

**If you don't read these it will take far longer to help you with your problem.**

## More Documentation

`brew help`, `man brew` or check the [Homebrew documentation](https://github.com/Homebrew/homebrew/tree/master/share/doc/homebrew#readme).

## License

Code is under the [MIT license](https://github.com/gunzy83/homebrew-custom/tree/master/LICENSE.txt).
