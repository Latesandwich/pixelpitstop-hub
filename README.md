# Pixel Pit Stop Hub

Public status page for the Pixel Pit Stop shorts pipeline: https://latesandwich.github.io/pixelpitstop-hub/

- `status.json` is written by the cloud agents (see `pipeline/PROTOCOL.md` in the private production repo). It holds
  status only: no source, no secrets, no unreleased video.
- The page's buttons open command issues (`[cmd] stop`, `resume`, `approve`, `feedback`, `next`) in the private repo,
  so only its owner can send them.
