# Adding Another Paper

Use the following process when another manuscript needs private repository access during peer review.

1. Create a folder under `papers/` using a short venue name and a short manuscript name, for example:

   `papers/venue-name/manuscript-short-name/`

2. Copy `templates/PAPER_ACCESS_TEMPLATE.md` into the new folder as `README.md`.
3. Replace every bracketed placeholder with the manuscript-specific information.
4. Add one row to the **Current peer-review access** table in the root `README.md` and link it to the new paper page.
5. Check that the public page contains no private code, results, datasets, reviewer identities, unpublished submission identifiers, credentials, or confidential manuscript material.
6. Open every link in a signed-out browser before sharing the landing-page URL.
7. When the paper is accepted and its complete repository becomes public, update the paper page and the root table with the public repository link.

Keep each paper's implementation and evidence in its separate private repository. This landing repository should contain access instructions only.
