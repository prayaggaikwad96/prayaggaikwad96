# Profile repository branch protection policy

Protect the `main` branch using **Settings → Branches → Add branch protection rule**:

- Require a pull request before merging where practical.
- Require status checks only when this repository has checks that run on the relevant changes.
- Require conversation resolution.
- Block force pushes and branch deletion.
- Restrict bypass to documented emergencies.

For a profile README-only repository, do not invent a CI requirement. A pull request review and branch protection against force pushes/deletion are still useful safeguards.

**Important:** This file documents the desired policy; it does not itself enable GitHub branch protection. Apply the settings in repository Settings (the connected GitHub integration cannot administer branch protection for this account).
