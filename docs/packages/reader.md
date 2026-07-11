# reader

A pure-Go (`CGO=0`) multi-source news & social **aggregator** with a go-widgets UI. Subscriptions are `kind:channel` and repeatable — e.g. `reddit:golang`, `hackernews:`, `syndication:https://blog/feed.xml`, `mastodon:#golang`, `bluesky:@user.bsky.social`, `lemmy:technology`, `usenet:comp.lang.go`, `usenet:search:ubuntu`. The `newsreader` CLI can render the merged feed to an image, dump it as JSON, or serve a live view in a browser. Each source is a standalone client library in its own org, wrapped by a thin `provider/<name>` adapter that maps onto the normalized `source.Item`.

## Install

```bash
go install github.com/go-news-reader/reader/cmd/newsreader@latest
```

Requires Go 1.26.4 or newer. `CGO_ENABLED=0`.

## Links

- Source: <https://github.com/go-news-reader/reader>
- API reference: <https://pkg.go.dev/github.com/go-news-reader/reader>

!!! note
    See the module's README for full, up-to-date details.
