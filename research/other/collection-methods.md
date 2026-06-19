# Collection Methods

Collected on: 2026-06-19  
Topic: YouTube content strategy for B2B SaaS

## Tools Used

- Codex web search for expert discovery and public LinkedIn/post lookup.
- `youtube-transcript-api` for YouTube caption retrieval where transcripts were accessible.
- `yt-dlp` for YouTube metadata such as title, channel, upload date, duration, and URL.
- YouTube RSS feeds for channel recency checks when a channel ID was available.
- Manual review of public LinkedIn pages, podcast pages, agency pages, and article pages.

## Transcript Handling

The assignment requested YouTube transcripts via API. I retrieved captions for the initial batch of relevant YouTube videos with `youtube-transcript-api`, then stored transcript-derived research notes instead of full raw transcripts. This keeps the repository useful for later synthesis while avoiding wholesale reproduction of copyrighted video text.

The API returned usable captions for videos from Samu Kovacs, Sam Dunning / Breaking B2B, Ali Schwanke interviews, Tom Whatley / Grizzle, Hansel Alvarez, and Justin Simon's Breaking B2B episode. After the first batch, YouTube began returning an IP-block message for additional transcript requests, so later items are documented through metadata, LinkedIn posts, podcast notes, or public article pages.

## LinkedIn Handling

LinkedIn post files are manual collections from public LinkedIn pages discovered through search. Each file records:

- post URL
- public date label observed on 2026-06-19
- short summary
- relevance to the future playbook

Where a post page exposed only snippets or comments, I recorded the accessible portion and did not infer unavailable details.

## Why These Sources Are Useful

The collection intentionally mixes:

- YouTube-first SaaS practitioners who run channels or agencies
- B2B SaaS marketers using YouTube together with SEO/AEO and LinkedIn
- content distribution experts who explain how long-form video becomes many buyer touchpoints
- video podcast operators who treat shows as a repeatable content engine

That mix should support a later playbook that covers strategy, content ideation, packaging, production workflow, distribution, and measurement.
