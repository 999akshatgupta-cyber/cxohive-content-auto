# SOURCE_MAP — CXO Hive content intelligence

Living list. Last updated 2026-09-11 (Friday hunt). Firecrawl MCP first; one named-URL Apify hop (0 items).

## How to get results when one path dies (Apify is constrained)

Do **not** keyword-soup LinkedIn on Apify. That burns the budget and returns rings or zeros.

Order that actually produced objects this week:

1. Open this file. Then named-outlet Firecrawl `qdr:w` / `qdr:d`, then **scrape the article**, not the topic hub.
2. Google-index discovery: `site:linkedin.com` + a named deal or person. Read the snippet. **Do not Firecrawl-scrape LinkedIn**.
3. Scrape public non-LinkedIn primaries / named reprints (ETGCC, Mint, BS, BW People).
4. Apify **only** on a specific profile or post URL the index already found. One Actor, small `maxPosts`/`maxComments`, `maxTotalChargeUsd` cap. If 0 items: log the miss and **stop**.
5. Phrase-hop comments on a known operator post beats any new keyword search.
6. If Firecrawl 429s, finish from already-scraped primaries.

Burned / failed methods: company+title+empty/PIP on Apify; ACw URL profile-posts; last-24h `news`+`includeDomains` (empty this pass); Firecrawl scrape of LinkedIn; retrying empties; treating Dhatrak 250/16 or Rajesh 248/16 as ICP proof; `qdr:d` news source group (returned `news: []`).

## Named news outlets (open these first)

- Economic Times / ET Tech / ET Careers / ET CIO / ETGCC / ETEnterpriseAI
- Livemint — 2 Sep 2026 TimeScope (Jas Bardia, `11788171055386`); 8 Sep Accenture–Google FDE (WSJ reprint, `11788871475878`); 11 Sep Best-of-Week recirculated TimeScope
- Business Standard — 11 Sep Reuters/Wipro 20k (already used as a post; keep as contrast object)
- The Hindu Business Line — 8 Sep TeamLease GCC hiring pattern (used)
- Financial Express — 11 Sep GCC 2,100 / $98bn number dump; skip
- Moneycontrol — market tape; weak for career objects this pass
- Reuters — Wipro 20k permalink can 404; use ET/BS reprint
- Times of India (business) — Best Buy–TCS still unconfirmed
- India Today — Cognizant PERM 9 Sep (used)
- BW People — 3 Sep TimeScope recap of Mint FAQ (`622121`)
- Porsche Newsroom / Wipro newsroom — older primaries

`includeDomains` + last-24h still returns topic hubs or empty news arrays. Prefer `qdr:w` then scrape the article. Mint/ET paywalls truncate; scrape the reprint (BW People, NewsBytes, BS).

## Seed ICP operators (employed, India, mid-senior / site)

| Person | Why on the list | Notes |
|---|---|---|
| Ganpat Anchaliya | Site Head, Novartis Hyderabad | 11 Sep ETGCC interview. Country-head adjacent. Apify profile-posts `UIGuXFGFaoRdWO7JN`: **0 items. Do not retry this week.** |
| Kapil Khaneja | Was Director GBS India / BT | LinkedIn now “Country Head \| GCC Expert”. Drop as ICP seed. Do not hop. |
| Goutam C S | Director, 4flow India; Ex-VP IT & Cyber | “approval chain tells you the truth.” Low reach. |
| M I Sheriff | Director – Finance, HPE Bengaluru | Do not retry month profile-posts. |
| Bhalchandra Dhatrak | VP Risk, Compliance & Data Privacy | 250/16 is a ring. 45/0 “board stare” cleaner. |
| Swarup Acharjee | Senior Engineering Program Manager, HPE | Seed. |
| Prem Kumar S. R. | Engineering Leader, Digital & AI | “hatchback budget / Mercedes service.” |
| chetan sharma | Engineering Leader | Do not retry month profile-posts. |
| Dinesha Khataukar | Strategic Leadership / Demand Planning | Do not retry month profile-posts. |
| Yogesh Kantak | Head, GCC & Digital Transformation | #yogism — not usable as own posts. |
| Aditya Singh | Enterprise AI & Global Ops, BFS | % of stop/start decisions in India. |
| Smitha Sriharsha | Global Cybersecurity Leader, Bengaluru | Still not recovered. Firecrawl 429 mid-hop 11 Sep. |
| Prem Iyangar | Accenture India Lead, Life Sciences tech | Index hop 9 Sep did not recover a clean URL. |
| Karthik Rao U | GCC/GBS, 23 yrs, Bengaluru | Seed. |
| Raktim Singh | Infosys, Senior Industry Principal | Adjacent operator-creator. |
| Indira Muthumani | VP, Bank of America | Thin; keep as hop. |
| Venkatakrishnan Radhakrishnan | 30+ yrs finance/governance, ex-IBM | Authority vs more work. |
| Surendra Bashani | VP, Head of Best Buy India | Do not retry month profile-posts. |
| Nithya Subramanian | Sr Director, Data & AI COE, Best Buy | Still not hopped. 429 this pass. |
| Sudarshan Datta | Senior Engineering Manager, FinTech | “boarding pass” / Global Coordination Centre. SEM, not full ICP. |
| Abhinav Dev | VP, Deutsche Bank | Commented “Insightful” on Rajesh. Hop own posts next. |
| Rajesh Ramaswami | SVP, Persistent | 11 Sep hop was a ring. Stop. |
| Manish Tambe | ETGCC 10 Sep panel | Hop *own* posts, not the ETGCC page. |

Do not treat CHRO / founder / recruiter / coach / Country Head as seed ICP.

## Adjacent creators (calibration only)

| Person | Role | Rule |
|---|---|---|
| Dr Mudit Saxena | CXO Hive | Coach-circle. Not market proof. |
| Rakesh Rana | Adjacent executive coach | Differentiate. |
| Julie Sweet / Karan Bajwa | Accenture exec | Vendor FDE posts. Calibration only. |
| AI PUNNCH / StartupFox | TimeScope aggregators | Not ICP. Ring-adjacent news accounts. |
| Inc42 / DwarfsPlanet | Nilekani reprints | Media. |
| Rajesh Srivastava | GCC Leader | 248/16. Do not clone. |
| Deepika Gandhi | GCC advisor | Creator. |
| Gaurav Vasu | UnearthInsight | Vendor. |
| Pareekh Jain | EIIRTrend | Analyst. |
| Neeti Sharma | TeamLease Digital | Staffing voice. |
| Quess Corp | Staffing | Source for adoption-manager 65%. Not ICP. |

## Phrases to hunt (found — do not start the next run from a keyword soup)

- “India owns the strategy” / “careful not to claim”
- “15% boomerangs” / “left for better titles”
- “idle laptop” / TimeScope / “active time”
- “productivity to outcomes” vs utilisation file
- “1,000 forward-deployed” / Gemini Enterprise Business Group
- “structured roles” / “net job losers” (Nilekani, GFF 2026)
- “AI adoption manager” / “transformation lead” / 65% Quess
- Older still live: “month 18”; “boarding pass”; Cognizant PERM ≠ H-1B; Infosys JL6 / Jan 2027

## Burned / do-not-clone

- Uber flatten / micro-teams
- Hindu BL GCC fractional CXO + ₹1Cr+
- Oracle 6 AM email / Slack member-count
- Mudit 31 Aug / 4 Sep; Rakesh “Rohit became invisible”
- Nasscom–Zinnov / FE 2,100 GCC / ET 100+ GCC number dumps
- WACKER–HCLTech Pune; TCS GVIC
- Leftover Directors / two files / decision rights / AI roadmap (7 Sep)
- Month-18 / US-hire vs PERM / GCC follows IT-services shrink (9 Sep)
- Wipro 20k / India talent vs enterprise talent / H-1B 60-day (11 Sep earlier pass)
- Dhatrak 250/16; Rajesh Srivastava 248/16; Rajesh Ramaswami credit-post
- TimeScope as a privacy/surveillance rant (the *contrast with outcomes* is the unused angle; the recap is burned once posted)

## Engagement rings / noise

- Sarabjit Singh GCC “nerve center”
- Sahil Kapoor layoff roundups
- Sunil Khatwani across GCC posts
- Sandeep Arora / Gupta Polisetty (GCC Academia)
- TimeScope aggregator accounts (AI PUNNCH, StartupFox)
- Cognizant PERM comments: coaches / Immediate Joiner
- `"passed over" promotion`: government DPC

## News objects still live

- TOI 2 Sep: Best Buy–TCS Bengaluru GCC. Still unconfirmed.
- Porsche 24 Aug MHP → TCS. Confirmed.
- Wipro 15 May Mindsprint. Confirmed.
- India Today + ET 9 Sep: Cognizant PERM. Do not write as H-1B freeze.
- **New 11 Sep:** Novartis Hyderabad 25 years / strategy-not-owned / 15% boomerangs (ETGCC).
- **New 2–11 Sep:** Wipro TimeScope idle-laptop → leave (Mint). Recirculated 11 Sep.
- **New 8 Sep:** Accenture + Google Cloud, 1,000 FDEs, Gemini Enterprise Business Group (WSJ/Mint).
- **New 11 Sep:** Nilekani GFF — structured roles in large firms; six IT majors revenue up, headcount flat.
- **New 11 Sep:** ET / Quess — AI adoption managers +65%. Pay numbers behind ET paywall.
- Infosys JL6+ January 2027 — still no ICP thread.

## Apify this pass

- `harvestapi/linkedin-profile-posts` `UIGuXFGFaoRdWO7JN` — Ganpat Anchaliya, week, maxPosts 3, comments on. **0 items. Do not retry this week.**

Do **not** re-run: chetan / Sheriff / Dinesha / bashani month profile-posts; Dhatrak 250/16 comments; 9 Sep Rajesh–Deepika–Pareekh–Gaurav URLs (`lE847qi4jAB0EI8H7`, `qBcygReM6FKC0Ds7R`); 11 Sep Dhanya / Standard India / ETGCC / Rajesh Ramaswami (`ZE3pDN4wxmfESjg8X`).

## Next-run hunts

1. Employed TCS / Infosys / Wipro / HCL / Accenture / Cognizant / Best Buy **Directors in their own voice** — still the missing 9.0.
2. Nithya Subramanian; Abhinav Dev own posts; Manish Tambe own posts. Not Kapil (Country Head). Not Ganpat this week.
3. Women SM/Directors in their own voice. Smitha still missing.
4. Company statement on Best Buy–TCS. Do not invent a denial.
5. H2 appraisal / JL6 January 2027 as October approaches.
6. TimeScope comments from a *named Wipro SM/Director* only. Aggregators are burned.
7. Do not start from yesterday’s keyword list. Open this file, then named outlets, then the seed operators. Apify last, named URL only.
