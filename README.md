# SpecFlow

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

SpecFlow was a pragmatic BDD (Behavior-Driven Development) solution for .NET that used the Gherkin specification language to bridge the communication gap between domain experts and developers. Originally developed by TechTalk, acquired by Tricentis in 2020, and reached end-of-life on December 31, 2024. The community continuation is [Reqnroll](https://reqnroll.net/).

**URL:** [https://github.com/SpecFlowOSS/SpecFlow](https://github.com/SpecFlowOSS/SpecFlow)

> **Note:** SpecFlow reached end-of-life on December 31, 2024. The successor project is [Reqnroll](https://reqnroll.net/), a community fork maintaining full backward compatibility with .NET 8.0 and .NET 9.0 support.

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

.NET, BDD, Cucumber, Gherkin, Testing

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-02

## Products

| Product | Description |
|---|---|
| [SpecFlow](https://github.com/SpecFlowOSS/SpecFlow) | BDD framework for .NET using Gherkin syntax (retired Dec 2024) |
| [Reqnroll](https://reqnroll.net/) | Community fork and successor to SpecFlow with .NET 8/9 support |

## Artifacts

### JSON Schema

- [specflow-scenario-schema.json](json-schema/specflow-scenario-schema.json) — Schema for SpecFlow Scenario resources including Gherkin steps
- [specflow-feature-schema.json](json-schema/specflow-feature-schema.json) — Schema for SpecFlow Feature file structure

### JSON Structure

- [specflow-feature-structure.json](json-structure/specflow-feature-structure.json) — Structure documentation for Feature files and their relationships

### JSON-LD

- [specflow-context.jsonld](json-ld/specflow-context.jsonld) — JSON-LD context mapping SpecFlow vocabulary to linked data semantics

### Examples

- [specflow-feature-example.json](examples/specflow-feature-example.json) — Example Gherkin feature file with Scenario and ScenarioOutline

### Vocabulary

- [specflow-vocabulary.yml](vocabulary/specflow-vocabulary.yml) — Domain vocabulary for SpecFlow/BDD concepts including Gherkin, step definitions, hooks, and patterns

## Resources

- [GitHub Repository](https://github.com/SpecFlowOSS/SpecFlow)
- [Documentation](https://docs.specflow.org)
- [NuGet Package](https://www.nuget.org/packages/SpecFlow/)
- [Reqnroll (Successor)](https://reqnroll.net/)
- [End-of-Life Announcement](https://reqnroll.net/news/2025/01/specflow-end-of-life-has-been-announced/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
