# RDRS Bangladesh MIS Internship — Master Learning, Schedule & Presentation Study Guide

> **Source Report:** *Evaluating MIS Practices in Project Monitoring: A Study on RDRS Bangladesh*  
> **Use Case:** Master study reference for viva/defense preparation and source outline for building the internship presentation slide deck.

---

## 1. Quick-Reference Metadata & The Core Idea ("Big Picture")

### 1.1 Placement Identity Card

| Field | Details |
| :--- | :--- |
| **Report Title** | *Evaluating MIS Practices in Project Monitoring: A Study on RDRS Bangladesh* |
| **Intern / Author** | A. R. Mahmud (Student ID: `12022065`), BBA (Major in MIS), Begum Rokeya University, Rangpur (BRUR) |
| **Academic Supervisor** | Mohammad Rakibul Islam Bhuiyan, Assistant Professor, Department of MIS, BRUR |
| **Host Organization** | RDRS Bangladesh — Monitoring, Evaluation and Learning (MEL) Department |
| **Placement Location** | Central Coordination Office (CCO), Jail Road, Rangpur (Head Office: House 43, Road 10, Sector 6, Uttara, Dhaka) |
| **Host Supervisors** | Mr. Mamunur Rashid (Head of MEL) & Dabasish Mahata (Coordinator – Monitoring) |
| **Internship Duration** | 01 September 2026 – 30 November 2026 (3 months) |
| **Presentation & Submission** | Presentation Session: **26 November 2026** \| Final Report Submission: **30 November 2026** |
| **Guiding Research Question** | *How is monitoring data at the village level or at the branch desk communicated to the management level of RDRS Bangladesh, and where does the system work or fail?* |

---

### 1.2 The Main Idea / Central Thesis of the Internship

Before starting this internship, university BBA MIS textbooks framed Management Information Systems around corporate ERPs, cloud databases, and live executive dashboards where every transaction updates automatically. Three months inside RDRS Bangladesh's MEL Department taught a very different lesson:

> **Core Thesis:** In a large NGO operating across remote river islands (*chars*), handwritten passbooks, strict donor cycles, and hundreds of field offices, **software alone does not create reliable MIS**. Good software only works when backed by disciplined field verification habits at the exact boundary **"where paper meets the screen."**

#### Three Core Contrasts Learned Across the 3 Months

1. **Classroom MIS Theory vs. Northern Bangladesh Field Reality**
   - **Textbooks assume:** Clean digital input $\rightarrow$ instant cloud database sync $\rightarrow$ real-time KPI dashboards.
   - **RDRS reality:** Monitoring must operate amid unstable mobile connectivity in *chars*, community outreach workers writing on paper follow-up cards, teacher turnover in rural learning centers, and 288 microfinance branches reconciling weekly *samity* passbooks.
   - As Laudon & Laudon (2020) define it, MIS is an assembly of **people, work processes, hardware, and software**. In NGO settings, the main bottleneck is rarely software cost—it is **confidence in the number at the bottom of the monthly table**.

2. **Two Parallel MIS Worlds Inside the Same Organization**
   - **Track A — Microfinance MIS (Mature, Standardized, Automated):** Evolved across 30 years from a person-dependent internal tool (`Micro Bank`, 1995–97) $\rightarrow$ a commercial transition (`South Tech`, 2011) $\rightarrow$ a web-based enterprise platform (`G Banker`, 2017/18–present) across 288 branches. One click produces branch balance sheets (`POMIS-5`), income statements (`POMIS-4`), Credit Organizer changes, On-Time Repayment (`OTR`), and Portfolio at Risk (`PAR`)—eliminating key-person dependency.
   - **Track B — Development Project MEL (Flexible, Grant-Driven, Fragmented):** Uses offline `KoBo Toolbox` (Android/Enketo) for mobile surveys, manual `Excel` workbooks and macros to clean data and compute composite indices (such as the Household Climate Vulnerability Index, `HCVI`), and `Power BI` for donor dashboards. It has **zero integration** with `G Banker` and relies on manual exports between tools.

3. **Where Friction Happens ("Where Paper Meets the Screen")**
   - **Last-Mile Data Inflation & Missing Paper Trails:** In the May 2023 *Somriddhi* audit, central MIS reported **100%** student attendance in Beruabari while classroom rollbooks showed **89%**, and **65%** of expenditure vouchers for BDT 1,00,000 rehabilitation grants were missing on site. In *Jononni*, outreach worker paper cards (ELCO/PW) can drift from clinic monthly totals unless manually checked during Data Quality Assessments (`DQA`).
   - **Paper Bottlenecks Inside Digital Processes:** Even where `G Banker` handles loan accounting cleanly, *Credit Shield* death insurance claims still move as physical paper folders across 4 office tiers to Dhaka before Guardian Life can settle them. Similarly, because district courts lack digital query APIs, 6 *Access to Justice (A2J)* paralegals had to count **77,849** paper case files by hand across court benches (*Ejlash*) and clerk offices (*Serestha*).
   - **The Scheduling Irony Inside MEL:** MEL officers visit branches every month to catch reporting errors, yet their own monthly monitoring roster was built manually in Microsoft Word tables, with no duplicate check or multi-month branch coverage tracking. Observing this daily bottleneck led to building **Dishari**, an offline browser-based planning and reporting application.

---

### 1.3 Theoretical Foundations Connected to Field Practice (Chapter 3 Synthesis)

| Academic / Standard Framework | Core Concept | How It Showed Up at RDRS Bangladesh |
| :--- | :--- | :--- |
| **Laudon & Laudon (2020) — MIS** | People + processes + hardware + software turning raw data into managerial decisions | At RDRS, software (`G Banker`, `KoBo`, `Power BI`) only delivers trustworthy management tables when paired with people-driven verification rules and branch checks. |
| **OECD-DAC (2010) — Monitoring vs. Evaluation** | *Monitoring* is continuous tracking of activities/indicators during implementation; *Evaluation* measures periodic long-term impact | MEL separates continuous monthly monitoring (2x/month MFI branch visits, DQA, DHIS2 checks) from milestone baselines/endlines (`ICPS`, `C-RANGPUR`). |
| **Three Functional MEL Habits** | 1. **Baseline Studies** (pre-project reference)<br>2. **Data Quality Assessments (DQA)** (validity, reliability, accuracy, timeliness)<br>3. **Mixed Methods** (Quant survey + Qual FGD/KII) | Demonstrated directly in `ICPS` (21 UNICEF indicators split between HH survey and FGD/KII), `C-RANGPUR` (10-section KoBo survey), and `Jononni` (ELCO/PW DQA). |
| **Three NGO/MFI MIS Lessons** | 1. Avoid key-person programming dependency<br>2. Guard against last-mile inflation when targets pressure staff for 100%<br>3. Fixed monthly calendars beat ad-hoc file requests | 1. `Micro Bank` $\rightarrow$ `G Banker` removed single-programmer risk<br>2. *Somriddhi* 100% vs. 89% attendance gap<br>3. RDRS uses a formal monthly monitoring schedule (automated via `Dishari`). |

---

## 2. Complete Internship Schedule & Chronological Learning Log

This section preserves **both** the official 13-step placement schedule signed by the Head of MEL and the granular 19-phase fieldwork/office log kept throughout the three months, so you can present an exact timeline and recall what you did and learned in every phase.

### 2.1 Official 13-Step Internship Schedule (Signed by Mr. Mamunur Rashid, Head of MEL)

*Participant: BBA Student, Begum Rokeya University, Rangpur | Duration: 01 September 2026 to 30 November 2026*  
*Purpose: Provide practical exposure to MIS practices in project monitoring for RDRS Bangladesh and bridge theoretical knowledge with real-world practice.*

| # | Date | Location | Main Activities | Responsible / Contact Person |
| :-: | :--- | :--- | :--- | :--- |
| 1 | **01 Sep 2026** | Central Coordination Office, Rangpur | Orientation and Reporting Guidelines | **Mr. Mamunur Rashid**, Head of MEL<br>**Dabasish Mahata**, Coordinator–Monitoring |
| 2 | **02–10 Sep 2026** | Central Coordination Office, Rangpur | Overview of RDRS Bangladesh Programs and Projects | **Mr. Iftekharul Islam**, Manager–Monitoring<br>**Fahmida Mostafa**, Senior MEL Officer |
| 3 | **13–17 Sep 2026** | C-RANGPUR Project *(noted as C-RANGPU in schedule)* | Baseline Data Collection of C-RANGPUR Project | **Moushumi Akter**, MDO, C-RANGPUR Project (`01745761900`) |
| 4 | **20–24 Sep 2026** | Rangpur Region | Branch Office Visit, Observe Data Verification, and Documentation Process | **Maydul Islam**, Senior Monitoring Officer (`01730328212`)<br>**Md. Ziaur Rahman**, Senior Officer, Admin & MIS (`01730328234`) |
| 5 | **27 Sep 2026** | HR Department, Rangpur | Know about HRM Policy and Process | **Md. Ziaur Rahman**, Sr. Coordinator–HR (`01730328011`) |
| 6 | **28 Sep 2026** | Rupantar Project, Rangpur | Activities of Agriculture Department and Rupantar Project | **Dr. Salah Uddin**, Team Leader Environment & Climate Change (`01716263216`)<br>**Pallab Goswami**, Research Associate (`01738 375951`) |
| 7 | **29 Sep 2026** | Social Development, Rangpur | Briefing on Social Empowerment Activities and the Federation Concept | **Rashedul Arefeen**, Team Leader (SD) (`01730328044`) |
| 8 | **30 Sep 2026** | Safeguarding Department, Rangpur | RDRS Safeguarding Policy and Practice | **Rumana Azim Ansari**, Coordinator–Safeguarding (`01730328039`) |
| 9 | **01 Oct 2026** | Admin & General Service Dept., Rangpur | Administrative & General Service activities (Procurement, Guest House, Store & GS) | **Maj Shammita Kabir (Retd)**, Head of Admin & General Service |
| 10 | **04 Oct – 12 Nov 2026** | Rangpur Central Coordination Office | MIS practice in MEL Department | **Dabasish Mahata**, **Md. Ajazul Haque**, MEL Department |
| 11 | **15–25 Nov 2026** | Rangpur Central Coordination Office | Report preparation and sharing of learning with RDRS Bangladesh | **Mr. Mamunur Rashid**, Head of MEL |
| 12 | **26 Nov 2026** | Rangpur Central Coordination Office | Internship Presentation Session | **Mr. Mamunur Rashid**, Head of MEL |
| 13 | **30 Nov 2026** | Rangpur Central Coordination Office | Final Report Submission | **Mr. Mamunur Rashid**, Head of MEL |

*(Note: Two different staff members named Md. Ziaur Rahman appear in the schedule—one in Admin & MIS (`01730328234`) and one as Sr. Coordinator–HR (`01730328011`).)*

---

### 2.2 Detailed Chronological Activity & Learning Log (All 19 Phases)

| Date Block | Activity | Who I Worked With | What I Did & What I Learned |
| :--- | :--- | :--- | :--- |
| **01 Sep 2026** | Induction and reporting rules | Mr. Mamunur Rashid; Dabasish Mahata | Received the signed 13-step placement plan; read the **6th Strategic Plan (2023–2027)**; recorded RDRS's core scale (**406 Union Federations**, **1.64 million** participants) and MEL's role as an independent internal audit unit separate from implementation teams. |
| **02–04 Sep 2026** | Overview of MEL tools and projects | Mr. Iftekharul Islam; Fahmida Mostafa | Learned RDRS's 5 program domains, active donor projects (*Jononni*, *SEEDS*, *MCGL*, *ICPS*), and how daily MEL connects **paper registers & Excel** (routine branch checks) with **KoBo Toolbox** (ad-hoc mobile surveys) and **Power BI** (dashboards). |
| **07–09 Sep 2026** | Microfinance MIS history walkthrough | Mr. Iftekharul Islam | Traced 30 years of microfinance software: `Micro Bank` (1995–97, FAO/GTZ, 27-developer team including grandfather **Boro Abbu** and colleague **Mahabub**) $\rightarrow$ `South Tech` (2011) $\rightarrow$ `G Banker` (2017/18–present). Learned the lesson of **key-person risk** when one staff programmer holds reporting queries. |
| **10–11 Sep 2026** | Inspecting live `G Banker` reports | Udayan Branch Office exports | Examined three real outputs: **CO-wise Program Changes Report**, **POMIS-5** (Statement of Financial Position / balance sheet), and **POMIS-4** (Statement of Comprehensive Income & Expenditure). Observed one-click **OTR** and **PAR** reporting. |
| **13–17 Sep 2026** | `C-RANGPUR` baseline fieldwork | Moushumi Akter (MDO) | Observed live household enumeration on mobile **Enketo** forms (`ee-eu.kobotoolbox.org/x/wzjSgzZ6`) in the field; checked digital consent screens, skip logic, GPS capture, and offline data collection realities. |
| **20–24 Sep 2026** | Branch visits and ledger verification | Maydul Islam; Md. Ziaur Rahman (Admin & MIS) | Visited Rangpur region microfinance branches; matched physical **borrower passbooks** and *samity* collection sheets against branch loan books and `G Banker` ledgers; reviewed overdue collection notes and sanction sheets to see how **phantom loans** are prevented. |
| **27 Sep 2026** | HR policy rotation | Md. Ziaur Rahman (Sr. Coordinator–HR) | Reviewed HR staff records, biometric attendance logs, and leave tracking workflows to understand how staff deployment and compliance are tracked centrally. |
| **28 Sep 2026** | Agriculture & *Rupantar* briefing | Dr. Salah Uddin; Pallab Goswami | Explored **Climate Smart Agriculture (CSA)** plots, homestead gardening, and flood-tolerant crop data collection used in rural northern districts. |
| **29 Sep 2026** | Social Development briefing | Rashedul Arefeen | Learned how **406 member-run Union Federations** operate as local apex bodies—tracking civic claims, government safety-net allowances, and community mediation logs. |
| **30 Sep 2026** | Safeguarding policy walkthrough | Rumana Azim Ansari | Reviewed RDRS safeguarding complaint registers and confidential incident escalation paths protecting beneficiaries and staff. |
| **01 Oct 2026** | Admin & General Service visit | Maj Shammita Kabir (Retd) | Inspected physical procurement registers, Guest House/store inventory sheets, vehicle logbooks, and fixed-asset tagging controls. |
| **04–16 Oct 2026** | Deep MEL practice, `ICPS`, `C-RANGPUR` & start of **Dishari** | Dabasish Mahata; Md. Ajazul Haque; Md. Saiful Alam (Shekul) | Spent ~2 hours with Shekul learning the **6-step baseline lifecycle** (`ICPS`, 21 UNICEF indicators, `ESS`, `TOR`, `Inception Report`, `MEL maturity`). Worked with Ajazul Haque on `C-RANGPUR`'s 10-section form, **matrix `F01-112`**, **HCVI 30/30/40 math**, and Power BI pipeline. Identified the manual Word scheduling bottleneck and started coding **Dishari**'s timezone-safe calendar math. |
| **18–22 Oct 2026** | *Jononni* field trip to Lalmonirhat | Jononni Project Head (RDRS); Assoc. Prof. Omar Faruque (BRUR) | Met the Jononni head before departure; traveled to **Lalmonirhat** to watch field **DQA** checking **ELCO** and **PW** registers and safe delivery cards against clinic summaries. Unexpectedly met **Assoc. Prof. Omar Faruque** (Accounting, BRUR) on site and discussed real-world NGO expense vouchers and field verification vs. university lectures. |
| **24–28 Oct 2026** | *A2J for Women* & court audit review | A2J Project Focal (28+ yrs); DPO; 2 Paralegals | Studied the formal (RDRS) vs. informal (*Nijera Kori* CDR) justice split; analyzed the **April 2025 physical court audit** where 6 paralegals hand-counted **77,849 cases** across *Ejlash* and *Serestha*; flagged the 12 vs. 13 staffing count discrepancy for HR confirmation. |
| **29 Oct – 05 Nov 2026** | *Somriddhi* archival file review | MEL Department Archives | Analyzed the May 2023 PKSF-funded *Somriddhi* monitoring report (Panchagarh & Kurigram); uncovered hard quantitative proof of paper-to-MIS gaps: **89% rollbook vs. 100% MIS attendance**, **11/74 teacher exits** in 4 months, and **65% missing rehabilitation vouchers**. |
| **06–12 Nov 2026** | **Dishari** completion & compliance audit | Microfinance staff; MEL team | Studied **Credit Shield Microinsurance** (4-tier paper death claim lag), **AML/CFT** BFIU reporting (>BDT 50 lakh), and **loan approval hierarchy**. Completed **Dishari**'s 3-step workflow, `Smart Assist` (3-month cooldown), Reports `.docx`/`.pdf` importer, and **294 passing unit tests**. |
| **15–25 Nov 2026** | Report drafting & internal review | Mr. Mamunur Rashid | Compiled field notes, mathematical tables, figures, findings matrix, and practical recommendations into the formal LaTeX report for internal MEL feedback. |
| **26 Nov 2026** | Internship presentation | MEL Leadership & Staff | Presented key MIS findings and walked the MEL team through a live demonstration of **Dishari** at Rangpur CCO. |
| **30 Nov 2026** | Final report submission | Academic Supervisor & Head of MEL | Submitted bound report to the Department of MIS (BRUR) and the RDRS MEL Department. |

---

### 2.3 Key Informant Interviews (KIIs) & People Met

| Person | Role / Affiliation | Main Topics & Specific Learnings |
| :--- | :--- | :--- |
| **Md. Saiful Alam (Shekul)** | ICPS Baseline Team (ex-Technical Specialist, MEAL & GIS, Save the Children, Sylhet) | 2-hour walkthrough of MEL vs. MEAL, the **6-step baseline lifecycle**, 21 UNICEF indicators (quant HH survey vs. qual FGD/KII), **ESS**, **TOR**, **Inception Report**, and **MEL maturity**. |
| **Fahmida Mostafa** | Senior MEL Officer, RDRS | RDRS organizational scale (406 Federations, 1.64M people), 5 program areas, active projects (*Jononni*, *SEEDS*, *MCGL*, *ICPS*), and daily flow from field sites $\rightarrow$ Excel/KoBo $\rightarrow$ Power BI $\rightarrow$ management. |
| **Mr. Iftekharul Islam** | Manager, Monitoring, RDRS | 30-year evolution of RDRS microfinance MIS from manual ATM ledgers and `Micro Bank` (1995–97, with intern's grandfather) to `South Tech` (2011) and `G Banker` (2017/18), plus live `POMIS-4`/`5` reports. |
| **Md. Ajazul Haque** | Manager, MEL, RDRS | 5 technical questions on `C-RANGPUR`: KoBo Enketo design, `F01-112` indicator formulas, **HCVI 30/30/40 weights** & inversion of ACI, numeric codes for **SPSS**, and lack of link to `G Banker`. |
| **Jononni Head & Assoc. Prof. Omar Faruque** | Jononni Project Head (RDRS); Assoc. Prof. of Accounting, BRUR | Maternal/neonatal tracking across village clusters in Lalmonirhat, ELCO/PW register verification (DQA), and comparing university accounting/MIS theory with field voucher checks. |
| **A2J Project Focal, DPO & Paralegals** | Access to Justice for Women (Rangpur) | Formal vs. informal CDR split, LSID court desk, 18 March 2025 mediation order for *aposh-joggo* cases, and manual counting of **77,849** court files across *Ejlash* and *Serestha*. |

---

## 3. Organizational Overview & Scale (Key Facts to Memorize)

### 3.1 History & Evolution (Over 50 Years)
- **February 1972:** Established by the **Lutheran World Federation (LWF), Department for World Service (Geneva)** as *Rangpur Dinajpur Relief Service* to provide post-Liberation War relief (food, shelter, clinics, seeds, tools) in northwestern Bangladesh.
- **1976–1989:** Transitioned from emergency relief to long-term rural development (schools, health posts, agriculture); renamed *Rangpur Dinajpur Rural Service (RDRS)*.
- **1990–1997:** Built community-led Union Federations; in **1997**, localized and registered under the **Trust Act** as an independent Bangladeshi NGO governed by a national Board of Trustees.
- **2022–Present:** Celebrated its **50th anniversary in February 2022**; currently operating under its **6th Strategic Plan (2023–2027)**.
- **Why Northwest Bangladesh:** Selected deliberately due to recurrent Teesta/Jamuna/Brahmaputra floods, riverbank erosion, isolated river islands (*chars*), and *Monga* (the seasonal pre-harvest hunger gap around September–November).

### 3.2 Vision, Mission & Core Values
- **Vision:** A just and peaceful society where citizens live in dignity, free from poverty, distress, and ignorance in a sustainable environment.
- **Mission:** RDRS works with disadvantaged and marginalized communities and their organizations to empower them, make them resilient, and ensure sustainable improvements in their lives with dignity.
- **Core Values (5):** **Compassion, Commitment, Innovation, Adaptability, Accountability** *(in MIS terms, accountability means: does the branch ledger match the monthly dashboard?)*.

### 3.3 Institutional Scale & Microfinance Portfolio Numbers

| Dimension | Scale / Figure | Scope & Notes |
| :--- | :--- | :--- |
| **Union Federations** | **406 Federations** | Independent member-run apex community bodies at Union level |
| **Administrative Footprint** | **33 Districts \| 183 Upazilas \| 872 Unions** | Primarily all 8 districts of **Rangpur Division** (Kurigram, Gaibandha, Thakurgaon, Dinajpur, Nilphamari, Panchagarh, Rangpur, Lalmonirhat) + **Cox's Bazar** (Ukhiya, Teknaf) + **Sylhet, Mymensingh, Rajshahi** |
| **Direct Participants** | **1,642,724 individuals** (~1.64 million) | People directly engaged in RDRS programs |
| **Governance & Oversight** | Board of Trustees, General Body, Executive Director | Regulated by **NGO Affairs Bureau** (`FD-6` under Foreign Donations Regulation Act 2016) & **Microcredit Regulatory Authority (MRA)** |
| **Management Hierarchy** | 3 operational tiers | **16–17 Regional Offices** $\rightarrow$ **59–61 Area Offices** $\rightarrow$ **278–288 Branch Offices** |
| **Microfinance Scale** *(Dec 2024 Portfolio Sheet)* | **288 Branches** across **29 Districts** | **21,134** *samity* groups \| **458,819** members \| **377,250** borrowers |
| **Microfinance Financials** *(Dec 2024)* | **BDT 5.14B** savings \| **BDT 15.09B** outstanding | **95.08%** loan recovery rate *(Dishari master catalog holds **332** branches across **32** district strings including historical/sub-units)* |

### 3.4 Five Core Program Domains & Six Active Projects Studied

- **Five Program Domains** *(each Monitoring Officer supports all five, not a single grant)*:
  1. **Skills, Employment and Entrepreneurship** (vocational training, youth programs, market linkages)
  2. **Social Empowerment** (406 Union Federations, legal aid, anti-child marriage, gender justice)
  3. **Agriculture, Food Security and Climate Change** (flood-tolerant crops, solar irrigation, Climate Smart Agriculture)
  4. **Microfinance and Employment Creation** (group/individual loans, savings, microinsurance)
  5. **Emergency and Humanitarian Response** (northern *char* flood relief, Rohingya refugee & host support in Cox's Bazar)

- **Six Projects Observed During Placement:**

| Project | Focus & Activities | Donor, Timeline & Scale |
| :--- | :--- | :--- |
| **Jononni** | Strengthening Maternal and Neonatal Health System; ELCO/PW listing, safe delivery tracking, DQA | **Save the Children** \| Mar 2023 – Dec 2027 \| Rangpur & Lalmonirhat |
| **SEEDS** | *Socio-Economic Empowerment with Dignity and Sustainability*: schooling & livelihoods for *adibashi* adolescent girls | **Strømme Foundation** \| Jan 2024 – Dec 2028 \| 3,000 families (Rangpur) |
| **MCGL** | *MOMENTUM Country and Global Leadership*: maternal, newborn & child health; DHIS2 data validation | **U.S. Dept. of State via Jhpiego** \| Panchagarh & Rangpur |
| **ICPS** | *Disability-Inclusive Child Protection Systems*: Output 4.2 (social services) & Output 4.3 (harmful practices); 21 indicators | **UNICEF** \| Jun 2026 – Dec 2027 \| **BDT 2,20,40,834** (Mymensingh, Rajshahi, Rangpur) |
| **C-RANGPUR** | Climate resilience, IGA, CSA adoption, civic claims, health/NCDs, & **HCVI** composite | **RDRS MEL Department** \| Baseline launched Sep 2026 (6 districts: Rangpur, Lalmonirhat, Kurigram, Sirajganj, Gaibandha, Jamalpur) |
| **A2J for Women** | Formal court legal aid, LSID desk, DLAC/UZLAC/UPLAC, mediation for *aposh-joggo* cases, court docket audit | **MoLJPA (Bangladesh) & German GIZ** \| 1 Mar 2024 – 31 Dec 2026 (ext. Mar 2027) \| **BDT 1,82,25,931** (Rangpur) |

### 3.5 Microfinance Products & Why Product Type Dictates Monitoring

| Product | Target Client & Terms | What Monitoring Officers Must Verify on the Ground |
| :--- | :--- | :--- |
| **Udayan** | Group-based loan for newly joined village women meeting weekly in a *samity*; peer cross-guarantee | Verify **weekly *samity* collection sheets** and **member passbooks** line-by-line |
| **Unnoti** | Individual microenterprise loan for graduated borrowers; underwritten on business cash flow | Verify **household business cash-flow appraisal** and **Area/Regional Manager signatures** |
| **Compulsory Savings** | Min **BDT 50/week** (min **BDT 200/month** for Udayan; **BDT 500/month** for Unnoti); **6% annual profit share** | Reconcile weekly deposits in passbooks against branch ledger refunds/balances |
| **General Voluntary & MSDS** | General Voluntary: up to **BDT 10,000** at **7% simple interest**; Monthly Savings Deposit Scheme (**MSDS**): 3-year at **7%**, 5-year at **7.5%** | Check deposit continuity, premature withdrawal approvals, and interest accruals |
| **Water Credit** | **BDT 10,000–100,000** for deep tube wells & sanitary latrines + hygiene training; **93 branches across 6 districts** (Dinajpur, Nilphamari, Thakurgaon, Panchagarh, Habiganj, Moulvibazar) | **Physical field inspection** confirming an actual sanitary latrine or tube well was built |
| **Livelihood Restoration Loan (LRL Phase 2)** | Post-COVID recovery loan up to **BDT 50,000**; **6-month grace period**; max **24 months**; **8% declining-balance service charge** repaid in **18 monthly installments** | Verify grace-period compliance, declining-balance schedule, and genuine livelihood recovery use |

---

## 4. Deep-Dive Technical & Operational Learnings (7 Modules)

### Module 4.1: How the MEL Department Works & Its Daily Tool Stack

The MEL Department in Rangpur acts as an **independent internal data-auditing unit**, stationed outside project implementation teams to preserve audit objectivity.

#### The 5-Tool Stack Used Daily

| Operational Job | Tool Used | How & Why Staff Use It |
| :--- | :--- | :--- |
| **Routine monthly branch monitoring** | Structured Excel templates & paper registers | Standard reporting formats; physical registers keep an auditable paper trail at branch/village level |
| **Ad-hoc & baseline surveys** | **KoBo Toolbox** (Android KoBo Collect / Enketo Express on EU servers) | Works **offline** in flood-prone *chars*, captures GPS, enforces skip logic, and exports quickly to Excel |
| **Central data cleanup & scoring** | **Microsoft Excel** | Pivot tables, manual data cleaning, formula joins, and weighting macros (e.g., HCVI) |
| **Visual summaries & donor reports** | **Microsoft Power BI** | Interactive KPI visuals and donor-facing dashboards |
| **Microfinance core accounting** | **G Banker** | Web-based MFI ledger across **288 branches**; one-click `POMIS-4`, `POMIS-5`, `OTR`, and `PAR` calculations |

#### Dual-Track Monthly Monitoring Flow (Observed in September 2026 Schedule)

```
Field Visits (Twice-Monthly MFI / Monthly Grant Tasks)
   ├──> Paper Registers & Passbooks  ──┐
   └──> KoBo Mobile / Enketo Offline ──┼──> MEL Branch Audits & Verification ──> Excel / G Banker ──> Management & Power BI Dashboards
```

1. **Microfinance Track (10 Repeat Tasks, Visited Twice Monthly: `02–15 Sep` & `16–28 Sep`):**
   Each officer is assigned specific branches per window to execute 10 standard checks: (1) group-level loan & savings verification, (2) staff productivity checks, (3) watching savings collection & refunds, (4) checking loan disbursement paperwork, (5) following up loan ceilings & overdue loans, (6) following up write-offs & rescheduled loans, (7) audit & reconciliation checks, (8) investigating write-off cases, (9) checking misappropriation adjustments, and (10) assessing pre-service training.
2. **Development Project Track (Grant-Specific Monthly Tasks in September 2026):**
   - `C-RANGPUR` baseline survey (6 districts: Rangpur, Lalmonirhat, Kurigram, Sirajganj, Gaibandha, Jamalpur)
   - `MCGL` DHIS2 data validation & process checks (Panchagarh)
   - `Jononni` DQA + ELCO & PW listing/result checks (Lalmonirhat & Rangpur)
   - `SEEDS` economic inclusion & education checks (Rangpur)
   - `ICPS` baseline fieldwork (`06–24 Sep` in Mymensingh, Rajshahi, and Rangpur divisions by Md. Saiful Alam Shekul & Fahmida Mostafa)
   - `RERP` IGA post-distribution follow-up (Cox's Bazar)
   - `CALDRI` beneficiary selection checks (Kurigram)

---

### Module 4.2: Baseline Design Lifecycle (Learned from `ICPS` & Md. Saiful Alam "Shekul")

- **Project Context (`ICPS`):** *Strengthening Disability-Inclusive Child Protection Systems to Prevent and Respond to Violence against Children with Disabilities in Selected Communities of Bangladesh*. Donor: **UNICEF** \| Period: **June 2026 – December 2027** \| Budget: **BDT 2,20,40,834** \| Scope: **Output 4.2** (social service systems) and **Output 4.3** (harmful practices) \| **21 UNICEF indicators**.
- **The 6-Step Baseline Design Process (Before Enumerators Enter Villages):**
  1. **Review Project Document** (understand objectives, outputs, budget, and target groups)
  2. **Select Indicators** (lock exact metrics required by the donor—e.g., 21 UNICEF indicators)
  3. **Build Indicator & Methodology Matrix (MEL Matrix)** (assign data source, tool, frequency, and disaggregation per indicator)
  4. **Draft Baseline Concept Paper** (high-level rationale and study approach)
  5. **Write Formal Terms of Reference (TOR)** (contractual scope, deliverables, roles, and method)
  6. **Write Inception Report** (confirms finalized sampling plan, instruments, and field calendar before fieldwork)
- **Method Split & Terminology:**
  - **Qualitative track (soft indicators like community attitudes/norms):** Focus Group Discussions (**FGD**) and Key Informant Interviews (**KII**).
  - **Quantitative track (hard indicators like prevalence or service utilization):** Structured **Household Sample Surveys**.
  - **MEL vs. MEAL:** INGOs like Save the Children use **MEAL** (**A = Accountability** to beneficiaries via feedback/complaint channels); RDRS titles its unit **MEL**.
  - **ESS (Environmental and Social Safeguards):** Mandatory check that project activities do not cause environmental harm or social exclusion.
  - **MEL Maturity:** How systematic, standardized, regular, and evidence-based an organization's M&E practices are.

---

### Module 4.3: Survey Engineering, Indicator Formulas & HCVI Math (`C-RANGPUR` & Md. Ajazul Haque)

#### A. The 10-Section `C-RANGPUR` Baseline Instrument (`ee-eu.kobotoolbox.org/x/wzjSgzZ6`)

| Sec | Section Title | Key Variables Captured | Linked Output / Metric |
| :-: | :--- | :--- | :--- |
| **1** | Location Background | District, Upazila, Union, Ward, Village; Hazard zones: *Char*, Riverbank erosion, Flood, Waterlogging, Drought | Geographic controls |
| **2** | Respondent Profile | Name, sex, NID, phone, ethnicity, marital status, education, occupation, disability type, prior RDRS membership | Beneficiary ID |
| **3** | Household Composition | Household head details; counts of children $<5$, pregnant/lactating women, elderly ($60+$), disabled members | Vulnerability profile |
| **4** | Assets & Infrastructure | Housing material, electricity, drinking water, latrines, 14 livestock/asset types, land tenure | Baseline asset base |
| **5** | Livelihoods & Income | Income sources (15 codes), IGA support, CSA awareness/adoption (18 practices), 3-year income trend | **Indicators 1.1 & 1.2** |
| **6** | Community Participation | Membership in 21 community bodies, meeting attendance, speaking up, female leadership | **Indicator 2.1** |
| **7** | Social Services & Claims | Safety-net receipt (14 types), claims submitted, acknowledged/responded, resolution status | **Indicator 2.2** |
| **8** | Primary Health Access | Healthcare seeking across 13 facilities (incl. RDRS Eye Care), barriers to treatment | **Indicator 3.1** |
| **9** | Non-Communicable Diseases | 8 diagnosed NCDs (hypertension, diabetes, cataract, etc.), screening history, lifestyle | **Indicator 3.2** |
| **10** | Climate Vulnerability | 16-item scored module: Exposure (5), Sensitivity (5), Adaptive Capacity (6) | **HCVI Composite** |

#### B. All 7 Operational Indicator Formulas (Monitoring Matrix `F01-112`)

Every indicator in `F01-112` explicitly fixes its numerator and denominator so two monitoring officers never calculate the same percentage differently:

$$\text{Indicator Result (\%)} = \left(\frac{\text{Observed Target Numerator (Eligible Population Meeting Criteria)}}{\text{Total Baseline Denominator (Surveyed Sample Group)}}\right) \times 100$$

| Indicator | Operational Definition / Target | Numerator / Denominator |
| :--- | :--- | :--- |
| **1.1** | Climate-affected HH adopting $\ge 1$ additional IGA ($+25\%$ from baseline) | **Num:** HH adopting $\ge 1$ new IGA / **Den:** Total targeted HH surveyed |
| **1.2** | $\ge 40\%$ of farming HH increasing income by $20\%$ via Climate Smart Agriculture (CSA) | **Num:** HH adopting $\ge 1$ promoted CSA practice / **Den:** Total targeted farming HH surveyed |
| **2.1** | Active participation of disadvantaged people in local decision-making ($+30\%$ from baseline) | **Num:** Disadvantaged members attending meetings, speaking, **AND** having opinions considered / **Den:** Total disadvantaged respondents surveyed |
| **2.1 (women)** | Female active participation in community decision-making bodies | **Num:** Female respondents meeting all 2.1 criteria / **Den:** Total female respondents surveyed |
| **2.2** | Proportion of citizen claims resolved by local public authorities *(also tracked via 5 sub-metrics: submitted, acknowledged, resolved, response rate $[\text{Responded} \div \text{Submitted}] \times 100$, resolution rate $[\text{Resolved} \div \text{Submitted}] \times 100$)* | **Num:** Claims fully or partially resolved by authorities / **Den:** Total formal claims submitted in period |
| **3.1** | $25\%$ of disadvantaged members accessing formal primary health care | **Num:** Respondents receiving care at public/RDRS clinic / **Den:** Respondents reporting health need in last 12 months |
| **3.2** | Reduction in selected NCD prevalence by $25\%$ against baseline | **Num:** Adults diagnosed with $\ge 1$ selected NCD / **Den:** Total adult respondents surveyed |

*Example from Matrix `F01-112` (Indicator 1.1 Planning Row):* Tracks Quantitative data (HH ID, baseline/current IGAs, enterprise type, launch date, monthly income) + Qualitative data (motivation, operational challenges, market barriers, perceived benefits) + Disaggregation (sex/age of HH head, disability, geographic zone, poverty class) via HH survey & KIIs at baseline, semi-annual review, and annual consolidation.

#### C. Household Climate Vulnerability Index (`HCVI`) Math

Adapted from **IPCC (2022)**, **Hahn et al. (2009)**, and **FAO (2016)**:

$$\text{Vulnerability} = \text{Exposure} + \text{Sensitivity} - \text{Adaptive Capacity}$$

**Master Weighted Composite Formula (0 to 100 scale; lower = more resilient, higher = more vulnerable):**

$$\text{HCVI} = (\mathrm{EI} \times 0.30) + (\mathrm{SI} \times 0.30) + \bigl[(100 - \mathrm{ACI}) \times 0.40\bigr]$$

- **Sub-Index A — Exposure Index ($\mathrm{EI}$, 30% weight):** $\mathrm{EI} = \left(\frac{\text{Raw Score}}{20}\right) \times 100$ (5 items, Q10.1–Q10.5, 0–4 pts each = 20 max):
  1. Frequency of hazard in last 3 years
  2. Time affected
  3. Months affected per year
  4. Temporary evacuation
  5. Daily livelihood disruptions
- **Sub-Index B — Sensitivity Index ($\mathrm{SI}$, 30% weight):** $\mathrm{SI} = \left(\frac{\text{Raw Score}}{20}\right) \times 100$ (5 items, Q10.6–Q10.10, 0–4 pts each = 20 max):
  1. Months of food shortage
  2. Period of income loss
  3. Damage to properties
  4. Problem in drinking water
  5. Number of vulnerable dependent persons requiring additional support
- **Sub-Index C — Adaptive Capacity Index ($\mathrm{ACI}$, 40% weight, inverted as $100 - \mathrm{ACI}$):** $\mathrm{ACI} = \left(\frac{\text{Raw Score}}{24}\right) \times 100$ (6 items, Q10.11–Q10.16, 0–4 pts each = 24 max; binary `0` or `4` for CSA, IGA, and preventive health):
  1. Access to early warning
  2. Disaster readiness actions
  3. Adoption of $\ge 1$ CSA practice *(0/4 binary)*
  4. Initiation of risk-reduction IGA *(0/4 binary)*
  5. Membership in community group
  6. Preventive health actions *(0/4 binary)*

| Score Band | $\mathrm{EI}$ / $\mathrm{SI}$ / $\mathrm{ACI}$ Level | Overall $\mathrm{HCVI}$ Status |
| :--- | :--- | :--- |
| **0 – <20** | Very Low | **Very Low Vulnerability** |
| **20 – <40** | Low | **Low Vulnerability** |
| **40 – <60** | Moderate | **Moderate Vulnerability** |
| **60 – <80** | High | **High Vulnerability** |
| **80 – 100** | Very High | **Very High Vulnerability** |

> **Why is Adaptive Capacity weighted 40% and inverted ($100 - \mathrm{ACI}$)?**  
> As **Md. Ajazul Haque** explained: RDRS cannot prevent a Teesta flood or physically relocate a family off a *char* island (Exposure/Sensitivity). What RDRS *can* directly change—through CSA training, micro-capital, community Federations, and clinics—is **Adaptive Capacity**. Inverting $\mathrm{ACI}$ ensures higher capacity reduces overall vulnerability.

#### D. Pipeline Gaps & Codebook Bugs Discovered
- **3-Tool Handoff Friction:** `KoBo Mobile Capture` $\rightarrow$ `KoBo Cloud Server` $\rightarrow$ `Manual MEL Check` $\rightarrow$ `Excel Cleaning & Weighting Macros` $\rightarrow$ `Power BI Dashboard` (numeric `Code` columns also support **SPSS** correlation/variance runs).
- **Zero MFI Integration:** `KoBo`/`Power BI` has no link to `G Banker`.
- **Instrument Quality Defects Found:** Typo `C RANGPU` in Q5.3.2 vs. `C RANGPUR` in Q5.4.1; Section 8 carries the heading *"Indicator 3.2 Measurement Matrix"* even though Section 8 measures Indicator 3.1; multi-select fields collapse into concatenated option strings in Word specs, requiring extra `0/1` binary parsing before Power BI ingestion.

---

### Module 4.4: 30-Year Microfinance MIS Evolution (Learned from Mr. Iftekharul Islam)

```
ERA 1: PERSON-DEPENDENT (1995–2011)      ERA 2: TRANSITIONAL (2011–2017/18)      ERA 3: ENTERPRISE WEB SYSTEM (2017/18–Now)
[ Micro Bank (FAO & GTZ, 27 devs) ] ───> [ South Tech (Commercial DB) ]   ───> [ G Banker (288 Branches, 1-Click POMIS) ]
  High key-person risk (Boro Abbu)         Reduced single-person risk              Institutional memory locked into shared software
```

1. **Era 1 — `Micro Bank` (1995–1997 to 2011):** When RDRS formally launched microfinance, field officers were called **ATMs (Assistant Thana Managers)**. Built with **FAO** and German **GTZ** *(noted in notebooks as ZTZ)* by **27 developers**, including the intern's grandfather (**Boro Abbu**) and his colleague **Mahabub**. Afterwards, Boro Abbu ran almost all reporting queries himself—creating severe **key-person risk** where reporting could stall if one person fell ill or retired.
2. **Era 2 — `South Tech` (2011–2017/18):** Brought in specifically to eliminate single-programmer dependence; Boro Abbu helped migrate data and establish the workflow before retiring.
3. **Era 3 — `G Banker` (2017/18–Present):** Bangladeshi web-based MFI platform now running across all **288 branches**.
   - **Three Live `G Banker` Outputs Inspected (Udayan Office Sample):**
     1. **Micro Finance Program Changes Report (CO-wise):** Month-to-month tracking per Credit Organizer (CO count, *samity* count, member balance, savings, borrower count, overdue, outstanding, `OTR`, `PAR`, profit/loss, disbursement, write-offs).
     2. **POMIS-5 (Statement of Financial Position):** One-click branch balance sheet comparing current year vs. previous year.
     3. **POMIS-4 (Statement of Comprehensive Income & Expenditure):** Branch monthly and annual income statement generated directly from daily branch entries.

---

### Module 4.5: Field Verification, Risk Controls, Governance & Compliance

1. **Jononni Maternal Health Field Visit (Lalmonirhat, 18–22 Oct 2026):**
   - Unlike `G Banker` (which enforces balanced columns every evening), maternal health monitoring in *Jononni* relies on community outreach workers maintaining handwritten **ELCO (Eligible Couple)** lists, **PW (Pregnant Women)** registers, and safe-delivery/postnatal cards. If a family migrates or a date is missed, monthly totals drift until a monitoring officer runs an on-site **DQA**.
   - Unexpectedly encountered **Assoc. Prof. Omar Faruque** (Department of Accounting, BRUR) working on *Jononni* activities in Lalmonirhat, comparing field register/expense voucher verification against university accounting and MIS coursework.

2. **Special Monitoring Checklist (Branch Audits):**
   - `G Banker` overdue alert $\rightarrow$ physical visit to borrower's home $\rightarrow$ written non-payment note filed with Branch Loan Committee.
   - Cross-check Loan Committee sanction sheets against cash disbursement slips and member passbooks to expose **phantom loans**.
   - Monthly monitoring of `PAR` and `OTR`; separate investigation files for suspected cash skimming/forgery from branch complaint boxes; unannounced inspections by Area, Regional, and District Managers.

3. **Credit Shield Microinsurance (Guardian Life Insurance Ltd., since July 2024):**
   - **Terms:** Compulsory premium of **BDT 6 per BDT 1,000** disbursed. On death of borrower or co-borrower, wipes out remaining principal + accrued service charge (up to **BDT 20 lakh**) and pays an immediate **BDT 15,000 funeral cash grant**.
   - **Paper Bottleneck:** `G Banker` writes off the loan at the end, but the claim travels physically as paper folders (death certificate, medical notes, Union Parishad attestation):
     `Death Confirmed at Branch` $\rightarrow$ `Branch Focal Verifies (2 days)` $\rightarrow$ `Regional Focal Review` $\rightarrow$ `Central Focal (Dhaka)` $\rightarrow$ `Guardian Life (10 days)` $\rightarrow$ `Payout (5 days)`.

4. **AML/CFT Regulatory Recordkeeping (Effective January 2022):**
   - Internal KYC register for trustees, senior management, and major financial transactions (NID, TIN, permanent address, photo, external board positions).
   - Mandatory **BFIU (Bangladesh Financial Intelligence Unit)** threshold reporting to Bangladesh Bank for cash transactions exceeding **BDT 50,00,000 (50 lakh)**.

5. **Credit Governance & Loan Approval Hierarchy (Audited in Reverse by MEL):**
   - `Credit Organizer (Recommends)` $\rightarrow$ `Branch Manager (<= BDT 1.5 Lakh)` $\rightarrow$ `Area Manager (<= BDT 3.0 Lakh)` $\rightarrow$ `Regional Manager (<= BDT 5.0 Lakh)` $\rightarrow$ `Head of Microfinance (> BDT 5.0 Lakh)`.

---

### Module 4.6: Case Studies in Paper-to-Digital Friction (*A2J* & *Somriddhi*)

#### Case Study A: Access to Justice for Women (`A2J`) & The 77,849 Court Docket Audit
- **Project Setup:** Bilateral G2G project (**Law & Justice Division, MoLJPA** + **German GIZ**); `1 Mar 2024 – 31 Dec 2026` (extended to Mar 2027); Rangpur budget **BDT 1,82,25,931**.
- **Institutional Split:** **RDRS** manages formal justice (Courts, DLAO, Police Stations, Rangpur Central Prison); **Nijera Kori** manages informal Community Dispute Resolution (**CDR**) at village level.
- **Outputs (up to April 2025):** Assisted **6,092 justice seekers** (**3,348 female**, **2,744 male**); runs **LSID** (Legal Service Information Desk) in court; coordinates **DLAC / UZLAC / UPLAC**; secured Senior District and Sessions Judge Office Order (**18 March 2025**) approving panel mediators for *aposh-joggo* (compoundable CrPC) offenses.
- **April 2025 Manual Court Count:** Lacking any digital court API, **6 RDRS paralegals** walked through every courtroom bench (*Ejlash*) and clerk office (*Serestha*) in Rangpur to count active paper folders by hand:
  - **Grand Total:** **77,849 active cases**
  - **Criminal Cases (56.8% — 44,215 files):**
    - Magistracy: **25,612** (Judicial Magistracy incl. GRO: `15,794`; Metro Magistracy incl. GRO: `9,818`)
    - Sessions Courts: **11,339** (District Sessions: `8,936`; Metro Sessions: `2,403`)
    - Tribunals: **7,264** (*Nari O Shishu Nirjatan Daman* Tribunals: `6,068` [*Tribunal-1* alone holds `3,662`]; Specialized ATT/CT/AHTT/ST: `1,196` [*Anti-Terrorism Tribunal* has only `9`])
  - **Civil Cases (43.2% — 33,634 files):** Highest load in **Land Survey Tribunal (`5,493` files)** vs. Additional District & Sessions Judge-1 (`51` files).
- **Observations Flagged:** 12 active posts listed verbally (1 Project Focal with 28+ yrs at RDRS, 1 DPO, 1 Finance/Admin Officer, 6 Paralegals, 3 Support Staff) vs. 13 on handwritten slide update; need to track exact diversion counts into the mediation panel.

#### Case Study B: *Somriddhi* Programme Field Monitoring Audit (May 2023 Archive, PKSF-Funded)
Covered Vojanpur & Debiduba unions (Panchagarh, started 2014) and Beruabari union (Kurigram, started 2018):
- **Education (74 Centers: 34 Beruabari, 40 Debiduba; 1,926 students; 12 visited):**
  - Central MIS reported **100%** average attendance in Beruabari vs. **89%** in physical classroom rollbooks (**11-point last-mile inflation**).
  - Pass rates: **Bangla 82%**, **Math 61%**, **English 53%**; **11 of 74 centers** changed teachers within 4 months; only **45%** followed lesson plans properly; short on play materials.
- **Health Cards:** Household coverage was **17%** (Beruabari) and **38%** (Debiduba); 4-month card & diabetes test fees totaled **BDT 47,620** and **BDT 91,660**.
- **Ultra-Poor Rehabilitation Grants (~BDT 1,00,000/HH, 2018–19 cohort: 4 Beruabari, 8 Debiduba):** **65% of income/expenditure vouchers were missing** on site; in Beruabari most recipients were over age 70 and incomes fell, while **60%** in Debiduba saw incomes rise.
- **Homestead (*Somriddhi Bari*, 25 Beruabari, 20 Debiduba):** Fruit tree survival was **35%** (Beruabari) vs. **49%** (Debiduba) due to floods, late planting, and weak saplings; vermicompost, eco-stoves, and pheromone traps were rarely used.

---

### Module 4.7: Building **Dishari** — Replacing Manual Word Schedules & Blind Annual Tracking

#### A. Five Pain Points of the Old Word Schedule Workflow
Every month, the Monitoring Coordinator updated a 6-column A4 landscape Microsoft Word table covering **9 permanent officers** (*Moyen Uddin, Md. Nuruzzaman, Kartick Bhowmik, Jamir Uddin, Sanchya Sarker, Mamunur Rashid, Rashedul Islam, Anwarul Islam, Md. Laku Mia*) and temporary managers (*Maydul Islam, Iftekharul Islam*):
1. Manual counting of working days around Bangladesh's **Friday/Saturday weekends** and government/moon-sighting holidays (causing accidental weekend scheduling).
2. Typing **300+ branch names** from memory introduced spelling drift (e.g., *Narsingdi* vs. *Narshingdi*), breaking later spreadsheet lookups.
3. Word tables gave zero warning if two officers were booked into the same branch in one window, or if an officer revisited the same branch two months in a row.
4. Manually merging vertical `rowSpan` cells across the **8 numbered monitoring activities** and fixing page breaks for A4 landscape printing.
5. Isolated monthly `.docx` files made it impossible to see annual branch coverage, lagging northern districts, or officer field days.

#### B. How **Dishari** ("Pathfinder / Navigator") Solves This
- **Tech Stack:** **React 19.2**, **TypeScript 6.0**, **Vite 8.3**, **Tailwind CSS 4.3**.
- **Deliberate Offline Architecture:** Runs 100% client-side in the browser—zero server cost, zero login overhead, immune to Rangpur internet outages. Stores data in `localStorage` (`msp:settings`, `msp:holidays`, `msp:month:YYYY-MM`, `msp:meta` at **Schema Version 3**) via `src/lib/storage-adapter.ts` with in-memory fallback and JSON backup/restore.
- **Timezone-Safe Local Calendar Math (`src/lib/date.ts`):** Standard JS `Date.toISOString()` converts to UTC, shifting dates back 6 hours in Bangladesh (`UTC+6`) and placing officers on the wrong day. Dishari uses pure local `YYYY-MM-DD` strings with strict overflow checks—no UTC conversion ever.
- **Three-Step Workflow + Multi-Month Reports:**
  1. **Step 1 — Plan (`figures/dishari-plan.png`):** Sunday-first calendar (Fri/Sat gray columns on right); draggable visit windows snap to valid workdays (`working-days.ts`, `schedule-ops.ts`) with live workday pills (e.g., `04–13 Oct 8d`, `14–27 Oct 10d`); per-officer custom windows (e.g., Md. Nuruzzaman `04–15 Oct`); Day Overview modal; bilingual English/Bengali holiday JSON parser (`holidays.ts`); 8-activity reference drawer.
  2. **Step 2 — Assign (`figures/dishari-assign.png`):** **22 officer-window slots** paired with a searchable combobox (`branch-combobox.tsx`) over **332 master branches across 32 district strings** (`branch-master-data.ts`) with spelling normalization (`branches.ts`), presets (`Issue-Based Monitoring`, `Special Visit at`), drag-and-drop reassignment, and **Smart Assist** (`suggestAssignments` / `rotateFromLastMonth` in `suggest.ts`):
     - Prevents same-month branch duplicates
     - Enforces a **strict 3-month officer cooldown**
     - Scores unvisited branches with **+100 base points** and unvisited districts with a **+25 bonus**
  3. **Step 3 — Review & Export (`figures/dishari-review.png`):** **0–100 Readiness Engine** (`assessScheduleReadiness` in `readiness.ts`: **60 pts** slot completion, **30 pts** zero blockers, **10 pts** zero warnings such as $<4$ workdays, overlapping windows, or 3-month repeats). Intentional exceptions (e.g., two temp managers both assigned *Issue-Based Monitoring*) can be moved to an audited **Ignored Issues** tray (with Restore) to reach 100% Ready. A single canonical matrix (`buildDocumentModel` in `document-model.ts`) generates live A4 print preview, vector PDF (`jsPDF`, `jspdf-autotable`), and editable `.docx` (`docx`) with vertical `rowSpan` merges so screen and print never diverge.
  4. **Reports View (`figures/dishari-reports.png`):** Drag-and-drop historical `.docx` (`JSZip` XML parser in `import-docx.ts`) and `.pdf` (`pdfjs-dist` coordinate clustering in `import-pdf.ts`) schedules without retyping. `buildReport` (`report.ts`) produces branch coverage KPIs (**75% = 249 of 332 branches across 264 visits** on the illustrative 12-month 2026 demo dataset), **5 pure-SVG charts** (`report-charts.tsx`), Northern Bangladesh district tile map, Data Quality misspelling detector, and a **7-sheet `.xlsx` export** (`exceljs`).
- **Verification & Safety:** **294 unit tests passing across 31 test files** (`Vitest 5.0.3` + `React Testing Library`, 100% pass rate, zero TypeScript or Oxlint errors) + **50-step Undo/Redo stack** per month (`src/state/history.ts`).

---

## 5. Consolidated Findings & The 3 Actionable Recommendations

### 5.1 Summary Findings Matrix (Strengths vs. Gaps)

| System / Practice | What Happens on the Ground | Status |
| :--- | :--- | :--- |
| **G Banker Platform** | Instant CO-wise Changes, `POMIS-4`, and `POMIS-5` statements across 288 branches | **STRENGTH** — Fast, consistent PAR & OTR reporting |
| **Microfinance Continuity** | Transitioned from `Micro Bank` (1995) $\rightarrow$ `South Tech` (2011) $\rightarrow$ `G Banker` (2017/18) | **STRENGTH** — Eliminated key-person reporting risk |
| **Monthly Monitoring Schedule** | Named officers, branches, and visit windows twice a month | **STRENGTH** — Clear staff accountability |
| **KoBo Mobile Surveys** | Offline Android/Enketo forms with GPS, skip logic, and fast Excel export | **STRENGTH** — Cuts out paper questionnaire retyping |
| **Dishari Scheduler App** | Built offline React/TS planner for 332 branches, Smart Assist, & multi-month coverage | **STRENGTH** — Replaces Word tables; 294 unit tests pass |
| **Register-to-MIS Match** | **89%** classroom rollbook attendance entered as **100%** in *Somriddhi* MIS | **GAP** — Last-mile inflation; no sign-off gate |
| **Asset Grant Files** | **65%** of ~BDT 1 lakh rehabilitation grant vouchers missing in *Somriddhi* check | **GAP** — Weak paper filing at union level |
| **C-RANGPUR Pipeline** | HCVI math split across KoBo, manual Excel macros, and Power BI; minor typos | **GAP** — Manual handoffs & no G Banker link |
| **Credit Shield Claims** | Physical death certificate dossiers routed across 4 office tiers to Dhaka | **GAP** — Slow physical transport delays payouts |
| **A2J Docket Audit** | 6 paralegals hand-counted **77,849** paper court files across *Ejlash* & *Serestha* | **GAP** — Heavy manual count burden (no court API) |
| **Jononni Field Check** | ELCO/PW paper card updates require manual DQA reconciliation | **GAP** — Drifts unless verified regularly on site |

### 5.2 Three Practical Recommendations

1. **Require a Mandatory 10% Physical Register Sign-Off Before Monthly Lock *(Priority #1 if only one change is funded)*:**
   Before a Branch Manager or Project Officer closes a monthly `G Banker` or `Excel` report, a Monitoring Officer must audit at least **10%** of primary paper records (passbooks, school rollbooks, ELCO/PW cards, payment vouchers) line-by-line against digital figures and co-sign a 1-page sign-off sheet. If discrepancy exceeds **5%**, lock is blocked until resolved.
2. **Automate the KoBo-to-Power BI Link for Development Projects:**
   Replace manual Excel HCVI macro exports by connecting KoBo Toolbox directly to Power BI (or a compact central PostgreSQL store) via API webhooks. Compute $\mathrm{HCVI} = 0.30\,\mathrm{EI} + 0.30\,\mathrm{SI} + 0.40\,(100 - \mathrm{ACI})$ once in Power Query/DAX and enforce form validation to stop typos like `C RANGPU`.
3. **Institutionalize Rule-Checked Scheduling with Dishari & Digitize Paper Dossiers:**
   Adopt **Dishari** for monthly officer rosters, 3-month branch cooldowns, and annual district coverage tracking with zero server cost; maintain dual-trained backup owners for every recurring report family; and scan Credit Shield death certificates/attestations straight into `G Banker` rather than shipping paper folders across 4 offices to Dhaka.

---

## 6. Presentation Slide Deck Blueprint (14 Slides + Speaker Notes)

Use this structure directly to build your PowerPoint / Google Slides / Canva presentation. Existing screenshots in `figures/` (`dishari-plan.png`, `dishari-assign.png`, `dishari-review.png`, `dishari-reports.png`) drop straight into Slide 12.

### Slide 1: Title Slide
- **On-Slide Text:**
  - *Evaluating MIS Practices in Project Monitoring: A Study on RDRS Bangladesh*
  - A. R. Mahmud (ID: `12022065`) | Department of MIS, Begum Rokeya University, Rangpur
  - Host: Monitoring, Evaluation & Learning (MEL) Department, RDRS Bangladesh (CCO, Rangpur)
  - Placement: 01 Sep – 30 Nov 2026 | Supervisor: Mohammad Rakibul Islam Bhuiyan
- **Speaker Notes:** Greet the panel/audience. Introduce the report title and explain that this presentation summarizes 3 months embedded inside RDRS Bangladesh's MEL Department in Rangpur—comparing textbook MIS with real NGO field monitoring and presenting a working software tool built during placement.

### Slide 2: Guiding Question & The Big Lesson
- **On-Slide Text:**
  - **Guiding Question:** *How does monitoring data move from a village group or branch desk to RDRS management—and where does it work or fail?*
  - **Textbook MIS:** Transactions $\rightarrow$ Cloud ERP $\rightarrow$ Live Executive Dashboard
  - **NGO Reality:** Poor connectivity in *chars*, paper passbooks, donor timelines, 288 branches
  - **Core Takeaway:** *Software alone doesn't guarantee data integrity—friction happens where paper meets the screen.*
- **Speaker Notes:** Contrast what we study in BBA MIS classes with northern Bangladesh fieldwork. Emphasize that RDRS has strong microfinance software, yet real data problems occur at the "last mile" where physical paper records turn into digital numbers.

### Slide 3: RDRS Bangladesh at a Glance
- **On-Slide Text:**
  - **1972:** Founded by LWF (Geneva) as post-war relief $\rightarrow$ **1997:** Bangladeshi Trust NGO $\rightarrow$ **2023–27:** 6th Strategic Plan
  - **Reach:** **406** Union Federations | **33** Districts | **183** Upazilas | **872** Unions | **1.64M** participants
  - **Microfinance (Dec 2024):** **288** branches | **21,134** samities | **458,819** members | **BDT 15.09B** loans | **95.08%** recovery
  - **5 Program Domains:** Skills/Enterprise, Social Empowerment, Agriculture/Climate, Microfinance, Humanitarian Response
- **Speaker Notes:** Give quick context on RDRS's scale—especially its concentration across all 8 Rangpur Division districts to combat floods, river erosion, and *Monga*, plus Cox's Bazar. Point out that MEL monitors *all five* domains.

### Slide 4: My 3-Month Internship Schedule & Journey (Sep–Nov 2026)
- **On-Slide Visual:** Clean 4-phase horizontal timeline:
  - **Early Sep (01–11 Sep):** Orientation, 5 Domains, `Micro Bank` $\rightarrow$ `G Banker` history, Udayan reports
  - **Mid–Late Sep (13 Sep – 01 Oct):** `C-RANGPUR` KoBo field observation, Branch ledger checks + HR, Agriculture (*Rupantar*), Social Dev, Safeguarding, Admin rotations
  - **Oct – Mid Nov (04 Oct – 12 Nov):** `ICPS` baseline & `HCVI` math, *Jononni* visit (Lalmonirhat), *A2J* court count, *Somriddhi* audit, building **Dishari**
  - **Late Nov (15–30 Nov):** Report drafting, Presentation (26 Nov), Submission (30 Nov)
- **Speaker Notes:** Walk through the structured 13-step schedule signed by Head of MEL Mr. Mamunur Rashid, highlighting how rotations across HR, Agriculture, Federations, Safeguarding, and Admin led into deep MEL practice and field trips.

### Slide 5: How the MEL Department Works & Its 5-Tool Stack
- **On-Slide Text:**
  - **Role:** Independent internal data-auditing unit (separate from implementation teams)
  - **Dual-Track Monthly Schedule (Sep 2026):**
    - *Microfinance:* 10 repeat branch audit tasks, **2x/month** (`02–15` & `16–28`)
    - *Projects:* Grant-specific (`C-RANGPUR`, `MCGL` DHIS2, `Jononni` DQA, `SEEDS`, `ICPS`, `RERP`, `CALDRI`)
  - **5 Tools:** Paper Registers & Excel templates | `KoBo Toolbox` (offline mobile) | `Excel` (cleaning/macros) | `Power BI` | `G Banker`
- **Speaker Notes:** Explain why MEL sits apart from project teams to keep audits unbiased, and describe how routine MFI tracking differs from grant-funded development projects.

### Slide 6: Story 1 — 30 Years of Microfinance MIS (`Micro Bank` $\rightarrow$ `G Banker`)
- **On-Slide Visual:** 3-box evolution diagram:
  - **1995–2011 `Micro Bank`:** FAO/GTZ + 27 devs (incl. grandfather *Boro Abbu*); **High Key-Person Risk**
  - **2011–2017/18 `South Tech`:** Commercial DB migration; eliminated single-programmer bottleneck
  - **2017/18–Present `G Banker`:** Web-based across **288 branches**; 1-click **CO-wise Changes**, **POMIS-5** (Balance Sheet), **POMIS-4** (Income Statement), **OTR & PAR**
- **Speaker Notes:** Share the insight from Mr. Iftekharul Islam (and your family connection). Highlight the management lesson: relying on 1–2 programmers for custom queries puts a huge NGO at risk; standardizing on `G Banker` preserved institutional memory.

### Slide 7: Story 2 — Development Project MEL & Baseline Design (`ICPS`)
- **On-Slide Text:**
  - **Case:** `ICPS` (UNICEF, BDT `2,20,40,834`, 21 indicators, disability-inclusive child protection)
  - **6-Step Baseline Lifecycle:** `1. Doc Review` $\rightarrow$ `2. Indicators` $\rightarrow$ `3. MEL Matrix` $\rightarrow$ `4. Concept Paper` $\rightarrow$ `5. TOR` $\rightarrow$ `6. Inception Report`
  - **Mixed Methods:** Quantitative **Household Survey** (hard counts) + Qualitative **FGD & KII** (norms/attitudes)
  - **Key Concepts Learned:** `ESS` (Safeguards), `MEAL` vs. `MEL`, and `MEL Maturity`
- **Speaker Notes:** Summarize what Md. Saiful Alam (Shekul) taught you during the 2-hour walkthrough while the `ICPS` baseline was running live in September 2026.

### Slide 8: Inside `C-RANGPUR` — Survey Pipeline & `HCVI` Math
- **On-Slide Text:**
  - **Instrument:** 10-section offline KoBo/Enketo survey + Matrix `F01-112` (7 fixed numerator/denominator formulas)
  - **Pipeline:** `KoBo Mobile` $\rightarrow$ `Cloud` $\rightarrow$ `Manual MEL Check` $\rightarrow$ `Excel Macros (+ SPSS)` $\rightarrow$ `Power BI` *(No link to G Banker)*
  - **HCVI Formula:** $\text{HCVI} = (0.30 \times \mathrm{EI}) + (0.30 \times \mathrm{SI}) + [0.40 \times (100 - \mathrm{ACI})]$
  - **Why 40% & Inverted ACI?** RDRS can't stop river floods (`EI`), but it builds farmers' **Adaptive Capacity** (`ACI`)
- **Speaker Notes:** Explain why exact indicator formulas in `F01-112` stop calculation disputes, explain the 30/30/40 weighting insight from Md. Ajazul Haque, and note minor defects spotted (`C RANGPU` typo, Sec 8 header mismatch, manual Excel macro risk).

### Slide 9: Field Verification in Action — *Jononni* & Branch Audits
- **On-Slide Text:**
  - **Microfinance Audits (Rangpur Branches):** Match passbooks & *samity* sheets to `G Banker`; verify `Udayan` (group), `Unnoti` (cash flow + Area/Regional sign-off), `Water Credit` (physical latrine/tubewell); catch **phantom loans**; audit loan approval chain in reverse (`CO` $\rightarrow$ `BM <=1.5L` $\rightarrow$ `AM <=3L` $\rightarrow$ `RM <=5L` $\rightarrow$ `Head >5L`)
  - **Jononni Visit (Lalmonirhat):** On-site **DQA** checking handwritten **ELCO/PW cards** & safe delivery registers against clinic summaries (met BRUR Assoc. Prof. Omar Faruque on site!)
- **Speaker Notes:** Contrast how `G Banker` enforces balanced columns every night whereas *Jononni*'s community health registers can drift if workers miss household moves—making physical field DQA essential.

### Slide 10: Where Paper Meets Screen — Three Real Bottlenecks
- **On-Slide Text (3 High-Impact Cards):**
  1. **Last-Mile Inflation (*Somriddhi*, May 2023):** **100%** MIS attendance vs. **89%** classroom rollbook; **65%** missing BDT 1L grant vouchers; 11/74 teacher exits; 35% vs. 49% tree survival
  2. **Paper Claim Lag (*Credit Shield*, Guardian Life):** BDT 6/1,000 premium (up to BDT 20L write-off + BDT 15k funeral grant), but paper death dossiers travel across **4 office tiers** to Dhaka
  3. **Zero Digital APIs (*A2J for Women*):** 6 paralegals hand-counted **77,849** court files (**44,215** criminal / **33,634** civil) across *Ejlash* & *Serestha*
- **Speaker Notes:** Use these concrete numbers—they are the strongest empirical proof in your entire report showing why paper-to-digital transitions break down.

### Slide 11: The Scheduling Irony Inside MEL
- **On-Slide Text:**
  - MEL officers audit branches for errors, **yet their own monthly monitoring roster ran on manual Word tables**
  - **5 Daily Headaches:**
    1. Hand-counting workdays around **Fri/Sat** weekends & moon-sighting holidays
    2. Typing **300+ branch names** by hand $\rightarrow$ spelling drift (*Narsingdi* / *Narshingdi*)
    3. Zero alerts for same-window duplicates or back-to-back officer repeats
    4. Tedious manual `rowSpan` cell merging for 8 activities on A4 landscape
    5. 12 isolated monthly files $\rightarrow$ blind to annual district/branch coverage
- **Speaker Notes:** Explain how noticing this gap on the Coordinator's desk in October inspired you to turn your MIS internship from pure observation into building a real solution.

### Slide 12: My Solution — **Dishari** (Monitoring Schedule Planner)
- **On-Slide Visual:** Display the 4 screenshots from `figures/` (`dishari-plan.png`, `dishari-assign.png`, `dishari-review.png`, `dishari-reports.png`)
- **On-Slide Text:**
  - **Architecture:** 100% client-side offline web app (`React 19.2`, `TypeScript 6.0`, `Vite 8.3`, `localStorage` + JSON backups, zero server cost, timezone-safe `YYYY-MM-DD` dates avoiding `UTC+6` shift)
  - **3-Step Workflow:** **Plan** (Sunday-first auto-snapping windows) $\rightarrow$ **Assign** (332 branches, **Smart Assist** with strict **3-month cooldown** + `+100`/`+25` scoring) $\rightarrow$ **Review** (**0–100 readiness score**, Ignored tray, unified PDF & `.docx` export)
  - **Reports View:** Imports legacy `.docx`/`.pdf` files, generates 5 SVG charts, district tile map, and 7-sheet `.xlsx`
  - **Quality:** **294 passing unit tests** (31 files), 50-step Undo/Redo
- **Speaker Notes:** Highlight the engineering choices tailored to Rangpur's constraints: offline-first so internet drops never halt work, pure local date strings so Bangladesh's `UTC+6` offset never misplaces an officer, and legacy `.docx`/`.pdf` import so past months aren't lost.

### Slide 13: Consolidated Findings — Strengths vs. Gaps
- **On-Slide Two-Column Matrix:**
  - **Strengths:** Mature `G Banker` across 288 branches (no key-person risk); clear monthly audit cadence; offline `KoBo` field capture; **Dishari** automation prototype
  - **Gaps:** Last-mile register vs. MIS mismatches (89% vs. 100%, 65% missing vouchers); disconnected `KoBo`–`Excel`–`Power BI` handoffs; paper-bound `Credit Shield` claims & manual `A2J` docket counts
- **Speaker Notes:** Present a balanced assessment: RDRS is not failing at MIS—its core microfinance accounting is very strong—but targeted fixes at the paper-digital boundary can unlock huge reliability gains.

### Slide 14: Three Recommendations & Conclusion
- **On-Slide Text:**
  1. **Mandatory 10% Physical Register Sign-Off (#1 Priority):** Check 10% of paper passbooks/rollbooks/ELCO cards before monthly lock; block close if variance $>5\%$
  2. **Automate KoBo $\rightarrow$ Power BI API Pipeline:** Run `HCVI` math once in Power Query/DAX with form validation (no manual Excel macros)
  3. **Adopt Dishari & Digitize Dossiers:** Use **Dishari** for conflict-free rosters & annual coverage; dual-train report owners; scan `Credit Shield` claim PDFs into `G Banker`
  - **Closing Thought:** *Great MIS isn't just clean code—it's clean verification where field paper meets software.*
- **Speaker Notes:** Conclude cleanly. Thank BRUR (Supervisor Mohammad Rakibul Islam Bhuiyan & Assoc. Prof. Omar Faruque) and the RDRS MEL team (Mr. Mamunur Rashid, Dabasish Mahata, Fahmida Mostafa, Mr. Iftekharul Islam, Md. Ajazul Haque, Md. Saiful Alam Shekul), and invite questions.

---

## 7. Viva / Presentation Q&A Prep & Complete Glossary

### 7.1 Twelve High-Probability Defense Questions & Crisp Answers

1. **Q: What is the single biggest finding of your internship?**  
   *A:* Microfinance reporting (`G Banker` across 288 branches) is mature and standardized, whereas development project monitoring is fragmented across KoBo, manual Excel macros, and Power BI—and the biggest failures happen at the "last mile" where physical paper registers (rollbooks, ELCO cards, grant receipts) are entered into digital tables without a mandatory verification gate (e.g., *Somriddhi*'s 89% vs. 100% attendance gap and 65% missing vouchers).

2. **Q: Why does RDRS weight Adaptive Capacity (`ACI`) at 40% and invert it ($100 - \mathrm{ACI}$) in `HCVI`?**  
   *A:* Exposure (30%) and Sensitivity (30%) capture external climate hazards and household shocks that an NGO cannot directly stop (like river floods or eroding *chars*). Adaptive Capacity measures things RDRS programs *can* build—early warning access, CSA farming, IGAs, community groups, and preventive health. Inverting it ($100 - \mathrm{ACI}$) makes higher capacity pull the overall vulnerability score down.

3. **Q: How did RDRS solve "key-person risk" in microfinance MIS?**  
   *A:* From 1995–2011, custom queries in `Micro Bank` depended heavily on one developer (my grandfather, *Boro Abbu*). RDRS first migrated to `South Tech` (2011) and then to the standardized web system `G Banker` (2017/18), encoding rules (`POMIS-4`, `POMIS-5`, `OTR`, `PAR`) into shared software across 288 branches so reporting never depends on one programmer.

4. **Q: Why did you also find `MEL` vs. `MEAL` in your notes?**  
   *A:* INGOs like Save the Children (where Md. Saiful Alam Shekul previously worked) add **A for Accountability** to beneficiaries (`MEAL`), whereas RDRS names its department **MEL** (Monitoring, Evaluation and Learning).

5. **Q: What is the difference between `Udayan`, `Unnoti`, and `Water Credit`, and how does monitoring differ?**  
   *A:* `Udayan` is a group (*samity*) loan requiring weekly passbook and collection-sheet audits. `Unnoti` is an individual microenterprise loan requiring business cash-flow checks and higher-tier manager approvals. `Water Credit` (BDT 10k–100k in 93 branches) requires physical inspection of the built tube well or sanitary latrine alongside hygiene training.

6. **Q: How are large loans approved and audited at RDRS?**  
   *A:* Recommended by the Credit Organizer $\rightarrow$ Branch Manager ($\le$ BDT 1.5L) $\rightarrow$ Area Manager ($\le$ BDT 3.0L) $\rightarrow$ Regional Manager ($\le$ BDT 5.0L) $\rightarrow$ Head of Microfinance ($>$ BDT 5.0L). Monitoring officers audit that chain in reverse before disbursement to prevent unauthorized or phantom loans.

7. **Q: Why did you build **Dishari** as an offline browser app using `localStorage` instead of a cloud database?**  
   *A:* Deliberately so the MEL department pays zero monthly server fees, manages zero database logins, and never stalls when Rangpur internet drops. Data stays under `msp:*` keys (Schema Version 3) with JSON export/import for moving schedules across laptops.

8. **Q: Explain the `UTC+6` date bug you solved in **Dishari**.**  
   *A:* JavaScript's `Date.toISOString()` converts local midnight in Bangladesh (`UTC+6`) backward by 6 hours to `18:00` of the *previous* UTC date, putting an officer on the wrong workday. Storing and calculating all dates as pure local `YYYY-MM-DD` strings in `src/lib/date.ts` eliminated the bug entirely.

9. **Q: How does **Dishari**'s `Smart Assist` recommend branches?**  
   *A:* It blocks branches already assigned in the same month, enforces a strict **3-month cooldown** per officer, and ranks eligible branches using **+100 base points** for unvisited branches plus a **+25 bonus** for unvisited districts.

10. **Q: How did you verify **Dishari** works accurately?**  
    *A:* Through automated unit and UI tests using `Vitest 5.0.3` and `React Testing Library` covering calendar math, timezone safety, legacy `.docx`/`.pdf` parsers, readiness scoring, and UI state—achieving **294 passing tests across 31 test files (100% pass rate)** with zero TypeScript or Oxlint errors.

11. **Q: What was the `77,849` figure in the `A2J` case study, and why did it matter for MIS?**  
    *A:* Because district courts lack digital APIs for partner NGOs, 6 RDRS paralegals physically counted **77,849** active files (**44,215** criminal; **33,634** civil) across court *Ejlash* and *Serestha* rooms in April 2025. It shows how missing public digital infrastructure forces skilled field staff into heavy manual counting.

12. **Q: If RDRS only implements one recommendation from your report, which should come first and why?**  
    *A:* The **mandatory 10% physical register sign-off** before monthly lock (blocking close if discrepancy $>5\%$). Fixing downstream dashboards doesn't help if bad or inflated paper counts enter the system at the source.

---

### 7.2 Complete Master Glossary (Abbreviations & Field/Court Terms)

#### A. Technical & Institutional Abbreviations

| Term | Full Form / Meaning |
| :--- | :--- |
| **A2J** | Access to Justice for Women (bilateral G2G project with MoLJPA & GIZ) |
| **ACI** | Adaptive Capacity Index (40% weight, inverted in `HCVI`) |
| **ADR** | Alternative Dispute Resolution (court-annexed mediation) |
| **AML / CFT** | Anti-Money Laundering / Combating the Financing of Terrorism (`BFIU` threshold: `>BDT 50,00,000`) |
| **ATM** | Assistant Thana Manager (historic RDRS microfinance field role, 1995–97) |
| **ATT / CT / AHTT / ST** | Anti-Terrorism / Cyber / Anti-Human Trafficking / Special Tribunal |
| **BFIU** | Bangladesh Financial Intelligence Unit (Bangladesh Bank) |
| **CDR** | Community Dispute Resolution (informal village justice managed by *Nijera Kori*) |
| **CO** | Credit Organizer (*samity*-level microfinance field staff) |
| **CrPC** | Code of Criminal Procedure |
| **CSA** | Climate Smart Agriculture (18 practices tracked in `C-RANGPUR`) |
| **DBLA** | District Bar Legal Aid |
| **DLAC / UZLAC / UPLAC** | District / Upazila / Union Parishad Legal Aid Committee |
| **DLAO** | District Legal Aid Officer / Office |
| **DQA** | Data Quality Assessment (checks validity, reliability, accuracy, timeliness) |
| **EI** | Exposure Index (30% weight in `HCVI`) |
| **ELCO** | Eligible Couple (tracked in *Jononni* maternal health registers) |
| **ESS** | Environmental and Social Safeguard |
| **FGD** | Focus Group Discussion (qualitative method) |
| **GIZ** | *Deutsche Gesellschaft für Internationale Zusammenarbeit* (German development agency) |
| **GRO** | General Register Officer (Court Police) |
| **HCVI** | Household Climate Vulnerability Index ($\mathrm{EI}$, $\mathrm{SI}$, $\mathrm{ACI}$) |
| **HH** | Household |
| **ICPS** | Strengthening Disability-Inclusive Child Protection Systems (UNICEF project) |
| **IGA** | Income Generating Activity |
| **KII** | Key Informant Interview (qualitative method) |
| **KoBo Toolbox** | Offline mobile data collection suite (KoBo Collect / Enketo Express) |
| **LRL** | Livelihood Restoration Loan (post-COVID scheme up to BDT 50k, 8% declining balance) |
| **LSID** | Legal Service Information Desk (operated by RDRS in court premises) |
| **MEAL** | Monitoring, Evaluation, Accountability and Learning (used in INGOs e.g. Save the Children) |
| **MEL** | Monitoring, Evaluation and Learning (RDRS department) |
| **MFI** | Microfinance Institution |
| **MSDS** | Monthly Savings Deposit Scheme (3-yr 7%, 5-yr 7.5%) |
| **NCD** | Non-Communicable Disease (8 tracked in `C-RANGPUR` Sec. 9) |
| **OTR** | On-Time Repayment rate |
| **PAR** | Portfolio at Risk |
| **PKSF** | Palli Karma-Sahayak Foundation (funded *Somriddhi*) |
| **PNGO** | Partner Non-Governmental Organization |
| **POMIS-4 / POMIS-5** | Standard microfinance statements in `G Banker` (`POMIS-4`: Income & Expenditure; `POMIS-5`: Financial Position / Balance Sheet) |
| **PW** | Pregnant Woman (tracked in *Jononni*) |
| **SI** | Sensitivity Index (30% weight in `HCVI`) |
| **SPSS** | Statistical Package for the Social Sciences (used with numeric survey codes) |
| **TOR** | Terms of Reference (scope & methodology contract for a baseline study) |
| **WASH** | Water, Sanitation and Hygiene |

#### B. Bengali, Field & Court Terms

| Term | Meaning in RDRS Field Context |
| :--- | :--- |
| ***Aposh-joggo*** | Compoundable offenses under the CrPC that can legally be settled through mediation / ADR |
| ***Boro Abbu*** | Intern's grandfather; one of the 27 developers on RDRS's original `Micro Bank` team (1995–97) who later helped transition to `South Tech` |
| ***Char*** | Shifting low-lying river island in northern Bangladesh vulnerable to annual floods and erosion |
| ***Dishari*** | Bengali for "pathfinder / navigator"; name of the offline browser scheduling & reporting app built during the internship |
| ***Ejlash*** | Open courtroom and judge's/magistrate's bench where formal hearings occur |
| ***Federation*** | Autonomous member-run community apex body formed by RDRS at Union level (**406** active) |
| ***Monga*** | Traditional pre-harvest seasonal hunger/lean employment period in northwest Bangladesh (~Sep–Nov) |
| ***Samity*** | Village microcredit group (typically 15–30 women) meeting weekly for savings and loan repayments (**21,134** active) |
| ***Serestha*** | Court clerk's administrative office holding physical case folders, registers, and cause lists |
