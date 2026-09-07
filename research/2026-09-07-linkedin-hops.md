# LinkedIn hops — 2026-09-07 (Apify, specified hops only)

Budget-tight pass. Actors: `harvestapi/linkedin-profile-posts`, `harvestapi/linkedin-profile-search` (Short), `harvestapi/linkedin-post-comments`. `maxTotalChargeUsd` split across runs (≤ $2.50 early; later `bashani` hop capped at $0.80). No keyword soup. No `linkedin-post-search`. No retries on empty.

---

## 1) Profile posts

**Input:** `maxPosts` 4, `postedLimit` month, `includeReposts` false, no reactions/comments scrape.

### chetan sharma — `chetan03sharma`

- URL: https://www.linkedin.com/in/chetan03sharma
- Run: `eeGY65GD3OI3u1Rnb` (shared with Sheriff). SUCCEEDED in 3.5s.
- **MISS:** dataset `omo7lPPYszt9mx4jE` returned **0 items**. Not retried.

### M I Sheriff — `m-i-sheriff-2646037`

- URL: https://www.linkedin.com/in/m-i-sheriff-2646037
- Same run as above.
- **MISS:** 0 posts in the month window (or scrape returned empty). Not retried.

No post rows to report (author / headline / URL / date / reactions / comments / reposts / text). Do not invent them.

### Dinesha Khataukar — search then posts

**Search** (`harvestapi/linkedin-profile-search`, Short, `maxItems` 3, locations India, `searchQuery` "Dinesha Khataukar"). Run `MGeOV7qFbf3Fr2dw2`. SUCCEEDED. 1 result (not junk):

| Field | Value |
|---|---|
| Name | Dinesha Khataukar CSCP |
| Location | Greater Bengaluru Area |
| Headline / summary | Senior Supply Chain and IT Leader, 28+ years; demand planning, IT, enterprise systems; semiconductor / technology / financial services. Matches prior comment identity (demand planning / CSCP). |
| Profile URL returned | https://www.linkedin.com/in/ACwAAAD9VeQBslDr_3VnzehasrhwCkrPUPKqcFM |
| publicIdentifier | **not returned** (ACw / member id only) |
| Current positions | empty in Short mode |

**Posts** on that URL. Run `bLtmvn7wE6vL3HyrR`. SUCCEEDED in 5.1s. Dataset `m7w0yqkY2GeP48vOr` = **0 items**.

**MISS:** no own posts in the month window (or ACw URL flake — same failure mode as prior Sheriff ACw scrapes). Not retried. No extra Actors.

---

## 2) Comments — Dhatrak 250/16

**Post:** https://www.linkedin.com/posts/bhalchandra-dhatrak-1682727_riskmanagement-compliance-leadership-activity-7498589121347489792-9vMX  
Bhalchandra Dhatrak, VP Risk / Compliance / Data Privacy. Prior brief: 27 Aug 2026, **250 reactions, 16 comments, 0 reposts** (those post-level metrics are from the earlier brief, not re-scraped this hop).

**Actor:** `harvestapi/linkedin-post-comments`. `maxItems` 12, `profileScraperMode` short, no replies. Run `743pkkMNB19gGMTZ1`. SUCCEEDED. **9 comments returned** (asked 12; post listed 16). Not retried for the rest.

### Verdict: engagement ring / mixed international compliance network — not India SM–VP MNC/IT/GCC

Zero commenters in this sample are clearly **employed India SM–VP at an MNC / IT major / GCC**. The thread is coaches, job-seekers, and global compliance people reacting to a generic leadership / CoE-build story. Do **not** treat 250/16 as ICP proof or a format to clone. The 45/0 “board stare” post remains the cleaner presence object (author is ICP; this comment thread is not).

### Comment table

| Name | Position (as returned) | Flag | Likes | Comment (full; all under 400 chars except Ivana) |
|---|---|---|---|---|
| Ivana Čapková | Leading global compliance efforts with strong problem-solving skills. | **Job-seeker** (says four months of job hunting). Not India ICP. | 0 | “Do you believe a woman with the same profile would be asked to do a job without any previous direct experience? I highly doubt it. I hear this from my male colleagues and friends a lot - getting a job even without relevant experience. What I’m seeing in my own experience now for the past four months of job hunting, we are much more scrutinised for every single job requirement and if it’s even a little bit different, we don’t even get the initial screening call, let alone the interview with the hiring manager or the job for which we have like 90% relevant experience.” (truncated at ~400; rest is gender-bias / learning-curve question.) |
| Grace T. | Compliance Officer | International / junior-title. Not India SM–VP MNC/IT/GCC. | 1 | “A great leader motivates the team by putting talents in the right place, and asking questions.” |
| Kamla Ramlall | Compliance & Risk Executive \| 25+ years Capital Markets \| … \| Exploring Leadership Opportunities in London (Open to NY) | **Job-seeker** (London/NY). Not India. | 1 | “This is a prime example of true Leadership ENABLING the team to deliver by optimizing transferable skills.” |
| Vimal Vyas | Director – Customer Experience @Quantiphi \| … \| Ex – Mooofarm, Tata CLiQ, Orange, Vodafone | **India-adjacent Director**, AI-services (Quantiphi), not MNC/IT/GCC. Closest to ICP in the sample; still CX/services, not the target seat. | 1 | “Bhalchandra Dhatrak, this is so true and I can totally relate.” |
| Yogesh S Gandhi | Developing skills, driving talent… coaching to unlock potential | **Coach / L&D / talent** | 1 | “What a brilliant post, Bhal. Thank you for sharing this - it will allow so many more to believe that this can happen too!” |
| Faizan Gul ACA, CIA | Risk, Compliance & ESG Leader \| … 5 markets | Employed-sounding operator, **not India-located** in this record. | 1 | “I connect with every word in there..thats real practical knowledge. Thanks for sharing” |
| Suniel Kumar L | Global Ethics & Compliance Executive \| Regulatory Affairs & AI Governance | Indian name; comment is **emoji / hashtag engagement** (#CSuiteLeadership…). Not usable as ICP. Employer not given. | 1 | Praise + hashtag dump. Not operating detail. |
| Yejide Adewolu | Lawyer \| Regulatory Compliance & Risk \| Financial Crime | International (not India). | 1 | Resonates: experience without the title; judgement and convening matter more than the name tag. |
| Murk Creusen | Founder, Strength Hack AI \| … \| Executive Coach & Author | **Coach / founder** | 1 | Coach-style question about pushback from technical experts when building a CoE. |

Timestamps (UTC, actor): 27–30 Aug 2026. Not a 15-minute burst. Still not an ICP thread — it is a **topic-network ring** (global GRC / coaches), spread over a few days.

---

## 3) Profile posts — Surendra Bashani (later same day)

**Why this hop, not keyword soup:** Head of Best Buy India is the named leftover-title object. Web index already had `https://www.linkedin.com/in/bashani`. Apify reserved for this one URL.

**Input:** `harvestapi/linkedin-profile-posts`, `maxPosts` 4, `postedLimit` month, `includeReposts` false. Run `pfeV92ETulzJe992C`. Dataset `n6Pa0f0LLG78bffpf`. SUCCEEDED in ~4.9s.

**MISS:** **0 items.** Not retried. Do not invent a statement. Do not switch to an ACw URL.

---

## What this hop does *not* change

- No new own-voice posts from chetan, Sheriff, or Dinesha. Prior comment-only evidence (leftover Directors; cost-arbitrage floor; 12-hour wait) still stands. Do not invent new metrics or posts.
- Dhatrak 250/16 should not be cloned as a performing ICP format.
- Best Buy–TCS company confirmation and employed TCS/Infosys/Wipro/HCL/Accenture/Cognizant Director comments remain missing. Named-outlet re-hunt still found no other TCS handover names. Bashani month posts empty — leftover title is public, his voice is not.

## Runs (do not re-fire)

| Actor | Run | Dataset | Result |
|---|---|---|---|
| linkedin-profile-posts | eeGY65GD3OI3u1Rnb | omo7lPPYszt9mx4jE | 0 (chetan + Sheriff) |
| linkedin-profile-search | MGeOV7qFbf3Fr2dw2 | fbYC1YtrmqswGAgaH | 1 (Dinesha, real) |
| linkedin-profile-posts | bLtmvn7wE6vL3HyrR | m7w0yqkY2GeP48vOr | 0 (Dinesha ACw) |
| linkedin-post-comments | 743pkkMNB19gGMTZ1 | 2adCcHXBF4eYMwuDc | 9 comments |
| linkedin-profile-posts | pfeV92ETulzJe992C | n6Pa0f0LLG78bffpf | 0 (bashani) |
