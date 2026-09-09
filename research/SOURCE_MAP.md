# SOURCE_MAP — CXO Hive content intelligence

Living list. Last updated 2026-09-09 (Monday cron). Firecrawl/web-index first; two named-URL Apify hops.

## How to get results when one path dies (Apify is constrained)

Do **not** keyword-soup LinkedIn on Apify. That burns the budget and returns rings or zeros.

Order that actually produced objects this week:

1. Open this file. Then named-outlet Firecrawl `qdr:w` / `qdr:m`, then **scrape the article**, not the topic hub.
2. Google-index discovery: `site:linkedin.com` + a named deal or person. Read the snippet. **Do not Firecrawl-scrape LinkedIn**.
3. Scrape public non-LinkedIn primaries (Porsche newsroom, Wipro IR, Reuters, Hindu BL).
4. Apify **only** on a specific profile or post URL the index already found. One Actor, small `maxPosts`/`maxComments`, `maxTotalChargeUsd` cap. If 0 items: log the miss and **stop**.
5. Phrase-hop comments on a known operator post beats any new keyword search.
6. If Firecrawl 429s, finish from already-scraped primaries.

Burned / failed methods: company+title+empty/PIP on Apify; ACw URL profile-posts; last-24h `news`+`includeDomains`; Firecrawl scrape of LinkedIn pulse; retrying empties; treating Dhatrak 250/16 or Rajesh 248/16 as ICP proof.

## Named news outlets (open these first)

- Economic Times / ET Tech / ET Careers / ET CIO
- Livemint
- Business Standard
- The Hindu Business Line — 8 Sep 2026: Neeti Sharma / TeamLease Digital, GCCs will follow IT-services hiring pattern (`article71441218.ece`). 6 Sep notice-period piece is HR, not ICP.
- Financial Express
- Moneycontrol
- Reuters — 24 Aug 2026: TCS–Porsche MHP
- Times of India (business) — Best Buy–TCS still primary: Shilpa Phadnis, 2 Sep 2026, `articleshow/133694028.cms`. Still unconfirmed by companies as of 9 Sep.
- India Today — 9 Sep 2026: Cognizant PERM freeze (`2990324-2026-09-09`)
- Porsche Newsroom — 24 Aug 2026 MHP sale (primary)
- Wipro newsroom — 15 May 2026 Mindsprint close (primary)

`includeDomains` + last-24h still returns topic hubs. Prefer `qdr:w` then scrape the article.

## Seed ICP operators (employed, India, mid-senior / site)

| Person | Why on the list | Notes |
|---|---|---|
| Goutam C S | Director, 4flow India; Ex-VP IT & Cyber | “approval chain tells you the truth.” Low reach. |
| M I Sheriff | Director – Finance, HPE Bengaluru | Do not retry month profile-posts. |
| Bhalchandra Dhatrak | VP Risk, Compliance & Data Privacy | 250/16 is a ring. 45/0 “board stare” cleaner. |
| Swarup Acharjee | Senior Engineering Program Manager, HPE | Seed. |
| Prem Kumar S. R. | Engineering Leader, Digital & AI | “hatchback budget / Mercedes service.” |
| chetan sharma | Engineering Leader | Do not retry month profile-posts. |
| Dinesha Khataukar | Strategic Leadership / Demand Planning | Do not retry month profile-posts. |
| Yogesh Kantak | Head, GCC & Digital Transformation | #yogism — not usable as own posts. |
| Aditya Singh | Enterprise AI & Global Ops, BFS | % of stop/start decisions in India. |
| Smitha Sriharsha | Global Cybersecurity Leader, Bengaluru | Index hop 9 Sep returned noise, not her. Hop again with a cleaner publicIdentifier. |
| Prem Iyangar | Accenture India Lead, Life Sciences tech | Index hop 9 Sep did not recover a clean URL. |
| Karthik Rao U | GCC/GBS, 23 yrs, Bengaluru | Seed. |
| Raktim Singh | Infosys, Senior Industry Principal | Adjacent operator-creator. |
| Indira Muthumani | VP, Bank of America | Thin; keep as hop. |
| Venkatakrishnan Radhakrishnan | 30+ yrs finance/governance, ex-IBM | Authority vs more work. |
| Surendra Bashani | VP, Head of Best Buy India | Do not retry month profile-posts. |
| Nithya Subramanian | Sr Director, Data & AI COE, Best Buy | Still not hopped. |
| Sudarshan Datta | Senior Engineering Manager, FinTech | New 9 Sep: “boarding pass” / Global Coordination Centre. SEM, not full ICP. Phrase-hop only. |
| Abhinav Dev | VP, Deutsche Bank | Commented “Insightful” on Rajesh. Title is closer to ICP than the comment. Hop own posts next. |
| Rajesh Ramaswami | SVP, Persistent (ex-Microsoft, Accenture) | New 9 Sep: product ownership is the harder one. IT-major SVP — hop own posts. |

Do not treat CHRO / founder / recruiter / coach as seed ICP.

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
| Sunil Khatwani | Celix / GCC advisory | **On Deepika 7–9 Sep.** Ring. Adjacent, not ICP. |
| Manan Sharma | HR analytics / GCC-design vendor | Do not hop. |
| Rajesh Srivastava | GCC Leader / Global Product & Tech | 7 Sep 248/16 “month 18.” Creator. Do not treat metrics as ICP proof. |
| Deepika Gandhi | Global Tech & GCC Leader / Director / Board Advisor | 7–9 Sep ownership-without-authority. Creator/advisor. |
| Gaurav Vasu | UnearthInsight founder | Vendor intel. Best Buy 40/0; MHP 24/1. Calibration only. |
| Pareekh Jain | EIIRTrend | Analyst. Cognizant PERM 62/2 — coaches/job-seekers in comments. |
| Neeti Sharma | CEO, TeamLease Digital | Staffing voice. Source, not ICP. |

## Phrases to hunt (found — do not start the next run from a keyword soup)

- “month 18” / “twenty-four months, start to handover”
- “boarding pass” / “Global Coordination Centre”
- “permission to ship”
- “higher level leadership” revision (TeamLease)
- “one person who can do the work of a thousand”
- “safe haven” GCC → now following IT-services shrink
- “approval chain” / “who signs off”
- “decision rights” / leftover / “director and above”
- “waits 12 hours”
- “the India team”
- Microsoft **PIP** as a paper-trail object
- Infosys **JL6** / January 2027 hike calendar
- Cognizant **PERM** / green-card file (not “H-1B ban” unless a primary says so)
- Naukri **16+ years** AI/ML doubling (supporting, not a recap)

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
- Rajesh 248/16 as a format to clone
- Dhatrak 250/16
- ET 9 Sep “100+ GCCs / $108bn” number dump

## Engagement rings / noise

- Sarabjit Singh GCC “nerve center”
- Sahil Kapoor layoff roundups
- Sunil Khatwani across GCC posts (again on Deepika)
- Sandeep Arora / Gupta Polisetty (GCC Academia) on Rajesh 248/16
- `"approval chain" GCC` without India filters: Gulf marketing spam
- `"passed over" promotion`: government DPC
- Cognizant PERM comments so far: sales coaches, “Immediate Joiner,” abusive. Not ICP.
- Jihan Merlin immigration posts: do not treat as DOL fact (ET: PERM ≠ H-1B)

## News objects still live

- TOI 2 Sep: Best Buy–TCS Bengaluru GCC. Still unconfirmed by companies. Commenter claim of a “rumour” denial is **not** a primary.
- Porsche 24 Aug: MHP → TCS, 4,500+, Ludwigsburg. Confirmed primary. Bengaluru entity Oct 2024, no senior India owner — Gaurav observation, not a company line.
- Wipro 15 May: Mindsprint close, 3,200+. Confirmed primary. Announced 6 Apr.
- HCLTech–Guardian (older): still the named India captive buy.
- India Today + ET 9 Sep: Cognizant PERM filings suspended; Cloudera also named. Cognizant announced 1,500 US grads + 15,000 Frontier US roles the day before. **Do not write this as an H-1B freeze.**
- Hindu BL 8 Sep: GCCs will follow IT-services hiring pattern (Neeti Sharma).
- Naukri JobSpeak 8 Sep: AI/ML +31%; 16+ years AI/ML postings more than doubled.
- ET 9 Sep: 100+ new GCCs / $108bn — number dump, do not recap.
- ET 24 Aug: Infosys JL6+ January 2027 — still no ICP thread.
- Shammi “fourth TCS handover since April”: **other three still unnamed in named-outlet news.** MHP is not a Bengaluru GCC handover. Mindsprint is Wipro, not TCS.

## Apify this pass

- `harvestapi/linkedin-profile-posts` `lE847qi4jAB0EI8H7` — Rajesh, Deepika, Gaurav Best Buy, Sriram (discard). 14 items.
- `harvestapi/linkedin-profile-posts` `qBcygReM6FKC0Ds7R` — Pareekh PERM, Gaurav MHP. 5 items.

Do **not** re-run chetan / Sheriff / Dinesha / bashani month profile-posts or Dhatrak 250/16 comments.

## Next-run hunts

1. Employed TCS / Infosys / Wipro / HCL / Accenture / Cognizant / Best Buy Directors in their own voice — still the missing parameter-honest 9.5.
2. Company statement on Best Buy–TCS. Do not invent a denial from Meha’s comment.
3. Rajesh Ramaswami (SVP Persistent) and Abhinav Dev (VP Deutsche Bank) own posts — named, unused profile hops.
4. Women SM/Directors in their own voice. Smitha still not recovered.
5. H2 appraisal / JL6 January 2027 as October approaches.
6. Cognizant / other IT-major PERM or mobility language from employed India SM–VP only. Ignore immigration attorneys.
7. Do not start from yesterday’s keyword list. Open this file, then named outlets, then the seed operators. Apify last, named URL only.
