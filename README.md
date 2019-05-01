# My Dev Environment

Notes on setting up my development environment

## Mac

#### iTerm
[see iterm2] (iterm2/)

#### Oh My Zsh
https://github.com/robbyrussell/oh-my-zsh

#### Brew
- Install brew from https://brew.sh/

#### Java
(Borrowed from https://stackoverflow.com/questions/52524112/how-do-i-install-java-on-mac-osx-allowing-version-switching)

##### Install a JDK
`brew tap homebrew/cask-versions`
`brew search java`
`brew cask info java`
`brew cask install java (java8, java9, java10, java11)`

##### Switching JDKs
`/usr/libexec/java_home -V`
`/usr/libexec/java_home -v 12`

###### Setting JAVA_HOME
`export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk-12.jdk/Contents/Home`

###### Alias to switch versions
```
export JAVA_8_HOME=$(/usr/libexec/java_home -v1.8)
export JAVA_9_HOME=$(/usr/libexec/java_home -v9)
export JAVA_10_HOME=$(/usr/libexec/java_home -v10)
export JAVA_11_HOME=$(/usr/libexec/java_home -v11)
export JAVA_12_HOME=$(/usr/libexec/java_home -v12)

alias java8='export JAVA_HOME=$JAVA_8_HOME'
alias java9='export JAVA_HOME=$JAVA_9_HOME'
alias java10='export JAVA_HOME=$JAVA_10_HOME'
alias java11='export JAVA_HOME=$JAVA_11_HOME'
alias java12='export JAVA_HOME=$JAVA_12_HOME'
```

#### Installing thefuck
Correcting previous console command. Useful for pushing new branches when using git
https://github.com/nvbn/thefuck

#### Docker
https://docs.docker.com/docker-for-mac/install/

#### Slack
https://slack.com/downloads/mac

#### AWS CLI
https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-install.html
