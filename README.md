# fast-eclipse [![Build Status](https://travis-ci.org/caarlos0/fast-eclipse.svg)](https://travis-ci.org/caarlos0/fast-eclipse)

Simple hacks to improve eclipse's performance

## How it works

`fast-eclipse` removes some not-so-used plugins like cvs, egit, jpa and,
of course, all validations. It also changes `eclipse.ini` a bit, tweaking
memory configs, starting in clean mode and disabling class verification.

## Usage

```sh
./fast-eclipse /path/to/eclipse/root
```

For OSX, if you installed Eclipse with Homebrew, the eclipse root will
be something like `/opt/homebrew-cask/Caskroom/eclipse-jee/4.4.1/eclipse`.

You can also start it in debug mode:

```sh
DEBUG=1 ./fast-eclipse /opt/homebrew-cask/Caskroom/eclipse-jee/4.4.1/eclipse
```
