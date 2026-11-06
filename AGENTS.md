# Widescreen Loading Screens: repository rules

- EU4 mod for Anbennar. It replaces the images in `gfx/loadingscreens` and no checksummed file:
  that is what keeps ironman and achievements as they are, so a change must keep it so.
- English in code and docs. Do not imply affiliation with Paradox Interactive.
- The agent owns the pull request flow: it works on a branch with Conventional Commits,
  pushes it and opens the PR as a draft. Once ready (green CI, the change tested as above,
  no blocking review findings, not put on hold by the user) it marks the PR ready and
  squash-merges it; GitHub does not allow auto-merge on a draft. Pull requests from other
  contributors get a review and a recommendation; the maintainer decides on merging them.
  Do not bypass CI or branch protection, and do not change repository settings beyond what
  auto-merge needs.
