# Sirius XM Holdings

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Sirius XM Holdings Inc. (NASDAQ: SIRI) is the leading audio entertainment company in North America. The holding company operates a portfolio of subscription, ad-supported streaming, podcast, and advertising-technology businesses, anchored by satellite radio service SiriusXM and ad-supported streaming service Pandora. SiriusXM Holdings was split off from Liberty Media in September 2024 and now trades as an independent public company.

**Ticker:** NASDAQ: SIRI
**Headquarters:** New York, NY
**Corporate site:** [https://corporate.siriusxm.com/](https://corporate.siriusxm.com/)
**Consumer site:** [https://www.siriusxm.com/](https://www.siriusxm.com/)
**Investor relations:** [https://investor.siriusxm.com/](https://investor.siriusxm.com/)
**APIs.yml:** [View APIs Index](https://raw.githubusercontent.com/api-evangelist/sirius-xm-holdings/refs/heads/main/apis.yml)

## Scale (FY2025)

- ~33 million SiriusXM paid subscribers
- ~40 million Pandora active users
- ~255 million combined monthly listeners
- USD 8.558 billion total revenue
- USD 2.665 billion adjusted EBITDA
- USD 1.256 billion free cash flow

Source: [SiriusXM Investor Relations](https://investor.siriusxm.com/).

## Brand Portfolio

Consumer and partner brands operated by SiriusXM Holdings:

- **[SiriusXM](https://www.siriusxm.com/)** - Subscription satellite radio and streaming, including connected-vehicle distribution.
- **[Pandora](https://www.pandora.com/)** - Ad-supported and premium music streaming with a public partner developer API.
- **[SiriusXM Media](https://www.siriusxmmedia.com/)** - Consolidated audio advertising sales arm.
- **[AdsWizz](https://www.adswizz.com/)** - Programmatic digital-audio adtech platform (ad insertion, SSP, DSP, SDKs).
- **[Simplecast](https://www.simplecast.com/)** - Podcast hosting, distribution, and analytics with a public REST API.
- **[Pandora AMP](https://amp.pandora.com/)** - Artist Marketing Platform.
- **[SiriusXM Connected Vehicle Services](https://www.siriusxmconnectedvehicles.com/)** - Telematics and infotainment for OEM partners.
- **[SiriusXM Marine](https://www.siriusxm.com/marine)** - Satellite weather, fishing, and audio for marine users.
- **[SiriusXM Aviation](https://www.siriusxm.com/aviation)** - Satellite weather and audio for general aviation.
- **[SiriusXM for Business](https://business.siriusxm.com/)** - Commercial audio service.
- **[Pandora for Business / CloudCover](https://business.pandora.com/)** - Commercial background music.

## Corporate Timeline

- **2018** - SiriusXM acquires AdsWizz.
- **Feb 2019** - SiriusXM completes acquisition of Pandora Media.
- **2020** - SiriusXM acquires Simplecast (podcast hosting); also acquires Stitcher.
- **2024** - Stitcher / Stitcher Ads business divested.
- **Sept 2024** - Liberty Media split-off completed; SiriusXM Holdings becomes an independent public company under NASDAQ: SIRI.

## Developer Resources

The holding-company entity itself does not operate a developer program. Developer surfaces live in the operating subsidiaries:

- **Pandora Developer Center** - GraphQL partner API for catalog, playback, search, collection, feedback, and profile. [https://developer.pandora.com/](https://developer.pandora.com/)
- **AdsWizz Domain API** - Programmatic audio advertising API. [https://docs.adswizz.com/domain-api/v8/](https://docs.adswizz.com/domain-api/v8/)
- **AdsWizz SDKs** - iOS (Swift), Android (Kotlin), and Web (JavaScript) audio-ad SDKs. [https://docs.sdk.adswizz.com/](https://docs.sdk.adswizz.com/)
- **Simplecast API** - REST API for show, episode, and analytics management, token bearer auth at `https://api.simplecast.com/`. Docs: [https://apidocs.simplecast.com/](https://apidocs.simplecast.com/)
- **SiriusXM GitHub Organization** - Small public-tooling presence (`snapshot4s`, `node-soap`, `shopping-cart-test-data`). [https://github.com/SiriusXM](https://github.com/SiriusXM)
- **AdsWizz GitHub Organization** - Verified org with ~24 repos focused on infrastructure tooling and media tech. [https://github.com/adswizz](https://github.com/adswizz)

The consolidated, operations-side API index for the group is profiled in the companion repository:

- **[api-evangelist/sirius-xm](https://github.com/api-evangelist/sirius-xm)**

## Notable Absences

- No corporate-level developer portal at the holdings entity itself.
- No public OpenAPI spec for SiriusXM's own player or content APIs (only internal `player.siriusxm.com` and `api.mountain.siriusxm.com` endpoints surface in network traffic).
- No public status page, changelog, or RSS feed at the holdings level.
- No public pricing for AdsWizz, Pandora Developer API, or Simplecast partner tiers - all sales-led.

## Maintainers

- Kin Lane (kinlane@gmail.com)
