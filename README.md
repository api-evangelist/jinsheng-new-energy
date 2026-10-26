# Jinsheng New Energy

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

Guangdong Jinsheng New Energy Co., Ltd. (广东金晟新能源股份有限公司) is a Chinese lithium-battery
recycling and cathode-materials company headquartered in Zhaoqing, Guangdong. Founded in 2010 as a
nickel sulfate producer, it now runs a closed-loop "urban mine" business — harmless treatment,
echelon (second-life) use and hydrometallurgical regeneration of retired lithium-ion batteries into
battery-grade nickel sulfate, cobalt sulfate, manganese sulfate and lithium carbonate, plus ternary
and iron-phosphate precursors, LFP cathode material, and downstream cells for light mobility,
commercial and industrial storage, outdoor power stations and solar street lighting. Production runs
from Zhaoqing (Gaoyao) in Guangdong and Yichun/Ganzhou in Jiangxi via the wholly owned subsidiary
Jiangxi Ruida New Energy Technology, with approved capacity of roughly 204,000 t/yr of spent
lithium battery.

## API surface

**None found.** Jinsheng New Energy is an industrial materials manufacturer with no developer
program. Its public web presence is a corporate CMS site (about / products / news / contact) at
[www.zqjs.cn](https://www.zqjs.cn/). Full contract discovery was run on 2026-08-23 against both
company hosts — REST spec paths (`/openapi.json`, `/openapi.yaml`, `/swagger.json`,
`/v1/openapi.json`, `/api-docs`, `/docs`, `/redoc`), a GraphQL introspection surface, every
canonical `/.well-known/` document, and both A2A agent-card paths — and nothing was served. Every
`200` on `www.zqjs.cn` is the same 3,679-byte CMS catch-all page, i.e. a soft 404, not a spec. No
GitHub organization exists for the company.

What this repo does hold is a probed record of that absence, plus the company's real domain
security posture:

- `security/jinsheng-new-energy-domain-security.yml` — TLS 1.3, HSTS (max-age 31536000), DNSSEC
  enabled on `zqjs.cn`; no CAA, SPF or DMARC records.
- `well-known/jinsheng-new-energy-well-known.yml` — the `/.well-known/` probe, all misses.

- https://www.zqjs.cn/
- https://www.hiive.com/securities/jinsheng-new-energy-stock
