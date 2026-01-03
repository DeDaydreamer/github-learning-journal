# Repository Review Guide (Manager View)

## 1. Repo structure
- [ ] Clear top-level folders (core code, config, docs, content).
- [ ] README explains purpose, how to run, and who owns it.
- [ ] High-risk areas identified (e.g., functions/api, deploy scripts).

## 2. History and commits
- [ ] Commit messages are specific (few “fix stuff” or “update” only).
- [ ] Commits are reasonably sized (not huge unrelated bundles).
- [ ] Mix of content, config, and behaviour changes makes sense for the project.

## 3. Collaboration habits
- [ ] Issues are used or there is a clear alternative process.
- [ ] PRs have clear titles and Context / Changes / Risk sections.
- [ ] Draft PRs are used for work in progress; old drafts are cleaned up.

## 4. Releases and stability
- [ ] Tags or releases mark important shipped versions (if production).
- [ ] Notes exist for breaking changes or migrations.
- [ ] If no releases: project treated as early/experimental.

## 5. Current assessment – thedaydreamverse-site
- README, ownership, and deployment: clear and complete.
- No open issues; one draft PR (manager learning note).
- GitHub Releases and Actions workflows are not configured; the site is live, but deployments and versioning are managed outside GitHub’s releases/automation features.
