# go-news-reader

Pure-Go multi-source news & social aggregator — one unified feed.

go-news-reader is a pure-Go (CGO=0) multi-source news & social aggregator with a go-widgets UI: one app, one unified feed, many sources — each behind the same small `source.Provider` contract. Each platform has a standalone pure-Go client library in its own org (go-reddit, go-syndication, go-hackernews, go-newsgroups, go-mastodon, go-lemmy, go-atproto/Bluesky, …); this org's `reader` adds a thin provider adapter per source that maps onto a normalized `source.Item`.

Everything is **pure Go** (`CGO_ENABLED=0`), standard-library-first, and
cross-compiles to every 64-bit Go target. Licensed BSD-3-Clause.

## Repository

<div class="pk-grid" markdown>
<a class="pk-card" href="packages/reader.md"><code>reader</code><br><small>Pure-Go multi-source news/social aggregator (Reddit, RSS, HN, Usenet, Mastodon, Lemmy, Bluesky, Twitter, Instagram, TikTok) with a go-widgets UI. CGO=0.</small></a>
</div>
