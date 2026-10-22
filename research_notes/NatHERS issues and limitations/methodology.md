# NatHERS (Home Energy Rating) star ratings for new houses: methodology, assumptions, exclusions and documented limitations

**How to read these notes**
- **Scope.** NatHERS thermal (heating and cooling) star ratings for new Class 1 houses. NatHERS has been branded "Home Energy Rating" since 1 July 2026. WA points are marked **WA**. The notes are current to 22 October 2026.
- **Quotes.** No page was opened. WebFetch was tried once (ahd.csiro.au) and failed with `getaddrinfo ENOTFOUND`. Every quotation is therefore a **search extract**. The search tool sometimes paraphrases, so check each quote on the live page before it is published.
- **Budget.** 44 of the 45 allowed web searches were used.
- **Issue IDs** are used throughout:
  - M: metric and star bands
  - O: occupant assumptions
  - C: climate data
  - P: physics and design features
  - X: exclusions
  - T: tools and consistency
  - V: validation
  - R: reforms
- **Where each field sits.** For every issue, the Cited Findings hold what it is, the evidence (source, year, type and quote) and the counter-evidence. The table in each Inferences section holds the evidence strength, whether the criticism also applies to H6V2 (the backfire risk), a marketing-safety rating and suggested wording.
- **Evidence strength.**
  - Strong: primary government or peer-reviewed data, corroborated.
  - Moderate: a single primary source, or peer-reviewed work that is narrow or old.
  - Weak: media, industry or advocacy claims, or an extract that couldn't be confirmed.
- **H6V2 backfire.**
  - High: the same criticism applies fully to a simulation-based H6V2 Performance Solution.
  - Medium: it applies partly.
  - Low: it doesn't apply, or H6V2 differs.
- **Internal sources.** Two Thermarate repo documents are cited by their local paths. The first is [the H6V2 independent review](/home/user/test/H6V2_shading_independent_review.md), which quotes the NCC 2022 H6V2 text from ABCB XML and the ABCB housing handbook v1.1. The second is [the Performance Solutions awareness strategy](/home/user/test/Performance_Solutions_awareness_strategy.md).
- **Already established, not repeated.** These points are relied on but not re-argued:
  - the certificate's statement of standard assumptions and its appliance exclusion;
  - 7 stars as the NCC 2022 minimum;
  - the area correction factor (SAP 2023), zero at about 196 m² (CSIRO, 2012);
  - CSIRO's 2021 thermal-bridging findings;
  - Wingrove, Heffernan and Daly (2024), +10.4%;
  - that H6V2 fixes its own assumptions and must use non-NatHERS ASHRAE 140 software.
- **Additions or corrections to the established points:**
  - **7-star minimum.** In NCC climate zones 1–2 it is relaxed to 6.5 or 6 stars with a qualifying outdoor living area (P8).
  - **CSIRO air-infiltration report.** Search extracts date it June 2024 (Ambrose & Maxwell). The strategy document cites a 2025-10 NatHERS-hosted PDF, probably a republication; check which is current (P5).
  - **Thermal bridging.** NatHERS applies thermal bridging only to steel framing, "based on a comparison to timber framing as a benchmark" (P9).

---

## Q1. How is the star rating calculated (Chenath, MJ/m², star bands, area correction factor), and does per-m² hide total energy or favour larger homes?

### Takeaway
All four accredited tools run the same CSIRO Chenath engine. The engine estimates annual heating and cooling loads per m² of conditioned floor area, applies an area correction factor, and converts the result to 0–10 stars using bands set separately for each of the 69 climate zones. The bands were recalibrated in 2022, by curve-fitting, so that on average the 6-star level did not change.

The evidence does **not** support "bigger homes rate more easily". NatHERS's own explanation is that raw MJ/m² would favour large homes, and the area correction factor exists to offset that, so it marks large homes down. What the evidence strongly supports is that a per-m² rating says nothing about **total** energy. Growth in house size has eroded the savings that higher star levels should have delivered.

### Cited Findings

#### M1 — One CSIRO engine (Chenath) under all accredited tools, updated in versions
- **What it is.**
  - NatHERS gives a 0–10 star rating of thermal performance based on the design and materials.
  - About 600 assessors use "one of four accredited software tools, all built on the CSIRO physics engine, Chenath".
  - The inputs cover climate, orientation, walls, windows, floors and roof.
  - Source: [CSIRO, "It's in the stars" (2021)](https://www.csiro.au/en/news/all/articles/2021/september/its-in-the-stars-how-scientists-figure-out-your-homes-energy-rating). Government (CSIRO). Search extract: "A 1-star home would be poorly performing, while a 10-star home would need little or no energy to stay comfortable year-round" (CSIRO's Anthony Wright).
- **History.** NatHERS began in 1993, based on the Victorian scheme and the CHEETAH/CHEENATH engine. Source: [Wikipedia](https://en.wikipedia.org/wiki/Nationwide_House_Energy_Rating_Scheme), a tertiary source, so weak.
- **Version history.**
  - **Chenath 3.21 (2019)** fixed "double height void modelling, basement zones and shared wall adjacency in apartment buildings, improved edge slab insulation and waffle pod modelling", and added limestone. Source: [NatHERS News Issue 8, May 2019](https://nathers.gov.au/node/320). Government. Search extract.
  - **NCC 2022 compliance** can only be shown with software using Chenath 3.22 or 3.23. In Victoria the transition ended on 1 May 2024, and 3.21 is now allowed only on a written request from the building surveyor. Sources: [VBA industry alert (2023)](https://www.vba.vic.gov.au/news/news/2023/industry-alert-use-of-older-nathers-software-versions), a government regulator; also [SA DIT Advisory Notice 03/23](https://dit.sa.gov.au/__data/assets/pdf_file/0005/1281317/Advisory-Notice-03-23-Adoption-of-NatHERS-software-from-1-October-2023-for-NCC-2019-and-NCC-2022-Energy-Efficiency.pdf).
  - **Chenath 3.24.** AccuRate Home v1.3.3.24 uses Chenath v3.24 ([NatHERS software updates](https://www.nathers.gov.au/node/295)). The release date wasn't found.
- **NCC 2025 accreditation.**
  - The Software Accreditation Protocol (SAP) for New Homes 2025 is dated 22 November 2024 and "only applies to software tools using the Chenath Engine". Source: [SAP New Homes 2025](https://www.nathers.gov.au/sites/default/files/2025-11/SAP%20New%20Homes%202025%2020241122.pdf). Government.
  - "Minimal changes to residential provisions and NatHERS software tools" were expected for NCC 2025. Source: [NatHERS News, 7 March](https://nathers.gov.au/node/596) and [HIA](https://hia.com.au/resources-and-advice/sustainable-homes/energy-efficiency/articles/do-you-use-nathers-software-for-energy-ratings). The extract did not say which of the two said it.
- **Counter-evidence and context.**
  - AccuRate is the scheme's benchmark tool.
  - The SAP sets "software accuracy requirements" in Appendix 2 ([2019 SAP](https://www.nathers.gov.au/sites/default/files/2019-10/2019%20NatHERS%20Software%20Accreditation%20Protocol.pdf); [SAP Thermal 2022](https://www.nathers.gov.au/sites/default/files/2022-09/SAP%20Thermal%202022%2020220901.pdf)). The tolerance values weren't retrieved.

#### M2 — The rating is per m² of conditioned floor area, so total energy is hidden
- **What it is.** "The energy rating is calculated on the basis of 'energy loads' per square metre of the floor area." Source: [NatHERS, Area correction factor](https://nathers.gov.au/node/299). Government. Search extract.
- **Clune, Morrissey and Moore (2012).** *Energy Policy* 48:657–667, peer-reviewed ([IDEAS/RePEc](https://ideas.repec.org/a/eee/enepol/v48y2012icp657-667.html); [RMIT repository](https://research-repository.rmit.edu.au/articles/journal_contribution/Size_matters_House_size_and_thermal_efficiency_as_policy_strategies_to_reduce_net_emissions_of_new_developments/27454575)).
  - The study modelled 72 houses.
  - Search extract: between 2003 and 2009 in Victoria, "growing house size cut the value of moving from 5 to 6 stars by 38%."
  - A related article argues that per-m² metrics can reward larger dwellings, because energy use grows more slowly than floor area. It also says stricter standards for large homes are "problematic". Source: [The Fifth Estate](https://thefifthestate.com.au/innovation/residential-2/the-benefits-of-insulation-have-been-blown-by-big-houses/). Media.
- **Stephan and Crawford (2016).** Peer-reviewed journal article; the extract didn't name the journal ([journal listing](https://findanexpert.unimelb.edu.au/scholarlywork/1109668-the-relationship-between-house-size-and-life-cycle-energy-demand--implications-for-energy-efficiency-regulations-for-buildings); [University of Melbourne news](https://findanexpert.unimelb.edu.au/news/5136-size-does-matter--australia)).
  - Search extract: "Most energy efficiency regulations only measure energy use per square metre. Using this metric, larger houses appear to be more efficient because energy use increases at a slower rate than house size."
  - Search extract: the energy embodied in a 392 m² Melbourne house "alone is larger than both the embodied and operational energy demands of a 100-square-metre house with three occupants, over 50 years."
- **Wingrove and Heffernan (2024).** Their headline +10.4% is already established. Additional quotes:
  - "A policy focus on energy efficiency has not led to falls in the predicted energy requirements for heating and cooling – either for individual homes or the new home sector as a whole."
  - The 2023 policy improvements "do not directly address the impact of floor area on heating and cooling energy requirements".
  - Sources: [University of Sydney news, 11 March 2024](https://www.sydney.edu.au/news-opinion/news/2024/03/11/bigger-home-designs-wipe-out-energy-efficiency.html); [CSIRO Australian Housing Data (AHD) post](https://ahd.csiro.au/?p=2309). University media, peer-reviewed underlying study. Search extracts.
- **Counter-evidence.**
  - The area correction factor (M3) penalises large homes.
  - A University of Melbourne piece on Stephan and Crawford's research notes that "the Australian 6-star standard accounts for house size in heating and cooling while other certifications do not" ([University of Melbourne](https://findanexpert.unimelb.edu.au/news/5136-size-does-matter--australia)). Search extract, attribution approximate.

#### M3 — The area correction factor: whom it favours and penalises
- **What it is and which way it works.** Smaller homes have walls and ceilings that are large relative to their floor area, and windows that make up a bigger share of their walls.
  - Search extract: "Without an area correction factor, smaller dwellings would have more difficulty meeting each star level than larger ones."
  - Worked example: 4 stars before correction becomes about **5.2 stars for a 50 m² home in Hobart**, while **a 350 m² home in Brisbane drops to 3.2 stars**.
  - "All NatHERS Accredited Software includes an area correction factor."
  - Source: [NatHERS, Area correction factor](https://nathers.gov.au/node/299). Government. Search extract.
- **Already established:** the factor is in SAP 2023 and is zero at about 196 m² (CSIRO, 2012).
- **Counter-evidence.** No independent evaluation was found of whether the factor removes the size bias exactly, or over- or under-corrects (see Gaps).

#### M4 — Star bands by climate zone, and the 2022 recalibration
- **What it is.** "Unique Star Bands are set for each Climate Zone to allow fair comparisons of buildings despite extreme regional variability in weather conditions." Source: [NatHERS Star bands (2019 PDF)](https://www.nathers.gov.au/sites/default/files/2019-10/NatHERS%20Star%20bands.pdf). Government. Search extract.
- **How the 2022 bands were set.** New climate files could shift ratings unevenly, so the bands were reset.
  - A 2019 study offered two options: "limited change" (±0.2 stars) or "zero average change". The NatHERS steering committee chose zero average change.
  - Method: 18 dwelling designs were rated in all 69 zones at 1, 5, 6, 7 and 9 stars, then re-rated with the new climate files. A best-fit curve was fitted for each zone and used to set the new bands.
  - Sources: [NatHERS 2022 Starbands](https://www.nathers.gov.au/node/517); [TIC final report on the impact of updated climate files on the 2022 star bands](https://www.nathers.gov.au/sites/default/files/2023-05/TIC-Final-Report-Impact-Update-Climate-Files-on-NatHERS-2022-Star-Bands-References-updated.pdf). Government and consultant.
- **The outcome.**
  - "The 6-star energy level has, on average, been maintained at current levels."
  - "High starbands (greater than 6) slightly lower than the current settings in performance terms."
  - This appears to mean that bands above 6 stars became slightly less stringent; check the wording. Same sources. Search extract.
- **Example band value.** 7 stars in Melbourne is 62 MJ/m². Source: [Australian Glass Group presentation (MBAV, 2024)](https://mbav.com.au/sites/default/files/7_Star_Glazing_Solutions-Mike_Ward-Australian_Glass_Group-Green_Living_Conference_2024.pdf). Industry. The extract didn't say which edition of the bands this is; check it against the official 2022 table. The Perth values weren't retrieved.
- **Separate load limits.**
  - NCC 2022 added separate heating and cooling load limits "to reflect the overarching stringency increase in NCC 2022 to the equivalent of NatHERS 7 stars".
  - "Some climates dominated by hot or cold weather, such as some climate zones in Western Australia (WA), do not need separate heating and cooling limits."
  - Sources: [ABCB Standard, NatHERS Heating and Cooling Load Limits 2022](https://www.nccb.gov.au/sites/default/files/resources/2022/nathers-heating-cooling-load-limits-2022.pdf); [NatHERS 2022 Starbands](https://www.nathers.gov.au/node/517). Government. Search extract; which of the two said which is approximate.
  - **WA:** a WA variation removes the separate NatHERS heating and cooling load limits ([internal strategy document](/home/user/test/Performance_Solutions_awareness_strategy.md); already established).

#### M5 — Most new homes are designed only to the minimum (a stringency issue, not a method issue)
- **Moore, Berry and Ambrose (2019).** "Aiming for mediocrity", *Energy Policy* 132:602–610, peer-reviewed.
  - The study analysed over 187,000 NatHERS certificates from 2016–2018.
  - It found 81.7% of housing was "designed only to meet minimum standards" and 98.5% fell below the economic and environmental optimum. The average rating was 6.2 stars.
  - Sources: [IDEAS/RePEc](https://ideas.repec.org/a/eee/enepol/v132y2019icp602-610.html); [ASBEC summary](https://www.asbec.asn.au/news-items/aiming-for-mediocrity-the-case-of-australian-housing-thermal-performance/). Search extract: "Only 1.5% of new homes are built to optimum economic and energy performance."

### Inferences

| ID | Issue | Evidence strength | Does the same criticism apply to H6V2? (backfire) | Marketing | Suggested accurate wording |
|---|---|---|---|---|---|
| M1 | One engine, updated in versions | Strong as fact; not a flaw in itself | **High if used as a criticism.** H6V2 lets any ASHRAE 140 tool be used, so it is less standardised, not more | Avoid as a criticism | (Neutral, if needed:) "Every NatHERS rating is calculated by the same CSIRO engine under fixed national settings." |
| M2 | Per-m² metric hides total energy | **Strong** (three peer-reviewed studies plus NatHERS's own description) | **High.** H6V2 compares with a same-size reference, so it doesn't limit total energy either | Use with care | "A star rating measures heating and cooling need per square metre, so two 7-star homes of different sizes can need very different amounts of energy in total." |
| M3 | Area correction factor | Strong for the mechanism; weak for any claim that it is unfair | **Medium.** H6V2 has no size adjustment. Large homes escape the markdown and small homes lose the uplift, so critics could call H6V2 a big-house advantage | Use with care | "NatHERS adjusts ratings for floor area, marking larger homes down and smaller homes up. H6V2 instead compares your design with a Code-compliant version of the same house." |
| M4 | Star bands and the 2022 recalibration | Strong (NatHERS's own method) | **Low.** H6V2 uses no star bands, but the stringency of its DTS reference is equally a regulatory choice | Avoid. It's technical, and "7 stars got easier" would overreach | (If needed:) "Star bands are set separately for each of 69 climate zones and were recalibrated in 2022 when the weather files changed." |
| M5 | Most homes built to the minimum | **Strong** (187,000 certificates, peer-reviewed) | **High.** H6V2 also aims only at equivalence with the DTS minimum | Avoid | — |

- **"Bigger homes rate more easily" is not supported once the area correction factor applies.** NatHERS says the factor exists because raw MJ/m² made large homes rate more easily. The defensible claim is about total energy (M2), not about ease of rating.
- **H6V2 is size-neutral.** H6V2(3)(f) fixes the same floor plan in both models, so no area correction factor applies.
  - For homes above roughly 196 m², which NatHERS marks down, H6V2 may therefore be *relatively* easier than NatHERS.
  - For small homes, which NatHERS marks up, NatHERS may be easier.
  - This is a hypothesis to test on priced jobs, and a reason for the Pathway Check to screen by floor area. It also invites a "big-house loophole" criticism, so frame it as "the same house compared with its own Code version".
- **M5 backfires.** Thermarate sells a route designed to reach Code-equivalent performance at lower cost, so attacking "minimum" ratings would undercut its own product.

### Gaps
- The current area correction factor formula (SAP 2023 and 2025) and its zero point, and any independent test of whether it over- or under-corrects. Not found.
- The 2022 MJ/m² star bands for the Perth NatHERS zones (13 Perth, and the secondary-sourced 47 Bickley and 52 Swanbourne). The table in the search extract cut off at zone 51.
- The SAP Appendix 2 tolerances between accredited tools and the AccuRate benchmark. The values weren't retrieved.
- The average floor area of new Perth houses, needed to say how many WA homes the area correction factor marks down. No source found.

---

## Q2. What occupancy, thermostat, schedule and zoning assumptions are used, and how do they compare with real use?

### Takeaway
NatHERS fixes these settings:
- Heating to 20°C in living areas from 7am to midnight.
- Bedrooms heated to 18°C from 7–9am and 4pm–midnight, and to 15°C overnight.
- Cooling set-points of 22.5–27°C, depending on the climate zone.
- Living zones occupied 7am–midnight and bedrooms 4pm–9am, with each zone conditioned separately.

Field studies find real households differ from these settings:
- Bedrooms are used in the daytime.
- Some homes use 2–3 times the predicted heating energy.
- Cooling may be under-estimated.

But the largest monitoring study (129 houses) supports the static-thermostat approach, and CSIRO has said NatHERS was never meant to predict metered use. Because H6V2 also fixes thermostat settings, schedules, occupancy, zoning and internal gains, this is the **highest-backfire** category.

### Cited Findings

#### O1 — Fixed thermostat set-points
- **What it is.**
  - Living areas are heated to 20°C.
  - Bedrooms have "a minimum heating thermostat setting of 18 degrees Celsius from 7.00am to 9.00am and from 4.00pm to midnight and a heating setting of 15 degrees Celsius from midnight to 7.00am".
  - Cooling is set at 22.5–27°C depending on the NatHERS climate zone.
  - Source: [NatHERS Software Accreditation Protocol, June 2012, Appendix B](https://www.nathers.gov.au/sites/default/files/NatHERS%2520Software%2520Accreditation%2520Protocol-June%25202012.pdf). Government. Search extract. Whether a later SAP changed the values wasn't checked.
- **Basis of the cooling set-point.** It is set from the January neutral temperature for the zone, and cooling is "triggered at 2.5°C above the neutral temperature", based on the ASHRAE adaptive comfort model. Source: [SAP 2012](https://www.nathers.gov.au/sites/default/files/NatHERS%2520Software%2520Accreditation%2520Protocol-June%25202012.pdf) and/or [Low Carbon Living CRC RP1024](https://www.lowcarbonlivingcrc.unsw.edu.au/sites/all/files/publications_file_attachments/rp1024_indoor_air_temperatures.pdf). The extract didn't say which. Search extract.
- **Critique: UTS (Thomas et al., 2023).** The authors argue bedrooms should be assessed with a night-time heating set-point of 18°C instead of 15°C. Search extract: assumptions such as bedrooms being occupied only at night are "out of touch with observed and prevailing practices". Source: [UTS, "Regulation for comfort", ASA 2023](https://opus.lib.uts.edu.au/handle/10453/176133) ([PDF](https://opus.lib.uts.edu.au/bitstream/10453/176133/2/LThomasetal-ASA2023-Regulation%20for%20Comfort.pdf)). Peer-reviewed conference paper.
- **Critique: cooling under-estimated.** Search extract: "the default settings for cooling use in the NatHERS calculator seem to underestimate cooling. When estimated cooling energy is too low, it has little impact on the energy rating." Source: [The Fifth Estate, "Why do new energy-efficient houses need cooling?"](https://thefifthestate.com.au/innovation/residential-2/why-do-new-energy-efficient-houses-need-cooling/). Media citing CSIRO field data. The date wasn't shown.
- **Acknowledged by CSIRO.** In 2018 an expert group set out to review "heating and cooling thermostat setting temperatures" and "the triggering temperatures for heating and cooling". Monitored data "was not sufficient at the time to conduct a full review". Source: [CSIRO AHD, 12 December 2018](https://ahd.csiro.au/?p=677). Government. Search extract.
- **Counter-evidence.**
  - RP1024 monitored 129 houses in Adelaide, Brisbane and Melbourne from 2012 to 2014.
  - The temperature band in which occupants are least likely to use air conditioning shifts upward in warmer climates. The authors say this supports "the simplified static thermostat setting approach used in the AccuRate software", though the settings "should be adjusted with more research".
  - Source: [Low Carbon Living CRC RP1024](https://www.lowcarbonlivingcrc.unsw.edu.au/sites/all/files/publications_file_attachments/rp1024_indoor_air_temperatures.pdf). CRC research report. Search extract.
- **The same feature in H6V2.**
  - H6V2(3) requires the same "(n) function and use of the building and spaces, including zoning and hours of occupation", "(o) operating schedules for heating and cooling in Table H6V2a", and "(p)–(t) thermostat settings, occupancy, internal heat gains and air infiltration" in both models ([internal H6V2 review](/home/user/test/H6V2_shading_independent_review.md)).
  - The NT's H6V2 sets "space temperature settings in the range 20ºC to 21ºC for heating and 25ºC to 28ºC for cooling" ([ABCB, NCC 2022 NT Part H6](https://www.abcb.gov.au/editions/ncc-2022/adopted/volume-two/6-northern-territory/h6-energy-efficiency)).
- **History.**
  - The NCC 2019 reference-building Verification Method used 20–21°C for heating and 25–28°C for cooling.
  - CSIRO advised that "in most instances NatHERS tools are not appropriate" for that method ([WA Building Commission IB 89](https://wa.gov.au/system/files/2024-10/ib_89_0.pdf)). Government.
  - "Users are unable to change the relevant conditions in the NatHERS accredited tools" ([FR5 reposting CSIRO's alert, 2017](https://www.fr5.com.au/news/2017/07/25/csiro-advise-caution-nathers-tools-unsuitable-for-the-ncc-reference-building-verification-method-v2.6.2.2)).
  - "NatHERS does not accredit tools for use under other NCC compliance pathways" ([NatHERS](https://nathers.gov.au/node/125)).

#### O2 — Occupancy schedules and internal gains
- **What it is.** Each space has a function and a usage window, and a standard occupancy pattern applies "so homes can be compared fairly". Living spaces are conditioned from 7am to midnight and sleeping spaces from 4pm to 9am. Source: [NatHERS, Internal heat loads](https://nathers.gov.au/node/301). Government. Search extract.
- **Confirmed by CSIRO's comfort-rating method.** "Occupied hours match those assumed for Energy Star Ratings: living zones 7am to midnight, and bedrooms 4pm to 9am." Source: [CSIRO Darwin Living Lab, Darwin home comfort rating](https://research.csiro.au/darwinlivinglab/darwin-home-comfort-rating). Search extract.
- **Critique.** The UTS 2023 study of monitored western Sydney households looks at "the energy penalty incurred when bedrooms are more frequently used in the daytime" ([UTS ASA 2023](https://opus.lib.uts.edu.au/handle/10453/176133)).
- **Already established.** Daniel, Soebarto and Williamson (2015) found that occupant behaviour departs from NatHERS assumptions.
- **H6V2.** The schedules (Table H6V2a), occupancy and internal gains are fixed and are the same in both models ([internal review](/home/user/test/H6V2_shading_independent_review.md)).

#### O3 — Zoning and how much of the house is conditioned
- **What it is.** The 2018 expert group listed "zoning of the heating and cooling operation" for review, noting "the current model assumes each zone is operated separately" ([CSIRO AHD, 2018](https://ahd.csiro.au/?p=677)). Search extract.
- **Evidence on heating.** In monitored homes on Adelaide's Lighthouse estate, cooling was closely correlated with NatHERS, but heating less so. "Some homes using two to three times the NatHERS predicted energy use" for heating, possibly because of leakage or occupants heating more than the model assumes. Source: [Tim O'Leary, The Fifth Estate](https://thefifthestate.com.au/innovation/building-construction/high-nathers-ratings-deliver-results-so-long-as-builders-step-up/). Media article by the researcher; the underlying peer-reviewed O'Leary et al. (2016) is already established.
- **Evidence on benchmarks.** A Low Carbon Living CRC report found "discrepancies in energy consumption for space heating and cooling, lighting and plug loads". It recommends "updating and improving the benchmarks utilised by the NatHERS and BASIX assessment models". Source: [Low Carbon Living CRC BASIX short report (2019)](https://www.lowcarbonlivingcrc.unsw.edu.au/sites/all/files/publications_file_attachments/basix_short_report_final_26-03-19.pdf). CRC research. Search extract.
- **Counter-evidence and acknowledgement.** NatHERS "measures the inherent thermal performance of the building shell all other things being equal"; it was not designed to predict metered energy use. Source: [Department of the Environment and Heritage submission to the Productivity Commission energy-efficiency inquiry (c. 2004–05), reporting CSIRO's response](https://www.pc.gov.au/inquiries/completed/energy-efficiency/submissions/department_of_the_environment_and_heritage/sub069.pdf). Government. Search extract.
- **H6V2.** H6V2(3)(n) fixes "zoning and hours of occupation" ([internal review](/home/user/test/H6V2_shading_independent_review.md)).

#### O4 — One combined heating-plus-cooling metric, which can let winter performance offset summer
- **What it is.** Field data showed that "although the efficient homes had much lower heating energy use, their cooling energy use was not lower". A commenter proposed that compliance should "split the total load for both summer and winter performance", as BASIX does. Source: [The Fifth Estate](https://thefifthestate.com.au/innovation/residential-2/why-do-new-energy-efficient-houses-need-cooling/). Media. Search extract.
- **Partial fix.** NCC 2022 added separate heating and cooling load caps ([ABCB Standard 2022](https://www.nccb.gov.au/sites/default/files/resources/2022/nathers-heating-cooling-load-limits-2022.pdf)).
  - **WA:** the WA variation removes them ([internal strategy document](/home/user/test/Performance_Solutions_awareness_strategy.md)).
- **H6V2 differs.**
  - In NCC climate zones 2–7, H6V2(1)(a)(iii) requires "a heating load and a cooling load equal to or less than that of the reference building".
  - Zone 1 tests cooling only and zone 8 heating only ([internal review](/home/user/test/H6V2_shading_independent_review.md)).
  - Perth's urban councils are in NCC climate zone 5 ([ABCB WA climate zone map](https://codemark.abcb.gov.au/sites/default/files/resources/2020//ClimateZoneMapWA.pdf)).

### Inferences

| ID | Issue | Evidence strength | Does the same criticism apply to H6V2? (backfire) | Marketing | Suggested accurate wording |
|---|---|---|---|---|---|
| O1 | Fixed thermostat set-points | **Moderate** (a peer-reviewed conference paper, a media report and CSIRO's own review), but a 129-house study supports the approach | **High.** H6V2(3) fixes thermostat settings too, and the NT version uses 20–21°C and 25–28°C | Avoid as a differentiator | "Every compliance model, NatHERS or H6V2, uses standard thermostat settings, so neither predicts your energy bill." |
| O2 | Occupancy schedules | Moderate | **High.** Table H6V2a schedules, occupancy and gains are fixed | Avoid | As for O1 |
| O3 | Zoning and conditioned area | Moderate (heating 2–3 times predicted in some homes; cooling matched) | **High.** H6V2(3)(n) fixes zoning and hours | Avoid | — |
| O4 | Combined metric; cooling under-weighted | Moderate to weak (commentary, though NCC 2022's caps imply the problem was recognised) | **Low.** H6V2 tests heating and cooling separately in zones 2–7, which is *stricter* | Use with care. It's a credibility point, not a savings point | "In WA, a NatHERS rating is judged on combined heating and cooling. H6V2 requires the design to match or beat the reference on each separately." |

- **Assumption bias works the same way in both pathways.** NatHERS star bands and the H6V2 reference are both benchmarks computed under the same fixed assumptions.
  - A biased set-point or schedule changes *which* design features are rewarded, under both pathways.
  - H6V2's like-for-like comparison cancels some absolute error, but not bias that depends on the feature.
  - The ABCB handbook says H6V2's fixed items exist "to ensure that only the thermal performance of the building fabric … affects the simulated energy demand, rather than any differences in underlying simulation assumptions" ([internal review, handbook p 94](/home/user/test/H6V2_shading_independent_review.md)).
  - Thermarate cannot credibly attack NatHERS's assumptions while relying on equivalent ones.
- **O4 cuts against savings claims (WA).** Because the separate NatHERS load caps are removed in WA, a design that is heavy on cooling but light on heating could reach 7 stars yet fail H6V2's separate cooling test. Don't imply H6V2 is easier in general.

### Gaps
- The national NCC 2022 H6V2 thermostat settings table values weren't retrieved. If they mirror NatHERS's 20/18/15°C and zone-based cooling, the O1 backfire is total. The NT version is known: 20–21°C heating and 25–28°C cooling.
- The outcome of CSIRO's 2018 expert-group review of thermostat settings, zoning and the ceiling-fan model. Not found.
- A Darwin study of 38 households compared measured cooling behaviour with NatHERS assumptions; its results weren't in the extract.
- No study was found that quantifies how partial heating (only some rooms) changes predicted versus actual energy.

---

## Q3. Climate data: 69 zones, RMY files, postcode mapping, and historical versus future climate

### Takeaway
Each of the 69 NatHERS zones has a Reference Meteorological Year (RMY) file. The NCC 2022 files use 1990–2015 observations, replacing 1970–2005 data. Zones follow postcode boundaries "for convenience", with alternative zones where terrain differs, and the star bands were recalibrated so the change of files didn't move the average 6-star house.

CSIRO publishes projected (future) weather files in NatHERS format, but no plan to use them for regulation was found. Advocates argue historical data under-states future heat. H6V2(5) also requires historical typical-year data, so the future-climate critique backfires.

### Cited Findings

#### C1 — Historical climate files (1990–2015), not future climate
- **What it is.** The NCC 2022 climate files "will now include data from 1990 to the end of 2015 instead of 1970 to 2005". "Each of the 69 Climate Zones has its own Reference Meteorological Year (RMY) file." Source: [NatHERS 2022 Climate Files](https://nathers.gov.au/node/518). Government. Search extract.
- **How the files were built.**
  - The 2016 revision by New Zealand's National Institute of Water and Atmospheric Research (NIWA) used data "since 1990, but now extending to the end of 2015".
  - It was derived directly from half-hourly and synoptic data, rather than from the Australian Climate Data Bank used in earlier revisions.
  - It added Christmas Island to the 82 sites in the 2011 version.
  - Source: [NIWA NatHERS climate file report (2016)](https://www.nathers.gov.au/sites/default/files/2021-08/niwa_nathers_climate_file_2016_final_report.pdf). Consultant for NatHERS.
- **Access.**
  - CSIRO's guide describes hourly data for one year at "one of 83 Australian locations" ([CSIRO TMY user guide v6](https://ahd.csiro.au/wp-content/uploads/Typical-meteorological-year-weather-files-User-Guide-v6.pdf)).
  - The NatHERS Administrator provides the files "for research purposes only … on request" ([NatHERS, climate zones and weather files](https://nathers.gov.au/node/300)).
  - Sources differ on the count (69 zones versus 83 sites or files).
- **Future-climate files exist but are voluntary.**
  - CSIRO's projected files cover 83 locations, three emissions scenarios (RCP2.6, 4.5 and 8.5) and four future years.
  - They come in .epw and NatHERS format, for AccuRate, BERS Pro, FirstRate5 and HERO, and are free.
  - They were produced by "morphing" the 1990–2015 typical year with global climate model outputs.
  - Sources: [CSIRO AHD, projected weather files](https://ahd.csiro.au/?p=1567); [CSIRO Ag Data Shop](https://agdatashop.csiro.au/future-climate-predictive-weather). Government.
- **Critique (advocacy).**
  - Sweltering Cities and Renew argue ratings use "out-of-date climate data that underestimates how hot it's going to get in homes in the future" ([Sweltering Cities project report, Energy Consumers Australia, 2025](https://energyconsumersaustralia.com.au/sites/default/files/2025-05/pg016_swelteringcities_projectreport_futurehomeclimateresilience.pdf)). Search extract.
  - Renew projects that Brisbane cooling energy could roughly double by 2050, and that "a 7-star Queensland home built today could score zero stars by 2090 under a severe climate scenario" ([Renew, "Future-proofing Australia's homes"](https://renew.org.au/?p=19124); [HVACR News, 2026](https://hvacrnews.com.au/news/old-climate-data-leaving-australian-homes-exposed/)). Advocacy and media. Search extract.
- **Counter-evidence.** The same modelling found that "in cooler climates reduced heating use can offset increased cooling" ([Sweltering Cities report](https://energyconsumersaustralia.com.au/sites/default/files/2025-05/pg016_swelteringcities_projectreport_futurehomeclimateresilience.pdf)). Search extract.
- **H6V2.** H6V2(5): "Climatic data employed in the calculation method must be based on hourly recorded values and be representative of a typical year for the proposed location" ([internal review](/home/user/test/H6V2_shading_independent_review.md)).

#### C2 — Mapping postcodes to climate zones
- **What it is.** "Climate zones are generally aligned with postcode boundaries for convenience, except where there is likely to be a topographical or other feature within the postcode area that impacts the local climate. In this scenario, alternative zones are offered for the same postcode." Source: [NatHERS, climate zones and weather files](https://nathers.gov.au/node/300). Government. Search extract.
- **The NatHERS map's own disclaimer.** The map was last updated in September 2019, and "where there is any discrepancy between climate zones in this Climate Zone Map and the accredited NatHERS software, the climate zones provided in the accredited NatHERS software take precedence" ([NatHERS climate map](https://www.nathers.gov.au/themes/custom/govcms8_uikit_starter/climate-map/index.html)). A postcode spreadsheet was updated in September 2024 ([NatHERS](https://nathers.gov.au/node/300)).
- **WA zones.**
  - Zone 13 is Perth ([NatHERS Star bands PDF](https://www.nathers.gov.au/sites/default/files/2019-10/NatHERS%20Star%20bands.pdf)).
  - Zone 47 (Bickley) and zone 52 (Swanbourne) appear only in a [third-party pre-design form](https://form.jotform.com/90094003203946), a secondary source; check them.
  - The separate NCC zones put Perth's urban councils, such as Cottesloe and Claremont, in NCC climate zone 5 ([ABCB WA climate zone map](https://codemark.abcb.gov.au/sites/default/files/resources/2020//ClimateZoneMapWA.pdf)).

#### C3 — Changing the climate files shifted ratings, so the star bands were recalibrated
- **What it is.** The 2022 update put new climate files into all 69 zones and recalibrated the star bands so that most home types would, on average, see no change in rating. Source: [NatHERS overview and regulatory information session slides (November 2021)](https://www.nathers.gov.au/sites/default/files/2021-11/NatHERS%20Overview%20and%20Regulatory%20info%20session%20web%20slides.pdf). Government.
- **Size of the shift.** A Melbourne home rated 7 stars on the older data "would only achieve 6 Stars under the updated data", which is the effect *before* recalibration. Source: [Renew, "Building for a changing climate"](https://renew.org.au/renew-magazine/efficient-homes/building-for-a-changing-climate). Advocacy. Search extract.
- **The recalibration options** were "limited change" (±0.2 stars) or "zero average change" ([NatHERS 2022 Starbands](https://www.nathers.gov.au/node/517)).

### Inferences

| ID | Issue | Evidence strength | Does the same criticism apply to H6V2? (backfire) | Marketing | Suggested accurate wording |
|---|---|---|---|---|---|
| C1 | Historical climate files, no future climate | **Strong** as fact; **moderate** on impact (advocacy modelling) | **High.** H6V2(5) requires recorded, typical-year data, and in practice may use the same RMY or CSIRO typical-year files | Avoid as a differentiator. Use with care as education. Optionally offer a voluntary future-climate run as an extra | "Both NatHERS and H6V2 use historical 'typical year' weather (NatHERS uses 1990–2015 data), not projected future climate." |
| C2 | Postcode-to-zone mapping | Moderate (NatHERS's own description; no study of errors found) | **Medium.** The H6V2 modeller picks a file "representative … for the proposed location", which has the same distance-from-station problem plus discretion over which file | Use with care | "A NatHERS rating uses the weather file for your postcode's climate zone, which may come from a weather station some distance from your site." |
| C3 | Change of climate files and recalibration | Moderate | **Low to medium.** H6V2 compares two models on the same file | Avoid | — |

- **WA.** Perth spans several NatHERS zones, but H6V2's pass test is set by NCC climate zone (5).
  - Thermarate should record which weather file it uses, and why, in the design brief.
  - That pre-empts any "climate-file shopping" criticism.

### Gaps
- No official plan to adopt future-climate files for regulation was found as of October 2026.
- No study quantifying postcode-to-zone misallocation was found.
- Which weather station each Perth-area zone file is based on, and the MJ/m² differences between zones 13, 47 and 52 (and any others in Perth), weren't retrieved.

---

## Q4. How are natural ventilation, ceiling fans, thermal mass, slabs, infiltration, shading, roof colour, outdoor living areas and thermal bridging handled?

### Takeaway
Chenath combines several sub-models: multi-zone ventilation, occupant comfort, ceiling-fan air movement, a ground (slab) model and component-based infiltration. Each has documented debates:
- **Free-running or passive design** is poorly captured by a metric that assumes conditioning (peer-reviewed, 2009).
- **Ground, roof-space and thermal-mass algorithms** were flagged for further work by empirical validation in Tasmania.
- **Uninsulated slabs** differ by about 50% between tools.
- **Steel-frame bridging** is counted only for steel, and is benchmarked against timber.
- **Infiltration** assumptions match measured new homes reasonably well (CSIRO, 2024).

There is **no** independent evidence that NatHERS under-credits Perth double brick. Nearly every physics critique applies at least as strongly to a general-purpose ASHRAE 140 model used for H6V2.

### Cited Findings

#### P1 — Natural ventilation and free-running (passive) performance
- **What it is.** NatHERS software "integrated a multi-zone ventilation model, an occupant thermal comfort model, and air movement driven by ceiling fans". The 2018 expert group suggested that "combined or separated metrics for naturally ventilated and mixed-mode buildings should be developed". Source: [CSIRO AHD, 2018](https://ahd.csiro.au/?p=677). Government. Search extract.
- **Transparency.** "BERS Pro and other House Energy Rating Software packages make assumptions regarding the ventilation openings of various window types. No indication is given on how the ventilation openings were calculated." Source: [Breezway technical bulletin](https://www.breezway.com.au/downloads/hawaii/TB_Ventilation_Openings.pdf). Manufacturer. Search extract.
- **Kordjamshidi and King (2009),** *Energy and Buildings*, peer-reviewed. Search extract: "an efficient design for a house in conditioned operation mode differs from that for the same house in the free-running operation mode, and … this is a primary reason for the inability of current energy based rating schemes to adequately assess the performance of passive design in a temperate climate." Source: [UNSWorks](https://unsworks.unsw.edu.au/entities/publication/5c4b41aa-5449-43f3-8e2a-43bbb74b236a/full).
  - Kordjamshidi's 2011 Springer book, *House Rating Schemes: from energy to comfort*, extends the argument. It challenges these schemes' "inability to evaluate free running buildings which do not need an energy load for heating and cooling". Source: [Kordjamshidi publications page](https://umz.academia.edu/MariaKordjamshidi). Attribution approximate: the extract didn't say which result described the book.
- **Warm-humid climates (older paper).** "NatHERS works well in the southern states of the country, where the primary use of energy is for heating", but it "worked poorly in warm humid climates such as found in Queensland", which led to the modifications that became AccuRate. Source: ["Problems of house energy rating (HERS) in warm-humid climates"](https://core.ac.uk/works/6264971). Year not shown, but it predates AccuRate. Search extract.
- **Counter-evidence.** A NatHERS Administrator study of northern climates found the software "provides significant reward for traditional hot climate design techniques" ([Application of NatHERS Software in Northern Australian Climates (ANSNAC)](https://nathers.gov.au/publications/validation-nathers-software-tropical-regions)). Government. Search extract.
- **The exact Chenath window-opening algorithm wasn't found** (see Gaps).

#### P2 — Ceiling fans
- **What it is.**
  - The software "does not take into account appliances, apart from the airflow impacts from ceiling fans" ([CSIRO AHD, 2018](https://ahd.csiro.au/?p=677)).
  - The ceiling-fan model was listed for review ("the cooling effect of air movement including the ceiling fan model").
  - ANSNAC has a section headed "Ceiling fans can provide a substantial benefit to the star rating, particularly in tropical and hot climates" ([ANSNAC report](https://www.nathers.gov.au/sites/default/files/Final%2520ANSNAC.pdf)). Government. Search extract; only the contents page was seen.
- **NCC concession for outdoor living areas with fans** (see P8). The fan must cover no more than 15 m² if its blades are under 1200 mm, or 25 m² if they are 1200 mm or more ([NCC 2022 Volume Two, house energy rating software](https://ncc.abcb.gov.au/editions/ncc-2022/adopted/volume-two/h-class-1-and-10-buildings/42-house-energy-rating-software)).

#### P3 — Thermal mass, including Perth double brick (WA)
- **Modelling evidence.** Gregory et al. (2008), *Energy and Buildings*, used AccuRate to examine thermal mass in cavity brick, brick veneer, reverse brick veneer and lightweight construction ([University of Newcastle repository](<https://ogma.newcastle.edu.au/vital/access/ /manager/Repository/uon:5457>)). Peer-reviewed. Its Perth-specific conclusions weren't in the extract.
- **Validation concern.**
  - The University of Tasmania (Dewsbury) found "discrepancies between the simulated and measured temperatures of the test buildings", and "the need for further investigation of the ground, subfloor, roof space and thermal mass algorithms" ([UTAS thesis](https://figshare.utas.edu.au/articles/thesis/The_empirical_validation_of_house_energy_rating_HER_software_for_lightweight_housing_in_cool_temperate_climates/23226212/1)). Thesis on lightweight test buildings; search extract.
  - The study was prompted by the timber industry. Forest and Wood Products Australia "wanted to know if AccuRate was predicting fairly how timber performed in houses, compared to other heavier materials" ([Homestyle Green podcast #200](https://homestylegreen.com/200-how-accurate-is-accurate/)). Media.
- **Heatwave risk for heavy construction.** "If there's no ventilation and no drop in temperature overnight, a double-brick house won't get the chance to cool down for days." Thermal mass "can work well in locations with fluctuating day and night temperatures like Perth". Source: [Particle (Scitech), on Perth double brick](https://particle.scitech.org.au/earth/could-climate-change-diminish-perths-desire-for-double-brick-homes). Science media quoting an academic. Search extract.
- **Industry counter-evidence: NatHERS does credit masonry.** Insulated cavity brick reached 8.1 stars, and insulated brick veneer 7.1 stars, in YourHome's findings ([Think Brick factsheet via Midland Brick](https://www.midlandbrick.com.au/wp-content/uploads/2025/10/TBA-7-Star-Brick-Homes-Study-Factsheet.pdf)). Industry body.
  - YourHome's Perth design notes that covering the slab with finishes such as carpet "reduces the effectiveness of the thermal mass" ([YourHome Acacia, Perth](https://www.yourhome.gov.au/sites/default/files/2021-08/Design%20Options%20-%20Acacia%20Perth.pdf)). Government.

#### P4 — Slab-on-ground and the ground model
- **Validation.**
  - The Chenath ground model, tested against a slab-on-ground test house at the University of Newcastle, showed "reasonable correspondence between actual heat flux measurements and the predictions of the model".
  - A limitation: heat flux was generalised across the slab from a single sensor.
  - The model was consistent with the 3D software HEAT3.
  - Source: [NatHERS research report, Ground Heat Transfer](https://www.nathers.gov.au/sites/default/files/Research%2520Rep%2520-%2520Ground%2520Heat%2520Transfer.pdf). Government. Search extract.
- **Chen's BESTEST ground-model paper.**
  - "For uninsulated slab-on-ground buildings, the ground model performs satisfactorily considering the balance between calculation speed and accuracy". Further development is recommended.
  - "Differences in ground-coupled heat transfer around 50% or higher were reported among various simulation tools for uninsulated slabs."
  - Source: [Chen, AIVC paper (BESTEST ground model)](https://www.aivc.org/sites/default/files/p_986.pdf). CSIRO author, conference paper. Search extract.
- **Model change.** Chenath 3.21 "improved edge slab insulation and waffle pod modelling" ([NatHERS News, May 2019](https://nathers.gov.au/node/320)).

#### P5 — Infiltration is modelled, not measured
- **CSIRO's air-infiltration study (Ambrose and Maxwell, June 2024).**
  - Blower-door tests were run on 233 new homes in Melbourne, Sydney, Canberra, Brisbane and Adelaide, with a "50% improvement" over a 2015 CSIRO study.
  - "Actual air infiltration rates were comparable with the NatHERS assumptions."
  - Leaks came mostly from bathroom fans, sliding doors and door seals.
  - Some apartments were "extremely airtight", which can cause problems "if controlled ventilation is not included".
  - The report recommends displaying the modelled infiltration rate on certificates, and letting measured rates be specified voluntarily, linked to ATTMA blower-door certificates.
  - Sources: [NatHERS, Air Infiltration report page](https://nathers.gov.au/air-infiltration-report); [CSIRO PDF](https://ahd.csiro.au/wp-content/uploads/air-infiltration-of-new-dwellings-final-report.pdf). Government. Search extract.
- **Software change.** An air-tightness display developed by CSIRO has been added to the benchmark tool, AccuRate Home, in regulatory mode, and is expected in other tools' next versions ([NatHERS News](https://nathers.gov.au/node/596)). Attribution approximate.
- **H6V2.** H6V2(3) requires the same "air infiltration" in both models ([internal review](/home/user/test/H6V2_shading_independent_review.md)).

#### P6 — Shading, including neighbouring buildings and adjustable shading
- **What was found.**
  - The NatHERS Technical Note (Version 1, September 2022) is written for Chenath 3.22 ([NatHERS Technical Note](https://nathers.gov.au/sites/default/files/2024-07/NatHERS%20Tech%20Note%2020220901.pdf)). Its shading rules weren't in the extract.
  - Technical Note 1.1 (2013) sets out principles for ratings in "regulation mode" ([Technical Note 1.1](https://nathers.gov.au/sites/default/files/Technical%2520Note%25201.1.pdf)).
  - NSW certificates state that shading was "modelled in accordance with NatHERS principles" and record horizontal projections and vertical features ([example NSW certificate](https://www.planningportal.nsw.gov.au/sites/default/files/documents/2022/Beane%20St%20NatHERS%20Certificate%20-%20Gosford.PDF)).
- **Heat stress.** Researchers attribute heat-stress problems partly to a "lack of natural ventilation and shading" ([ArchitectureAU](https://architectureau.com/articles/energy-rating-schemes-sabotaging-heat-stress-resistance-of-australian-homes-study-finds)).
- **H6V2.** H6V2 doesn't list shading among the items that must be the same, so the reference's shading may differ from the proposed building's. How much freedom that gives is contested ([internal review](/home/user/test/H6V2_shading_independent_review.md)).

#### P7 — Roof colour (solar absorptance)
- **What it is.**
  - NatHERS "requires the roof SA to be entered directly or as a range representing dark, medium and light colours" ([Lysaght TB-39](https://cdn.dcs.lysaght.com/download/technical-bulletin-tb-39-thermal-performance-of-roofing-materials)). Manufacturer, 2023. Search extract.
  - In BASIX's comparable scheme, "medium" covers solar absorptance of 0.475–0.7, "light" is below 0.475 and "dark" is above 0.7 ([NSW Planning Portal](https://www.planningportal.nsw.gov.au/basix-thermal-comfort/design-principles/solar-absorptance)). Government (NSW).
- **Heat stress.** Heat-stress researchers recommend lighter, reflective roof colours ([ArchitectureAU](https://architectureau.com/articles/energy-rating-schemes-sabotaging-heat-stress-resistance-of-australian-homes-study-finds)).

#### P8 — Outdoor living areas: the NCC concession in climate zones 1–2 (relevant to northern WA, not Perth)
- **The NCC 2022 text.** The baseline is 7 stars. In climate zones 1–2 the requirement is 6.5 stars with a covered outdoor living area. It is "6 stars if the building has an outdoor living area … fully covered with an impervious roof having a Total R-Value greater than or equal to 1.5 (for downward heat flow); and has at least one permanently installed ceiling fan" ([NCC 2022 Volume Two](https://ncc.abcb.gov.au/editions/ncc-2022/adopted/volume-two/h-class-1-and-10-buildings/42-house-energy-rating-software)). Government. Search extract.
- **On the certificate.** Certificates note that minimum ratings in northern Australia "may also be affected by the presence or absence of an outdoor living area and/or an outdoor living area ceiling fan" ([example NatHERS certificate in a NSW development application](https://www.midwestern.nsw.gov.au/files/assets/public/v/1/das-on-exhibition/14-oct-december-24/da01062025/nathers-and-basix-da0106_2025.pdf)). Search extract; attribution to this certificate is approximate.

#### P9 — Thermal bridging in steel frames (NCC 2022)
- **What it is.** NatHERS's thermal bridging function applies only to repeating steel-framed elements; "ratings of timber framed dwellings will be unaffected".
  - "Thermal bridging calculations are based on a comparison to timber framing as a benchmark rather than the actual performance of steel frames."
  - If framing details aren't supplied, assessors must model the default steel framing in Table 7 of the Technical Note.
  - Thermal breaks must be at least R0.2, and R0.2 is modelled as the default if a break is required but not specified. An additional R0.16 air gap is entered.
  - The method follows NZS 4214:2006.
  - Sources: [NatHERS, Thermal Bridging (NCC 2022)](https://www.nathers.gov.au/node/515); [NatHERS Thermal Bridging Guidance Note (September 2023)](https://www.nathers.gov.au/sites/default/files/2023-09/NatHERS%20Thermal%20Bridging%20Guidance%20Note%2020230927.pdf); [CSIRO implementation report (2023)](https://www.nathers.gov.au/sites/default/files/2023-05/ThermalBridgingImplementation_20230403_V5_FINAL.pdf). Government. Search extract.
- **Size of the effect.** Floors with unmitigated steel thermal bridges had R-values of 64–81% of the equivalent timber-framed floor ([University of Wollongong thermal bridging modelling, Stage 1, for the ABCB](https://cpd.nccb.gov.au/sites/default/files/resources/2022/UoW%20Thermal%20bridging%20additional%20modelling%20-%20Stage%201%20Final%20Report.pdf)). University research report for the ABCB, 2022, from the draft-code stage. This is a floor R-value result, not a change in star rating.
- **Counter-evidence.** Assessors "can add thermal breaks and/or improve other elements of the home's design to compensate" ([NatHERS](https://www.nathers.gov.au/node/515)).

#### V1 — Engine validation, the counter-evidence to every P-issue
- **BESTEST (2004).** "In general, the AccuRate simulation engine agrees very well with the reference programs, and no major discrepancies were found." One "simple bug" was found and fixed. Source: [NatHERS, Validation of the AccuRate engine using BESTEST](https://www.nathers.gov.au/node/465) ([PDF](https://www.nathers.gov.au/sites/default/files/Validation%2520of%2520the%2520AccuRate%2520Simulation%2520Engine%2520Using%2520BESTEST_0.pdf)). Government (CSIRO). Search extract.
- **Measured data.**
  - Chenath against measured air temperatures: "hourly nRMSD and MBD of 10.8% and 1.5°C".
  - A 2012 ANZAScA paper found Chenath, run through AccuRate, "compare[s] favourably" with two other engines and with measured data.
  - Source: [University of Adelaide repository](https://digital.library.adelaide.edu.au/dspace/handle/2440/77158). Attribution between the two items approximate.
- **The predecessor engine performed poorly.** In a 1992 Cranfield test-room study of the older Cheetah engine, "less than half the predications … were within the estimated error bands". Chenath improved on Cheetah in later comparisons between programs. Sources: [NatHERS BESTEST validation page](https://www.nathers.gov.au/node/465) and/or the [University of Adelaide repository](https://digital.library.adelaide.edu.au/dspace/handle/2440/77158). Search extract; attribution uncertain.
- **Darwin field validation** was carried out by the University of Adelaide ([CSIRO Darwin Living Lab PDF](https://research.csiro.au/darwinlivinglab/wp-content/uploads/sites/278/2022/09/Darwin-field-validation-of-house-energy-rating-software.pdf)). Results not extracted.

### Inferences

| ID | Issue | Evidence strength | Does the same criticism apply to H6V2? (backfire) | Marketing | Suggested accurate wording |
|---|---|---|---|---|---|
| P1 | Natural ventilation and free-running performance | Moderate (peer-reviewed 2009; CSIRO's own review) | **High.** General ASHRAE 140 tools model ventilation with rules the modeller sets; H6V2(3)(m) only requires the *same* ventilation in both models | Avoid | — |
| P2 | Ceiling fans | Moderate | **Medium.** The fan and outdoor-living concession belongs to the NatHERS route; H6V2 fan modelling depends on the tool | Avoid in Perth; use with care in zones 1–2 | See P8 |
| P3 | Thermal mass and double brick (WA) | **Weak** for "NatHERS undervalues mass"; **moderate** for the algorithm questions and heatwave risk | **Medium to high.** Other engines are no better documented on mass, and H6V2 also uses annual loads | **Avoid** "NatHERS undervalues double brick". Use with care for the heatwave point | "Thermal mass helps most when a house can cool down at night; a star rating doesn't show how a house copes with a heatwave." |
| P4 | Slab and ground model | Moderate (reasonable validation, but a ~50% spread between tools for uninsulated slabs) | **High.** Ground models diverge more across ASHRAE 140 tools | Avoid | — |
| P5 | Infiltration modelled, not measured | **Strong** (CSIRO, 233 homes) | **High.** H6V2 uses the same infiltration in both models and is also design-stage | Avoid any "leakier than assumed" claim. Use the established "design, not build" line | (Already established) "A rating checks the design, not the build." |
| P6 | Shading and neighbouring buildings | Weak (gap) | **High.** H6V2's latitude on reference shading is contested | Avoid | — |
| P7 | Roof colour | Moderate | **High.** It is the same input under both pathways | Use with care (education) | "Roof colour is a modelled input. If it changes after approval, the home's performance changes too." |
| P8 | Outdoor-living concession (zones 1–2) | **Strong** (NCC text) | **Low.** It isn't in H6V2, and H6V2 compares cooling only in zone 1 | Use, for northern WA only | "In NCC climate zones 1 and 2, the NatHERS minimum can drop to 6.5 or 6 stars with a qualifying covered outdoor living area and ceiling fan." |
| P9 | Thermal bridging in steel frames | **Strong** (NatHERS documents; CSIRO 2021 already established; University of Wollongong) | **Medium.** The physics applies under any method, and the DTS reference also needs thermal breaks. If Thermarate models bridging less rigorously than NatHERS, critics will say H6V2 dodges it | Use with care. Never say NatHERS treats steel unfairly | "Since NCC 2022, NatHERS counts heat loss through steel frames, which can make 7 stars harder for steel-framed homes. H6V2 compares the design with a Code-compliant reference house instead." |
| V1 | Engine validation | Moderate to strong | H6V2 tools are validated with the same ASHRAE 140 (BESTEST) family of tests | **Avoid** "unvalidated" | "NatHERS's engine has been tested against international benchmarks; like any model, it estimates rather than measures." |

- **P9 and steel framing (relevant to the steel-framing partners).** NatHERS treats timber as the zero baseline and penalises steel relative to it, so a steel-framed design must compensate to reach 7 stars.
  - Under H6V2, the reference must comply with DTS Part 13.2, whose Total R-value and thermal-break rules also account for steel bridging ([internal review, H6V2(2)](/home/user/test/H6V2_shading_independent_review.md)).
  - Whether H6V2 *reduces* the steel disadvantage depends on how the reference's framing and R-values are set, and on whether bridging is modelled in both models. This needs checking against the H6V2(3) list and the Part 13.2 text before any claim is made.
- **P3 (WA).** The double-brick evidence cuts both ways. Mass is credited in ratings (an insulated cavity-brick house reached 8.1 stars in the industry's account of YourHome's work), but heatwave persistence is a risk. A claim that "NatHERS penalises double brick" has no support.
- **General pattern.** Physics critiques of Chenath mostly come from validation work showing *some* error. General-purpose tools have comparable or larger spreads (for example, about 50% between tools for uninsulated slabs). Using physics critiques in marketing invites the reply that H6V2 is less standardised.

### Gaps
- Chenath's exact window-opening, natural-ventilation and ceiling-fan algorithms, including trigger temperatures and openable-area defaults. Not found.
- NatHERS rules for modelling neighbouring buildings, alfresco areas under the main roof, and adjustable shading. The current Technical Note wasn't retrievable.
- The NatHERS default solar absorptance when the roof colour is unknown. Not confirmed; the BASIX ranges may not equal NatHERS's.
- Gregory et al. (2008) Perth results; no independent study comparing measured double-brick performance with NatHERS predictions in Perth was found.
- The size of the star-rating change in CSIRO's 2023 report, which compares the previous and current thermal-bridging methods. Not retrieved.
- Whether national H6V2 modelling must include thermal bridging explicitly. The H6V2(4) list wasn't retrieved in full.

---

## Q5. What does the rating leave out?

### Takeaway
A star rating covers only modelled annual heating and cooling need per m², under standard assumptions, at the design stage. It leaves out:
- appliances, hot water and solar (Whole of Home is separate);
- embodied energy and carbon;
- peak demand;
- free-running comfort, overheating and heat stress;
- condensation and indoor air quality;
- total energy;
- the as-built house.

The evidence is strongest for heat stress and embodied energy (peer-reviewed). **Every one of these exclusions also applies to an H6V2 Performance Solution**, which addresses only heating and cooling loads (H6P1). They are safe only as neutral education, or as gaps Thermarate fills voluntarily.

### Cited Findings

#### X1 — Appliances, hot water, lighting and solar (Whole of Home is separate)
- The certificate's exclusion statement is already established.
- **H6V2.** It covers heating and cooling (H6P1). Whole of Home (H6P2) "is met separately", and "solar panels can't make up for the building fabric" ([internal strategy document](/home/user/test/Performance_Solutions_awareness_strategy.md)).

#### X2 — Embodied energy and carbon
- **Crawford, Bartak, Stephan and Jensen (2016).** *Renewable and Sustainable Energy Reviews*, peer-reviewed ([University of Melbourne listing](https://findanexpert.unimelb.edu.au/scholarlywork/1067383-evaluating-the-life-cycle-energy-benefits-of-energy-efficiency-regulations-for-buildings); [UCLouvain](https://research.dial.uclouvain.be/entities/publication/378dabc6-0edb-458b-9ddb-32b2382a5488)).
  - The study modelled case-study houses in Melbourne and Brisbane over 50 years.
  - The extra embodied energy in added insulation and better windows can cancel the operational savings.
  - Search extract: the point where extra insulation stops giving life-cycle energy benefits "sits just above Australia's current minimum efficiency requirements" (then 6 stars).
  - Search extract: "Embodied energy from these measures is currently not considered in most existing building energy regulations."
- **Authors' commentary.** "Pushing houses beyond the current minimum requirement does not produce significant energy savings and can even increase energy demand." Source: [The Fifth Estate, "Higher star ratings for housing don't necessarily save energy"](https://thefifthestate.com.au/columns/spinifex/higher-star-ratings-for-housing-dont-necessarily-save-energy/). Media by the authors.
- **Thesis.** Omrany's 2021 University of Adelaide thesis argues for including embodied energy in Australia's building energy codes ([University of Adelaide](https://digital.library.adelaide.edu.au/dspace/handle/2440/135107)). Abstract only.
- **House size and embodied energy.** See M2 (Stephan and Crawford, 2016).
- **Counter-evidence.** These are case studies of particular houses in two cities, and the authors don't argue for lower standards, but for broader (life-cycle) regulation.

#### X3 — Peak demand
- **What it is.** The rating models "how much heating or cooling a home's design would need over a year" ([Development Ready, a NatHERS explainer](https://www.developmentready.com.au/content-hub/article/nathers-star-ratings-guide-understanding-australias-house-energy-rating-scheme)). Industry. Search extract; attribution approximate.
- **Load limits.** Separate heating and cooling load limits apply in some locations under the NatHERS pathway ([ABCB Standard, NatHERS Heating and Cooling Load Limits 2022](https://www.nccb.gov.au/sites/default/files/resources/2022/nathers-heating-cooling-load-limits-2022.pdf)). They limit annual loads, not peak demand. In WA a variation removes them ([internal strategy document](/home/user/test/Performance_Solutions_awareness_strategy.md); see M4).
- **UNSW study (per the search extract; conference paper hosted by the Air Infiltration and Ventilation Centre).** "A higher star rating did not necessarily coincide with a decrease in cooling consumption, demand and overheating." Heatwaves "are also responsible for the annual peak electricity demand in cooling-focused regions." Source: [AIVC-hosted paper](https://www.aivc.org/sites/default/files/7_2.pdf). Conference paper. Search extract; authorship not confirmed.
- **Media.** Reliance on air conditioning is driving up power prices ([ESD News](https://esdnews.com.au/air-conditioning-reliance-driving-power-prices)).

#### X4 — Summer overheating, heat stress and free-running comfort
- **The UniSA heat-stress studies (Hatvani-Kovacs and colleagues).**
  - A 2016 Low Carbon Living CRC paper, "Overheating risk in the Australian Nationwide House Energy Rating Scheme" ([CRC PDF](https://www.lowcarbonlivingcrc.unsw.edu.au/sites/all/files/publications_file_attachments/hatvani-kovacs-2016-overheating_risk_in_the_australian_nationwide_house_energy_rating_scheme.pdf)).
  - A paper hosted in the ABCB resource library, "Does Australian nationwide house energy rating scheme ensure heat stress resistance" ([ABCB-hosted PDF](https://www.nccb.gov.au/sites/default/files/resources/2022/Does-australian-nationwide-house-energy-rating-scheme-ensure-heat-stress-resistance.pdf)).
  - A peer-reviewed article, "Heat stress-resistant building design in the Australian context", *Energy and Buildings*.
  - The work tested 6–8-star design scenarios, plus two traditional constructions, in AccuRate for a single-storey Adelaide house. It combined the Excess Heat Factor with the adaptive comfort model.
  - Search extracts: "High star rating does not necessarily indicate a building with high heat stress resistance"; "the integration of overheating risk into the rating scheme would be warranted".
  - The authors concluded, in paraphrase, that NatHERS does not directly encourage heat-stress resistance in new homes.
- **Media report of the findings.** Newer 6-star homes "used the same amount of energy to cool the interior as an older double brick home with just 2.6 stars". The lead author blamed "over-insulated buildings with very high air tightness with a lack of natural ventilation and shading" ([ArchitectureAU](https://architectureau.com/articles/energy-rating-schemes-sabotaging-heat-stress-resistance-of-australian-homes-study-finds)). Media. Search extract.
- **Counter-evidence (the same authors).** "Energy efficiency and heat stress resistance can be both achieved in the design process." Their recommended measures include orientation, light roofs, reflective foil, outdoor blinds and night ventilation ([ArchitectureAU](https://architectureau.com/articles/energy-rating-schemes-sabotaging-heat-stress-resistance-of-australian-homes-study-finds); [Low Carbon Living CRC paper (2016)](https://www.lowcarbonlivingcrc.unsw.edu.au/sites/all/files/publications_file_attachments/hatvani-kovacs-2016-overheating_risk_in_the_australian_nationwide_house_energy_rating_scheme.pdf)). Search extract.
- **Acknowledged by government.**
  - The NT Government says "current energy ratings assess energy use when air conditioners are in use". The new Darwin comfort ratings assess living rooms and bedrooms "when no air conditioning is used".
  - They are voluntary and run through a trial AccuRate build that "cannot be used for NatHERS energy star rating purposes".
  - Sources: [NT Government, Darwin Living Lab house comfort ratings](https://dipl.nt.gov.au/projects/darwin-living-lab-house-comfort-ratings); [CSIRO, comfort-rating rollout resources for assessors](https://research.csiro.au/darwinlivinglab/thermal-comfort-rating-rollout-resources-for-assessors). Government. Search extract.
- **Peer-reviewed.** See also Kordjamshidi and King (2009) under P1.

#### X5 — Condensation and indoor air quality
- **Indoor air.** CSIRO says overly airtight homes "without controlled ventilation, can lead to condensation and mould". It also links poor airflow to higher carbon dioxide and carbon monoxide.
  - It recommends airtightness standards in the NCC, mandatory controlled ventilation in apartments, compulsory air barriers, and airtightness values on NatHERS certificates.
  - Source: [CSIRO, "Testing the leakiness of Australian homes" (August 2024)](https://www.csiro.au/en/news/all/articles/2024/august/testing-leakiness-australian-homes). Government. Search extract.
- **Condensation is regulated separately.** NCC 2022 added "new verification methods for condensation management and building envelope sealing", with "quantified targets for allowable condensation risk", and roof-space ventilation in climate zones 6–8. Sources: [ABCB, "Improved condensation management in NCC 2022"](https://cpd.nccb.gov.au/news/2022/improved-condensation-management-ncc-2022); [ABCB Condensation in Buildings Handbook (2023)](https://www.nccb.gov.au/sites/default/files/resources/2023/Condensation-in-buildings-handbook.pdf). Government.

#### X6 — The rating checks the design, not the as-built house
- **What it is.** "NatHERS rates the plans; home energy disclosure will rate the house" ([The Good Builder](https://thegoodbuilder.com.au/nathers-rates-the-plans-home-energy-disclosure-will-rate-the-house/)). Industry media. The main point is already established.
- **The 2015 compliance-inspection pilot (New Home Energy Efficiency Compliance Inspections Project).**
  - Nine councils ran 86 inspections across 59 homes.
  - 30 of the 59 homes "could not be marked as compliant or non-compliant".
  - For glazing, 18 were compliant, 3 non-compliant and 26 inconclusive.
  - The authors warned that the sample was too small to generalise.
  - Sources: [The Fifth Estate](https://thefifthestate.com.au/?p=79646); ["As Built" house energy ratings (EIB)](https://eib.edu.au/?p=4660). Media and industry training body; the extract didn't separate the two sources. The jurisdiction wasn't confirmed.
- **Voluntary verification.** Sustainability Victoria offers "as built verification" tests, using thermal imaging and a "pressurised fan to test the air-tightness". They are free under its 7 Star Homes Program and otherwise cost $1,000–1,500 ([Sustainability Victoria](https://www.sustainability.vic.gov.au/news/media-releases/builders-of-new-7-star-homes-offered-free-thermal-efficiency-tests)). Government (Vic).

### Inferences

| ID | Exclusion | Evidence strength | Does the same criticism apply to H6V2? (backfire) | Marketing | Suggested accurate wording |
|---|---|---|---|---|---|
| X1 | Appliances, hot water, solar | Strong (already established) | **High.** H6V2 covers H6P1 only | Use, as neutral education about both routes | "A star rating, like an H6V2 assessment, covers heating and cooling need only. Appliances, hot water and solar are assessed separately (Whole of Home)." |
| X2 | Embodied energy and carbon | Strong to moderate (peer-reviewed case studies) | **High.** H6V2 also leaves it out | Use with care | "Neither a star rating nor an H6V2 assessment counts the energy or carbon used to make the building materials." |
| X3 | Peak demand | Moderate | **High.** H6V2 also compares annual loads | Use with care | "Star ratings estimate a year's heating and cooling, not how much power a house draws on the hottest afternoon." |
| X4 | Overheating, heat stress and free-running comfort | **Strong to moderate** (peer-reviewed, an ABCB-hosted paper, NT Government acknowledgement) | **High,** unless Thermarate adds a voluntary overheating check | Use with care | "A star rating estimates heating and cooling energy with air conditioning available; it doesn't show how hot the house gets without it." |
| X5 | Condensation and indoor air quality | Moderate | **High** | Use with care | "Energy ratings don't assess condensation or indoor air quality; the NCC deals with condensation separately." |
| X6 | Design-stage only | Strong | **High.** H6V2 is design-stage too | Use (already-established wording) | "A rating checks the design, not the build. If performance matters to you, test the finished house." |

- **These exclusions are useful to Thermarate only in two ways.** First, as neutral education ("what neither route measures"). Second, as a *value-add* Thermarate can provide inside a Performance Solution report, such as a free-running overheating check, a future-climate sensitivity run or a recommended blower-door test. They are not differentiators.
- **X4 is the most robust "what a star doesn't tell you" message.** It rests on peer-reviewed work and a government acknowledgement (NT/CSIRO). Wording must not imply that H6V2 measures overheating unless Thermarate actually reports it.

### Gaps
- No peer-reviewed Australian study was found that quantifies NatHERS star ratings against measured *peak* demand.
- The year and authors of the AIVC-hosted UNSW paper weren't confirmed.
- No NatHERS statement explicitly confirming that the rating excludes condensation or indoor air quality was found. The point is inferred from its heating-and-cooling scope.
- Which jurisdiction ran the 2015 inspection pilot wasn't confirmed.

---

## Q6. How do the accredited tools and Chenath versions differ? How are defaults and regulatory versus non-regulatory mode handled? Does the same house get different ratings?

### Takeaway
- **Engine and tools.** AccuRate (the benchmark), BERS Pro, FirstRate5 and HERO all run Chenath. Accreditation requires matching the benchmark within SAP accuracy limits; the values weren't retrieved. Regulators restrict which Chenath versions may be used for each NCC edition: 3.22 or 3.23 for NCC 2022, with 3.24 now in AccuRate Home.
- **Regulation mode** locks the standard settings, so users can't change thermostats or schedules. Research utilities (AccuBatch, a comfort-rating trial build) aren't accredited for ratings. Defaults fill missing inputs, for example default steel framing and an R0.2 thermal break.
- **Consistency evidence.** No published NatHERS study of different assessors or tools rating the same house was found. The evidence of inconsistency comes from a manufacturer (up to a whole star) and from a regulator acknowledging "concerns". All of it backfires on H6V2, which has *no* common engine, accredited operators or certificate audit system.

### Cited Findings

#### T1 — Different tools or assessors producing different ratings
- **Manufacturer claim.** "Lack of calibration between software employed by energy assessors is leading to inconsistent energy assessments", with "discrepancies of up to a whole star when modelling reflective versus bulk roof insulation". Source: [Architecture & Design, reporting Kingspan Insulation](https://architectureanddesign.com.au/news/industry-news/rating-tools-called-into-question). Media reporting a manufacturer. Date not shown. Search extract.
- **WA regulator.** The WA Building Commission is "aware of concerns about inconsistencies in star ratings from assessors", which it attributes partly to "a lack of clarity about the use of NatHERS accredited software for code compliance". Sources: [WA Government announcement](https://www.wa.gov.au/government/announcements/energy-efficiency-compliance-using-nathers-accredited-software); [Industry Bulletin 044](https://wa.gov.au/system/files/2024-10/ib_044_complianceusingnathers_0.pdf). Government. Original date not shown; re-hosted 2024. Search extract.
- **University of Tasmania.** Differences "may have a significant impact on the House Energy Star rating"; "continuous improvement and calibration of the AccuRate software is needed" ([UTAS conference paper](https://figshare.utas.edu.au/articles/conference_contribution/An_empirical_validation_of_the_AccuRate_software_envelope_model_in_an_Australian_cool-temperate_climate/23090960)). Embargoed conference paper. Search extract.
- **A US comparison, not NatHERS.** A blind study commissioned by the US Department of Energy found an "average rating variability observed for an individual home was approximately 13 points" ([SEEA white paper on HERS variability](https://www.seealliance.org/wp-content/uploads/HERS-variability-study-white-paper.pdf)). Not Australian; use only as an analogue.
- **Counter-evidence.** All four tools share Chenath, and the SAP sets "software accuracy requirements" against the AccuRate benchmark ([2019 SAP](https://www.nathers.gov.au/sites/default/files/2019-10/2019%20NatHERS%20Software%20Accreditation%20Protocol.pdf)).

#### T2 — Chenath version changes
- Older versions are restricted for NCC 2022 work ([VBA alert, 2023](https://www.vba.vic.gov.au/news/news/2023/industry-alert-use-of-older-nathers-software-versions); [SA DIT Advisory Notice 03/23](https://dit.sa.gov.au/__data/assets/pdf_file/0005/1281317/Advisory-Notice-03-23-Adoption-of-NatHERS-software-from-1-October-2023-for-NCC-2019-and-NCC-2022-Energy-Efficiency.pdf)).
- Each version changes the modelling: for example, 3.21's fixes to slab edges and waffle pods ([NatHERS News, May 2019](https://nathers.gov.au/node/320)), and the arrival of 3.24 ([NatHERS software updates](https://www.nathers.gov.au/node/295)).

#### T3 — Regulation mode versus other modes
- **Regulation mode.**
  - Tools are accredited "in regulation mode" for the DTS pathway, and "NatHERS does not accredit tools for use under other NCC compliance pathways" ([NatHERS](https://nathers.gov.au/node/125)).
  - Technical Note 1.1 sets out principles for ratings "in regulation mode" ([Technical Note 1.1](https://nathers.gov.au/sites/default/files/Technical%2520Note%25201.1.pdf)).
  - "Users are unable to change the relevant conditions in the NatHERS accredited tools" ([FR5, 2017](https://www.fr5.com.au/news/2017/07/25/csiro-advise-caution-nathers-tools-unsuitable-for-the-ncc-reference-building-verification-method-v2.6.2.2)).
- **Non-accredited utilities.**
  - AccuBatch, a separate CSIRO utility, can change heating and cooling hours and thermostat settings "to represent a more average condition", and can run in free-running mode. It is not an accredited rating mode ([ANSNAC appendices](https://www.nathers.gov.au/sites/default/files/Final%2520Appendices%2520ANSNAC.pdf)). Attribution approximate.
  - The comfort-rating trial build "cannot be used for NatHERS energy star rating purposes" ([CSIRO Darwin Living Lab](https://research.csiro.au/darwinlivinglab/thermal-comfort-rating-rollout-resources-for-assessors)).

#### T4 — Default values
- **Thermal bridging.** If no steel framing details are given, the default steel framing in Table 7 is modelled, and the R0.2 thermal break is the default when a break is required but not specified ([NatHERS Thermal Bridging](https://www.nathers.gov.au/node/515)).
- **Roof colour.** It is entered directly or by light, medium or dark category ([Lysaght TB-39](https://cdn.dcs.lysaght.com/download/technical-bulletin-tb-39-thermal-performance-of-roofing-materials)).

#### T5 — Assessor accreditation and audit transparency
- **Industry concerns (c. 2020).** Accredited assessors said unaccredited competitors, "not being subject to oversight, could provide substandard and even fraudulent assessments". At that time "only in NSW" was accreditation (by ABSA or BDAV) required to put an energy rating into a BASIX report. Source: [The Fifth Estate, "Industry frustration with NatHERS sees new body spawned"](https://thefifthestate.com.au/innovation/rating-tools/industry-frustration-with-nathers-sees-new-body-spawned/). Media; this is an industry view, not an audit finding, and may be out of date.
- **Audit transparency.** No published aggregate audit results for new-home ratings were found. NatHERS for Existing Homes has an assurance strategy with "independent desktop audits" ([NatHERS for Existing Homes Assurance Strategy (2025)](https://www.nathers.gov.au/sites/default/files/2025-07/NatHERS%20for%20Existing%20Homes%20Assurance%20Strategy.pdf); [Audit Policy](https://www.nathers.gov.au/node/633)). Government.

### Inferences

| ID | Issue | Evidence strength | Does the same criticism apply to H6V2? (backfire) | Marketing | Suggested accurate wording |
|---|---|---|---|---|---|
| T1 | Different tools or assessors, different ratings | **Weak to moderate** (a manufacturer claim, a regulator's "concerns", one validation study; no NatHERS inter-rater study) | **Very high.** H6V2 allows any ASHRAE 140 tool, has no benchmark engine or accredited-operator system, and leaves more to the modeller | **Avoid** | — |
| T2 | Chenath version changes | Moderate | **Medium.** General-purpose tools also change versions, with less control | Avoid | — |
| T3 | Regulation mode locks the inputs | Moderate | **High.** H6V2 fixes its own inputs | Avoid | — |
| T4 | Default values | Moderate | **High.** Under H6V2 the modeller has more discretion, which is a typical surveyor objection | Avoid | — |
| T5 | Assessor quality and audit transparency | Weak | **Very high,** given the 2017 misuse of the reference-building method (already established) | Avoid | — |

- Thermarate's best defence on consistency is process transparency rather than criticism of NatHERS: publish the modelling method and the weather file, run sensitivity checks, and agree assumptions with the surveyor in the design brief. The strategy document already recommends this.

### Gaps
- No published NatHERS study of different assessors or tools rating the same house was found.
- The SAP Appendix 2 tolerance values weren't retrieved.
- No aggregate audit or error-rate data for new-home NatHERS certificates was found.
- The current state-by-state rules on assessor accreditation weren't checked.
- No documentation was found of a named "non-regulatory mode" in the current tools, beyond AccuBatch and the comfort trial build.

---

## Q7. Which limitations do NatHERS, CSIRO or the ABCB acknowledge, and what reforms are planned?

### Takeaway
The scheme's own documents acknowledge several limitations:
- the per-m² size effect (hence the area correction factor);
- that ratings don't predict metered use;
- that thermostat, zoning and ceiling-fan assumptions needed review (2018);
- that bands above 6 stars became slightly less stringent in 2022;
- that thermal bridging is benchmarked against timber;
- that energy ratings don't assess comfort without air conditioning (NT/CSIRO);
- that over-tight homes risk condensation (CSIRO).

The reforms are incremental:
- Chenath point releases (3.24);
- a minimal NCC 2025 update;
- an airtightness display in AccuRate;
- voluntary future-climate files;
- a Darwin comfort-rating trial;
- the extension of NatHERS to existing homes.

**No evidence was found of a full Chenath rewrite, regulatory adoption of future-climate files, or a national as-built verification scheme.**

### Cited Findings

**Limitations acknowledged by the scheme's own bodies:**

| Limitation | Acknowledged by | Source |
|---|---|---|
| A per-m² metric disadvantages small homes, so the area correction factor is applied | NatHERS | [NatHERS, Area correction factor](https://nathers.gov.au/node/299) |
| Ratings measure "inherent thermal performance … all other things being equal", not metered use | CSIRO, in a Commonwealth submission (c. 2004–05) | [DEH submission to the Productivity Commission](https://www.pc.gov.au/inquiries/completed/energy-efficiency/submissions/department_of_the_environment_and_heritage/sub069.pdf) |
| Thermostat settings, trigger temperatures, zoning and the ceiling-fan model needed review; monitored data was insufficient; metrics for naturally ventilated buildings were suggested | CSIRO-led expert group (2018) | [CSIRO AHD](https://ahd.csiro.au/?p=677) |
| Bands above 6 stars ended "slightly lower than the current settings in performance terms" after the 2022 recalibration | NatHERS | [NatHERS 2022 Starbands](https://www.nathers.gov.au/node/517) |
| Thermal bridging is "based on a comparison to timber framing as a benchmark rather than the actual performance of steel frames" | NatHERS | [NatHERS, Thermal Bridging](https://www.nathers.gov.au/node/515) |
| "Current energy ratings assess energy use when air conditioners are in use" (not comfort without them) | NT Government and CSIRO | [NT Government, Darwin comfort ratings](https://dipl.nt.gov.au/projects/darwin-living-lab-house-comfort-ratings) |
| Very airtight homes without controlled ventilation risk condensation and mould; certificates should show infiltration | CSIRO (2024) | [CSIRO news](https://www.csiro.au/en/news/all/articles/2024/august/testing-leakiness-australian-homes); [NatHERS-hosted report](https://nathers.gov.au/air-infiltration-report) |
| NatHERS tools are unsuitable for the NCC reference-building Verification Method because their settings are fixed | CSIRO (2017) | [FR5 reposting CSIRO's alert](https://www.fr5.com.au/news/2017/07/25/csiro-advise-caution-nathers-tools-unsuitable-for-the-ncc-reference-building-verification-method-v2.6.2.2); [WA IB 89](https://wa.gov.au/system/files/2024-10/ib_89_0.pdf) |
| The climate zone map may differ from the software, and the software takes precedence | NatHERS | [NatHERS climate map](https://www.nathers.gov.au/themes/custom/govcms8_uikit_starter/climate-map/index.html) |
| Heat-stress critique hosted in the ABCB resource library (hosting is not endorsement) | ABCB (host) | [ABCB-hosted PDF](https://www.nccb.gov.au/sites/default/files/resources/2022/Does-australian-nationwide-house-energy-rating-scheme-ensure-heat-stress-resistance.pdf) |

**Reforms and their status:**
- **R1. Engine.** Development is incremental:
  - 3.21 in 2019, 3.22 and 3.23 for NCC 2022, and 3.24 in AccuRate Home ([NatHERS News, May 2019](https://nathers.gov.au/node/320); [VBA](https://www.vba.vic.gov.au/news/news/2023/industry-alert-use-of-older-nathers-software-versions); [NatHERS software updates](https://www.nathers.gov.au/node/295)).
  - The NCC 2025 protocol (dated 22 November 2024) still applies "only … to software tools using the Chenath Engine" ([SAP New Homes 2025](https://www.nathers.gov.au/sites/default/files/2025-11/SAP%20New%20Homes%202025%2020241122.pdf)).
  - No source describing a full Chenath rewrite was found.
- **R2. Future climate.** CSIRO's projected files are free and in NatHERS format, but voluntary ([CSIRO AHD](https://ahd.csiro.au/?p=1567)). Advocates are pressing for them ([Sweltering Cities report](https://energyconsumersaustralia.com.au/sites/default/files/2025-05/pg016_swelteringcities_projectreport_futurehomeclimateresilience.pdf)). No plan to adopt them was found.
- **R3. Airtightness and as-built checks.**
  - AccuRate Home's regulatory mode now displays airtightness, and other tools are expected to follow ([NatHERS News](https://nathers.gov.au/node/596)).
  - CSIRO recommends showing infiltration on certificates and allowing voluntary blower-door inputs ([NatHERS air infiltration report](https://nathers.gov.au/air-infiltration-report)).
  - Sustainability Victoria offers voluntary as-built verification ([Sustainability Victoria](https://www.sustainability.vic.gov.au/news/media-releases/builders-of-new-7-star-homes-offered-free-thermal-efficiency-tests)).
  - An industry-proposed Building Verification Council has been reported, status unknown ([The Fifth Estate](https://thefifthestate.com.au/innovation/rating-tools/industry-frustration-with-nathers-sees-new-body-spawned/)).
  - Home energy disclosure at point of sale is moving measurement to sale time, starting in NSW ([The Good Builder](https://thegoodbuilder.com.au/nathers-rates-the-plans-home-energy-disclosure-will-rate-the-house/)).
  - No national as-built verification requirement was found.
- **R4. Comfort ratings.** The Darwin home comfort ratings are voluntary, run on a trial AccuRate build, and rate NatHERS climate zone 1 dwellings on a 0–10 comfort scale ([CSIRO Darwin Living Lab](https://research.csiro.au/darwinlivinglab/darwin-home-comfort-rating); [NT Government](https://dipl.nt.gov.au/projects/darwin-living-lab-house-comfort-ratings)).
- **R5. Existing homes.**
  - NatHERS for Existing Homes has its own assurance and audit framework ([Assurance Strategy, 2025](https://www.nathers.gov.au/sites/default/files/2025-07/NatHERS%20for%20Existing%20Homes%20Assurance%20Strategy.pdf)).
  - CSIRO is testing a method to extend ratings to existing homes ([CSIRO, February 2025](https://www.csiro.au/en/news/All/Articles/2025/February/Improving-home-energy-efficiency)).
  - A CSIRO and CoreLogic artificial-intelligence pilot, "RapidRate", estimates star ratings ([iTWire](https://itwire.com/science-news/energy/new-tech-to-drive-energy-%E2%80%98efficiency-gains%E2%80%99-in-australian-homes)).
- **R6. Regulatory freeze.** NCC 2025 keeps Part H6 and H6V2 substantively unchanged, and residential NCC changes are paused until mid-2029 ([internal strategy document](/home/user/test/Performance_Solutions_awareness_strategy.md); already established).

### Inferences
- **Quote NatHERS's own acknowledgements.** The safest critique lines come from the scheme itself, consistent with the strategy document's "use NatHERS's own words" approach. These include:
  - "assess energy use when air conditioners are in use" (NT and CSIRO);
  - "all other things being equal" (CSIRO);
  - the area correction factor rationale;
  - thermal bridging "based on a comparison to timber framing" (NatHERS).
- **Every reform so far also leaves H6V2's weaknesses in place.** No future-climate requirement, comfort metric or as-built check applies to H6V2 either. If any of these reforms arrives for NatHERS first (for example, airtightness on certificates), H6V2 could look *less* transparent by comparison. Thermarate could pre-empt that by offering an airtightness target and test.
- **Marketing.**
  - **Use with care.** "NatHERS itself says a star rating measures the building shell under standard conditions, not your bills or comfort without air conditioning."
  - **Avoid** implying reforms are "coming to fix NatHERS". The evidence shows only incremental change.

### Gaps
- No source was found on a planned full Chenath rewrite, a "next-generation engine", or its timing.
- No NatHERS or ABCB plan was found to adopt future-climate files, add an overheating or comfort metric nationally, or require as-built verification for new homes.
- The outcome of the 2018 expert-group review wasn't found.
- No new technical information was found on the July 2026 "Home Energy Rating" rebrand beyond what the strategy document already records.
