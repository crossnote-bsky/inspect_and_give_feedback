# crossnote: inspect and give feedback

The demo page for [crossnote](https://github.com/crossnote-bsky/crossnote_bsky): paste a Bluesky post that crossnote labeled to see the Community Note it was matched to, how each stage scored it, try an edited version, and say whether the match is right.

Live at **https://crossnote-bsky.github.io/inspect_and_give_feedback/**.

The page reads from the labeler's `/demo` API ([`src/demo-api.ts`](https://github.com/crossnote-bsky/crossnote_bsky/blob/main/src/demo-api.ts)). To preview it, run `python3 -m http.server 8000` here and open `http://localhost:8000/` (reads from the live Fly API), or add `?api=http://localhost:8080` to use a local labeler.
