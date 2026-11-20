# AI Assisted Research #5 — corrected publication review

**November 19, 2026 (America/Chicago). Public publication checks passed within scope. Monitor reconciliation is blocked before staging.**

## Published version and provenance

Blogger post `5189770922046338568` in blog `5793283855177519383` was originally published at `2026-11-10T11:42:38.051-06:00`. The public single-post feed reports the corrected version updated at `2026-11-19T21:29:58.948-06:00`. The canonical page and feed independently returned HTTP 200 at `2026-11-20T03:32:00Z` (November 19 at 9:32 p.m. Central), both with Last-Modified `2026-11-20T03:29:58Z` at HTTP header precision. [Canonical post](https://www.beyond-the-light-barrier.com/2026/11/ai-assisted-research-5-can-ai-help-us.html) · [Public Blogger JSON feed](https://www.beyond-the-light-barrier.com/feeds/posts/default/5189770922046338568?alt=json)

| Retrieved artifact | Bytes | SHA-256 |
|---|---:|---|
| UTF-8 encoding of decoded feed `entry.content.$t` | 33,037 | `7a6dfa5a05a7474d47e28371caa7fe7bcaf5dd5e70625a8fd00f5d860bfe9e15` |
| Raw public single-post JSON | 43,155 | `d6254832843c45ada714e0c53d3487a245df4b31d458b2558bb3505f76afe325` |
| Raw canonical page HTML | 107,723 | `c6013c0c5859b3488a8670ec6544d37900969fd858caa9035b9814ed406db2d9` |
| Article element cut from raw canonical page | 32,811 | `afc7b5c9a0c0997400579da557c62395ae976190920f513dc3a84cd0ed53a372` |
| Inline Figure 1 PNG | 600 × 307 px | `f350e915d9aa7f08f2dafed09476578a3e84139ec8e9c8213b2cc7ccc54555f4` |

The raw editor attachment path was unavailable. I reconstructed the 32,998-byte `Pasted text(20261120-032249).txt` baseline from the archived November 17 feed HTML and the earlier exact unified diff. Its SHA-256 reproduced the previously recorded editor digest `a1d2c283f780342e6efb6483e35b2e3a42f35aa2f3b06545ba83d4fadb099cc4`. Inserting the 39-byte responsive attribute on the Figure 1 image yielded a byte-for-byte match to the current feed HTML. The canonical page and feed article have identical decoded, whitespace-normalized text and matching parsed tag/attribute sequences except for the page image's added `loading="lazy"`. Raw serialization also differs in whitespace and character references.

The Blogger API v3 request returned HTTP 403 `PERMISSION_DENIED` and `ACCESS_DENIED` at `2026-11-20T03:32:01Z` (error payload SHA-256 `cbf612f20f4ecbdd7806032a900dabeae94c9a3f74e64e19e84d2727995e1a9b`). The public feed timestamp and hash describe the feed representation. API v3 `updated`, `content`, and serialization parity remain unverified. [Blogger v3 post endpoint](https://www.googleapis.com/blogger/v3/blogs/5793283855177519383/posts/5189770922046338568)

## Scientific and editorial findings

- **Figure 1** — Both representations link to the replacement conceptual graphic, using the 600-pixel rendition inline and the 1752-pixel rendition as the link target. The inline rendition returned HTTP 200 and was visually inspected. The published image tag includes `style="max-width: 100%; height: auto;"` and `width="600"`. This verifies responsive markup at source level. Narrow-viewport rendering was not measured. The caption, alt text and image identify a hypothetical example and describe evidence as supporting, constraining or contradicting a model within the tested domain.
- **Einstein** — The linked 1916 wave-paper reference reads “German text, digital edition.” Edition Open Sources identifies the linked item as the Blum and Rickles sourcebook edition of Einstein’s paper. [Digital edition](https://edition-open-sources.org/sources/10/4/index.html)
- **GW150914** — The wording attributes the September 14, 2015 observation to the two LIGO detectors, describes the signal as consistent with a binary black hole merger, and dates the peer-reviewed report to February 2016. The observation and subsequent publication dates agree with Abbott et al. [Observation paper and Fig. 1](https://doi.org/10.1103/PhysRevLett.116.061102)
- **Revision history and evidence classification** — The November 16 revision note remains visible. The current text identifies what the pinned earlier snapshot actually preserves, namely the figure URL and markup. The historical November 16 wording remains in its own snapshot. The teaching equation remains hypothetical, and the article introduces no new validated model, simulation result or experimental finding.

## Historical dispositions and reconciliation

Both archived JSON bodies were read at commit `4d1b20573c246590881d6fe2d07166c20de165b0`. Their raw archive, embedded HTML and stored-text SHA-256 values were recomputed and checked against the snapshot and manifest fields as applicable.

| Historical version | Retained assessment | Archive SHA-256 |
|---|---|---|
| November 10, `aed587625b2d1094774c2bd0a569913b8cdc43edc7cb2cbddc941f769a02ec48` | **FINDINGS.** Original illustration and markup documented by the snapshot. Original image bytes remain unverified. [Pinned snapshot](https://github.com/markkoehn0/btlb-feed-monitor/blob/4d1b20573c246590881d6fe2d07166c20de165b0/articles/5189770922046338568/aed587625b2d1094774c2bd0a569913b8cdc43edc7cb2cbddc941f769a02ec48.json) | `8193afbec766089322cc077992baa71d2ad141081f0a9dd70c6c79c5b03cbef2` |
| November 16, `a15105afa914acfe70443afff54248d416e3bdeefdf792873afd591366977f7f` | **FINDINGS.** Historical revision note makes a stronger image-archive claim than the available evidence supports. The current article corrects that claim. [Pinned snapshot](https://github.com/markkoehn0/btlb-feed-monitor/blob/4d1b20573c246590881d6fe2d07166c20de165b0/articles/5189770922046338568/a15105afa914acfe70443afff54248d416e3bdeefdf792873afd591366977f7f.json) | `a613aadb4806b6e894cbccf9a0b4247a7f3cb983f70ef25fac422cc061cdf392` |

The current feed capture documents the corrected public successor for both historical entries. The monitor did not contain a snapshot at the observed feed hash (GitHub contents returned HTTP 404), and API v3 parity could not be checked. The manifest read showed both entries pending among nine, at Git blob `0bfeb7d0644e7e9def7a5e869a7ef8bd0601c463`. Each independent offline projection removed its exact target and preserved the order and content of the other eight entries. These projections carry no approval hashes. The immutable monitor successor and guarded verifier evidence are required for production staging and a fresh `READY` dry run for each entry. Any live acknowledgment requires separate explicit approval against the corresponding fresh approval hash.
