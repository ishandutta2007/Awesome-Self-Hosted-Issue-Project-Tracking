# Awesome-Self-Hosted-Issue-Project-Tracking

## Top Self-Hosted Issue & Project Tracking Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on On-Premises Issue Tracking, Agile Planning & Self-Managed DevOps Platforms*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Self-Hosted Issue & Project Tracking**. These tools enable teams to manage bugs, tasks, and sprints on infrastructure they control—preserving data residency, avoiding per-seat cloud pricing, and maintaining full control over customization, while accepting the operational responsibility that self-hosting demands.



**Examples** include Jira Server (EOL), Redmine, GitLab Self-Managed, GitHub Enterprise Server, Bugzilla, MantisBT, OpenProject, Trac, YouTrack Server, and Phabricator (the category leaders).



**Open-source emphasis**: Self-Hosted Issue & Project Tracking is a domain where open-source tooling is **mature and production-proven across distinct workflows**, but the landscape carries critical EOL traps. **Jira Server reached end-of-support on February 15, 2024**—no security patches will ever ship again, making it a compliance liability . **Jira Data Center follows with full EOL on March 28, 2029** (new sales ended March 30, 2026; expansions end March 30, 2028) . On the open-source side, **Redmine** remains the battle-tested veteran with two decades of ecosystem and plugins for almost anything , **OpenProject** offers the most complete enterprise-grade project management with Gantt charts, budgets, and cost reporting , **Taiga** excels at proper Scrum mechanics for teams that actually run sprints , and **Trac** continues active development (commits through August 2026) as a minimalist wiki-plus-issue-tracker . The critical caveat: **Phabricator is no longer actively maintained** (Phacility wound down in 2021) —the community fork **Phorge** is the actively updated path forward . **Jira Server must not be deployed for new projects**—migration to an open-source alternative or Jira Cloud is mandatory.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Jira Server](https://www.atlassian.com/)**  

  **END OF SUPPORT: February 15, 2024.** No updates, security patches, bugfixes, or technical support will ever ship . **Do not deploy for new projects**—running it is a compliance liability. Migrate to Data Center, Cloud, or an open-source alternative.



- **[Jira Data Center](https://www.atlassian.com/)**  

  Self-managed Jira for organizations needing on-premises control. **Critical timeline**: new sales ended March 30, 2026; license expansions end March 30, 2028; **full EOL is March 28, 2029**—after which licenses expire and instances become read-only . Data Center receives no new feature development and no Rovo AI . Organizations still on Data Center must plan migration now.



- **[GitLab Self-Managed](https://about.gitlab.com/)**  

  Self-hosted DevOps platform with source control, CI/CD, issue tracking, and container registry; provides full control over infrastructure and data residency.



- **[GitHub Enterprise Server](https://github.com/enterprise)**  

  Self-hosted GitHub for organizations requiring on-premises source control; includes repositories, pull requests, Actions, and security features.



- **[YouTrack Server](https://www.jetbrains.com/youtrack/)**  

  JetBrains' issue tracker available in self-hosted Server edition; known for search-driven workflows and keyboard-centric UX.



## Open-Source GitHub Projects



### Traditional Issue Trackers



- **[Redmine](https://github.com/redmine/redmine)**  

  The **battle-tested open-source issue tracker** (GPLv2, free) with two decades of development and an enormous plugin ecosystem—there is a plugin for almost anything . Features: issue tracking, subprojects, roles and permissions, time tracking, wikis, forums, Gantt charts, and calendar views . **Caveats**: the interface is dated; Kanban boards, OIDC login, and most modern conveniences come from **third-party plugins pinned to versions and maintained by volunteers** . **Best for teams comfortable assembling and maintaining a plugin stack**, or anyone already running it—zero license cost, complete control, and a mature ecosystem in exchange for less modern UX and more maintenance .



- **[Trac](https://github.com/edgewall/trac)**  

  Minimalist open-source **wiki and issue tracking system** (modified BSD License) with **active development**—commits through August 2026 . Integrates with Git and Subversion, provides an integrated wiki, flexible issue tracking, and report facilities via wiki markup that links issues, changesets, documentation, and files together . **Best for small teams wanting a lightweight, proven tracker** with minimal dependencies—but it is minimal by design, lacking modern boards and Agile ceremony support .



- **[Bugzilla](https://www.bugzilla.org/)**  

  Long-standing open-source **bug tracker** (MPL 2.0) from Mozilla; powerful query system and mature permissions, but dated UI and no Agile/kanban features. **Best for traditional bug tracking** in large, long-running projects—not modern software team workflows.



- **[MantisBT](https://mantisbt.org/)**  

  Open-source **bug tracker** (GPLv2) with a straightforward interface, email notifications, and plugin support; lighter than Bugzilla and easier to deploy. **Best for small to mid-sized teams** needing simple bug tracking without Agile overhead.



### Agile & Scrum-Focused



- **[Taiga](https://github.com/kaleidos-ventures/taiga)**  

  Open-source **Agile project management** (MPL-2.0, free to self-host) organized around **Scrum ceremonies**—sprints, story points, burndown charts, epics, and both Kanban and Scrum boards . **The methodology is baked in**: if your team runs Scrum properly rather than aspirationally, it supports that better than most alternatives . **Caveats**: if you do not run Scrum, much of it is overhead; development pace is slower than newer tools . **Best for teams committed to Scrum** who want sprint mechanics as first-class features .



### Enterprise-Grade Project Management



- **[OpenProject](https://github.com/opf/openproject)**  

  The **most complete open-source enterprise project management platform** (GPLv3 Community Edition, AGPLv3 for some components) , continuously developed since 2012 with a sustainable funding model through OpenProject GmbH . Features: **Gantt charts** with drag-and-drop dependencies, critical path visualization, and baseline comparisons; **Scrum boards** with sprint planning, backlog management, and velocity tracking; **time and cost tracking** with budgets and cost reports; meeting management; and product roadmaps . **Caveats**: AGPL copyleft may require legal review; **SSO is reserved for the Enterprise add-on**; the Gantt chart is functional but less polished than dedicated tools . **Best for organizations needing budgets, cost reporting, and baseline comparisons alongside scheduling**—the strongest open-source option for traditional project management at scale .



### Modern Self-Hosted Alternatives



- **[Plane](https://github.com/makeplane/plane)**  

  Modern open-source **Jira/Linear alternative** (AGPL-3.0 Community Edition, 59k+ GitHub stars) with work items, cycles (sprints), modules, pages, and five layout views (List, Board, Spreadsheet, Gantt, Calendar) . **Caveats**: **SSO starts at the Pro tier**—not free; development is very active but the Community edition withholds enterprise features . **Best for engineering teams** wanting a modern, actively developed tracker with self-hosting and a clear upgrade path.



- **[Kaneo](https://github.com/usekaneo/kaneo)**  

  Fast, simple open-source project management (MIT, free to self-host) with Board, List, Calendar, and Gantt views; subtasks, dependencies, labels, comments, and time tracking; **SSO included on every plan**—unlike OpenProject or Plane . Imports Jira Cloud and Jira Data Center projects (issue keys, columns, priorities, labels, assignees, sub-tasks, issue links, comments) . **Caveats**: attachments, sprints, and custom fields do not come across in imports . **Best for teams wanting a lightweight, modern tracker with free SSO and a clear Jira migration path** .



### Additional Strong Open-Source Options



- **Phabricator** — **NO LONGER ACTIVELY MAINTAINED** (Phacility wound down in 2021; no future updates) . The community fork **Phorge** released stable in September 2022 and is actively updated—use Phorge instead for new deployments .

- **Phorge** — Actively maintained fork of Phabricator; provides the same suite of development collaboration tools (code review, task management, project communication) with ongoing updates . **Best for teams already invested in the Phabricator workflow** who need a maintained path forward.

- **Leantime** — Lean project management with kanban, Gantt, goals, and time tracking; AGPL-3.0. **Best for startups** wanting an integrated project management + strategy tool.



**Frameworks for building custom systems**: For **traditional issue tracking with maximum plugin flexibility**, Redmine . For **enterprise project management with budgets and Gantt**, OpenProject . For **Scrum-first teams**, Taiga . For **modern Jira/Linear replacement**, Plane or Kaneo . For **lightweight wiki+issues**, Trac . **Avoid**: Jira Server (EOL February 2024, no security patches ever) ; plan migration from Jira Data Center before March 28, 2029 ; use Phorge instead of Phabricator for maintained development. No open-source project matches Jira's **enterprise ecosystem depth** or YouTrack's **polished search UX** out of the box—choose based on workflow fit and tolerance for maintenance.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Self-hosted issue trackers handling project data must comply with organizational security policies; **self-hosting places full responsibility for patching, backups, and uptime on the operator** .

- **Jira Server is EOL and must not be deployed**—no security patches have shipped since February 15, 2024, and none ever will . **Jira Data Center ends March 28, 2029**—organizations must plan migration now . **Phabricator is no longer maintained**—use the Phorge fork for active development .

- **Open-source self-hosted tracking is mature but requires operational investment**—Redmine, OpenProject, Taiga, and Plane provide production-grade alternatives. However, **feature gating varies**: OpenProject reserves SSO for Enterprise; Plane reserves SSO for Pro; Redmine relies on community plugins for modern features. Factor these into your evaluation.

- Verify license terms for commercial use; Redmine uses GPLv2 , OpenProject Community uses GPLv3 (with AGPL components) , Taiga uses MPL-2.0 , Plane uses AGPL-3.0 , and Kaneo uses MIT .



---



**Made for engineering managers, IT administrators, and teams choosing their self-hosted issue tracking stack.**  

Let's make self-hosted issue tracking more open, but with clear eyes about the Jira EOL deadlines and the feature-gating and maintenance trade-offs that define each path.
