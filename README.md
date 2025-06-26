123movies‑se.com

A zero‑piracy, all‑convenience alternative to the old 123movies.

“Stop streaming in the shadows—watch in the sunlight.”

What Is This?

A lightweight web directory that points you to legal VOD providers (Netflix, Prime Video, Disney+, et al.) instead of the malware‑infested, DMCA‑dodging clone farm you Googled two seconds ago.

Think of 123movies‑se.com as the IMDb of Where‑To‑Watch—minus the clutter, plus real‑time availability and pricing.



Why Another "123movies"?

Because the brand name is sticky, and the original… well, stuck its users with pop‑ups, viruses, and a nice helping of copyright infringement. This project keeps the convenience but drops the sketch.

Feature

123movies‑se.com

The Other Guys

100% legal links

✅

❌

Region‑aware catalog

✅

❌

API‑driven data

✅

❓

Pop‑up ads

❌

🗑️

Quick Start

# Clone the repo (if you want to self‑host the indexer)
$ git clone https://github.com/your‑org/123movies‑se.com.git
$ cd 123movies‑se.com

# Install dependencies
$ pnpm i

# Spin up the dev server
$ pnpm dev

The public site (https://123movies‑se.com) is already live; self‑hosting is optional for tinkerers.

Tech Stack

Next.js / React 18 – frontend

TypeScript everywhere – because undefined is not a type of happiness

Tailwind CSS – utility‑first, no‑nonsense styling

PlanetScale (MySQL) – serves availability + pricing snapshots

tRPC – end‑to‑end types between server and client

Vercel – production hosting ✨

How It Works

A cron job fetches catalog + pricing data from official platform APIs every 6 hours.

Results are normalized and stored in MySQL.

The frontend stitches region + price info and serves it in ~50 ms.

You click, land on the legal provider, hit play. Creators get paid, karma stays squeaky clean.

Roadmap



PRs welcome! Check CONTRIBUTING.md before hacking.

License

MIT – because you deserve freedom (and we’re not monsters).

Credits

Built with enough caffeine to power a small drone. Maintained by the 123movies‑se.com community. ❤️

# aurel
