# sagitta-stack organization handbook

> Shared operating defaults for repositories maintained under **sagitta-stack**. Repository-local policy may strengthen these rules but should not silently weaken them.

## Mission

sagitta-stack maintains application, platform, and shared-stack components. This `.github` repository is the canonical home for shared policy, reusable templates, community health files, and planning links.

## Repository contract

Each active repository must document purpose, ownership, maturity, supported environments, development and test commands, authoritative interfaces and configuration, release and rollback procedures, compatibility policy, and GitHub Project/Linear links. Shared components should also document dependency direction, initialization and shutdown, resource ownership, observability, configuration precedence, failure isolation, and upgrade paths.

## Change workflow

1. Anchor work in an issue, Linear item, or documented maintenance objective.
2. Keep branches and pull requests focused.
3. Explain motivation, scope, cross-repository impact, validation, compatibility, migration, and rollback.
4. Test startup, shutdown, timeout, retry, resource pressure, partial failure, and multi-version paths as relevant.
5. Resolve conflicts semantically by reconstructing both sides' intent.
6. Prefer squash merges for focused work unless commit structure materially improves auditability.

## Evidence, security, and documentation

Pull requests should include reproducible commands, expected and observed results, negative-path coverage, documentation updates, and CI or local-equivalent evidence. Never commit credentials, private keys, production configuration, or sensitive logs. Follow `SECURITY.md` for private reporting. Keep dependency boundaries explicit, examples executable, links current, compatibility matrices maintained, and important architectural and operational decisions recorded.

## Planning ownership

GitHub owns code, reviews, checks, releases, and delivery evidence. Linear owns priority, dependencies, sequencing, and cross-project planning. The organization GitHub Project is the cross-repository execution view; see `PROJECTS.md` for routing details.

## Organization health

- [ ] Profiles, descriptions, topics, and READMEs are current.
- [ ] Community health files and reusable issue/PR guidance are present.
- [ ] Dependency direction, resource ownership, failure isolation, and upgrade paths are documented.
- [ ] Required checks cover integration, compatibility, reliability, and supply-chain risk.
- [ ] Stale repositories are archived or clearly marked.
- [ ] GitHub Project and Linear links resolve and reflect completed work.
