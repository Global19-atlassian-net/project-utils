# Project Utils
- Any standalone, language and project agnostice executable used for project management is a good candidate for this repo
- Where the go-utils repo is a good place to store go libraries that are imported by multiple repos, this repo is a good place to store source that compiles to executable that are used by multiple repos.

# Current status
- Proposal - do we want to use this repo/usage pattern?
- At time of creating I (mitchdraft) was intending to put our cli-to-hugo-docs code here (shared between gloo, sqoop and squash)
  - However, I realized the shared logic also assumes the cli was written in go (Cobra) - so the shared code would be belong in go-utils, not this repo
- Other candidates:
  - Change log CLI
  - cloudbuild wrappers (if any)
  - TBD
