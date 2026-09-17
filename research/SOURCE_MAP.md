# SOURCE_MAP — CXO Hive content intelligence

Living list. Last updated 2026-09-17 (Thursday hunt). Firecrawl MCP first. Apify not run this pass (no new named ICP own-post URL).

## How to get results when one path dies (Apify is constrained)

Do **not** keyword-soup LinkedIn on Apify. That burns the budget and returns rings or zeros.

Order that actually produced objects this week:

1. Open this file. Then named-outlet Firecrawl `qdr:w` / `qdr:d`, then **scrape the article**, not the topic hub.
2. Google-index discovery: `site:linkedin.com` + a named deal or person. Read the snippet. **Do not Firecrawl-scrape LinkedIn**.
3. Scrape public non-LinkedIn primaries / named reprints (ETGCC, ET AMP, BL, India Today).
4. Apify **only** on a specific profile or post URL the index already found. One Actor, small `maxPosts`/`maxComments`, `maxTotalChargeUsd` cap. If 0 items: log the miss and **stop**.
5. Phrase-hop comments on a known operator post beats any new keyword search.
6. If Firecrawl 429s, finish from already-scraped primaries.

Burned / failed methods: company+title+empty/PIP on Apify; ACw URL profile-posts; last-24h `news`+`includeDomains` (empty again 17 Sep on Mint/BS/ET group); Firecrawl scrape of LinkedIn; retrying empties; treating Dhatrak 250/16 or Rajesh 248/16 as ICP proof; `qdr:d` news source group (returned `news: []`); Mint/ET desktop paywall without an AMP or reprint; treating LinkedIn News + ETHRWorld/StartupTalky Adidas posts as ICP demand.

`Research Rules.rtf` still has **no method ladder after a blocked 9.0**. Do not invent one.

## Named news outlets (open these first)

- Economic Times / ET Tech / ET Careers / ET CIO / ETGCC / ET AI / ETEnterpriseAI — Oracle 27k used 17 Sep; Adidas Gurugram AMP used 17 Sep; Infosys Indore dropped
- Livemint — TimeScope and Accenture–Google FDE already used; Oracle 6 AM reprints this week are burned
- Business Standard — Wipro 20k used; Adidas aggregator post this week not ICP
- The Hindu Business Line — TeamLease used; Axis Bank 400/−3% used 14 Sep
- Financial Express — GCC number dumps; skip
- Moneycontrol — market tape; weak
- Reuters — permalinks can 404; use ET/BS reprint
- Times of India (business) — Best Buy–TCS still unconfirmed; Adidas Gurugram town-hall recap 17 Sep
- Financial Times — PwC JV open dek used 14 Sep; body paywalled
- India Today — Cognizant PERM used; Adidas <20% statement used 17 Sep
- NDTV business — Adidas Dec 15 / handover colour; prefer ET + India Today for the company line
- BW People — TimeScope recap used
- Apexon PDF — 8 Sep ET FDE-army reprint (used 13 Sep)
- Porsche Newsroom / Wipro newsroom — older primaries
- EY.com GCC insights — Pulse Survey Nov 2025 80%/10% is **old**; do not treat a 12 Sep HR recirculation as this week’s news

`includeDomains` + last-24h still returns topic hubs or empty news arrays. Prefer `qdr:w` then scrape the article. ET desktop paywalls truncate; try AMP (`m.economictimes.com` / `amp_articleshow`) or a named reprint. Thursday 17 Sep last-24h was Adidas clarification + BRICS/unrelated leftover; the week objects were Oracle 16 Sep, leaner GCC 16 Sep, Adidas 16–17 Sep, Lalitha 15 Sep.

## Seed ICP operators (employed, India, mid-senior / site)

| Person | Why on the list | Notes |
|---|---|---|
| Ganpat Anchaliya | Site Head, Novartis Hyderabad | Used 11 Sep. Apify `UIGuXFGFaoRdWO7JN`: **0 items. Do not retry this week.** |
| Kapil Khaneja | Was Director GBS India / BT | LinkedIn now “Country Head \| GCC Expert”. Drop as ICP seed. Do not hop. |
| Goutam C S | Director, 4flow India; Ex-VP IT & Cyber | “approval chain tells you the truth.” Low reach. |
| M I Sheriff | Director – Finance, HPE Bengaluru | Do not retry month profile-posts. |
| Bhalchandra Dhatrak | VP Risk, Compliance & Data Privacy | 250/16 is a ring. 45/0 “board stare” cleaner. |
| Swarup Acharjee | Senior Engineering Program Manager, HPE | Seed. Week hop empty. |
| Prem Kumar S. R. | Engineering Leader, Digital & AI | “hatchback budget / Mercedes service.” |
| chetan sharma | Engineering Leader | Do not retry month profile-posts. |
| Dinesha Khataukar | Strategic Leadership / Demand Planning | Do not retry month profile-posts. |
| Yogesh Kantak | Head, GCC & Digital Transformation | #yogism — not usable as own posts. |
| Aditya Singh | Enterprise AI & Global Ops, BFS | % of stop/start decisions in India. 17 Sep name-search returned the wrong Adityas. Need the BFS profile URL before Apify. |
| Smitha Sriharsha | Global Cybersecurity Leader, Bengaluru | Still not recovered. |
| Prem Iyangar | Accenture India Lead, Life Sciences tech | Index hop 9 Sep did not recover a clean URL. |
| Karthik Rao U | GCC/GBS, 23 yrs, Bengaluru | Seed. |
| Raktim Singh | Infosys, Senior Industry Principal | Adjacent operator-creator. Week hop empty. |
| Indira Muthumani | VP, Bank of America | Thin; keep as hop. |
| Venkatakrishnan Radhakrishnan | 30+ yrs finance/governance, ex-IBM | Authority vs more work. |
| Surendra Bashani | VP, Head of Best Buy India | Do not retry month profile-posts. |
| Nithya Subramanian | Sr Director, Data & AI COE, Best Buy | 17 Sep week hop: **empty**. Still only vendor/event tags historically. |
| Sudarshan Datta | Senior Engineering Manager, FinTech | “boarding pass” / Global Coordination Centre. SEM, not full ICP. |
| Abhinav Dev | VP, Deutsche Bank | 17 Sep week hop: **empty**. Still no own-post URL. |
| Rajesh Ramaswami | SVP, Persistent | 11 Sep hop was a ring. Stop. |
| Manish Tambe | VP-global cloud transition, Dassault | SURGE quotes used 13 Sep. 17 Sep week hop empty. Hop *own* posts only. |
| Pawan Panjwani | CEO & country head, AllianceBernstein India | “just exit” used 13 Sep. Country-head adjacent. |
| Kailash Maisekar | Country director, Idox plc | Accountability vs ownership. Country-head adjacent. |
| Mohua Sengupta | SVP & country head, The Standard India | “India talent vs enterprise talent” **used**. |
| Bibhu Krishna | CTO, Policybazaar | Skills vs responsibility. C-suite. Calibration. |
| Suyog Saraiya | VP, DP World GSC | “SOP-given task” used 14 Sep. Country-head adjacent. Own posts not recovered. |
| Sreedevi Hegde | SVP & country head, Acentra Health | Coffee-check / junior idea used 14 Sep. Country-head. Own posts are GCC-setup tags. |
| Navin Bishnoi | VP & India country head, Marvell | Customer-not-paying used 14 Sep. Country-head. CONNECT/VDAT tags only. |
| Nagalakshmi Shetty | VP CDS & India country head, ICON | Fail-fast POC unused. Country-head. Keep as hop, not seed ICP. |
| Aruna Santosh | Director, PwC Acceleration Centers | 17 Sep: still profile only (`in/aruna-santosh-273000288`). Hackathon tags, not JV or own-voice. Next 9.0 hop if she posts on the JV. |
| Samarjit Mukherjea | Director, Assurance Quality, PwC ACs | “25 years at PwC” anniversary URL recovered; not a JV reaction. Do not Apify unless the post is about the JV. |
| Nithya Cadambi | GM – global CoE, Commvault | Quoted 16 Sep leaner GCC. No own-post URL recovered. Possible hop, not seed until title/location confirmed employed India. |
| Navaneet Mishra | Head and SVP, Hexagon R&D India | Quoted 16 Sep on owning the problem. No own-post URL. Country-head adjacent. |
| Teja Manakame | VP product and engineering, Curriculum Associates | Domain-intersection quote 16 Sep. Confirm India seat before treating as ICP. |
| Lalitha Indrakanti | CEO, JLR Technology and Business Services India | Faces of Change used 17 Sep. Country-head. Own posts not recovered. |

Do not treat CHRO / founder / recruiter / coach / Country Head / Partner-advisor / Head of HR / Global Head People Ops as seed ICP.

## Adjacent creators (calibration only)

| Person | Role | Rule |
|---|---|---|
| Dr Mudit Saxena | CXO Hive | Coach-circle. Not market proof. |
| Rakesh Rana | Adjacent executive coach | Differentiate. |
| Julie Sweet / Karan Bajwa | Accenture exec | Vendor FDE posts. Calibration only. |
| Ankit Garg | Partner, GCC Leadership and Transformation | PwC JV recap. **Not ICP.** |
| Munish Gupta | Unconfirmed; “worked both sides” on PwC JV | Do not treat as ICP until title is known. |
| AI PUNNCH / StartupFox | TimeScope aggregators | Not ICP. |
| Inc42 / DwarfsPlanet | Nilekani reprints | Media. |
| Rajesh Srivastava | GCC Leader | 248/16. Do not clone. Recapped Best Buy–TCS again last week. |
| Deepika Gandhi | GCC advisor | Creator. |
| Gaurav Vasu | UnearthInsight / UnearthIQ | Vendor/analyst. Quoted on Oracle 16 Sep. Not ICP. |
| Pareekh Jain | EIIRTrend | Analyst. Quoted on Oracle 27k. Not ICP. |
| Neeti Sharma | TeamLease Digital | Staffing voice. |
| Quess Corp | Staffing | FDE 1,300–1,500; adoption-manager 65%. Not ICP. |
| Shristi Achar | ET reporter | FDE-army recap. Not ICP. |
| CXO Lanes / CXO TechBOT / The 365 Circle | Appointment aggregators | Tambe elevation ring. Not ICP. |
| Dhananjay Sinha / Haslinda Amin | Analyst / Bloomberg | Axis reprints. Not ICP. |
| Sanketh Ramkrishnamurthy | Global Head – People Operations, AutoRABIT | HR. 80%/10% EY recirculation. Do not Apify. |
| Vivek Mishra | Former -Head (Adidas GCC post) | Not employed ICP. |
| Padmavati Rallapalli | Head of HR, The Hartford India | HR. 14 Sep ETGCC. Skip as voice. |
| Girija Kolagada | Country manager India & VP HR BP APAC, Progress | HR. Mid-career quote is usable; she is not ICP. |
| Somnath Baishya | People director, Tesco Business Solutions | HR. Skill-density colour only. |
| ETHRWorld / IndianStartupNews / StartupTalky / ThePeoplesBoard / VieStories | Adidas layoff aggregators | Ring. Not ICP. |
| Bhuvana Kamath | ETGCC reporter | Media. |

## Phrases to hunt (found — do not start the next run from a keyword soup)

- “several open roles” / “other technology hubs” / “15 December” / “less than 20%”
- “30,000 to 27,000” / “case-by-case” / “fit the bill” / “execute predefined tasks”
- “skill-density” / “mandate up, headcount flat” / “mid-career talent bridge”
- “opportunity before they feel completely ready” / “this is what we do not know yet”
- Older still live: “operating control” / “isn't about where work gets done” / “49.9%” (used 14 Sep)
- “400 branches” / “headcount fell 3%” (used 14 Sep)
- “SOP-given task” / “coffee check” / “If a customer is not paying for it” (used 14 Sep)
- “head of operations now is also my chief digital officer” (Axis Max — unused as a post)
- Burned as post copy: “India owns the strategy”; “idle laptop”; “India talent vs enterprise talent”; “AI adoption manager”; Oracle 6 AM / Slack-count

## Burned / do-not-clone

- Uber flatten / micro-teams
- Hindu BL GCC fractional CXO + ₹1Cr+
- Oracle 6 AM email / Slack member-count (Mint/ET reprints 14–16 Sep are the same object)
- Mudit 31 Aug / 4 Sep; Rakesh “Rohit became invisible”
- Nasscom–Zinnov / FE 2,100 GCC / ET 100+ GCC number dumps
- WACKER–HCLTech Pune; TCS GVIC; Woodside Bengaluru opening
- Leftover Directors / two files / decision rights / AI roadmap (7 Sep)
- Month-18 / US-hire vs PERM / GCC follows IT-services shrink (9 Sep)
- Wipro 20k / India talent vs enterprise talent / H-1B 60-day (11 Sep earlier)
- Novartis strategy-not-owned / TimeScope / Accenture 1,000 FDE / Nilekani structured roles / adoption-manager (Friday 11 Sep)
- just-exit / function KPI vs ownership / visibility ≠ top-line / skills vs responsibility / 8,900 vs 1,500 (Sunday 13 Sep)
- PwC 49.9% + operating control; Axis 400/−3%; SOP-given task; coffee-check; customer-not-paying (Monday 14 Sep)
- Dhatrak 250/16; Rajesh Srivastava 248/16; Rajesh Ramaswami credit-post
- TimeScope as a privacy/surveillance rant
- Do not recap Accenture–Google 1,000 seats when writing FDE
- Do not run Maisekar “accountability vs ownership” in the same week as Saraiya SOP **or** the 17 Sep leaner-GCC ownership quotes
- Do not write Adidas as “50% of 700” after the 17 Sep <20% statement
- Do not clone Panjwani “just exit” when writing the Adidas two-clock

## Engagement rings / noise

- Sarabjit Singh GCC “nerve center”
- Sahil Kapoor layoff roundups
- Sunil Khatwani across GCC posts
- Sandeep Arora / Gupta Polisetty (GCC Academia)
- TimeScope aggregator accounts (AI PUNNCH, StartupFox)
- Cognizant PERM comments: coaches / Immediate Joiner
- `"passed over" promotion`: government DPC
- Tambe “elevated to VP” congratulation accounts (CXO Lanes, CXO TechBOT, Business Success Elites, The 365 Circle)
- PwC JV: Partner / GCC-advisor recap ring (Ankit Garg, Techrecast, Tenzin Partners). Company-page tags ≠ ICP.
- Adidas Gurugram: ETHRWorld, Business Standard page, IndianStartupNews, StartupTalky, ThePeoplesBoard, VieStories, LinkedIn News story. Not ICP.
- Oracle this week: marketing-girl / TA / family-layoff / retired VP. Not ICP.

## News objects still live

- TOI 2 Sep: Best Buy–TCS Bengaluru GCC. Still unconfirmed.
- Porsche 24 Aug MHP → TCS. Confirmed.
- Wipro 15 May Mindsprint. Confirmed.
- India Today + ET 9 Sep: Cognizant PERM. Do not write as H-1B freeze.
- Infosys JL6+ January 2027 — still no ICP thread.
- Axis Max Life “head of ops is also CDO” / in-on-out-of-the-loop (8 Sep) — unused as a standalone.
- Nagalakshmi Shetty fail-fast POC (11 Sep ETGCC) — unused; country-head.
- Page Executive 94% / 41% (9 Sep) — recruiter dump; do not upgrade.
- EY GCC Pulse Nov 2025 80%/10% leadership-in-India — supporting colour only; not a Thursday object.
- Infosys Indore SDB-2 16 Sep — facility PR; dropped.
- **Used 13 Sep:** Panjwani “just exit”; Maisekar accountability vs ownership; Tambe top-line / no reporting line; Policybazaar skills vs responsibility; ET/Quess FDE 8,900 vs 1,300–1,500.
- **Used 14 Sep:** PwC 49.9% + operating control; Axis 400/−3%; Saraiya SOP-given task; Hegde coffee-check; Bishnoi customer-not-paying.
- **Used 17 Sep:** Adidas two-clock / other-hub handover / open roles; Oracle 30k→27k + case-by-case AI hiring; leaner GCC mid-career gap; Lalitha opportunity-before-ready.

## Apify this pass

- **None.** No new named ICP own-post URL. Did not Apify Sanketh (HR), Vivek Mishra (former-Head), Adidas aggregator URLs, or Oracle layoff-victim URLs.

Do **not** re-run: chetan / Sheriff / Dinesha / bashani month profile-posts; Dhatrak 250/16 comments; 9 Sep Rajesh–Deepika–Pareekh–Gaurav URLs (`lE847qi4jAB0EI8H7`, `qBcygReM6FKC0Ds7R`); 11 Sep Dhanya / Standard India / ETGCC / Rajesh Ramaswami (`ZE3pDN4wxmfESjg8X`); Ganpat `UIGuXFGFaoRdWO7JN`; Tambe vendor congratulation activity IDs; PwC Acceleration Centers company-page congratulations.

## Next-run hunts

1. Employed TCS / Infosys / Wipro / HCL / Accenture / Cognizant / Best Buy / **PwC AC / Adidas Gurugram / Oracle India Directors in their own voice** — still the missing 9.0. Aruna Santosh if she posts on the JV. An Adidas or Oracle SM/Director own post would unlock 9.0 on objects 1–2.
2. Nithya Subramanian own posts; Abhinav Dev own posts; Manish Tambe *own* posts only. Need Aditya Singh’s **BFS** profile URL (name-search is polluted). Not Kapil. Not Ganpat this week. Not Tambe aggregator URLs. Not Sanketh. Not Vivek Mishra.
3. Women SM/Directors in their own voice. Smitha still missing. Lalitha is country-head — do not treat her interview as ICP proof.
4. Company statement on Best Buy–TCS. Do not invent a denial.
5. H2 appraisal / JL6 January 2027 as October approaches.
6. Axis Max “ops head is also CDO” only if a named India SM/Director reacts — do not clone Policybazaar, Axis 400/−3%, or leaner-GCC ownership.
7. Nithya Cadambi / Navaneet Mishra own posts if a clean URL appears.
8. Do not start from yesterday’s keyword list. Open this file, then named outlets, then the seed operators. Apify last, named URL only.
