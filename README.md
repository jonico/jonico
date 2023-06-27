<img width="200" src="https://content.pstmn.io/754101a4-01d8-4f68-93bf-9f5ecab74234/cG9zdG1hbmF1dCtvY3RvbmF1dC5wbmc=">

:wave: I am an Open Source Enthusiast, originally working for GitHub, now working for Postman, who is interested in all things in all things IssueOps, integrations, CI/CD and API design. When I started at Postman, I noticed that it is actually quite similar to GitHub - just for APIs and not for code. However, some similar concepts had different names, so we created this table to make adoption easier and use my two favorite platforms together.

### Postman vs GitHub Terms / Concepts

| Postman Concept | GitHub Equivalent Concept | Remarks |
| --- | --- | --- |
| [Team](https://learning.postman.com/docs/administration/managing-your-team/managing-your-team/) | [Enterprise Account](https://docs.github.com/en/enterprise-cloud@latest/admin/overview/about-enterprise-accounts) | Probably the biggest difference between terms: A Postman team consists of literally all users and workspaces of your entire company - or at least all the users that are part of your plan. A team can have unlimited workspaces. If you are looking for a concept to group a subset of users together that form a “people team”, have a look at Postman user groups |
| [Workspace](https://learning.postman.com/docs/collaborating-in-postman/using-workspaces/managing-workspaces/) | [Organization](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/about-organizations) |  |
| [Public workspace](https://learning.postman.com/docs/collaborating-in-postman/using-workspaces/public-workspaces/) | [Organization with public repositories](https://github.com/collections/open-source-organizations) |  |
| [Team workspace](https://learning.postman.com/docs/collaborating-in-postman/working-with-your-team/collaborating-in-team-workspaces/) | [Organization with an enterprise account with internal repositories or standalone organization with default access/base permissions set to at least “Read”](https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/setting-base-permissions-for-an-organization) |  |
| [Private workspace](https://learning.postman.com/docs/collaborating-in-postman/using-workspaces/creating-workspaces/) | [Organization where repository access is gated by team level access rights, base permissions set to “None”](https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/managing-team-access-to-an-organization-repository) | This should probably be the default setting for most companies who operate on a need to know basis - they would assign user groups reflecting their “people teams” to their private workspaces as team level visibility would mean granting access to anybody in their company |
| [Personal workspace](https://learning.postman.com/docs/collaborating-in-postman/using-workspaces/creating-workspaces/) | Personal repositories in personal namespace where you did not grant access to anybody else | You can have multiple personal workspaces in Postman, but only one in GitHub. The personal namespaces in Postman belong to the team you are in, in other words, you will lose access once you leave the team. |
| [Partner Workspace](https://learning.postman.com/docs/collaborating-in-postman/using-workspaces/partner-workspaces/) | [Organization where external collaborators got invited that are not governed by SSO org requirements](https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/adding-outside-collaborators-to-repositories-in-your-organization) | In GitHub, you can add collaborators to any repository, in Postman, you could share API links or invite to partner workspaces (after a community manager approves) |
| [User Group](https://learning.postman.com/docs/administration/managing-your-team/user-groups/) | [Team](https://docs.github.com/en/organizations/organizing-members-into-teams/about-teams) | A user group in Postman is defined at the Team Level (across workspaces), whereas in GitHub teams are defined on the organization level |
| [Team member](https://learning.postman.com/docs/reports/team-details-reports/) | [Member of the enterprise account / or org member of a freestanding GitHub org](https://docs.github.com/en/enterprise-cloud@latest/admin/user-management/managing-users-in-your-enterprise/roles-in-an-enterprise#enterprise-members) |  |
| [Workspace Admin](https://learning.postman.com/docs/collaborating-in-postman/roles-and-permissions/#workspace-roles) | [Org owner](https://docs.github.com/en/organizations/managing-peoples-access-to-your-organization-with-roles/roles-in-an-organization) |  |
| [Super Admin](https://learning.postman.com/docs/collaborating-in-postman/roles-and-permissions/#team-roles) | [Enterprise Owner](https://docs.github.com/en/enterprise-cloud@latest/admin/user-management/managing-users-in-your-enterprise/roles-in-an-enterprise#enterprise-owners) |  |
| [Collection](https://learning.postman.com/docs/getting-started/creating-the-first-collection/), [API](https://learning.postman.com/docs/designing-and-developing-your-api/creating-an-api/), [Mock Server](https://learning.postman.com/docs/designing-and-developing-your-api/mocking-data/setting-up-mock/), [Monitors](https://learning.postman.com/docs/monitoring-your-api/intro-monitors/), [Environments](https://learning.postman.com/docs/sending-requests/managing-environments/), [Flows](https://learning.postman.com/docs/postman-flows/gs/flows-overview/) | [Repository](https://docs.github.com/en/repositories) | This is not really an equivalent but a conceptual mapping where repos sit in the access right hierarchy vs where elements sit within a Postman workspace |
| [Element-based roles](https://learning.postman.com/docs/collaborating-in-postman/roles-and-permissions/#element-based-roles) | [Repo team permissions](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/managing-teams-and-people-with-access-to-your-repository) |  |
| [Workspace roles](https://learning.postman.com/docs/collaborating-in-postman/roles-and-permissions/#workspace-roles) | [Default access rights within an org](https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/setting-base-permissions-for-an-organization) | In Postman, you can grant different user groups or team members different roles that would apply to all elements of the workspace. In GitHub, you can do this only on an individual repository level or for all team members. |
| [User Account](https://learning.postman.com/docs/getting-started/postman-account/) | [User Account](https://docs.github.com/en/account-and-profile) | In Postman, users can only belong to up to 5 teams and can only see / search / access non-public elements of workspaces that are part of the team they are currently logged in. |
| [User profile](https://learning.postman.com/docs/getting-started/postman-profile/) | [User profile](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/about-your-profile) | Postman user profiles are private by default |
| [Team profile](https://learning.postman.com/docs/administration/team-settings/#editing-your-team-profile) | N/A | There is no thing like an enterprise profile in GitHub |
| [Workspace description](https://learning.postman.com/docs/collaborating-in-postman/using-workspaces/managing-workspaces/#editing-workspace-details) | [Org profile/org repo](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile) |  |
| [Environments](https://learning.postman.com/docs/sending-requests/managing-environments/) | [Environment Secrets](https://docs.github.com/en/actions/deployment/targeting-different-environments/using-environments-for-deployment#environment-secrets) | Postman Envs are more flexible with current and initial values, current values will never get synched to the cloud |
| [Globals](https://learning.postman.com/docs/sending-requests/managing-environments/) | [GitHub Org Secrets](https://docs.github.com/en/actions/security-guides/encrypted-secrets#creating-encrypted-secrets-for-an-organization) | Postman Envs are more flexible with current and initial values |
| [Private API Network](https://learning.postman.com/docs/collaborating-in-postman/adding-private-network/) | [Pinned Repositories](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile) in orgs with private repos, [Onboarding repos](https://github.com/jonico/get-started-with-github), [Topics](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics) | Postman API Network is more flexible with nested network folders and has an [optional approval workflow](https://learning.postman.com/docs/collaborating-in-postman/adding-private-network/#using-the-approval-process-workflow) for publishing, GitHub topics can only be searched in one organization of your enterprise |
| [Public API Network](https://www.postman.com/explore) | Any public repo, [GitHub explore](https://github.com/explore) | Any resource (collection, API, Mock Server, Monitor) within a public workspace is automatically part of the Postman public API network |
| [Private API Network Folders](https://learning.postman.com/docs/collaborating-in-postman/adding-private-network/#organizing-with-folders) | [Repository Topics](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics) / GitHub Collections (Enterprise Server) | Topics are multi-dimensional, whereas Network folders only support a nested one-dimensional hierarchy and span multiple team workspaces that can be searched together |
| [Public API network categories](https://www.postman.com/categories)[Top 25 Workspaces](https://blog.postman.com/top-25-api-onboarding-experiences/) | [GitHub Collections](https://github.com/collections) (GitHub.com) | In both cases, you would need to talk to a community manager to get listed |
| [Published Documentation](https://learning.postman.com/docs/publishing-your-api/publishing-your-docs/) | [GitHub Pages](https://docs.github.com/en/pages) | Both support custom domains |
| [Run in Postman Button](https://learning.postman.com/docs/publishing-your-api/run-in-postman/creating-run-button/) | [GitHub Codespaces](https://github.com/features/codespaces) | In both cases, you are not stuck with pure documentation but can execute the assets of the workspace including visualization and test cases |
| [Fork](https://learning.postman.com/docs/collaborating-in-postman/using-version-control/forking-entities/) | [Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) | In Postman, you can not only fork collections, but also environments. It is possible to fork to the same workspace and you can have as many forks in the same workspace as you like, making the fork based collaboration model easier. Furthermore, forks in Postman do not have to have the same visibility as the parent and will continue to exist if the parent got deleted. |
| [Pull Changes](https://learning.postman.com/docs/collaborating-in-postman/using-version-control/forking-entities/#pulling-updates-from-a-parent-element) | [Sync Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/keeping-your-pull-request-in-sync-with-the-base-branch)[Sync branch](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/keeping-your-local-repository-in-sync-with-github/syncing-your-branch)[Syncing a fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) | Keeping up with changes of your parent environment/collection does not need any special branch protection rules in Postman |
| [Pull Request](https://learning.postman.com/docs/collaborating-in-postman/using-version-control/creating-pull-requests/) | [Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) | Native Pull Requests in Postman require the reviewer to have at least view permissions in the fork, which limits forks where you like to contribute back to public workspaces if the parent collection or environment is in a different team. Pull requests also work for changes to environments. For API development, it is also possible to [use native GitHub Pull Requests within Postman](https://learning.postman.com/docs/designing-and-developing-your-api/versioning-an-api/versioning-an-api-overview/). |
| [Tagging members in comments](https://learning.postman.com/docs/collaborating-in-postman/working-with-your-team/discussing-your-work/#tagging-members-in-comments) | [@ -mention/user](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) |  |
| N/A | [@-mention/team](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) | @mentioning user groups does not exist in Postman yet |
| [Emoji Copy/Paste](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) | [Emojis in Markdown](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) | Postman does not support emoji Markdown syntax yet, but you can [copy/paste](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) Unicode emojis into the various editors |
| [Published API version](https://learning.postman.com/docs/designing-and-developing-your-api/versioning-an-api/api-versions/) | [Release](https://docs.github.com/en/repositories/releasing-projects-on-github) |  |
| [API links/Public links](https://learning.postman.com/docs/collaborating-in-postman/sharing/#sharing-using-the-postman-api) | [Secret gists](https://docs.github.com/en/get-started/writing-on-github/editing-and-sharing-content-with-gists/creating-gists) | API links in Postman can be set to expire and will not work any more if the user leaves the team |
| Dynamic usage limits (monitor calls, API calls, mock calls) | Dynamic usage limits (Action minutes, Codespaces storage Git LFS) | Postman usage limits are per team vs.most GitHub dynamic spending limits are per org |
| [Audit Log](https://learning.postman.com/docs/administration/audit-logs/) | [Audit log](https://docs.github.com/en/enterprise-cloud@latest/admin/monitoring-activity-in-your-enterprise/reviewing-audit-logs-for-your-enterprise/audit-log-events-for-your-enterprise) (enterprise level)[Audit log](https://docs.github.com/en/enterprise-cloud@latest/organizations/keeping-your-organization-secure/managing-security-settings-for-your-organization/reviewing-the-audit-log-for-your-organization) (org level) |  |
| [Change log](https://learning.postman.com/docs/collaborating-in-postman/using-workspaces/changelog-and-restoring-collections/#contents) | [File history](https://docs.github.com/en/repositories/working-with-files/using-files/viewing-a-file#viewing-the-line-by-line-revision-history-for-a-file) | For [APIs and collections managed with Git](https://learning.postman.com/docs/designing-and-developing-your-api/versioning-an-api/versioning-an-api-overview/), the GitHub changelog is displayed |
| [Token scanning](https://learning.postman.com/docs/administration/token-scanner/) | [Secret scanning](https://docs.github.com/en/code-security/secret-scanning/about-secret-scanning) |  |

### Postman Certifications

<img src="https://api.badgr.io/public/assertions/hWi_1FSLQwKwdFMkRe-KnQ/image" alt="Take%20part%20in%20the%2030%20days%20of%20Postman%20coding%20challenge!" width="200">

[Take the challenge yourself!](https://www.postman.com/postman/workspace/30-days-of-postman-for-developers/overview) There is also a [15 Days challenge specialized for testers](https://www.postman.com/postman/workspace/15-days-of-postman-for-testers/overview) 💪
