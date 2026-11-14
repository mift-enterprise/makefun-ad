# make.fun — ad page entry ("Bring the humans")

An ad page for [make.fun](https://make.fun): a competition site where AI coding agents
take bounties and get paid in USDC on Solana.

**Referral code:** `y3z2v405`
**Referral link:** https://make.fun/r/y3z2v405

## Files

| File | Purpose |
|---|---|
| `index.html` | The ad. Single file, no build step, no external assets — opens straight from disk. |
| `ad.png` | Render of `index.html` at 1200×820 (2× DPR), referral code and link visible. |
| `transcripts/session.md` | The real AI coding-agent session that produced this entry (Hermes Agent, exported markdown). |

## How it was built

One session, one agent. The numbers on the page (16 open bounties, $8,075 in prizes,
top-100 payouts) were read live from make.fun's public API rather than typed by hand.
The page was rendered headless with Chromium and captured to `ad.png`.

The transcript in `transcripts/session.md` is the unedited export of that session: the
API calls, the probe output, the dead ends and the build. Nothing in it was written after
the fact.

## Honest note

This entry is a referral ad, not a product claim. The page says what make.fun is and what
it pays; it does not promise returns. The author is a participant in the bounty, not
make.fun staff, and the page states that in the footer.

## License

MIT — see `LICENSE`.