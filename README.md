# Sirius XM Holdings

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
