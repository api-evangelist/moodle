# Moodle (moodle)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Moodle is the world's open source learning platform, used by educators and organizations to deliver online courses and learning experiences. The Moodle developer platform exposes a broad set of internal APIs for plugin and core development, plus a Web Services API that enables external systems to integrate with Moodle for users, courses, enrollments, grading, and more.

**URL:** [Visit APIs.yml URL](https://raw.githubusercontent.com/api-evangelist/moodle/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - E-Learning, EdTech, LMS, Moodle, Open Source, Web Services

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-04-28

## APIs

### Moodle Web Services API
Exposes Moodle functionality as web services so external programs can integrate with a Moodle site for users, courses, enrollments, grading, and other operations. Supports REST, XML-RPC, and SOAP protocols with token-based authentication.

**Human URL:** [https://moodledev.io/docs/apis/subsystems/external/](https://moodledev.io/docs/apis/subsystems/external/)

#### Properties

- [Documentation](https://moodledev.io/docs/apis/subsystems/external/)

### Moodle External Functions API
Allows developers to expose parametrized functions to external systems, forming the basis of Moodle's web services and powering integrations consumed via REST, SOAP, and XML-RPC.

**Human URL:** [https://moodledev.io/docs/apis/subsystems/external/functions](https://moodledev.io/docs/apis/subsystems/external/functions)

#### Properties

- [Documentation](https://moodledev.io/docs/apis/subsystems/external/functions)

### Moodle Access API
Provides functions to determine what the current user is allowed to do, checking roles, capabilities, and permissions across system, course, and activity contexts.

**Human URL:** [https://moodledev.io/docs/apis/subsystems/access](https://moodledev.io/docs/apis/subsystems/access)

#### Properties

- [Documentation](https://moodledev.io/docs/apis/subsystems/access)

### Moodle Roles API
An extension of the Access API that defines the set of actions a user is allowed to perform on certain system levels through assignable roles and capabilities.

**Human URL:** [https://moodledev.io/docs/apis/subsystems/access/roles](https://moodledev.io/docs/apis/subsystems/access/roles)

#### Properties

- [Documentation](https://moodledev.io/docs/apis/subsystems/access/roles)

### Moodle Data Manipulation API (DML)
Enables safe, consistent database read and write operations across Moodle, abstracting the underlying database driver and providing helpers for common query patterns.

**Human URL:** [https://moodledev.io/docs/apis/core/dml](https://moodledev.io/docs/apis/core/dml)

#### Properties

- [Documentation](https://moodledev.io/docs/apis/core/dml)

### Moodle File API
Manages file storage across plugins, providing a unified interface for uploading, retrieving, and serving files associated with users, courses, and activities.

**Human URL:** [https://moodledev.io/docs/apis/subsystems/files](https://moodledev.io/docs/apis/subsystems/files)

#### Properties

- [Documentation](https://moodledev.io/docs/apis/subsystems/files)

### Moodle Form API
Defines and processes user data submitted through web forms, including validation, rendering, and persistence.

**Human URL:** [https://moodledev.io/docs/apis/subsystems/form](https://moodledev.io/docs/apis/subsystems/form)

#### Properties

- [Documentation](https://moodledev.io/docs/apis/subsystems/form)

### Moodle Events API
Defines event handlers for inter-plugin communication and logging, enabling decoupled, observer-style integrations across Moodle.

**Human URL:** [https://moodledev.io/docs/apis/core/event](https://moodledev.io/docs/apis/core/event)

#### Properties

- [Documentation](https://moodledev.io/docs/apis/core/event)

### Moodle Hooks API
Enables indirect communication between core and plugins through well-defined extension points, allowing plugins to react to and modify core behavior.

**Human URL:** [https://moodledev.io/docs/apis/core/hooks](https://moodledev.io/docs/apis/core/hooks)

#### Properties

- [Documentation](https://moodledev.io/docs/apis/core/hooks)

### Moodle Privacy API
Describes stored personal data and supports discovery, export, and deletion of user data across plugins for GDPR and similar privacy compliance.

**Human URL:** [https://moodledev.io/docs/apis/subsystems/privacy](https://moodledev.io/docs/apis/subsystems/privacy)

#### Properties

- [Documentation](https://moodledev.io/docs/apis/subsystems/privacy)

### Moodle Task API
Executes background jobs on a schedule or as one-off operations, allowing plugins to defer long-running work to cron processing.

**Human URL:** [https://moodledev.io/docs/apis/subsystems/task](https://moodledev.io/docs/apis/subsystems/task)

#### Properties

- [Documentation](https://moodledev.io/docs/apis/subsystems/task)

### Moodle Payment API
Manages payment processing in Moodle, providing pluggable payment gateways for paid enrollments and other monetized features.

**Human URL:** [https://moodledev.io/docs/apis/subsystems/payment](https://moodledev.io/docs/apis/subsystems/payment)

#### Properties

- [Documentation](https://moodledev.io/docs/apis/subsystems/payment)

## Common Properties

- [Portal](https://moodledev.io)
- [Documentation](https://moodledev.io/docs/apis)
- [Website](https://moodle.org)
- [Blog](https://moodle.com/news/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
