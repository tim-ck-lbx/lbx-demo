


## Mac Env Setup
- install homebrew
```sh
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

- install google-cloud-sdk
```sh
brew install --cask google-cloud-sdk
```

- add gcp to $PATH
```sh
source "$(brew --prefix)/Caskroom/google-cloud-sdk/latest/google-cloud-sdk/path.bash.inc"
source "$(brew --prefix)/Caskroom/google-cloud-sdk/latest/google-cloud-sdk/completion.bash.inc"

// check $PATH
echo $PATH

```

