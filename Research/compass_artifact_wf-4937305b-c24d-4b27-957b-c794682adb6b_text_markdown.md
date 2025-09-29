# UK DWP Attributes and Data Sharing: Comprehensive Analysis

**The UK benefits system collects overlapping personal data across fragmented services, with significant standardization opportunities undermined by technical barriers and failed digital identity infrastructure.** Government departments use over 20 different identifier systems, legacy IT affects 28% of systems, and the failed Gov.UK Verify achieved only 48% verification success versus a 90% target. While HMRC-DWP integration demonstrates effective data sharing with real-time earnings feeds, NHS and other authoritative sources remain largely siloed, requiring duplicate evidence collection from vulnerable claimants.

This research examines attribute collection across Universal Credit, PIP, Attendance Allowance, ESA, State Pension, and five other major DWP services, analyzes conceptual alignment potential, documents seven authoritative data sources beyond DWP, and quantifies the £154 million cost of digital identity failures that continue to impede cross-government verification.

## Comprehensive attribute catalogue across DWP services

### Universal Credit: The consolidation attempt

Universal Credit represents the most comprehensive single benefit, collecting **13 major attribute categories** spanning personal identity to work requirements. The service demonstrates both the potential and challenges of attribute consolidation.

**Core personal and household data:** UC collects standard identifiers (name, DOB, NI number, address) plus detailed household composition including relationship status, children's ages, and non-dependant residents. The system distinguishes children born before versus after 6 April 2017, affecting payment rates—a temporal attribute unique to UC's implementation timeline.

**Financial attributes with precise thresholds:** UC's financial data collection reveals specific measurement standards. Capital thresholds operate at **£6,000 (no impact), £6,001-£16,000 (tariff income of £4.35/month per £250), and £16,000+ (ineligible)**. The work allowance differs based on housing costs element receipt (£411/month with housing costs, £684/month without), with a 55% taper rate reducing UC by 55p per £1 earned above the allowance. These precise numerical thresholds enable automated calculation but create sharp cliff edges.

**Health and disability assessment:** UC collects condition descriptions, treatment details, healthcare professional contacts, and medication lists. The Work Capability Assessment (WCA) determines Limited Capability for Work (LCW, worth £158.76/month for pre-April 2017 claims) or Limited Capability for Work and Work-Related Activity (LCWRA, worth £423.27/month). The system asks how conditions affect specific activities, mobility, and whether special equipment is needed.

**Caring and childcare specificity:** For caring, UC requires the **precise 35-hour weekly threshold**, details of the person cared for including their qualifying disability benefit, and confirmation that care recipient receives PIP daily living component, DLA middle/highest care rate, or Attendance Allowance. For childcare, UC demands provider Ofsted registration numbers, exact costs per payment period, and dates covered—then reimburses 85% up to **£1,031.88/month for one child or £1,768.94/month for two or more children**.

**Housing cost complexity:** UC's housing element varies by tenure type (social housing versus private rental), applies Local Housing Allowance caps for private renters, and implements bedroom tax deductions (14% for one spare bedroom, 25% for two or more). The shared accommodation rate applies to single claimants under 35 with specific exceptions. This creates a complex matrix of housing attributes that must be verified and updated.

**Evidence automation through HMRC:** UC's most significant innovation is automated earnings verification through HMRC's Real-Time Information system, which shares employer-submitted payroll data with DWP **four times daily**. This eliminates manual payslip submission for employed claimants, though self-employed individuals still report monthly income and expenses manually.

### Personal Independence Payment: Functional assessment granularity

PIP operates on a **points-based functional assessment** fundamentally different from means-tested benefits. The system assesses **12 activities: 10 for daily living (preparing food, taking nutrition, managing therapy, washing and bathing, managing toilet needs, dressing and undressing, communicating verbally, reading and understanding, engaging with others, making budgeting decisions) and 2 for mobility (planning and following journeys, moving around)**.

**Precise descriptors and scoring:** Each activity has multiple descriptors with specific point values. For preparing food, descriptors range from 0 points (can prepare and cook unaided) to 8 points (cannot prepare and cook food). For moving around, descriptors use specific distance measurements: **more than 200 meters (0 points), 50-200m (4 points), 20-50m unaided (8 points), 20-50m with aid (10 points), and 1-20m or cannot stand (12 points)**. Claimants need 8-11 points for standard rate, 12+ for enhanced rate per component.

**Reliability criteria applied consistently:** PIP applies a reliability test requiring activities be completed safely, to acceptable standard, repeatedly, in reasonable time (no more than twice as long as non-disabled person), and over more than 50% of days in a 12-month period. This temporal dimension means fluctuating conditions are assessed across the full year, not just at a snapshot.

**Evidence from healthcare ecosystem:** PIP collects GP names, consultant details, hospital records, care plans, occupational therapy reports, and prescription lists. The application form (PIP2 "How your disability affects you") asks open-ended questions about how conditions affect each activity, requiring narrative descriptions rather than checkboxes. Face-to-face assessments by healthcare professionals add observational evidence to self-reported data.

### Attendance Allowance: Frequency-based care needs

Attendance Allowance for State Pension age individuals takes a **frequency-measurement approach** rather than points. The AA1 claim form asks "how often each day" or "how often each night" for each care need, distinguishing this from PIP's descriptor system.

**Granular frequency questions:** For toilet needs, AA asks separately about difficulty frequency, incontinence frequency, help needed frequency, and encouragement needed frequency—all per day. For night-time care, the form asks "how often each night? (1, 2, 3+)" and "how many minutes each time?" for turning over in bed, toilet needs, incontinence management, and medication needs. This creates time-based care profiles showing the 24-hour care burden.

**Specific care scenarios:** AA includes questions PIP doesn't emphasize as strongly, particularly around night-time supervision. Question 44 asks: "Do you need someone to watch over you at night? How many times a night does someone need to be awake? How long on average does someone need to be awake?" This captures the sleep disruption burden on carers, relevant for the supervision requirement.

**Two-rate structure:** AA has only two rates—lower (day OR night care) and higher (day AND night care)—making it simpler than PIP's four-rate structure (standard/enhanced for each of two components). Assessment criteria focus on whether personal care or supervision is needed, rather than a granular points calculation.

### Employment and Support Allowance: Work capability descriptors

ESA's Work Capability Assessment uses two schedules of descriptors representing different capability levels. **Schedule 2 (Limited Capability for Work) has 17 activities requiring 15+ points total**. Schedule 3 (Limited Capability for Work and Work-Related Activity) has 16 descriptors where **satisfying ANY ONE descriptor qualifies**.

**Physical function measurements:** ESA mobilizing descriptors use the same distance thresholds as PIP: cannot mobilize more than 50m (15 points), cannot mobilize more than 100m (9 points), cannot mobilize more than 200m (6 points). Standing and sitting descriptors measure time at workstation: cannot remain for more than 30 minutes (9 points) or more than 1 hour (6 points). These time and distance measurements enable objective comparison across claimants.

**Manual dexterity specificity:** ESA includes highly specific manual dexterity descriptors: cannot press button or turn pages with either hand (15 points), cannot pick up £1 coin with either hand (15 points), cannot use pen/pencil to make meaningful mark (9 points), cannot single-handedly use keyboard or mouse (9 points). These link functional limitations to specific workplace tasks.

**Mental function activities:** ESA's mental health descriptors include learning tasks (cannot learn beyond simple task like setting alarm clock), awareness of hazards (requires supervision for majority of time), initiating personal actions, coping with change (cannot cope with minor planned/unplanned changes), and appropriateness of behavior (daily/frequent/occasional uncontrollable episodes). The frequency distinctions (daily/frequently/occasionally) mirror AA's temporal approach.

**Non-functional "treat as" conditions:** ESA includes conditions that bypass functional assessment: terminal illness (6 months prognosis), receiving regular dialysis, undergoing chemotherapy/radiotherapy, or pregnancy creating serious health risk. The "substantial risk" provision allows capability to be found even without meeting descriptors if work/work-related activity would pose substantial risk to health.

### State Pension: Automated data integration

State Pension demonstrates the **most mature automated data sharing** in DWP services, relying almost entirely on HMRC's National Insurance contribution records. The service collects minimal additional data because the qualifying criteria—10 years minimum, 35 years for full amount—are verified through existing NI records.

**Key attributes collected:** NI number (links to contribution history), date of birth (determines State Pension age, currently 66), gender (for transitional provisions), marital/civil partnership status (for inheritance rights), and deferral decisions. Protected payments apply for those entitled to more under pre-2016 rules, requiring calculation of additional State Pension (SERPS/S2P) for pre-2016 contributions.

**Evidence minimization through integration:** State Pension applications rarely require documentary evidence because DWP automatically accesses HMRC data. The "Check your State Pension" online service pulls HMRC contribution records directly, showing claimants their forecast without manual verification. This represents the ideal of "tell us once" data sharing—citizens see the government's existing knowledge about them rather than repeatedly providing it.

### Other major DWP services

**Pension Credit** adds means-testing to State Pension, collecting weekly income from all sources and savings over £10,000 (counted as income at £1 per week per £500 over threshold). It includes carer and severe disability additions, creating attribute overlaps with Carer's Allowance and disability benefits.

**Carer's Allowance** requires the **same 35-hour weekly threshold as UC's carer element** but with stricter earnings limits (£196/week maximum versus UC's more generous work allowances). The service verifies that the person cared for receives a qualifying disability benefit—the same list as UC (PIP daily living component, DLA middle/highest care rate, Attendance Allowance, Constant Attendance Allowance, Armed Forces Independence Payment).

**Bereavement Support Payment** collects deceased partner's NI contribution history, death certificate details, relationship status, and whether responsible for children under 20. The service has two rates: higher with children (£3,500 lump sum + £350/month for 18 months) and standard (£2,500 lump sum + £100/month for 18 months). It requires evidence of the qualifying relationship through marriage certificate, civil partnership certificate, or cohabitation evidence if claiming as cohabiting partner.

**Jobseeker's Allowance (New Style JSA)** is contribution-based, requiring Class 1 NI contributions from employment in the previous 2-3 tax years. It collects employment history for the previous 6 months, job search activities, and availability for work (minimum 40 hours/week). JSA has strict time limits—maximum 182 days (approximately 6 months)—unlike UC which continues as long as conditions are met.

**Maternity Allowance** requires working in at least 26 weeks of a 66-week "test period" before the due date, earning at least £30/week in at least 13 of those weeks. The critical evidence is the **MAT B1 certificate** from doctor or midwife at 20 weeks of pregnancy. HMRC employment and earnings records verify the work test, demonstrating another successful automated data sharing pathway.

**Winter Fuel Payment** has expanded eligibility from 2025-26 to include those born before 22 September 1959 **with annual taxable income below £35,000**. The service relies entirely on automated data matching—DWP cross-references State Pension records, benefit records for qualifying benefits (Pension Credit, Universal Credit), and HMRC tax records for income verification. Most eligible recipients receive payment automatically without claiming.

## Conceptual alignment analysis and standardization potential

### Disability and health: The most fragmented domain

Disability assessment represents the **greatest conceptual misalignment** across DWP services, with four different assessment methodologies operating in parallel.

**Four incompatible approaches:** PIP uses a points-based functional assessment with 12 activities and specific descriptors. Attendance Allowance uses frequency-based care needs measurement asking "how often per day/night" without points. ESA uses two schedules of work capability descriptors with different scoring rules (15+ points for LCW, any one descriptor for LCWRA). Universal Credit adopts ESA's WCA descriptors for its own LCW/LCWRA determination. These systems assess overlapping concepts—mobility, personal care, cognitive function—but use incompatible frameworks making cross-benefit comparison impossible.

**Distance measurements show rare alignment:** The 50-meter, 100-meter, and 200-meter distance thresholds appear in both PIP (Activity 12: Moving around) and ESA (Activity 1: Mobilising), representing one of the **few standardized measurements across benefits**. PIP's "cannot stand or move more than 20 meters" and ESA's similar threshold create a common language for severe mobility limitation. This demonstrates that standardization is possible when departments choose to align.

**Health condition coding inconsistencies:** Research from DWP's own data standards work (2019) identifies that ESA uses ICD-10 chapter codes (too broad to identify specific disabilities), DLA uses "learning difficulties" as a category, while PIP uses "learning disabilities"—different terminology for overlapping populations. The Equality Act 2010's definition of disability ("substantial and long-term negative effect on ability to do daily activities") differs from operational benefit definitions, creating legal versus administrative concept misalignment.

**Reliability criteria partially shared:** PIP and ESA both apply reliability tests requiring activities be completed safely, repeatedly, to acceptable standard, and in reasonable time. However, PIP's "over 12-month period, more than 50% of days" temporal specification is more precise than ESA's practice. This partial alignment suggests a common conceptual framework exists but implementation details diverge.

**Assessment timescales vary:** PIP assesses capability over a 12-month period (3 months retrospective, 9 months prospective). Attendance Allowance has a 6-month qualifying period. ESA has a 13-week assessment phase. These different timescales mean the same condition might qualify for one benefit but not another purely due to duration requirements, not severity differences.

### Caring responsibilities: Threshold convergence

The **35-hour weekly threshold** appears identically in Universal Credit's carer element, Carer's Allowance, and Pension Credit's carer addition, representing **strong conceptual alignment**. All three benefits also use the same list of qualifying disability benefits that the person cared for must receive: PIP daily living component (either rate), DLA middle or highest care rate, Attendance Allowance, Constant Attendance Allowance, Armed Forces Independence Payment, and Scottish equivalents.

**Earnings treatment diverges:** Despite threshold alignment, how earnings affect carer support varies dramatically. Carer's Allowance has a strict £196/week earnings limit (approximately £10,200 annually). Universal Credit's carer element has no separate earnings limit but subject to UC's overall income assessment with work allowances and 55% taper. Pension Credit's carer addition is means-tested based on total income. The same caring situation thus produces different financial outcomes depending which benefit is claimed, despite the conceptual care requirement being identical.

**Hours of care verification differs:** UC, Carer's Allowance, and Pension Credit all require 35+ hours but verify this through different mechanisms. Carer's Allowance requires more detailed employment history to ensure work doesn't prevent caring. UC assesses caring alongside work requirements in the claimant commitment. This administrative divergence complicates multi-benefit claims where the same caring must be evidenced differently for each benefit.

### Financial attributes: Capital thresholds misaligned

Capital thresholds across benefits show **no standardization**, creating a complex landscape where the same savings produce different outcomes.

**Capital limit variations:** Universal Credit allows up to £16,000 (or was £16,000, with higher limits for those migrated from legacy benefits under transitional protection). Pension Credit has no upper capital limit but counts savings over £10,000 as income (£1/week per £500). Carer's Allowance (contribution-based variant, New Style JSA) has no capital limit as it's not means-tested. Housing Benefit (still operating separately) has its own capital rules. A person with £12,000 in savings would be affected differently by UC (tariff income reducing award), Pension Credit (income generation reducing award), and Carer's Allowance (no effect).

**Income assessment methodologies differ:** UC uses net income after tax, NI, and pension contributions with work allowances and a 55% taper. Pension Credit uses a weekly income calculation including assumed income from capital. ESA (contribution-based) doesn't assess income at all for eligibility. Housing Benefit has separate income assessment rules. These different methodologies mean claimants on multiple benefits face multiple calculations of "income" from the same earnings.

**Tariff income calculations diverge:** UC counts capital between £6,001-£16,000 as generating £4.35/month per £250 or part thereof (approximately £1/week per £250). Pension Credit counts capital over £10,000 as generating £1/week per £500. These different tariff income calculations mean the same £12,000 in savings generates **£42/week assumed income in UC (£10.50/week for £2,000 over £6,000 at £1/week per £250 after monthly conversion) but £4/week in Pension Credit (£2,000 over £10,000 at £1/week per £500)**. This mathematical inconsistency has no policy rationale.

### Housing costs: Attribute overlap with local authority systems

Housing cost assessment in UC creates **significant attribute duplication** between DWP and local authority systems. UC collects landlord details, rent amount, service charges, bedroom numbers, tenancy agreement dates—the same information collected by local authorities for Council Tax, housing registers, and Housing Benefit (still operating for some claimants). Local Housing Allowance rates, calculated by the Valuation Office Agency, must be matched to UC claims requiring geographic data alignment.

**Bedroom standards show rare consistency:** UC's bedroom entitlement rules align closely with Housing Benefit's, both allowing one bedroom for each: adult couple, single adult aged 16+, two children under 16 of same gender, two children under 10 of any gender, any other child, foster children, disabled child who cannot share, and non-resident carer for disabled person. This alignment arose from UC deliberately adopting Housing Benefit rules to ensure consistent treatment, demonstrating that policy decisions can create standardization when prioritized.

### Identity and personal data: Universal requirements with no universal verification

All benefits require **National Insurance number, date of birth, address, and bank account details**—these represent genuinely universal attributes across the entire DWP portfolio. Yet verification methods remain non-standardized. State Pension automatically verifies NI number through HMRC linkage. UC attempts online identity verification through GOV.UK Verify (48% success rate) or face-to-face at Jobcentre. PIP sends paper forms requiring identity documents. This verification fragmentation exists despite conceptual attribute identity.

**Name changes create cross-benefit issues:** Marriage, civil partnership, divorce, or deed poll name changes must be reported separately to each benefit. While the identity attribute (a person's legal name) is conceptually singular, the administrative systems treat it as separate data points requiring independent updates. HMRC, DWP, HMPO, and local authorities all hold name data but with no automated name change propagation.

## Quantified overlap and standardization opportunities

### Attribute categories: High-level overlap assessment

Analyzing the collected research, **approximately 8 core attribute categories** appear across multiple DWP services:

1. **Personal identity** (name, DOB, NI number, address): 100% of services
2. **Household composition** (relationship status, children, household members): 70% of services (UC, Pension Credit, Carer's Allowance, Bereavement Support, Maternity Allowance, Winter Fuel Payment)
3. **Financial - income**: 60% of services (UC, Pension Credit, Carer's Allowance, JSA have earnings assessments; others are contribution-based)
4. **Financial - capital/savings**: 30% of services (UC, Pension Credit, Housing Benefit have means testing)
5. **Health and disability**: 50% of services (UC's LCW/LCWRA, PIP, AA, ESA all assess disability but using different frameworks)
6. **Caring responsibilities**: 40% of services (UC carer element, Carer's Allowance, Pension Credit carer addition)
7. **Housing costs**: 30% of services (UC, Pension Credit, Housing Benefit)
8. **Employment and work history**: 60% of services (UC, JSA, Maternity Allowance, Carer's Allowance, ESA assess work)

**Service-specific attributes constitute approximately 30-40% of total data collected.** These include: PIP's specific functional descriptors (12 activities), AA's frequency measurements, UC's childcare provider registration numbers, Bereavement Support's deceased partner NI contributions, Maternity Allowance's test period calculations, and Winter Fuel Payment's age-based eligibility.

### Standardization feasibility: Three-tier classification

**Tier 1 - Already standardized (15-20% of attributes):** National Insurance number, date of birth, bank account details, the 35-hour caring threshold, qualifying disability benefits list for caring, and the 50/100/200-meter mobility distances. These demonstrate successful standardization and could be preserved as government-wide standards.

**Tier 2 - Standardizable with policy alignment (30-40% of attributes):** Capital limits and tariff income calculations, income assessment methodologies, bedroom entitlement rules, LCW/LCWRA descriptors across UC and ESA, reliability criteria for disability assessment, and qualifying NI contribution requirements. These have no inherent reason for variation—differences reflect historical policy choices rather than fundamental incompatibility. Aligning these would require policy decisions but face no technical barriers.

**Tier 3 - Legitimately service-specific (40-50% of attributes):** PIP's daily living activities differ from ESA's work capability activities because they assess different questions (can you live independently vs. can you work). Maternity Allowance's test period is specific to pregnancy timing. State Pension's qualifying years relate to contributory principle. Winter Fuel Payment's age threshold is a policy choice about who needs heating support. These attributes serve distinct policy purposes and shouldn't necessarily be standardized.

### Data sharing maturity: A spectrum

**Highly automated (10% of data flows):** HMRC-DWP earnings sharing through RTI represents gold standard data sharing, with four transfers daily and automatic matching to UC claims. State Pension's NI contribution record access is similarly mature. HMRC shares over **200 data items** in RTI Full Payment Submissions, but DWP only uses a subset relevant to benefits. This demonstrates that technical capability for rich data sharing exists but remains underutilized.

**Partially automated (20% of data flows):** Winter Fuel Payment's automated matching against benefit records and HMRC tax records shows progress. Tell Us Once covers death notifications to HMRC, DWP, DVLA, and HMPO, but only for life events, not ongoing data synchronization. Local authority Housing Benefit data shares with DWP for some UC claimants.

**Request-based manual (50% of data flows):** NHS medical evidence requires GP reports requested per benefit claim with patient consent. Life Events Verification enables electronic verification of births, deaths, marriages registered after 2009, but requires departmental request—it's not automatic. Passport verification through Passport Validation Service requires specific requests rather than continuous validation.

**Non-existent (20% of data flows):** DWP has no direct access to bank account data (proposed powers in 2025 legislation), property ownership records, or comprehensive address validation. Cross-benefit data sharing within DWP itself requires manual processes in many cases—a PIP award doesn't automatically update UC's disability records, requiring claimants to report the same information to both systems.

## Authoritative sources for citizen attributes beyond DWP

### Birth certificates and General Register Office: The foundational non-identity document

The General Register Office maintains England and Wales civil registration records from 1837, with **over 130 million digitized records** in the EAGLE system (Electronic Access to GRO Legacy Events). Birth certificates contain name, date and place of birth, sex, parents' names and occupations, and registration details—but explicitly state **"not evidence of a person's identity"** despite being treated as identity documents in practice.

**What GRO can authoritatively assert:** That a birth was registered with specific details on a specific date. The certificate confirms the registration event, not that the person presenting it is the person registered. This conceptual distinction matters—birth certificates verify that someone with this name was born, not that you are that person.

**Life Events Verification digital pathway:** The LEV service enables electronic verification of births, marriages, and deaths registered in England/Wales **after 2009** without paper certificates. HMRC and UK Visas & Immigration use LEV with legal authority under the Identity Documents Act 2010. This creates a two-tier system: post-2009 registrations can be verified digitally, pre-2009 require paper certificates costing **£12.50 standard or £38.50 priority**. The digital/paper divide creates access barriers for older citizens whose births predate the digital cutoff.

**Limitations as authoritative source:** Civil registration wasn't compulsory before 1875, meaning some births were never registered. Adoption creates discrepancies where original birth certificates differ from adoption certificates. Name changes after birth aren't reflected in original birth certificates—a married woman with changed surname must present both birth certificate and marriage certificate to establish identity continuity. GRO data doesn't automatically propagate to other government systems, requiring citizens to repeatedly present certificates.

### HM Passport Office: Biometric data with 80-year retention

HM Passport Office holds biometric photographs, passport numbers, names, dates of birth, places of birth, gender, nationality, and signatures for all passport holders. **E-passports issued from 2006 contain biometric chips** storing the photograph and personal details page data. Application records include additional attributes: NI number, residential address, previous names, parent/partner details—all retained for **80 years**.

**Identity verification standards:** Passports represent "medium level of confidence" under Government Proof of Identification (GPG 45) guidance. First-time applicants undergo interviews. Biometric facial recognition compares new photos against existing passport photos for fraud detection. Third-party corroboration requires someone in a "recognised profession" who has known the applicant for 2 years to confirm identity—creating a social network verification layer.

**Passport Validation Service:** PVS validates passport information for law enforcement agencies, employers (identity/immigration status verification), financial services (fraud prevention), and other government departments. This enables real-time passport validity checking without manual document inspection. However, **not all passport data is available to all departments**—sharing requires lawful basis and proportionality under UK GDPR Article 9(2)(g).

**The circular dependency problem:** First-time passport applications require corroboration from professionals who have known applicants for 2 years, but approximately **10% of UK citizens have never held a passport** (Digital ID consultation 2025 estimate). For services requiring passport for identity verification, this creates exclusion. The passport-as-prerequisite model assumes universal passport ownership, but citizenship doesn't require passport possession.

### NHS records: Rich clinical data, consent-gated sharing

The NHS holds the richest personal data in government: full medical histories, diagnoses, prescriptions, hospital admissions, specialist consultations, mental health records, and disabilities. The **NHS Number** serves as a unique 10-digit identifier across NHS organizations in England and Wales, enabling record linkage across GP practices, hospitals, and specialists.

**What health data can assert:** NHS records authoritatively document medical history, diagnosed conditions, treatments received, and healthcare professional observations. The Summary Care Record contains key information from GP records including medications, allergies, and adverse reactions, accessible by authorized healthcare providers. For disability benefits, GP records provide the evidential foundation for functional limitation claims.

**Current data sharing with DWP: Consent-based and request-driven:** DWP requests medical reports from GPs, consultants, or health professionals **with patient explicit consent** for benefits claims. Health professionals complete factual medical reports covering disabilities, conditions, symptoms, treatment, impact on daily activities, and recent hospital stays. Reports contain **only information the patient is already aware of**—no third-party information is shared, no retrospective investigations are required.

**Legal basis:** UK GDPR Article 6(1)(e) (public task) and Article 9(2)(b) (necessary for social security obligations) provide the legal framework, with common law duty of confidentiality satisfied by patient consent. GMC guidance allows accepting DWP assurance of consent without directly contacting patients. However, this consent requirement means NHS data isn't automatically available for benefit verification—each request is individual.

**Limitations as authoritative source:** Patient consent requirement prevents automatic data flows. GPs are not required to conduct new examinations for benefit reports, only provide factual information from existing records. The National Data Opt-out allows patients to prevent NHS England sharing their data for research/planning, though it doesn't affect individual care or statutory disclosures. NHS records are held at GP practice level, not centrally accessible without specific requests, fragmenting the data landscape.

**SR1 forms for terminal illness:** GPs, consultants, hospice doctors, or senior specialist nurses can complete SR1 forms for patients nearing end of life (12 months prognosis for PIP/AA, 6 months for ESA). This enables fast-track benefit claims, representing one of the few proactive NHS-to-DWP data flows, though still requiring healthcare professional action rather than automatic system integration.

### HMRC: The most successful data-sharing partnership

HMRC holds comprehensive employment, income, tax, and National Insurance data, making it **the most valuable authoritative source for DWP** with the most mature sharing infrastructure. The Real-Time Information system requires employers to submit Full Payment Submissions to HMRC on or before each payday, containing over **200 specified data items**.

**RTI data items include:** NI number, title, full name, DOB, gender, residential address, passport number (for right-to-work verification), employer PAYE reference, payroll ID, employment start/end dates, pay frequency, payment dates, tax week/month, hours worked (banded: up to 15.99, 16-23.99, 24-29.99, 30+, other), taxable pay, total tax deducted/refunded, NICs (employee and employer), student loan repayments, pension contributions, and statutory payments (SMP, SPP, SAP, ShPP, SPBP).

**DWP-HMRC integration mechanics:** RTI data transfers to DWP **four times daily** (approximately 3am, 9pm, and two other times). For Universal Credit, DWP registers interest in specific individuals with HMRC; RTI data for those individuals is automatically shared. Matching occurs using NI number, name, DOB, and address. Payment date determines which UC assessment period earnings are allocated to, creating time-sensitive calculation effects.

**BACS hash matching for validation:** Employers paying via BACS using their own Service User Number include hash codes in both RTI submissions and BACS payment instructions. HMRC/DWP validate earnings data against actual payments using these hashes, providing automatic validation that reduces UC disputes. This represents sophisticated technical integration beyond simple data transfer.

**What HMRC can authoritatively assert:** Employment status, earnings, tax payments, NI contributions, and contribution history. For State Pension, HMRC data provides the complete evidentiary basis—qualifying years, contribution types, credits for unemployment/caring/illness, and contracted-out periods. This enables State Pension to operate with **minimal additional evidence collection** from claimants.

**Self-employment data lag:** Unlike employed individuals' real-time earnings, self-employed people report through annual Self-Assessment tax returns. UC requires monthly self-employment income/expense reporting, creating a mismatch where HMRC has annual data but DWP needs monthly data. This represents a gap in the HMRC authoritative source for self-employed populations.

**Tax Credits data sharing:** HMRC shares Tax Credits data with local authorities for Housing Benefit administration under Tax Credits Act 2002 Schedule 5. The Eligibility Checking Service shares data with Department for Education for free school meals eligibility under Education Act 2005 s110. This demonstrates HMRC's role as data hub beyond DWP interactions.

### DVLA: Driving license verification with limited scope

DVLA holds driver numbers, names, DOB, gender, residential addresses, license validity dates, photographs (on photocard licenses), signatures, driving entitlements, restrictions, endorsements, penalty points, disqualifications, medical conditions affecting driving, and driving test history.

**Driver "check code" system:** Individuals generate 21-day single-use check codes online via GOV.UK. Codes allow third parties to view license status, endorsements, penalty points, expiry date, vehicle categories, and photograph. This individual-controlled sharing model contrasts with automatic RTI integration—drivers must proactively enable data sharing rather than it occurring automatically.

**Access restrictions:** DVLA data is released only for motoring incidents, road safety, or enforcing traffic legislation under Road Vehicles (Registration and Licensing) Regulation 2002. "Reasonable cause" must be demonstrated. Police and law enforcement have full access. Insurance companies and employers access with driver consent. This domain-specific data sharing model prevents DVLA data serving as general identity verification infrastructure despite holding verified addresses and photographs.

**Limited benefit system integration:** DVLA data doesn't integrate with benefit systems except where disability affects driving (must notify DVLA of conditions affecting driving ability). Blue Badge parking permits create a tenuous link between disability benefits and DVLA, but data flows are limited. Driving licenses serve as identity documents for benefit applications but require manual presentation rather than electronic verification in most cases.

### Local authorities: 300+ fragmented data silos

Local authorities collectively hold Council Tax records, housing information, housing registers, temporary accommodation placements, homelessness applications, and benefit claim data. **Across 300+ local authorities in England**, this data remains largely fragmented with no centralized national database.

**Council Tax data attributes:** Property address, property band (A-H), liable person(s) names, correspondence address, payment history, arrears, discounts/exemptions, single person discount eligibility, Council Tax Support entitlement, and household composition inferred from discounts. The Valuation Office Agency provides property attributes (rooms, bedrooms, property type) underpinning banding.

**Data sharing with DWP:** Welfare Reform Act 2012 Section 131 permits data sharing between DWP, local authorities, and social landlords for welfare services, social security, and council tax support. Permitted uses include troubled families programme, bedroom tax administration, disabled person's badge eligibility, housing support eligibility, disability adaptation grants, and Discretionary Housing Payments. Section 132 makes unauthorized disclosure a criminal offense, limiting wider data sharing.

**Fragmentation limitations:** No national Council Tax database means DWP cannot automatically verify housing costs or household composition from Council Tax records. Each local authority maintains separate systems with varying data quality. Address changes reported to one authority don't propagate to others or to central government. This fragmentation prevents Council Tax records serving as an authoritative source despite their potential value for household composition verification.

**Housing Benefit data exchange:** The ongoing Housing Benefit system (not yet fully replaced by UC) involves extensive data exchange between local authorities and DWP. Some UC claimants still receive Housing Benefit for temporary accommodation, creating dual systems requiring data synchronization between local and central government.

### GOV.UK One Login: Emerging digital identity infrastructure

GOV.UK One Login represents the government's attempt to create unified digital identity and authentication, rolling out to replace Government Gateway and other sign-in systems. As of November 2024, **50 services use One Login, with 1.5+ million verified identities issued and 2+ million app downloads**.

**Verification methods and standards:** One Login achieves "medium confidence level" under GPG 45 (Government Proof of Identity 45), providing confidence against impostors without relationship to claimed identity, impostors with limited information, and synthetic identities. The UK Digital Identity and Attributes Trust Framework maintained by the Office for Digital Identities and Attributes (OfDIA, part of DSIT) governs standards.

**Three verification routes:** (1) GOV.UK One Login app with photo ID scan (passport, driving license, BRP/BRC/FWP up to 18 months expired), biometric face scan matched to photo ID, liveness detection, and document authentication via biometric chip for passports. Requires smartphone with camera (iOS 15+ or Android 10+). (2) Online browser journey with photo ID details entry, security questions based on mobile phone contracts, bank accounts, credit cards, loans, and mortgages, validated through credit reference agency data. (3) In-person Post Office verification (private beta) where Post Office scans photo ID and takes photo, with results usually within a day.

**What One Login can assert:** Once verified, One Login provides services with email address (authentication only), core identity claims (name, DOB, address), driving license details (if used for verification), passport details (if used for verification), fraud indicators (if identity fraudulent), and level of confidence achieved. Selective disclosure enables users to share minimum information needed, such as "over 18" yes/no response rather than full DOB.

**Critical security gaps:** Computer Weekly investigation (November 2024) revealed One Login **only complies with 21 of 39 outcomes** in NCSC Cyber Assessment Framework designed for critical national services. This improved from 5 outcomes a year earlier but represents significant gaps. The service went live with known security risks, raising questions about governance. Consultancy 6point6 providing security assurance support noted the team "previously had insufficient security knowledge, weak controls and few standards."

**Coverage limitations:** One Login doesn't yet work with Universal Credit as of September 2025, limiting its value for the highest-volume benefit. Different services have different verification requirements, requiring multiple identity proving journeys. The system cannot be used by multiple people with the same email address—one email equals one verified identity, creating challenges for family members sharing email addresses. Failed verification requires manual support or alternative routes, with no clear pathway for those unable to verify digitally.

**Smartphone dependency:** App-based verification requires iOS 15+ or Android 10+ with functioning camera. Browser verification requires credit history for knowledge-based questions. In-person Post Office verification (addressing digital exclusion) remains in private beta. These requirements create barriers for vulnerable populations without smartphones, credit history, or digital literacy.

## Data sharing barriers and ontology challenges

### The identifier fragmentation crisis

The Public Accounts Committee's 2019 report "Challenges in using data across government" quantified the problem: **more than 20 different identifiers** used to identify people and organizations across just 10 departments. Departments hold inconsistent data in incompatible systems both within departments and across government, with no standardized ways of recording data. This makes bringing data together "difficult and expensive."

**National Insurance number as partial solution:** NI number appears universally across HMRC, DWP, and NHS systems, providing one standardized identifier. However, it doesn't extend to local authorities (which use local reference numbers), passport systems, DVLA, or many other government databases. NI numbers are sometimes recorded with spaces (e.g., "AB 12 34 56 C") and sometimes without, creating matching failures from trivial formatting differences.

**Address matching catastrophe:** ONS Working Paper (2017) documented that **no universally accepted standard** exists for what constitutes the "correct" address format in the UK. Royal Mail's Postcode Address File contains 29 million addresses with **4,000-5,000 daily updates**. When Ordnance Survey attempted to independently recreate PAF, **4.2 million addresses (over 1 in 10) required manual checking** due to missing or erroneous data. Problems include houses on private shared drives, houses with names but no numbers, newly built addresses not yet in databases, and flats with non-standard numbering. Different departments store addresses in many different forms—some as single text fields, others as structured data with separate house number/street name/postcode fields—making matching "significantly complicated."

**Disability definition inconsistencies:** DWP's own 2019 data standards work identified that ESA uses ICD-10 chapter codes for health conditions (too broad to identify specific disabilities), DLA uses "learning difficulties," while PIP uses "learning disabilities"—different terminology for overlapping populations. The Equality Act 2010's definition of disability differs from all operational benefit definitions, creating legal versus administrative misalignment. The Family Resources Survey changed disability questions over time, with surveyors noting "comparisons over time should be made with caution"—the government's own disability statistics are inconsistent across years.

### Gov.UK Verify: £154 million failure

Gov.UK Verify (2014-2020) represents **the most extensively documented digital identity failure** in UK government history, with National Audit Office investigation (March 2019) and Public Accounts Committee condemnation.

**Quantified failure metrics:** Target of 25 million users by 2020; achieved only 3.6 million by February 2019 (projected 5.4 million by 2020)—**14.4% of target, an 86% shortfall**. Target of 46 government services by March 2018; achieved only 19 services by March 2019. Target of 90% verification success rate; achieved only **48% success rate**—52% of attempts failed even for those who completed the process. For Universal Credit specifically, only **38% success rate**. Cost of at least **£154 million by December 2018** (likely underestimate excluding departmental reconfiguration costs).

**Revenue collection failure:** Only 1 of 7 departments (HMRC) paid invoices to verify providers. **£2 million of £3.6 million invoiced remained outstanding**, indicating departments didn't value the service enough to pay for it. This reveals not just technical failure but fundamental lack of departmental buy-in.

**Why Verify failed - structural causes:** GDS set over-optimistic expectations from the start (NAO and PAC found systematic optimism bias). Assurance levels were too high—not enough public data exists to prove identity in a 100% digital process for the entire population. The service only supported individual citizens with no functionality for intermediaries (Power of Attorney, carers, accountants) or business users, limiting use cases. Critical services like HMRC felt Verify didn't meet their needs and continued using Government Gateway—only ~4% of HMRC customers used Verify. Subject to **more than 20 internal and external reviews** during its lifetime, indicating repeated failure to address problems.

**Infrastructure and Projects Authority verdict:** In July 2018, IPA recommended the programme "be closed as quickly as practicable." Public Accounts Committee concluded Verify "failed to meet any of its original performance targets," was "simply not delivered," and was "characterised by poor decision-making" with "failure to take proper accountability."

**Impact on vulnerable groups:** NAO reported young people and disabled people were disproportionately affected by Verify failures—the populations most likely to need benefit access faced the highest barriers. This represents the inverse of good public service design where government should reduce barriers for vulnerable groups.

### Ontology differences impeding interoperability

**Date format inconsistency:** Government recommends ISO 8601 extended format (YYYY-MM-DD), but adoption is inconsistent. Legacy systems use various date formats including DD/MM/YYYY, MM/DD/YYYY, and text dates. This creates calculation errors and matching failures when dates are misinterpreted.

**Taxonomy governance failures:** Government Data Architecture Community (2021) noted lack of central governance for taxonomies across government. Departments use "tweaked" taxonomies for own purposes, impacting comparability. During the pandemic, individuals had trouble accessing benefits due to **organizations using different taxonomies for the same concepts**. A Taxonomy Oversight Group was created in 2021 to address coordination failures, indicating the problem was severe enough to require new governance.

**Character encoding variations:** GDS mandates UTF-8 character encoding, but legacy systems use various encodings (Latin-1, Windows-1252, etc.). This causes problems with names containing accented characters, Welsh names with special characters, or non-Western names. Data transfer between systems with different encoding can corrupt names, creating identity matching failures.

### Legal barriers to data sharing

**Complex legal requirements:** Organizations must identify lawful basis under UK GDPR Article 6 before sharing, plus identify legal power or gateway for public bodies to share personal data. Multiple frameworks apply: UK GDPR, Data Protection Act 2018, Digital Economy Act 2017, sector-specific laws. The Data Sharing Network of Experts 2025 report found **20% of data sharing cases lack clear guidance** at the outset, with late recognition of personal data protection requirements due to misconceptions about UK GDPR.

**Gateway requirement bottleneck:** Specific statutory gateways required for data sharing between departments. The Digital Economy Act 2017 created new legal frameworks, but by 2019 only **~36 new data sharing agreements** were approved—progress "slower than expected." Each agreement requires legal basis to be established, which is complex and time-consuming. Section 132 of Welfare Reform Act 2012 makes unauthorized disclosure a criminal offense, creating risk aversion that inhibits data sharing even where it might be lawful.

**Privacy concerns and public trust:** 2023 government consultation on data sharing for digital ID revealed public expressed strong concerns around data privacy. DWP bank account surveillance plans in 2025 legislation were critiqued by Disability Rights UK as "likely breach privacy law and could amount to unlawful." YouGov polling shows mixed public opinion: 34% support national ID cards, 25% strongly support, indicating substantial opposition. This creates political barriers to data sharing infrastructure even where legal authority exists.

### Technical barriers: Legacy system crisis

**Legacy IT prevalence:** Public Accounts Committee AI Report (January 2025) found **28% of central government systems are "legacy"** (defined as end-of-life product, out of support from supplier, impossible to update). Approximately **33% of Government's 72 highest-risk legacy systems still lack remediation funding**. Poor quality data is locked away in out-of-date systems. PAC stated: "Too often Government data are of poor quality."

**Incompatible data systems:** PAC Report (2019) found departments developed own systems "often to deliver a specific policy," resulting in "inconsistent data in incompatible systems both within departments and across government." Without data standards, bringing data together is "difficult and expensive," forcing people to develop "manual workarounds to match data." The Cabinet Office confirmed government needs "standardised ways of recording data so it can be shared between systems easily" but lacked a comprehensive list of legacy IT systems.

**Royal Mail PAF privatization issue:** The Postcode Address File is privatized and expensive to access. Daily updates (4,000-5,000 changes) mean data quality degrades rapidly if systems don't purchase regular updates. Different departments use different address validation services or none at all, creating data quality divergence. The privatized address infrastructure creates a perverse incentive where accurate address matching requires ongoing licensing fees to a private company.

### Organizational and cultural barriers

**Departmental silos:** PAC findings noted "Civil servants are unused to working outside departmental boundaries," creating an "extra hurdle" to cross-departmental initiatives. The Data Sharing Governance Framework identified "working in silos" as a primary barrier. Staff awareness and capability of how to share data properly needs improvement—around **200 people trained** on basics of data through the "data science accelerator" initiative, and GDS Academy introduced only **two courses on data**, revealing skills gap scale.

**Risk appetite differences:** Data Sharing Network of Experts report (2025) identified "managing differences in risk appetite between departments" as a key challenge. Different departments have varying levels of data maturity and governance—some are more risk-averse regarding data sharing. Fear of security breaches, legal liabilities, or changes to established processes creates resistance. This requires "shift in organizational culture, breaking down silos, and promoting cross-departmental collaboration."

**Data minimization tension:** DSNE identifies "implementing practical data protection principles, such as data minimisation" as an ongoing challenge. Tension exists between collecting enough data for robust verification versus privacy principles of collecting only necessary data. Different departments resolve this tension differently, creating inconsistent practices.

### Tell Us Once limitations

Tell Us Once enables reporting deaths to government departments in a single interaction but has **significant scope limitations**. Coverage includes only HMRC, DWP, DVLA, HMPO, Veterans UK, Social Security Scotland, and local council services (Housing Benefit, Council Tax, Blue Badges, electoral register). It does NOT cover banks, utility companies, private pension providers, insurance companies, employers, landlords/housing associations, or most private sector organizations.

**Operational constraints:** 28-day window to use the service after receiving unique reference number from death registrar. If inquest underway, must get interim death certificate from coroner first. Requires extensive information about deceased, executor/administrator, and surviving spouse including NI numbers. Legal professionals report the service creates a "false sense of security" for executors who assume more organizations are notified than actually are, leading to missed notifications and complications.

### DWP-specific challenges

**Limited access to authoritative sources:** DWP Eligibility Verification Powers Factsheet (2025) states: "For other eligibility criteria - such as savings and capital - DWP does not have direct access to authoritative sources." DWP uses HMRC data for employment/income verification but has limited access to other key data. The 2025 Public Authorities Fraud, Error and Recovery Bill proposes new powers for DWP to require banks and financial institutions to check accounts, indicating current access is insufficient.

**Limited third-party information powers:** Currently can only request information from a "limited number of third parties" and existing requests must be done by "writing" or "visit" with **little ability to enforce electronic response**. Under Data Protection Act 2018, organizations have choice whether to provide information. Approximately **20,000 requests made in 2023-24** under existing powers. New legislation aims to create "single, clear legal gateway" and enable digital responses, acknowledging current processes are inadequate.

**Duplicate data collection problems:** PAC Report (2018) found DWP **could not monitor its treatment of vulnerable claimants** (mental health, disabilities) because **data not collected** within systems on these groups—described as data quality being "an afterthought." This forces claimants to repeatedly provide the same information. Scope Forum Evidence (2024) documented a case where DWP investigation requested 6 months of bank statements, then **a year later requested the same statements again** because "taken them too long to investigate"—claimant responsibility to re-provide data already submitted.

**Data retention policy tensions:** DWP Managing Customer Records Guide states "Must not retain duplicate information under any circumstances" and prohibits retaining supporting records locally for longer than 4 weeks after upload. Tension exists between data protection requirements (not retaining indefinitely) and investigation needs. This creates scenarios where evidence must be re-provided because retention limits were reached during processing delays.

**Verification delay impacts:** Universal Credit manual processing increased when Verify verification failed (38% success rate). Verification checks can temporarily delay payments for legitimate claimants. System flags triggered by outdated contact details, recent benefit changes, joint claims, or bank detail changes. DWP verification procedures include cross-checking multiple data sources, but **limited access to authoritative data causes delays**. The National Fraud Initiative requires manual investigation of all matches, creating additional verification workload not automated.

## Summary: The fragmentation toll

The UK government's approach to citizen attributes remains fundamentally fragmented despite decades of digital transformation efforts. **Universal attributes like NI number, DOB, and address exist across all services, yet verification remains non-standardized.** The £154 million Gov.UK Verify failure demonstrates the difficulty of creating unified digital identity without addressing underlying data quality, system compatibility, and organizational culture issues.

**Approximately 30-40% of DWP attributes could be standardized** with policy alignment—capital thresholds, income assessment methodologies, bedroom rules, disability descriptors—but remain divergent due to historical policy choices rather than technical necessity. The successful HMRC-DWP RTI integration proves automated, real-time data sharing is possible when prioritized, yet NHS data remains consent-gated and request-driven, local authority data fragmented across 300+ bodies, and birth/death/marriage records only digitally verifiable for post-2009 registrations.

The 20+ different identifiers across departments, 4.2 million addresses requiring manual checking, inconsistent disability terminology, and 28% legacy IT systems create a landscape where "difficult and expensive" data sharing requires "manual workarounds" rather than automated processes. The proposed 2025 bank account verification powers—projected to save £940 million over 5 years—acknowledge DWP lacks access to authoritative capital/savings sources, forcing continued reliance on claimant-provided evidence for means-tested benefits.

Standardization opportunities exist in three tiers: 15-20% already standardized (NI number, caring thresholds, mobility distances), 30-40% standardizable with policy decisions (capital limits, income assessment), and 40-50% legitimately service-specific (PIP daily living versus ESA work capability). The question is not technical feasibility—RTI proves rich automated data sharing works—but rather organizational, legal, and political will to prioritize interoperability over departmental autonomy.