# Independent review: NCC 2022 H6V2, monthly shading factors for local shading excluded from the glazing calculation

**Sources.**
- **NCC text.** NCC 2022 Volume Two and the ABCB Housing Provisions were read from the requester's ABCB XML archives. That XML is the 2022 text with the ABCB's tracked edits toward NCC 2025. Tracked insertions were excluded, and only 2022 wording is quoted. H6V2, H6V1, H6P1, 13.3.2–13.3.4, the Notes to Figure 13.3.2b and the definition of *reference building* carry no tracked changes.
- **Handbook.** The ABCB *Housing energy efficiency* handbook (print version 1.1, September 2024) was read from the requester's PDF. Page numbers are the printed footers. The handbook says it "is not mandatory or regulatory in nature".
- **Status of NCC text.** Explanatory Information is non-mandatory (A1G4(1)(a)). A Note is mandatory (A1G4(3)(g)).
- **Volume One** clauses are used only for drafting comparison. They do not apply to Class 1 buildings.

**Characterisation.** As the requester specifies, the element is an operable or removable **shading device** of the dwelling, such as a louvred pergola, a retractable awning or a removable shade sail. It is not a roof or a separate structure. That holds whether the device is attached to the dwelling or stands beside it, consistent with the 13.3.4 Explanatory Information (section 2.3). The analysis is the same for each device type.

---

## 1. Short answer

### (a) May the reference building include this shading device at all?

**Yes, on the wording, and the ABCB guidance supports it.**
- Shading is not among the matters that H6V2(3) requires to be "the same" in both models.
- The handbook lists "degree of shading" among the "parameters that can be changed" between the models (p 103).
- The reference may therefore carry a shading device that differs from the proposed building, or that the proposed building does not have.
- On the premise, the reference's Part 13.3 glazing checks are met without this device, so the Part 13.3 limb of H6V2(2) is satisfied. 13.3.4 is not engaged by the device.

### (b) May the factor vary by month?

**Yes, on the wording.**
- Nothing in H6V2 addresses shading operation, months or seasons.
- On the requester's framing, the factor is the reference's "degree of shading", and twelve monthly factors are that degree in each month.
- H6V2(3) fixes neither the device nor any operating rule for it.
- For a device that is installed, extended or opened by season, a monthly factor is also a natural way to represent its operation.

### (c) The 1.0 / 0.2 example

- **Wording.** The example is permitted on the wording. It breaches no express term of H6V2 or Part 13.3. Neither the wording nor the ABCB guidance says whether there is any limit on how the monthly values may be selected. That is the only open question, and it is one of interpretation.
- **What it does.** In each month it puts the device in whichever of its two states gives the higher load for that month's dominant end use: opaque when heating dominates, largely open when cooling dominates. The months are classified from a run without the added shading, which I take to be the reference's own unshaded run.
- **Effect by climate zone.** These directions assume the software treats the plane only as an obstruction to solar radiation (section 4.4).
  - *Climate zone 1* (cooling test only): the example can only tighten the test.
  - *Climate zone 8* (heating test only): the example relaxes the test, but no more than a device held at 1.0 all year.
  - *Climate zones 2–7* (both tests): compared with a reference without the device, the example raises the heating limit and lowers the cooling limit.
- **Why zones 2–7 differ.** Any fixed degree of shading trades a higher reference heating load against a lower reference cooling load. The month-by-month assignment keeps almost all of the heating increase of a fully deployed device while avoiding most of its cooling reduction. No fixed degree of shading gives that combination. On the premise, no DTS check registers it.
- **My view.** I see no distinctive concern in zones 1 or 8. In zones 2–7 I regard this timetable as open to challenge as a reference assumption. It avoids the heating/cooling trade-off that limits any fixed setting, and the reference is "used to determine the maximum allowable heating load and cooling load". The ABCB states the intended outcome as "better than, or at least equivalent to, a DTS Solution". This is a reservation drawn from the definition and from non-mandatory guidance by analogy. It is not a prohibition, and no source resolves it.
- **Recommendation.** Because the point is untested and the input moves the benchmark materially, take two steps. First, record the timetable and how it was derived in the design brief's "technical basis for analysis" (A2G2(4)(a)). Second, obtain the appropriate authority's agreement before relying on it. If the authority considers the input falls outside H6V2, the analysis could not rely on H6V2. It would need another Assessment Method under A2G2(2), for example an Other Verification Method accepted by that authority (A2G2(2)(b)(ii)) or a Comparison with the Deemed-to-Satisfy Provisions (A2G2(2)(d)).

**Requirements and restrictions** are set out in section 6, separated into express wording, interpretation and recommendation.

---

## 2. Provisions (wording)

### 2.1 H6V2 and H6V1 (Volume Two)

- **H6V2(1)(a):** "compared to a reference building, using a calculation method other than house energy rating software, has—" followed by:
  - (i) climate zone 1: cooling load only;
  - (ii) climate zone 8: heating load only;
  - (iii) "in climate zones 2, 3, 4, 5, 6 and 7, a heating load and a cooling load equal to or less than that of the reference building".
- **H6V2(2):** "The reference building must comply with the Deemed-to-Satisfy Provisions in Parts 13.2, 13.3 and 13.5 of the ABCB Housing Provisions."
- **H6V2(3):** "The heating load and cooling load for the proposed building and the reference building must be determined using the same—" followed by items (a)–(t), including:
  - (a) "calculation method"
  - (f) "floor plan, including the location and size of glazing"
  - (m) "ventilation"
  - (n) "function and use of the building and spaces, including zoning and hours of occupation"
  - (o) "operating schedules for heating and cooling in Table H6V2a"
  - (p)–(t) thermostat settings, occupancy, internal heat gains and air infiltration

  No item names shading, shading devices or their operation. Tables H6V2a, H6V2c and H6V2d are 24-hour profiles with no monthly or seasonal variation.
- **H6V2(4):** "The calculation method used must comply with ANSI/ASHRAE Standard 140 and be capable of assessing the heating load and cooling load by modelling—", including "(b) glazing and shading".
- **H6V2(5):** "Climatic data employed in the calculation method must be based on hourly recorded values and be representative of a typical year for the proposed location."
- **H6V1(1):** "The Verification Methods in this Part only apply to—" "(a) a Class 1 building; and" "(b) an enclosed Class 10a building attached to a Class 1 building."

### 2.2 Definitions (Schedule 1)

- **Reference building** (Volume Two): "a hypothetical building that is used to determine the maximum allowable heating load and cooling load for the proposed building."
- **Heating load:** "The calculated amount of energy delivered to the heated spaces of the building annually by artificial means to maintain the desired temperatures in those spaces."
- **Cooling load** is defined in parallel. Both are annual totals.

### 2.3 Housing Provisions Part 13.3 (applied to the reference through H6V2(2))

- **13.3.2(3)(b)** (winter): "P/H must be determined in accordance with Figure 13.3.2b."
- **13.3.3(3)(b)** (summer): "P/H must be measured in accordance with Figure 13.3.2b."
- **13.3.4(1)** opens: "Where shading is required to comply with 13.3.2 or 13.3.3, it must—". It then provides:
  - (a) "be provided by an external permanent projection, such as a verandah, balcony, fixed canopy, eaves, shading hood or carport, which—"
  - (b) "be provided by an external shading device, such as a shutter, blind, vertical or horizontal building screen with blades, battens or slats, which— (i) is capable of restricting at least 80% of the summer solar radiation; and (ii) if adjustable, is readily operated either manually, mechanically or electronically by the building occupants."
- **Figure 13.3.2b, Note (a)** (mandatory): "An external shading device that complies with 13.3.4(b) is considered to achieve a P/H value of 2.00." Through 13.3.2(3)(b) and 13.3.3(3)(b), that value applies in both the winter and the summer check.
- **Exposure-factor tables.** In all 32 tables (13.3.2b–q winter, 13.3.3b–q summer), the exposure factor falls or stays the same as P/H rises. This reads two evident source typos, "0,43" and "023", as 0.43 and 0.23. For example, Table 13.3.2b (climate zone 2, north) gives E_W of 1.49 at P/H 0.00 and 0.12 at P/H 2.00.
  - Winter table Notes: "For P/H between those shown in this Table, either use the next highest P/H or interpolate."
  - Summer table Notes: "For P/H between those in this Table, either use the next lowest P/H or interpolate."
- **13.3.4 Explanatory Information** (non-mandatory):
  - "Shading devices can include fixed louvres, shading screens and other types of perforated or fixed angle slatted shades. However, such devices need to be designed for the climate and latitude to ensure that summer sun penetration is restricted, while winter sun access is achieved. Winter access refers to the availability of winter solar gains to offset conducted heat losses."
  - "The requirements of 13.3.2 and 13.3.3 consider solar heat gain to be either beneficial or detrimental to the energy efficiency of a building based on seasonal variation (winter/summer), climate zone, orientation and P/H."
  - "Shading devices can be either attached or located adjacent to the building. For example, a free-standing lattice screen may be considered to provide shading to glazing if it complies with 13.3.4(b)."

### 2.4 Governing Requirements

- **A2G2(2)** lists the Assessment Methods:
  - (a) Evidence of suitability;
  - (b) a Verification Method: "(i) The Verification Methods provided in the NCC." or "(ii) Other Verification Methods, accepted by the appropriate authority that show compliance with the relevant Performance Requirements.";
  - (c) Expert Judgement;
  - (d) "Comparison with the Deemed-to-Satisfy Provisions."
- **A2G2(4)(a):** "Prepare a performance-based design brief in consultation with relevant stakeholders."
- **A2G2(4)(d)(v):** the final report includes "details of conditions or limitations, if any exist, regarding the Performance Solution."
- **Performance-based design brief:** "The report that defines the scope of work for the performance-based analysis, the technical basis for analysis, and the criteria for acceptance of any relevant Performance Solution as agreed by stakeholders."

### 2.5 Volume One comparisons (not applicable to Class 1)

- **S45C3(1)(i)(ii)** (J1V5): the same "internal shading devices, including their colour and criteria for operation".
- **S34C3(5)(d)** (J1V3) is to similar effect.
- Where the NCC means to fix how shading devices operate in a reference comparison, it says so expressly, and here only for internal devices.

### 2.6 ABCB handbook v1.1 (non-mandatory)

- **pp 10 and 111:** "A key principle underpinning the NCC 2022 housing energy efficiency requirements is that all compliance options aim to offer an equivalent level of performance."
- **p 91:** the 2022 changes include "Inclusion of operating schedules for heating and cooling, thermostat settings, and maximum occupancy to provide more clarity for modelling." Shading is not mentioned.
- **p 92:** "The theoretical reference house characteristics are those of a house modelled using certain elemental DTS Provisions contained in the Housing Provisions."
- **p 93:** "Prior to NCC 2022, the VURB included a table with input values that had to be used in the model for the theoretical reference house. This is no longer the case."
- **p 94:** the matters that must be the same exist "to ensure that only the thermal performance of the building fabric for the reference and proposed house affects the simulated energy demand, rather than any differences in underlying simulation assumptions. Essentially, a fair and equal comparison of parameters between the 2 building models is required."
- **p 95:** "The calculation method is the energy rating software used to undertake the modelling runs."
- **p 103:** "parameters that can be changed include" "type of glazing - this includes the thermal performance of the glazing (Total System U-Value and Total System SHGC), ability to open, degree of shading, and the size and location of the glazing". The same tip lists glazing size and location, which H6V2(3)(f) fixes.
- **p 113:** "The intent of VURB is to provide a pathway that utilises the principle underpinning the Comparison with the DTS Provisions Assessment Method, in that the outcome must be better than, or at least equivalent to, a DTS Solution (see Chapter 4)."
  - The same page refers to "reasonable assumptions, parameters and exclusions". Those are the ones H6V2 itself specifies. I do not use that phrase as a test for inputs H6V2 leaves open.
- **p 114** (Chapter 7, other Performance Solutions): "This means both Performance Requirements contain measurable benchmarks that should be used in the acceptance criteria for a PBDB for housing energy efficiency."
- **p 131** (Appendix B): "Shading device: A device used to block direct rays from the sun, generally these devices are fixed or operable."
- Chapter 5 and Appendix D.7 do not address adjustable, operable or time-varying shading.

### 2.7 Other material

NatHERS guidance on modelling adjustable shading was not reviewed or relied on. It applies only to NatHERS ratings, and H6V2(1)(a) excludes house energy rating software.

---

## 3. What the wording decides and what it leaves open

**Decided by the wording**
1. The reference must comply with the DTS Provisions of Parts 13.2, 13.3 and 13.5 (H6V2(2)). On the premise, its glazing passes 13.3.2 and 13.3.3 without this device, and 13.3.4 is not engaged.
2. The items in H6V2(3)(a)–(t) must be the same in both models. Shading and its operation are not among them, so the reference's shading, including its monthly values, may differ from the proposed building's. The operating inputs in (m)–(t) are fixed. The prescribed values in (o)–(t) are 24-hour profiles and values with no monthly variation.
3. The calculation method must comply with ASHRAE 140, be capable of modelling glazing and shading, and use hourly typical-year climate data (H6V2(4), (5)).
4. The work is a Performance Solution, so the A2G2(4) steps apply. Under those steps the design brief's "technical basis for analysis" is agreed by stakeholders. A Verification Method other than those in the NCC needs the appropriate authority's acceptance (A2G2(2)(b)(ii)).

**Left open by the wording**
1. Whether there is any limit on how the reference device's monthly values may be selected.
2. Whether the reference's 13.3.2 winter check may disregard a device that the reference simulation extends over the glazing in winter. This is the narrow H6V2(2) issue, and here it is settled only by the premise.

---

## 4. Interpretation

### 4.1 Monthly variation as a technique

H6V2(4)(b) requires only that the method be *capable of* modelling "glazing and shading". Nothing requires shading to be static or to respond hour by hour. Operable and removable devices change state: louvres open and close, awnings extend and retract, and shade sails go up and come down. A fixed factor for each month is a coarse but legitimate way to represent that. I do not read H6V2 as prohibiting it.

### 4.2 Whether the reference may carry this shading device

H6V2(3) does not list shading among the matters that must be "the same". H6V2(4)(b) treats "glazing and shading" as something the method must be able to model, not something that must match. The handbook says expressly that "degree of shading" is among the "parameters that can be changed" (p 103), and defines a shading device as "fixed or operable" (p 131). The reference may therefore carry a shading device that differs from the proposed building, or that the proposed building lacks.

**One feature of this case.** A change to the reference's shading ordinarily flows through its own DTS glazing checks, because P/H enters 13.3.2 and 13.3.3. The DTS anchor in H6V2(2) then registers both the winter cost and the summer benefit. On the premise, this device is excluded from those checks, so the anchor registers neither, at any setting. That does not prevent inclusion. It is why section 6 recommends a robustness check (item 13).

### 4.3 Operation where the same device appears in both models

H6V2(3) does not list shading or its operation, and shading may differ between the models (section 4.2). A different timetable for the same physical device is a different degree of shading. H6V2 therefore does not require the reference to copy the proposed building's timetable.

Where the same physical device is in both models, I nonetheless recommend the same timetable in each. H6V2(3)(m)–(t) fix the other operating inputs, and the handbook explains the fixed items as avoiding "differences in underlying simulation assumptions" (p 94). A matched timetable keeps the comparison on fabric and glazing. This is a recommendation, not a requirement.

### 4.4 The 1.0 / 0.2 example

**Assumptions for the direction of effects.** The directions below assume the software treats the plane only as an obstruction to solar radiation. The factor describes the plane, not the share of radiation excluded at the window, so the size of each effect depends on geometry.

**Effect on the reference loads.** Both loads are annual totals, and H6V2's thermostats and schedules run in every month.

| Example compared with | Reference heating load | Reference cooling load |
|---|---|---|
| No device (as the DTS calculation treats it) | higher or equal | lower or equal |
| Device held at 1.0 all year | lower or equal (differs only in cooling-dominated months) | higher or equal |
| Device held at 0.2 all year | higher or equal (differs only in heating-dominated months) | lower or equal (normally slight) |
| Ordinary seasonal operation (open in heating-dominated months, deployed in cooling-dominated months) | normally higher | normally higher |

- **Rows 1–3** compare states that differ in one direction only, so these directions hold in every case.
- **Row 4** is the net of opposing monthly changes, so it gives the expected direction, not a certainty.

**How the timetable is assigned.** The example gives the opaque state to months that the unshaded run classes as heating-dominated, and the open state to cooling-dominated months. In each month it therefore uses whichever of the two states gives the higher load for that month's dominant end use. The direction comes from this assignment rule; the same classification with the opposite assignment would give ordinary seasonal operation. Taking the classification from the reference's own run ties the timetable to the benchmark.

**Effect by climate zone.**
- **Zone 1** (cooling only, H6V2(1)(a)(i)). Compared with no device, the reference cooling load falls, so the example only tightens the test.
- **Zone 8** (heating only, (1)(a)(ii)). The example relaxes the test. A device held at 1.0 all year relaxes it at least as much (row 2), so the example adds nothing distinctive here.
- **Zones 2–7** (both, (1)(a)(iii)). Any fixed setting trades a higher reference heating load for a lower reference cooling load. The example keeps almost all of the heating increase of a fully deployed device while avoiding most of the cooling reduction that the same device would cause if it stayed deployed. No fixed degree of shading gives that combination.

**DTS treatment, for context.** The DTS gives a qualifying device a single P/H of 2.00 in both the winter and the summer check (Figure 13.3.2b Note (a)). It treats such a device as shading the glazing in both seasons, and never gives a device different winter and summer states in either direction. The example's winter state matches that treatment; its summer state does not. The 13.3.4 Explanatory Information describes the opposite seasonal pattern: restrict summer sun, admit winter sun. That material is non-mandatory and framed around fixed devices, so I give it limited weight.

**Practical context: ordinary use of the device types mentioned.** This is not a requirement. It bears on how an appropriate authority may view the input.

| Device | Ordinary seasonal use | Example timetable |
|---|---|---|
| Removable shade sail | Installed for the warmer months, taken down for winter | Sail fully up in heating-dominated months, mostly open in cooling-dominated months |
| Retractable awning | Extended in sunny or warm periods, retracted for winter sun (and in high wind) | Extended in heating-dominated months, largely retracted in cooling-dominated months |
| Louvred pergola | Louvres closed for summer shade, opened for winter sun; often motorised, sometimes closing automatically on rain | Closed through heating-dominated months, largely open through cooling-dominated months |

Closing a louvred pergola for rain is plausible winter behaviour. A weather-driven rule would close it intermittently, however, not hold it opaque for whole heating-dominated months.

**Interaction with the premise** (noted, not re-argued).
- The exposure factors fall as P/H rises, so shading never helps in the winter check. 13.3.4 governs only reliance on shading, so it is not what keeps a winter-deployed device out of 13.3.2; that exclusion rests on the premise.
- Leaving the device out is favourable to the reference in the winter check and unfavourable in the summer check.
- The gap between a reference that passes 13.3.2 and the same reference simulated with an opaque winter shade comes from the winter-deployed state. It would be the same with the device held at 1.0 all year. The monthly variation adds withdrawal in cooling-dominated months. That avoids most of the lower reference cooling load, and so the tighter cooling limit, that holding the device at 1.0 would produce.

**My view on the example.**
- **Wording.** It is permitted.
- **Zones 1 and 8.** No distinctive concern remains.
- **Zones 2–7.** The assignment rule avoids the heating/cooling trade-off that limits any fixed degree of shading. On the premise, the reference's DTS glazing checks do not register this. The reference is "used to determine the maximum allowable" loads, and the ABCB states the intended outcome as "at least equivalent to, a DTS Solution" (p 113). A benchmark set this way can sit above what any fixed degree of shading would produce, in a way the DTS checks do not register.
- **Status of this reservation.** I regard that as a fair basis for an appropriate authority to question the input. It is a reservation, not a prohibition, and no source resolves it.

### 4.5 Cases

| Shading device present in | Position |
|---|---|
| Neither model | No issue. |
| Both models | Permitted. The timetable may differ, since it is part of the degree of shading (p 103). I recommend the same timetable in both (section 4.3). An opaque winter state also hides differences in SHGC between the reference and proposed glazing behind it. |
| Reference only | Permitted on the wording and the guidance (H6V2(3); handbook p 103). A fixed factor, or ordinary seasonal operation, raises no particular difficulty. The example timetable is permitted on the wording, but in climate zones 2–7 it is open to the reservation in section 4.4. |
| Proposed only | Permitted. It is a design feature of the proposed building, and its timetable should be documented. |

### 4.6 The strongest argument the other way, on the timetable

**The literal case.**
- H6V2(3) is a closed list. In 2022 it gained operating schedules for heating and cooling, thermostat settings and occupancy (handbook p 91), but none for shading, even though (4)(b) shows the drafters had shading in mind.
- Where the NCC means to fix how shading devices operate, it says so. Volume One fixes the "criteria for operation" of internal shading devices (S45C3(1)(i)(ii); S34C3(5)(d)). H6V2(3) has no such item.
- The handbook confirms that shading may differ between the models (p 103) and that NCC 2022 removed the prescribed reference inputs (p 93). It defines a shading device as "fixed or operable" and gives it no seasonal function (p 131).
- The factor is the degree of shading. Twelve monthly factors are that degree in each month, and nothing in H6V2 limits how they are chosen.
- The mandatory DTS treats a qualifying adjustable device as P/H 2.00 in the winter check as well as the summer check (Figure 13.3.2b Note (a); 13.3.2(3)(b)), so a winter-deployed state is not foreign to the DTS.
- The Part 13.3 limb of H6V2(2) is met on the premise.
- Explanatory Information and statements of purpose cannot add words the drafters left out.

**My assessment.**
- **Inclusion and monthly variation.** I adopt this reasoning: both are permitted.
- **Why I keep a reservation for zones 2–7.** The ABCB describes the intended outcome as "better than, or at least equivalent to, a DTS Solution" (p 113). On the premise, the device is outside the reference's DTS checks at any setting. That is equally true of a fixed factor. What the timetable adds is that it avoids the trade-off that limits any fixed setting. The reference's loads can therefore move further from the DTS level than any fixed setting would allow, without the DTS checks registering it.
- **How far it goes.** I accept that this is a reservation drawn from purpose and context, not a reading of express words. It does not make the example impermissible.

---

## 5. Weight of the ABCB handbook

The handbook is non-mandatory and contains drafting errors:
- The p 103 tip lists glazing size and location as changeable, contrary to H6V2(3)(f).
- Appendix D.7 Step 2 says the *proposed* house must comply with H6V2(2).
- Table D.13 still carries the NCC 2019 label "V2.6.2.2(a)(i)".

Its statement that "degree of shading" can be changed is consistent with the wording of H6V2(3), and I rely on it. Its statements on a fair comparison and equivalent performance are evidence of the ABCB's intent. None of them decides how monthly values may be selected.

---

## 6. Requirements and restrictions on the monthly variation

**A. Express wording**
1. The reference must comply with the DTS Provisions of Parts 13.2, 13.3 and 13.5 (H6V2(2)). On the premise, the device is excluded from the glazing calculation, so it cannot contribute to that compliance.
2. The reference's shading, including its monthly values, may differ from the proposed building's. This follows from omission from the closed list in H6V2(3), and handbook p 103 confirms it.
3. The same calculation method must be used for both models. It must comply with ANSI/ASHRAE Standard 140, be capable of modelling glazing and shading, and use hourly typical-year climate data (H6V2(3)(a), (3)(b), (4)(b), (5)).
4. Two things stay fixed while the shading varies:
   - The inputs prescribed by H6V2(3)(o)–(t) are fixed 24-hour profiles and values with no monthly or seasonal variation, so they cannot be varied by month alongside the shading.
   - Items (3)(f), (m) and (n) must be the same in both models.
5. The A2G2(4) steps must be followed: a performance-based design brief, whose "technical basis for analysis" is agreed by stakeholders; analysis; evaluation against acceptance criteria; and a final report including "details of conditions or limitations". An analysis that departs from H6V2 is no longer the NCC Verification Method and needs another Assessment Method under A2G2(2). An Other Verification Method needs the appropriate authority's acceptance (A2G2(2)(b)(ii)).

**B. Interpretation (my reading of H6V2 in context)**

6. Where the same physical device is in both models, H6V2 does not require the same timetable in each, because the timetable is part of the degree of shading. Matching them is recommended (section 4.3).
7. In climate zones 2–7, a timetable that switches the device month by month so as to avoid the heating/cooling trade-off of any fixed setting is open to challenge as a reference assumption (section 4.4). This is a reservation, not a prohibition.
8. A timetable that reverses the seasonal pattern described in the 13.3.4 Explanatory Information should be identified as such in the design brief.

**C. Recommendations**

9. Record the device, its geometry, the twelve monthly values, the basis on which they were chosen, and how the software applies them, in the design brief's technical basis for analysis.
10. If a lower-risk reference assumption is wanted, model the device at a fixed factor, or with ordinary seasonal operation for its type: deployed or installed in the cooling season, and open, retracted or removed in the heating season. Define the seasons as in item 11 (section 4.4).
11. Where seasons are used, define them from climate data or the device's specification, not from the reference's loads.
12. Report sensitivity cases. Where the device is also in the proposed design, apply each case to both models. Show whether the compliance result is the same in every case. If it is not, record the dependence as a condition or limitation under A2G2(4)(d)(v). The cases are:
    - device absent;
    - device held at 0.2;
    - device held at 1.0;
    - ordinary seasonal operation;
    - the proposed timetable.
13. Re-run 13.3.2 for the reference with the device counted in its winter-deployed position.
    - If the reference still passes, the H6V2(2) question disappears whatever the premise. The reference with the device held deployed is then DTS-compliant on any view, and the example differs from it only by opening the device in cooling-dominated months.
    - If it fails, state that the result depends on the premise.
14. Report the change the device causes in the reference heating and cooling loads, and say what the factor means (the opacity of the plane).
15. Include the Specification 44 load limits (H6P1) in the acceptance criteria, as handbook p 114 suggests. This gives a check that does not depend on the reference assumptions.
16. Obtain the appropriate authority's agreement before relying on the example timetable, or any other load-derived timetable.

---

## 7. Remaining uncertainty

- **The central question.** Whether the monthly values of a reference shading device are a matter for the assessor, subject only to H6V2(2), H6V2(3) and agreement in the design brief (the literal reading), or whether a timetable that avoids the heating/cooling trade-off of any fixed setting is open to challenge (my reservation, for climate zones 2–7 only). The text does not say.
- **H6V2(2) and the winter check.** Whether the reference's 13.3.2 check may disregard a device that its own simulation deploys in winter. This is settled here only by the premise. Recommendation 13 removes the question.
- **Acceptance.** How an appropriate authority will treat an untested reference input that meets every express term. This depends on state legislation and practice.
- **Size of the effect.** The directions are set out in section 4.4. The size depends on geometry, orientation, climate zone and how the software applies the factor.
- **Jurisdiction.** The XML records the following variations:
  - NSW deletes H6V2.
  - In Tasmania, Part H6 is replaced with BCA 2019 Amendment 1 Part 2.6.
  - The NT has its own H6V2.
  - Victoria replaces H6V1 with the same operative wording.

  Confirm the current position for the site.
