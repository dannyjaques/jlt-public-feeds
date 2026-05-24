# jlt-public-feeds

Public-facing RSS feeds + images for Sociamonials ingestion. Managed by the `jlt-publisher` skill in [jlt-aios](https://github.com/dannyjaques/jlt-aios).

## Contents

- `feeds/jlt-travel-collection-fb.xml` — RSS 2.0 feed Sociamonials polls. New `<item>` per scheduled FB post.
- `images/` — FB hero images referenced by feed enclosures. One WebP per published pack.

## Sociamonials configuration

Source URL: `https://raw.githubusercontent.com/dannyjaques/jlt-public-feeds/main/feeds/jlt-travel-collection-fb.xml`

Polling interval: 30 minutes recommended. Map `<pubDate>` to scheduled post time.

## Do not edit manually

Files in this repo are written by automated publisher runs. Manual edits will be overwritten on the next run.