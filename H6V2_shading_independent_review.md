# Independent review: NCC 2022 H6V2, monthly shading factors for local shading excluded from the glazing calculation

**Sources.**
- **NCC text.** NCC 2022 Volume Two and the ABCB Housing Provisions were read from the requester's ABCB XML archives. That XML is the 2022 text with the ABCB's tracked edits toward NCC 2025. Tracked insertions were excluded, and only 2022 wording is quoted. H6V2, H6V1, H6P1, 13.3.2–13.3.4, the Notes to Figure 13.3.2b and the definition of *reference building* carry no tracked changes.
- **Handbook.** The ABCB *Housing energy efficiency* handbook (print version 1.1, September 2024) was read from the requester's PDF. Page numbers are the printed footers. The handbook says it "is not mandatory or regulatory in nature".
- **Status of NCC text.** Explanatory Information is non-mandatory (A1G4(1)(a)); a Note is mandatory (A1G4(3)(g)).
- **Volume One** clauses are used only for drafting comparison. They do not apply to Class 1 buildings.

**Characterisation.** As the requester specifies, the element is treated as a **shading device** of the dwelling, not as a roof or a separate structure. Section 7 notes the one point that would change if a particular installation were classed otherwise.

---

## 1. Short answer

### (a) May the reference building include this shading device at all?

**Yes, on the wording, and the ABCB guidance supports it.**
- Shading is not among the matters that H6V2(3) requires to be "the same" in both models.
- The handbook lists "degree of shading" among the "parameters that can be changed" between the two models (p 103).
- The reference may therefore carry a shading device that differs from the proposed building, or that the proposed building does not have.
- On the premise, the reference's Part 13.3 glazing checks are met without this device, so H6V2(2) is satisfied, and 13.3.4 is not engaged by it.

### (b) May the factor vary by month?

- **Wording.** Nothing in H6V2 addresses shading operation, months or seasons. Monthly factors are not prohibited as a modelling technique.
- **My interpretation.** Monthly variation is acceptable if the timetable records a reasonable, documented way of operating the device, consistent with the function of a shading device.

### (c) The 1.0 / 0.2 example

- **Wording.** The example breaches no express term of H6V2 or Part 13.3. A literal reading permits it. The provisions do not resolve the question against it.
- **What the permission covers.** The permission to change the *degree of shading* settles that the reference may have this device. It does not address how the device's state is scheduled through the year, or how a schedule may be chosen. That narrower question is the one that remains open.
- **What the example does.** In each month it puts the device in whichever of its two states gives the higher load for the end use that dominates that month. It is deployed (opaque) when heating dominates and largely open when cooling dominates. The months are classified from a run without the added shading, which I take to be the reference's own unshaded run.
- **Effect against a reference without the device.** This assumes the software treats the plane only as an obstruction to solar radiation (section 4.4). The example:
  - raises the heating limit in climate zones 2–8;
  - lowers the cooling limit in climate zones 1–7;
  - in climate zone 1, can only tighten the single test that applies.
- **Effect against ordinary operation of a shading device** (open when heating dominates, deployed when cooling dominates). It normally raises both limits.
- **My view.** I do not regard this timetable as a sound reference assumption. Two features drive that view:
  - It runs a shading device in reverse of its function.
  - It is chosen month by month for its effect on the benchmark.

  The reference is hypothetical, so no real device's operation stands behind the timetable. On the premise, no DTS calculation registers its effect, yet it moves the limit that, by definition, the reference building is "used to determine". This is my interpretation of the definition and of H6V2's purpose, supported by non-mandatory ABCB guidance. It is not an express prohibition.
- **Recommendation.** Do not rely on the example unless the appropriate authority has expressly accepted it. If the authority considers the input falls outside H6V2, the analysis could not rely on H6V2. It would need another Assessment Method under A2G2(2), for example an Other Verification Method accepted by that authority (A2G2(2)(b)(ii)), or a Comparison with the Deemed-to-Satisfy Provisions (A2G2(2)(d)).

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
  - (c) "impact of adjoining structures and features"
  - (f) "floor plan, including the location and size of glazing"
  - (m) "ventilation"
  - (n) "function and use of the building and spaces, including zoning and hours of occupation"
  - (o) "operating schedules for heating and cooling in Table H6V2a"
  - (p)–(t): thermostat settings, occupancy, internal heat gains and air infiltration

  No item names shading, shading devices or their operation. Tables H6V2a, H6V2c and H6V2d are 24-hour profiles with no monthly or seasonal variation.
- **H6V2(4):** "The calculation method used must comply with ANSI/ASHRAE Standard 140 and be capable of assessing the heating load and cooling load by modelling—", including "(b) glazing and shading".
- **H6V2(5):** "Climatic data employed in the calculation method must be based on hourly recorded values and be representative of a typical year for the proposed location."
- **H6V1(1):** "The Verification Methods in this Part only apply to—" "(a) a Class 1 building; and" "(b) an enclosed Class 10a building attached to a Class 1 building."

### 2.2 Definitions (Schedule 1)

- **Reference building** (Volume Two): "a hypothetical building that is used to determine the maximum allowable heating load and cooling load for the proposed building."
- **Heating load:** "The calculated amount of energy delivered to the heated spaces of the building annually by artificial means to maintain the desired temperatures in those spaces." Cooling load is defined in parallel. Both are therefore annual totals.

### 2.3 Housing Provisions Part 13.3 (applied to the reference through H6V2(2))

- **13.3.2(3)(b)** (winter): "P/H must be determined in accordance with Figure 13.3.2b."
- **13.3.3(3)(b)** (summer): "P/H must be measured in accordance with Figure 13.3.2b."
- **13.3.4(1)** opens "Where shading is required to comply with 13.3.2 or 13.3.3, it must—" and continues:
  - (a): "be provided by an external permanent projection, such as a verandah, balcony, fixed canopy, eaves, shading hood or carport, which—"
  - (b): "be provided by an external shading device, such as a shutter, blind, vertical or horizontal building screen with blades, battens or slats, which— (i) is capable of restricting at least 80% of the summer solar radiation; and (ii) if adjustable, is readily operated either manually, mechanically or electronically by the building occupants."
- **Figure 13.3.2b, Note (a)** (mandatory): "An external shading device that complies with 13.3.4(b) is considered to achieve a P/H value of 2.00."
- **Exposure-factor tables.** In all 32 tables (13.3.2b–q winter, 13.3.3b–q summer), the exposure factor falls or stays the same as P/H rises. This reads two evident source typos, "0,43" and "023", as 0.43 and 0.23. For example, Table 13.3.2b (climate zone 2, north) gives E_W of 1.49 at P/H 0.00 and 0.12 at P/H 2.00.
  - Winter table Notes: "For P/H between those shown in this Table, either use the next highest P/H or interpolate."
  - Summer table Notes: "For P/H between those in this Table, either use the next lowest P/H or interpolate."
- **13.3.4 Explanatory Information** (non-mandatory):
  - "Shading devices can include fixed louvres, shading screens and other types of perforated or fixed angle slatted shades. However, such devices need to be designed for the climate and latitude to ensure that summer sun penetration is restricted, while winter sun access is achieved. Winter access refers to the availability of winter solar gains to offset conducted heat losses."
  - "The requirements of 13.3.2 and 13.3.3 consider solar heat gain to be either beneficial or detrimental to the energy efficiency of a building based on seasonal variation (winter/summer), climate zone, orientation and P/H."

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

- **S45C3(1)(i)(ii)** (J1V5): the same "internal shading devices, including their colour and criteria for operation". S34C3(5)(d) (J1V3) is to similar effect.
- Neither provision addresses the operation of external shading.

### 2.6 ABCB handbook v1.1 (non-mandatory)

- **pp 10 and 111:** "A key principle underpinning the NCC 2022 housing energy efficiency requirements is that all compliance options aim to offer an equivalent level of performance."
- **p 91:** the 2022 changes include "Inclusion of operating schedules for heating and cooling, thermostat settings, and maximum occupancy to provide more clarity for modelling." Shading is not mentioned.
- **p 92:** "The theoretical reference house characteristics are those of a house modelled using certain elemental DTS Provisions contained in the Housing Provisions."
- **p 93:** "Prior to NCC 2022, the VURB included a table with input values that had to be used in the model for the theoretical reference house. This is no longer the case."
- **p 94:** the matters that must be the same are fixed "to ensure that only the thermal performance of the building fabric for the reference and proposed house affects the simulated energy demand, rather than any differences in underlying simulation assumptions. Essentially, a fair and equal comparison of parameters between the 2 building models is required."
- **p 95:** "The calculation method is the energy rating software used to undertake the modelling runs."
- **p 103:** "parameters that can be changed include" "type of glazing - this includes the thermal performance of the glazing (Total System U-Value and Total System SHGC), ability to open, degree of shading, and the size and location of the glazing". The same tip lists glazing size and location, which H6V2(3)(f) fixes.
- **p 113:** "The intent of VURB is to provide a pathway that utilises the principle underpinning the Comparison with the DTS Provisions Assessment Method, in that the outcome must be better than, or at least equivalent to, a DTS Solution (see Chapter 4)." … "VURB provides a set of reasonable assumptions, parameters and exclusions to help ensure a Performance Solution produced using this Verification Method provides the intended level of performance."
- **p 114** (Chapter 7, other Performance Solutions): "This means both Performance Requirements contain measurable benchmarks that should be used in the acceptance criteria for a PBDB for housing energy efficiency."
- **Coverage:** Chapter 5 and Appendix D.7 do not address adjustable, operable or time-varying shading.

### 2.7 Other material

NatHERS guidance on modelling adjustable shading was not reviewed or relied on. It applies only to NatHERS ratings, and H6V2(1)(a) excludes house energy rating software.

---

## 3. What the wording decides and what it leaves open

**Decided by the wording**
1. The reference must comply with the DTS Provisions of Parts 13.2, 13.3 and 13.5 (H6V2(2)). On the premise, its glazing passes 13.3.2 and 13.3.3 without this device, and 13.3.4 is not engaged.
2. The items listed in H6V2(3)(a)–(t) must be the same in both models. Shading is not among them. The operating inputs prescribed in (o)–(t) are fixed 24-hour profiles and values with no monthly variation.
3. The calculation method must comply with ASHRAE 140, be capable of modelling glazing and shading, and use hourly typical-year climate data (H6V2(4), (5)).
4. The work is a Performance Solution, so the A2G2(4) steps apply. A Verification Method other than those in the NCC needs the appropriate authority's acceptance (A2G2(2)(b)(ii)).

**Left open by the wording**
1. How an operable shading device's state may be scheduled in the reference, and on what basis a timetable may be chosen.
2. Whether the same physical device, where it is in both models, must have the same timetable in each.
3. Whether the reference's 13.3.2 winter check may disregard a device that the reference simulation extends over the glazing in winter. This is the narrow H6V2(2) issue, and here it is settled only by the premise.

---

## 4. Interpretation

### 4.1 Monthly variation as a technique

H6V2(4)(b) requires only that the method be *capable of* modelling "glazing and shading". Nothing requires shading to be static or to respond hour by hour. Real adjustable devices change position, so a fixed factor for each month is a coarse but legitimate way to represent operation. I do not read H6V2 as prohibiting it.

### 4.2 Whether the reference may carry this shading device

Two things support inclusion:
- H6V2(3) does not list shading among the matters that must be "the same", and H6V2(4)(b) treats "glazing and shading" as something the method must be able to model, not something that must match.
- The handbook says so in terms: "degree of shading" is among the "parameters that can be changed" (p 103).

I therefore conclude that the reference may carry a shading device that differs from the proposed building, or that the proposed building lacks.

**One feature of this case.** Ordinarily, a change to the reference's shading flows through its own DTS glazing checks, because P/H enters both 13.3.2 and 13.3.3 (13.3.2(3)(b), 13.3.3(3)(b)). The DTS anchor in H6V2(2) therefore registers both the winter cost and the summer benefit. On the premise, this device is excluded from those checks, so the DTS anchor registers neither, and nothing in H6V2 bounds its effect on the reference loads. That does not prevent inclusion. It is why the device's assumed operation (section 4.4) carries more weight than usual, and why section 6 recommends a robustness check.

### 4.3 Operation where the same device appears in both models

H6V2(3)(n)–(t) standardise every occupant-behaviour and operating input the 2022 edition addresses, and the handbook explains this as avoiding "differences in underlying simulation assumptions" (p 94). Where the proposed building has the same physical device, giving it a different timetable in the reference is a difference in assumed operation rather than in design. I would model it with the same timetable in both.

H6V2 does not say this expressly. The handbook reads (3)(a) "calculation method" as the software (p 95), and (3)(n) is illustrated by zoning and hours of occupation. A different timetable could also be argued to be a different "degree of shading" (p 103). This point is interpretation only.

### 4.4 The 1.0 / 0.2 example

**Assumptions for the direction of effects.** The directions below assume the software treats the plane only as an obstruction to solar radiation. The factor describes the plane, not the share of radiation excluded at the window, so the size of each effect depends on geometry.

**Effect on the reference loads.** Both loads are annual totals, and H6V2's thermostats and schedules run in every month.

| Compared with | Reference heating load | Reference cooling load |
|---|---|---|
| No device (as the DTS calculation treats it) | higher | lower |
| Device held at 1.0 all year | lower or equal (differs only in cooling-dominated months) | higher |
| Device held at 0.2 all year | higher (differs only in heating-dominated months) | slightly lower |
| Ordinary operation (open in heating-dominated months, deployed in cooling-dominated months) | normally higher | normally higher |

The first three rows hold in every case, because each compares states that differ in one direction only. The last row is the net of opposing monthly changes, so it is the expected direction rather than a certainty.

**How the timetable is assigned.** The example assigns the opaque state to months that the unshaded run classes as heating-dominated, and the open state to cooling-dominated months. In each month it therefore uses whichever of the two states gives the higher load for that month's dominant end use. The direction comes from this assignment rule: the same classification with the opposite assignment would give ordinary operation. Taking the classification from the reference's own run ties the timetable to the benchmark.

**Effect by climate zone (compared with a reference without the device):**
- **Zone 1** (cooling only, H6V2(1)(a)(i)): the reference cooling load falls, so the example only tightens the test.
- **Zone 8** (heating only, (1)(a)(ii)): the heating limit rises, so the example only relaxes the test.
- **Zones 2–7** (both, (1)(a)(iii)): the heating limit rises and the cooling limit falls. The example helps a design limited by its heating load and can hurt one limited by its cooling load.

**Relation to the function of a shading device.** The DTS treats shading devices in two ways:
- **Qualifying devices.** An adjustable device relied on in the DTS must be "capable of restricting at least 80% of the summer solar radiation" (13.3.4(1)(b)(i)). It is then treated as P/H 2.00 in both checks (Figure 13.3.2b Note (a)). The DTS never models one as deployed in winter and open in summer.
- **Seasonal logic.** The 13.3.4 Explanatory Information states that summer sun should be restricted and winter sun admitted. It is non-mandatory and framed around fixed devices, so I apply it by analogy only.

The example runs the device the other way round: opaque when heating dominates, and largely open (a factor of 0.2) when cooling dominates.

**Interaction with the premise** (noted, not re-argued):
- The exposure factors fall as P/H rises, so shading never helps in the winter check. 13.3.4 governs only reliance on shading, so it is not what keeps a winter-deployed device out of 13.3.2. That exclusion rests on the premise.
- Leaving the device out is favourable to the reference in the winter check and unfavourable in the summer check.
- The gap between a reference that passes 13.3.2 and the same reference simulated with an opaque winter shade comes from the winter-deployed state. The monthly variation adds withdrawal in cooling-dominated months. That avoids most of the lower reference cooling load, and so most of the tighter cooling limit, that a device held at 1.0 all year would produce.

**My view on the example.** The permission to change the degree of shading answers whether the reference may have this device. It does not answer how the device's state may be scheduled. On that narrower question, the example's timetable has four features I consider difficult to accept:
- It runs a shading device in reverse of its function.
- It is chosen month by month for its effect on the benchmark.
- It belongs to a hypothetical building, so it cannot be justified by how a real device is or would be operated.
- On the premise, no DTS calculation registers its effect.

Its practical use is to relax the heating limit in climate zones 2–8, at some cost to the cooling limit in climate zones 2–7. In my view that is not one of the "reasonable assumptions" the handbook describes (p 113). It moves the "maximum allowable" loads (definition) in a way unrelated to a DTS-compliant building's performance. This is interpretation. No express term is breached.

### 4.5 Cases

| Shading device present in | Position |
|---|---|
| Neither model | No issue. |
| Both models | Permitted. On my interpretation, use the same timetable in both (section 4.3). An opaque winter state also hides differences in solar transmission (SHGC) between the reference and proposed glazing behind it, so the timetable should reflect realistic operation. |
| Reference only | Permitted on the wording and the guidance (H6V2(3); handbook p 103). The timetable is the open question: a fixed factor, or ordinary operation, raises no particular difficulty; the example timetable does (section 4.4). |
| Proposed only | Permitted. It is a design feature of the proposed building, and its timetable should be a realistic, documented operating rule. |

### 4.6 The strongest argument the other way, on the timetable

**The literal case.**
- H6V2(3) is a closed list. In 2022 it gained operating schedules for heating and cooling, thermostat settings and occupancy (handbook p 91), but none for shading, even though (4)(b) shows the drafters had shading in mind.
- The handbook confirms that shading may differ between the models (p 103), and that NCC 2022 removed the prescribed reference inputs (p 93).
- A shading timetable is simply the degree of shading in each month. If the degree may be changed, so may its timetable, and nothing in H6V2 says how it must be chosen.
- H6V2(2) is met on the premise.
- Explanatory Information and statements of purpose cannot add words the drafters left out.

**My assessment.** I adopt that reasoning for the inclusion question (section 4.2). For the timetable, it is respectable, and it is why I do not call the example expressly prohibited. I still do not adopt it there, for three reasons:
1. The reference exists to fix the "maximum allowable" loads. The ABCB describes the method as resting on "reasonable assumptions" and an outcome "at least equivalent to, a DTS Solution". A timetable chosen month by month to raise the benchmark sits poorly with both.
2. The timetable reverses the function that the DTS and its Explanatory Information attribute to shading devices. Nothing in the hypothetical reference can supply a reason for that reversal.
3. On the premise, the DTS anchor in H6V2(2) does not register the device's effect, so the timetable is the one input on which nothing else bears.

I accept that this rests on purpose and context rather than express words.

---

## 5. Weight of the ABCB handbook

The handbook is non-mandatory and contains some errors:
- The p 103 tip lists glazing size and location as changeable, contrary to H6V2(3)(f).
- Appendix D.7 Step 2 says the *proposed* house must comply with H6V2(2).
- Table D.13 still carries the NCC 2019 label "V2.6.2.2(a)(i)".

Its statement that "degree of shading" can be changed is nonetheless consistent with the wording of H6V2(3), and I rely on it for the inclusion question. Its passages on reasonable assumptions, a fair comparison and equivalence are evidence of the ABCB's intent. None of them decides the timetable question.

---

## 6. Requirements and restrictions on the monthly variation

**A. Express wording (mandatory)**
1. The reference must comply with the DTS Provisions of Parts 13.2, 13.3 and 13.5 (H6V2(2)). On the premise, the device is excluded from the glazing calculation and so cannot contribute to that compliance.
2. The same calculation method must be used for both models. It must comply with ANSI/ASHRAE Standard 140, be capable of modelling glazing and shading, and use hourly typical-year climate data (H6V2(3)(a), (3)(b), (4)(b), (5)).
3. The inputs prescribed by H6V2(3)(o)–(t) are fixed 24-hour profiles and values with no monthly or seasonal variation, so they cannot be varied by month alongside the shading. Items (3)(f), (m) and (n) must be the same in both models.
4. The A2G2(4) steps must be followed: a performance-based design brief, analysis, evaluation against acceptance criteria, and a final report including "details of conditions or limitations". An analysis that departs from H6V2 is no longer the NCC Verification Method and needs another Assessment Method under A2G2(2). An Other Verification Method needs the appropriate authority's acceptance (A2G2(2)(b)(ii)).

**B. Interpretation (my reading of H6V2 in context)**

5. The reference may carry a shading device that differs from, or is absent from, the proposed building. This is supported by H6V2(3) and handbook p 103.
6. Where the same physical device is in both models, it should have the same timetable in each.
7. The reference device's timetable should be a reasonable, documented operating assumption consistent with the function of a shading device. That means a fixed factor, ordinary operation, or the device's specified control rule. It should be fixed before the comparison, and its direction should not be chosen to raise the reference loads.
8. A timetable that reverses the ordinary function of a shading device needs specific, evidenced justification. The example has none, and a hypothetical reference cannot readily supply it.
9. The assumption, and how it was derived, belong in the design brief's "technical basis for analysis" so that stakeholders can agree it.

**C. Recommendations**

10. If the reference includes this device, model it at a fixed factor, or with ordinary operation (deployed in cooling-dominated months, open in heating-dominated months). Report its effect on both reference loads.
11. If seasonal variation is used, define the seasons from climate data or the device's specification, not from the reference's loads.
12. Report sensitivity cases. Where the device is also in the proposed design, apply each case to both models. Show that the compliance result is the same in every case. If it is not, rely on a case consistent with item 7 and record the dependence as a condition or limitation under A2G2(4)(d)(v). The cases are:
    - device absent;
    - device held at 0.2;
    - device held at 1.0;
    - ordinary operation;
    - the proposed timetable.
13. Re-run 13.3.2 for the reference with the device counted in its winter-deployed position. If the reference still passes, the H6V2(2) question disappears whatever the premise. If it fails, state that the result depends on the premise.
14. Report:
    - what the factor means (opacity of the plane);
    - the separately modelled geometry;
    - the twelve values and how the software applies them;
    - the change each causes in the reference heating and cooling loads.
15. Include the Specification 44 load limits (H6P1) in the acceptance criteria, as handbook p 114 suggests. This gives a check that does not depend on the reference assumptions.
16. Obtain the appropriate authority's written agreement before relying on a load-derived or reversed timetable.

---

## 7. Remaining uncertainty

- **The central question.** Whether the timetable of a reference shading device is a free choice for the assessor (the literal reading), or must be a reasonable assumption about how such a device operates (my reading). The text does not say.
- **Same device in both models.** Whether it must carry the same timetable in each. This is interpretation only.
- **H6V2(2) and the winter check.** Whether the reference's 13.3.2 check may disregard a device that its own simulation deploys in winter. This is settled here only by the premise.
- **Characterisation.** This review treats the element as a shading device of the dwelling, as the requester specifies. If an appropriate authority instead classed a particular installation as a separate structure, H6V2(3)(c) would require the same "impact of adjoining structures and features" in both models. A reference-only element would then not comply.
- **Acceptance.** How far an appropriate authority may refuse an analysis that meets every express term because of an operating assumption the clause does not mention. This depends on state legislation and practice.
- **Size of the effect.** The directions are set out in section 4.4. The size depends on geometry, orientation, climate zone and how the software applies the factor.
- **Jurisdiction.** The XML records the following variations:
  - NSW deletes H6V2.
  - In Tasmania, Part H6 is replaced with BCA 2019 Amendment 1 Part 2.6.
  - The NT has its own H6V2.
  - Victoria replaces H6V1 with the same operative wording.

  Confirm the current position for the site.
