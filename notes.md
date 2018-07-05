# Unknown Sample (Changeling, shapeshifter)

Parses AS2 feed and pipes to customisable/extensible templates.

Generates a static HTML and JSON site from an `activity+json` or `ld+json profile=..` feed..?

## Config

- Feed or list of feeds to consume.
- Any extensions

## Templates

- Basic templating for default AS2 stuff
- Customise or override templates for an instance

## Core

- Parse all posts out of a [Paged] Collection
- Maybe cache as AS2 JSON files on disk
  - in file structure of URL?
- Generates static html..?

## Bonus

- if it was really smart it'd be able to websub to the feed and regenerate the site when new stuff was pushed.. but I'm not that smart; maybe regular pulls, or something to trigger an update
- wouldn't it be cool if the homepage did JS pulls or received pushes and loaded new stuff at once