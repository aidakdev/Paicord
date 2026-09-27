# Contributing

Before you can have your contributions to this repository merged, you
need to follow these guidelines:

1. No given part of your contribution may be assisted or written by an
   LLM. This includes, but is not limited to: source code, assets, pull
   request description, and pull request title. Slop PRs will be closed
   without review.
3. Source code must be formatted and indented correctly. Use tools like
   Swift Format for this (`ctrl + shift + R` in Xcode, also CLI `swift format`).
5. Pull requests should have a separate branch named after what the PR
   is implementing. For instance, `feat/new-feature`. Pull requests should
   avoid touching multiple parts of the project and be focused to one spot.
   If this doesn't apply to your work (naturally large scope), commits must
   be well-named for review. If a PR has too large a scope of changes, it
   may be closed by a reviewer.
7. Pull request descriptions should contain screenshots when needed, for
   instance, a UI redesign should have screenshots of the new UI. PaicordLib
   changes must be thoroughly documented.
9. Many contributions in one pull request should be instead split up into
   multiple pull requests with a branch for each feature. This makes it
   easier for us to cherry-pick specific changes to merge, since not all
   contributions from a PR may be desired by us, or may need further review.
   Splitting contributions increases likelihood of merging and may be merged
   sooner.
