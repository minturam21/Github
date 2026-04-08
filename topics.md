# GitHub Topics: Beginner to Advanced

---

## 🟢 Beginner

### Git Basics
- What is Git and why it's used (version control)
- Installing Git and configuring (`git config --global`)
- Initializing a repo (`git init`)
- Cloning a repository (`git clone`)
- Checking status (`git status`)
- Staging files (`git add`, `git add .`)
- Committing changes (`git commit -m`)
- Viewing history (`git log`, `git log --oneline`)
- Undoing changes (`git restore`, `git checkout`)

### GitHub Basics
- Creating a GitHub account
- Creating and deleting repositories
- Public vs private repositories
- README.md — what it is and how to write one
- Pushing to GitHub (`git push`)
- Pulling from GitHub (`git pull`)
- `.gitignore` — ignoring files from tracking
- Forking a repository
- Starring and watching repositories
- GitHub profile and profile README

### Basic Collaboration
- Raising a GitHub Issue
- Commenting on Issues and Pull Requests
- Downloading/cloning someone else's project
- Using GitHub Desktop (GUI alternative)

---

## 🟡 Intermediate

### Branching & Merging
- Creating and switching branches (`git branch`, `git switch`)
- Merging branches (`git merge`)
- Resolving merge conflicts
- Deleting branches (local and remote)
- Difference between `git fetch` and `git pull`
- Remote tracking branches (`origin/main`)
- `git stash` — saving work temporarily
- Tags — lightweight vs annotated (`git tag`)

### Pull Requests
- Opening a Pull Request (PR)
- Writing a good PR description
- Requesting reviewers
- Reviewing a PR — approving, requesting changes, commenting
- Inline comments and suggestion blocks
- Merging strategies — merge commit, squash, rebase
- Draft Pull Requests
- Linking a PR to an Issue (`Closes #123`)
- PR templates (`.github/pull_request_template.md`)

### GitHub Workflow & Automation
- GitHub Actions — what it is and why it matters
- Writing a basic workflow YAML file
- Triggers — `on: push`, `on: pull_request`, `on: schedule`
- Jobs and steps
- Using pre-built Actions from the Marketplace
- Secrets — storing API keys safely (`Settings > Secrets`)
- `GITHUB_TOKEN` — automatic token for Actions
- Enabling branch protection rules
- Required status checks before merging

### Collaboration Tools
- `CODEOWNERS` file — auto-assigning reviewers
- Issue labels, milestones, and assignments
- GitHub Projects — Kanban boards for task tracking
- Issue and PR templates
- GitHub Discussions
- Pinning Issues and Releases

---

## 🟠 Advanced

### Git Internals & Power Commands
- Interactive rebase (`git rebase -i`) — squash, fixup, reorder commits
- `git cherry-pick` — applying specific commits
- `git bisect` — binary search to find a bug-introducing commit
- `git reflog` — recovering lost commits
- `git blame` — who changed which line
- `git diff` — staged, unstaged, between branches
- Rewriting history with `git filter-branch` / `git filter-repo`
- Signing commits with GPG
- Conventional Commits specification (`feat:`, `fix:`, `chore:`)
- Atomic commits — one logical change per commit

### Branching Strategies
- GitFlow — `main`, `develop`, `feature/`, `hotfix/`, `release/` branches
- GitHub Flow — lightweight `branch → PR → merge to main`
- Trunk-based development — short-lived branches, merge daily
- Feature flags — shipping incomplete code safely
- Release branching strategies

### GitHub Actions (Advanced)
- Matrix builds — testing across multiple OS/language versions
- Reusable workflows (`workflow_call`)
- Composite Actions — bundling steps into reusable units
- Custom Actions (JavaScript and Docker)
- Environment protection rules — dev / staging / prod gates
- `workflow_dispatch` — manually triggered workflows
- Caching dependencies (`actions/cache`)
- OIDC-based authentication — keyless cloud deploys (AWS, GCP, Azure)
- Dependabot — automated dependency updates and security patches
- CodeQL — static analysis security testing (SAST)
- Publishing packages to GitHub Packages (npm, Docker, Maven)

### Repository Management
- GitHub Releases — versioning and changelogs
- Semantic Versioning (`MAJOR.MINOR.PATCH`)
- Automated changelog generation
- Protected branches — required reviews, no force push
- Rulesets (enterprise branch rules)
- Repository insights — traffic, contributors, dependency graph
- Archiving repositories

---

## 🔴 Expert / Enterprise

### Monorepos
- What is a monorepo and why FAANG uses them
- Sparse checkout — only clone parts of a large repo
- Git submodules — embedding repos inside repos
- Git subtree — merging repo history
- Monorepo tooling — Nx, Turborepo, Lerna, Bazel

### Security & Compliance
- Secret scanning — automatically detect leaked credentials
- Security advisories and CVE management
- Dependabot security updates vs version updates
- SAML SSO — integrating GitHub with enterprise identity providers (Okta, Azure AD)
- Organisation-level permission management (owner / member / billing)
- Audit log — who did what and when
- GitHub Advanced Security (GHAS) — code scanning, secret scanning, supply chain

### GitHub API & Automation
- GitHub REST API — programmatic access to repos, PRs, Issues
- GitHub GraphQL API — efficient batched queries
- Webhooks — trigger external services on GitHub events
- GitHub Apps — OAuth-based integrations with fine-grained permissions
- Personal Access Tokens (PAT) vs GitHub Apps — when to use which
- `gh` CLI — manage GitHub from the terminal
- Octokit SDK — official JavaScript/TypeScript client

### Git Internals (Deep Dive)
- Git object model — blobs, trees, commits, tags
- Pack files and garbage collection (`git gc`)
- The index (staging area) internals
- Shallow clones and `--depth` flag for CI speed
- Partial clones (`--filter=blob:none`)
- Git hooks — `pre-commit`, `commit-msg`, `pre-push`
- Husky + lint-staged — enforcing quality in teams

### CI/CD at Scale
- Multi-environment deployment pipelines
- Blue/green and canary deployments
- GitOps — using Git as the single source of truth for infrastructure
- Infrastructure as Code (IaC) with GitHub Actions — Terraform, Pulumi
- Container image builds and pushing to registries
- Self-hosted GitHub Actions runners
- Large-scale test parallelisation

---

## 📚 Recommended Learning Order

1. Git basics → GitHub account → first push
2. Branching & merging → conflict resolution
3. Pull Requests → code review workflow
4. GitHub Actions → basic CI pipeline
5. Branch protection → team collaboration rules
6. Interactive rebase → clean commit history
7. Advanced Actions → reusable workflows, environments
8. Branching strategy → GitFlow vs trunk-based
9. Monorepo → security → API automation
10. Git internals → CI/CD at scale → expert tooling


---
