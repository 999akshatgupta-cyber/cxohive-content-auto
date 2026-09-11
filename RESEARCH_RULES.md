# CXO Hive — Research Rules (scoring contract)

This file **wins** on scoring floors, evidence split, Novelty, ingest, and stop conditions.

Read this before `Research Rules.rtf`. The RTF still governs research method (named outlets first, no LinkedIn scrape, no invented impressions). Where this file and the RTF or the Cursor automation prompt disagree on **numbers**, use this file.

The 9 Sep and 11 Sep briefs Novelty-inflated because of a contradiction: the RTF caps Evidence of Attention < 7 at **7.4**; the automation prompt caps news-without-ICP-comments at **8.4**, then says ingest only **9.0+** and lets Novelty stamp 9.0–9.5. ICP operators almost never comment publicly on employer news. Apify is budget-capped. So every run either ships nothing honest, or lies with Novelty. That is a scoring bug, not a quality bar.

---

## The score we keep

**Ship / ingest floor: 8.4**

That is the number we will actually hit on a good news week, and it is the number that still produces posts this audience will recognise. Do not raise it to 9.0. Do not lower it to 7.5.

| Score | What it means | Ship? |
|---|---|---|
| **< 8.4** | Topic, dump, visa FAQ, clone, vendor ring, or no named primary. | No. Do not ingest. |
| **8.4** | Named primary + specific tension + ICP would recognise it this week + original CXO Hive angle. ICP LinkedIn comments **not** required. | **Yes. Default ship band.** |
| **8.7–8.9** | 8.4 plus ICP-adjacent operator voice (India employed SM+ at MNC/IT/GCC in their **own** post, comments may still be thin). | Yes. Prefer over a bare 8.4 when both exist. |
| **9.0–9.4** | Qualified ICP (India employed SM–VP, 12–25 yrs, MNC/IT/GCC) in their own post **or** in comments that are not a ring. | Yes. Rare. Do not hunt until you force one. |
| **9.5** | Multiple qualified ICP voices + a named market object + an original angle. | Yes. Almost never. Not a “guarantee paragraph.” |

**8.4 is the publish-confidence bar.** It matches what the RTF meant by “strong enough we would confidently consider publishing” — that sentence was wrongly numbered 9.0, which made honest news unshippable.

**9.0 is proof the buyer already spoke.** It is not the weekly quota.

This morning’s three ideas were 8.4 / 8.4 / 8.4 under this contract. They were worth posting. They were not 9.5s.

---

## Evidence is two scores, not one

The RTF’s “Evidence of Attention < 7 → max 7.4” is correct for **LinkedIn posts** (a weak post is a weak post). It is wrong for **news** if “attention” is defined as ICP LinkedIn comments. The RTF already says: do not pretend a news story has performed before CXO Hive content exists.

Split it:

1. **Market attention** (news / named filing)
   - Named outlet, named operator or filing, specific number or clock.
   - Can score **≥ 7** with zero LinkedIn comments.
   - Journalist 5/0, company-page self-comment, vendor, US job ads, and comment rings do **not** raise this.

2. **ICP engagement** (buyer voice)
   - Qualified ICP in own post or comments.
   - Coaches, founders, country-head self-comments, GCC advisors, journalist reprints: **not ICP**.
   - This gates **9.0+ only**. It does not gate 8.4.

If you only have market attention, the ceiling is **8.4–8.6**, not 7.4 and not 9.5.

---

## Novelty cannot lift a score

Novelty is a news-source *factor* (is this a new development). It is not a stamp.

Forbidden:

- “Parameters cap at 8.4. Novelty lift to 9.5.”
- “Guarantee (why this is a 9.5 for our use case)” used as a substitute for ICP evidence.
- Labelling source type `News + Novelty` to clear an ingest floor the item did not earn.

A CXO Hive-derived angle is **Differentiation**, scored on the same ladder. Typical honest band for a sharp original angle on named news: **8.4–8.6**.

If the only way the item reaches the ingest floor is Novelty, **do not ingest it**. Either it is already 8.4 without the lift, or it is not shippable.

---

## Required checklist on every published item

Fill this. If any of 1–5 is No, the item is below 8.4.

1. Named primary URL (article or operator post): yes/no
2. Named India operator, company filing, or specific clock/number: yes/no
3. Specific tension (not a topic like “leadership” or “AI jobs”): yes/no
4. Employed SM–VP at MNC/IT/GCC would recognise it without a headline dump: yes/no
5. Original CXO Hive angle (not a clone of a used object this month): yes/no
6. Qualified ICP voice: none / adjacent / qualified / multiple
7. Novelty used as a numeric lift: **must be no**

Score from the table. Write the honest number. Then stop.

---

## Ingest and stop conditions

- Ingest **8.4+** only. Drafts, not published posts, unless a human asks otherwise.
- Prefer the three sharpest 8.4s over one fake 9.5.
- **Stop** when you have ≥ 3 items at 8.4+, **or** you have finished named-outlet scan + index hop + one named-URL Apify hop.
- Do **not** “keep going until 9.0.” There is no post-9.0 method ladder. Do not invent one.
- Do not re-fire burned Apify URLs (see `research/SOURCE_MAP.md`).
- Do not re-ingest GrowthX drafts unless a human asks.

---

## What still fails below 8.4 (do not weaken this)

- Hiring dumps, boom slides, sq-ft, unnamed “industry sources”
- Visa explainers, job-seeker gravity, “DM if your H-1B is stuck”
- Comment rings, journalist metrics treated as ICP proof
- Clones of used objects (Uber flatten, PERM freeze as a second H-1B post, leftover-Directors, PIP-file, month-18)
- Country heads / presidents as the buyer
- Skills/L&D recap of a training number

The floor moved from 9.0 to 8.4 so we can tell the truth. It did not move so we can ship dumps.

---

## Automation prompt (must match this file)

Until the Cursor automation template says **ingest 8.4+**, **Novelty cannot lift**, and **stop at 3 × 8.4 or full hop sequence**, the next cron will still Novelty-inflate. Repo rules lose if the prompt still says “ingest only 9.0+.” Change the template to match this file.
