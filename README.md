# Wikimedia Emoji Bot

[![Build Status](https://travis-ci.org/ch3nkula/Wikimedia-Emoji-Bot.svg?branch=master)](https://travis-ci.org/ch3nkula/Wikimedia-Emoji-Bot)

The source code for the Wikimedia Emoji Bot lives here

## Configuration

1. Clone project:
  ```shell
  git clone https://github.com/ch3nkula/Wikimedia-Emoji-Bot.git
  ```

2. Install Need Package Manager/Management (NPM) on Mac OS X:
  ```shell
  brew install npm
  ```

  Will add for other systems later here.

3. Install dependencies for the project:

  ```shell
  npm install
  ```

4. Copy the example `.env` file:

  ```shell
  cp .env.example .env
  ```

5. [Get credentials for your bot](https://dev.twitter.com/) and complete the `.env`

## Usage

### To post a status

```shell
npm run status
```

### To reply to replies

```shell
npm run reply
```

### Testing

```shell
npm test
```

## Contributing

Emoji additions, bug reports, fixes, and new features are welcomed. If you'd like to contribute code, please:

1. Fork the project

2. Start a branch named for your new feature or bug

3. Create a Pull Request

## Forked / Built on

This project is originally built on the [NYPL Emoji Bot project](https://github.com/lolibrarian/NYPL-Emoji-Bot project). Initial credits go to: Lauren Lampasone and other contributors for building the NYPL-Emoji-Bot.
