# SOURCE_MAP — CXO Hive content intelligence

Living list. Last updated 2026-09-11 (scoring contract). Firecrawl/web-index first; one named-URL Apify hop.

**Scoring:** `RESEARCH_RULES.md` wins. Ship/ingest floor is **8.4**. Novelty cannot lift. 9.0 requires qualified ICP voice, not a guarantee paragraph. Stop at ≥3 items at 8.4+ or after named outlets + index + one named-URL Apify hop. Do not hunt until 9.0.

## How to get results when one path dies (Apify is constrained)

Do **not** keyword-soup LinkedIn on Apify. That burns the budget and returns rings or zeros.

Order that actually produced objects this week:

1. Open this file. Then named-outlet Firecrawl `qdr:w` / `qdr:d`, then **scrape the article**, not the topic hub.
2. Google-index discovery: `site:linkedin.com` + a named deal or person. Read the snippet. **Do not Firecrawl-scrape LinkedIn**.
3. Scrape public non-LinkedIn primaries (ET reprint when Reuters 404s, Livemint, ETGCC).
4. Apify **only** on a specific profile or post URL the index already found. One Actor, small `maxPosts`/`maxComments`, `maxTotalChargeUsd` cap. If 0 items: log the miss and **stop**.
5. Phrase-hop comments on a known operator post beats any new keyword search.
6. If Firecrawl 429s, finish from already-scraped primaries.

Burned / failed methods: company+title+empty/PIP on Apify; ACw URL profile-posts; last-24h `news`+`includeDomains`; Firecrawl scrape of LinkedIn pulse; retrying empties; treating Dhatrak 250/16, Rajesh Srivastava 248/16, or **Rajesh Ramaswami 18/22 and 20/12** as ICP proof. There is **no** post-9.0 method ladder — do not invent one. Novelty-as-lift (9 Sep and 11 Sep) is also burned.

## Named news outlets (open these first)

- Economic Times / ET Tech / ET Careers / ET CIO / **ETGCC** — 10 Sep 2026: “India’s GCCs are creating CEO-ready leaders, but what’s missing?” (`/134009225`). 10 Sep: Wipro 20,000 capacity reprint (`articleshow/134022402.cms`).
- Livemint — 10–11 Sep 2026: DHS proposes ending H-1B 60-day post-layoff grace period.
- Business Standard — 4 Sep: Quess non-tech GCC routine-role decline (dropped as dump). 11 Sep: global tech layoff roundup (Oracle/Amazon) — not a new India-operator object.
- The Hindu Business Line — 8 Sep 2026: Neeti Sharma / TeamLease (used 9 Sep).
- Financial Express
- Moneycontrol
- Reuters — 10 Sep Wipro 20k URL 404’d on live scrape this run; use ET. 10 Sep hack-for-hire Entity List (not ICP career). 24 Aug TCS–Porsche MHP.
- Times of India (business) — Best Buy–TCS still primary: Shilpa Phadnis, 2 Sep 2026, `articleshow/133694028.cms`. Still unconfirmed by companies as of 11 Sep.
- India Today — 9 Sep Cognizant PERM freeze (`2990324-2026-09-09`)
- Porsche Newsroom — 24 Aug 2026 MHP sale (primary)
- Wipro newsroom — 15 May 2026 Mindsprint close (primary)

`includeDomains` + last-24h still returns topic hubs. Prefer `qdr:w` then scrape the article. Reuters permalinks can 404; grab the ET/Mint reprint the same day.

## Seed ICP operators (employed, India, mid-senior / site)

| Person | Why on the list | Notes |
|---|---|---|
| Goutam C S | Director, 4flow India; Ex-VP IT & Cyber | “approval chain tells you the truth.” Low reach. Index hop 11 Sep empty. |
| M I Sheriff | Director – Finance, HPE Bengaluru | Do not retry month profile-posts. |
| Bhalchandra Dhatrak | VP Risk, Compliance & Data Privacy | 250/16 is a ring. 45/0 “board stare” cleaner. |
| Swarup Acharjee | Senior Engineering Program Manager, HPE | Seed. |
| Prem Kumar S. R. | Engineering Leader, Digital & AI | “hatchback budget / Mercedes service.” |
| chetan sharma | Engineering Leader | Do not retry month profile-posts. |
| Dinesha Khataukar | Strategic Leadership / Demand Planning | Do not retry month profile-posts. |
| Yogesh Kantak | Head, GCC & Digital Transformation | #yogism — not usable as own posts. |
| Aditya Singh | Enterprise AI & Global Ops, BFS | % of stop/start decisions in India. |
| Smitha Sriharsha | Global Cybersecurity Leader, Bengaluru | Still missing. |
| Prem Iyangar | Accenture India Lead, Life Sciences tech | Still no clean URL. |
| Karthik Rao U | GCC/GBS, 23 yrs, Bengaluru | Seed. |
| Raktim Singh | Infosys, Senior Industry Principal | Adjacent operator-creator. |
| Indira Muthumani | VP, Bank of America | Thin; keep as hop. |
| Venkatakrishnan Radhakrishnan | 30+ yrs finance/governance, ex-IBM | Authority vs more work. |
| Surendra Bashani | VP, Head of Best Buy India | Do not retry month profile-posts. |
| Nithya Subramanian | Sr Director, Data & AI COE, Best Buy | Still not hopped. |
| Sudarshan Datta | Senior Engineering Manager, FinTech | Phrase-hop only. SEM, not full ICP. |
| Abhinav Dev | VP, Deutsche Bank | Still unused as own-post hop. Index 11 Sep did not recover him. |
| Rajesh Ramaswami | SVP, Persistent (ex-Microsoft, Accenture) | **Hopped 11 Sep.** 18/22 credit post + 20/12 IBM/AI post. Comments are a ring. Do not re-pull this week. Title is ICP; comments are not. |
| Kapil Khaneja | Director, GBS India / Chair, India Management Group, BT | New 11 Sep: quoted on ETGCC panel. Company-page posts only so far. Hop *his* profile next, not ETGCC’s. |
| Manish Tambe | VP–global cloud transition, Dassault Systèmes | New 11 Sep: “touch the top line.” Hop own posts. |

Do not treat CHRO / founder / recruiter / coach / country head as seed ICP. Mohua Sengupta is a **source**, not a seed (country head + co-founder).

## Adjacent creators (calibration only)

| Person | Role | Rule |
|---|---|---|
| Dr Mudit Saxena | CXO Hive | Coach-circle. Not market proof. |
| Rakesh Rana | Adjacent executive coach | Differentiate. |
| Prabal Bhayana | GCC CoS / ops | Skills-budget trap. |
| Anuraj Soni | GCC builder, Ex-CxO | Decision rights already used. |
| Pranav Kaushal | HCLSoftware | “Capability is not ownership.” |
| Dev R | Global delivery / ODC-GCC | 131/23 used 7 Sep. |
| Shammi Prabhakar Singh | GCC builder | “Fourth since April” still unproven in named news. |
| Sunil Khatwani | Celix / GCC advisory | Ring. Adjacent, not ICP. |
| Manan Sharma | HR analytics / GCC-design vendor | Do not hop. |
| Rajesh Srivastava | GCC Leader / Global Product & Tech | 7 Sep 248/16 “month 18.” Creator. |
| Deepika Gandhi | Global Tech & GCC Leader / Director / Board Advisor | Creator/advisor. |
| Gaurav Vasu | UnearthInsight founder | Vendor intel. Calibration only. |
| Pareekh Jain | EIIRTrend | Analyst. |
| Neeti Sharma | CEO, TeamLease Digital | Staffing voice. Source, not ICP. |
| Dhanya Skariachan | Reuters India companies editor | 11 Sep: Wipro 20k post 5/0. Journalist. Not ICP. |
| Roopesh Kumar | Gloplax partner / GCC advisor | On ETGCC Kapil post. Vendor. Phrase only: “visibility… shallow.” |
| Thomas Tsangaras | Career/relocation founder | **On both Rajesh Ramaswami posts 11 Sep.** Ring. |
| ICONIQSPHERE / Aniket A. | Influence vendor | On Rajesh credit post. Ring. |

## Phrases to hunt (found — do not start the next run from a keyword soup)

- “India talent as enterprise talent”
- “touch the top line”
- “accountability vs ownership” (function vs business)
- “20,000 of capacity” / “redeployed”
- “productivity to outcomes”
- “forward-deployed” (FDE) as the client-room seat vs the capacity pile
- “60-day grace”
- “month 18” / “twenty-four months, start to handover”
- “boarding pass” / “Global Coordination Centre”
- “permission to ship”
- “higher level leadership” revision (TeamLease)
- “one person who can do the work of a thousand”
- Cognizant **PERM** / green-card file (not “H-1B ban” unless a primary says so)
- Infosys **JL6** / January 2027 hike calendar — still no ICP thread as of 11 Sep

## Burned / do-not-clone

- Uber flatten / micro-teams
- Hindu BL GCC fractional CXO + ₹1Cr+
- Oracle 6 AM email / Slack member-count
- Mudit 31 Aug capability vs exposure
- Rakesh “Rohit became invisible”
- Mudit 4 Sep “missed promotion isn’t a verdict”
- Nasscom–Zinnov **number dump**
- Prabal 122/27 as a reskill/L&D post
- WACKER–HCLTech Pune GCC (vendor setup)
- TCS GVIC / “AI-native GCC” unit
- ET HDFC CEO succession
- Manan Sharma format
- Leftover Directors / fourth handover (used 7 Sep)
- The two files / PIP vs promotion file (used 7 Sep)
- Decision rights 9.2 / AI roadmap 9.1 (used 7 Sep)
- Rajesh Srivastava 248/16 as a format to clone
- Dhatrak 250/16
- ET 9 Sep “100+ GCCs / $108bn” number dump
- 9 Sep used: month-18 clock; US-hire vs PERM freeze; GCC follows IT-services shrink
- **Rajesh Ramaswami “WHEN SOMEONE ELSE GETS THE CREDIT”** — ring, not a format
- Wipro 20k as a **news recap / layoff scare** (the 11 Sep angle is the *filing*, not the number)
- ETGCC SURGE as an **event recap** or “how to become CEO” listicle
- H-1B 60-day as a visa FAQ or “DM me”

## Engagement rings / noise

- Sarabjit Singh GCC “nerve center”
- Sahil Kapoor layoff roundups
- Sunil Khatwani across GCC posts
- Sandeep Arora / Gupta Polisetty (GCC Academia) on Rajesh Srivastava 248/16
- `"approval chain" GCC` without India filters: Gulf marketing spam
- `"passed over" promotion`: government DPC
- Cognizant PERM comments: sales coaches, “Immediate Joiner,” abusive. Not ICP.
- Jihan Merlin immigration posts: do not treat as DOL fact
- **Rajesh Ramaswami comment set (11 Sep):** self-comments; Thomas Tsangaras (both posts); Elizabeth Lindsey; Michael Lee (fractional CRO); Ulrich Buckenlei; ICONIQSPHERE / Aniket A.; Nandan Mullakara; founder/CEO replies. Same shape as a ghost-comment ring.
- Forward-deployed LinkedIn hits this week: US job ads (Cognizant Plano, Handshake, Lockheed, EdgeVerve). Not ICP demand.

## News objects still live

- TOI 2 Sep: Best Buy–TCS Bengaluru GCC. Still unconfirmed by companies as of 11 Sep.
- Porsche 24 Aug: MHP → TCS. Confirmed primary.
- Wipro 15 May: Mindsprint close. Confirmed primary.
- India Today + ET 9 Sep: Cognizant PERM filings suspended. **Do not write as an H-1B freeze.**
- Livemint 10–11 Sep: DHS **proposal** to end 60-day H-1B grace after layoff. Comment period. Not in force.
- ET / Reuters 10 Sep: Wipro AI = 20,000-employee capacity, redeployed. FDE peer-set: TCS 8,900 / Infosys 6,000.
- ETGCC 10 Sep: “India talent vs enterprise talent” panel quotes.
- Hindu BL 8 Sep: GCCs will follow IT-services hiring pattern (used 9 Sep).
- Naukri JobSpeak 8 Sep: AI/ML 16+ years doubling (supporting).
- Shammi “fourth TCS handover since April”: **other three still unnamed in named-outlet news.**
- US lawmakers 10 Sep: Entity List ask for BellTroX / CyberRoot / Appin. Not a career object unless a named India security Director speaks.

## Apify this pass

- `harvestapi/linkedin-profile-posts` `ZE3pDN4wxmfESjg8X` — Dhanya Wipro 20k; The Standard India SURGE; ETGCC Kapil; Rajesh Ramaswami ×2. 24 items.

Do **not** re-run chetan / Sheriff / Dinesha / bashani month profile-posts, Dhatrak 250/16 comments, 9 Sep Rajesh Srivastava–Deepika–Pareekh–Gaurav URLs, or **this week’s Rajesh Ramaswami URLs**.

## Next-run hunts

1. Employed TCS / Infosys / Wipro / HCL / Accenture / Cognizant / Best Buy / **BT** Directors in their own voice — that is a 9.0, not a ship requirement. An 8.4 news object still ships. **Kapil Khaneja profile**, not the ETGCC page.
2. Company statement on Best Buy–TCS. Do not invent a denial.
3. Manish Tambe own posts; Abhinav Dev still unused.
4. Women SM/Directors in their own voice. Smitha still not recovered. Mohua is a source, not a substitute.
5. H2 appraisal / JL6 January 2027 as October approaches — still dark.
6. Employed Wipro / TCS SM–VP on “redeployed” / FDE — not journalists, not MartechAi.
7. Do not start from yesterday’s keyword list. Open this file, then named outlets, then the seed operators. Apify last, named URL only.
