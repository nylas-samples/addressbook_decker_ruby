# Address Book with Decker and Ruby

This project will show you how to Build an old-fashioned agenda using Decker (HyperCard) and Ruby.

## Setup

### System dependencies

- Ruby 3.1.1 or greater

### Gather environment variables

You'll need the following values:

```text
V3_TOKEN = ""
GRANT_ID = ""
```

Add the above values to a new `.env` file:

```bash
$ touch .env # Then add your env variables
```

### Install dependencies

We need to install [Decker](https://internet-janitor.itch.io/decker/purchase)

The download and intall [Lilt](https://github.com/JohnEarnest/Decker)

```bash
$ make lilt && make install
```

Also, we're going to need imagemagick

$ brew install imagemagick

### Install Ruby dependencies

```bash
$ gem install dotenv
$ gem install mini_magick
$ gem install nylas
$ gem install open-uri
```

## Usage

Clone the repository. Go to your terminal and type:

```bash
$ ruby address_book.rb
```
