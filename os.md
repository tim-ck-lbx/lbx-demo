## GCP Setup
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
sudo vim ~/.bash_profile
i -> insert
source "$(brew --prefix)/Caskroom/google-cloud-sdk/latest/google-cloud-sdk/path.bash.inc"
source "$(brew --prefix)/Caskroom/google-cloud-sdk/latest/google-cloud-sdk/completion.bash.inc"
esc
:wq

echo $PATH

```

## Jupyter Scala
- install spark
```sh
brew install apache-spark
```

- install scala kernal
```sh
pip install spylon-kernel
python -m spylon_kernel install
jupyter notebook

```

## IntelliJ 
- sbt
```
brew install sbt
sbt
clean
compile

```
- IntelliJ
  - [BUILDING A SCALA PROJECT WITH INTELLIJ AND SBT](https://docs.scala-lang.org/getting-started/intellij-track/building-a-scala-project-with-intellij-and-sbt.html)

