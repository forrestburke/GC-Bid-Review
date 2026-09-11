# GC Bid Review

Source code for the Treasure Dr renovation bid-comparison tool (kitchen/bath/garage remodel on both duplex sides plus the new backyard ADU, Santa Barbara CA).

**This repo is a code snapshot, not the live tool.** `index.html` is a static file — opening it locally or via GitHub Pages will show the comparison data, but flags and newly added estimates won't save or sync between people, because that requires the shared live database the file connects to when run as a Claude Artifact.

For the live, shared version — where anyone with the link can add estimates and flag line items, and everyone sees the same data update in real time — use:

https://claude.ai/code/artifact/c5d4b970-085b-4e79-9bd3-ce0301ec9ca3

Update this repo by re-exporting `index.html` from that artifact whenever you want to snapshot the current state or data.
