# Independent review: NCC 2022 H6V2, monthly shading factors for local shading excluded from the glazing calculation

**Sources.**
- **NCC text.** NCC 2022 Volume Two and the ABCB Housing Provisions were read from the requester's ABCB XML archives. That XML is the 2022 text with the ABCB's tracked edits toward NCC 2025; tracked insertions were excluded, and only 2022 wording is quoted. H6V2, H6V1, H6P1, 13.3.2–13.3.4, the Notes to Figure 13.3.2b and the definition of *reference building* carry no tracked changes.
- **Handbook.** The ABCB *Housing energy efficiency* handbook (print version 1.1, September 2024) was read from the requester's PDF. Page numbers are the printed footers. The handbook says it "is not mandatory or regulatory in nature".
- **Status of NCC text.** Explanatory Information is non-mandatory (A1G4(1)(a)); a Note is mandatory (A1G4(3)(g)).
- **Volume One** clauses are used only for drafting comparison. They do not apply to Class 1 buildings.

---

## 1. Short answer

### (a) May the reference building include this shading at all?

- **Wording.** No provision expressly allows or forbids it. Apart from the H6V2(3) items that must match the proposed building, H6V2(2) is the only express constraint on what the reference building contains. On the premise, the reference's Part 13.3 glazing checks are met without this shading, and 13.3.4 is not engaged by it.
- **Louvred roof.** H6V2(3)(c) requires the same "impact of adjoining structures and features" in both models. In my view the better reading is that this covers an open louvred-roof structure over an outdoor area, though it is finely balanced (section 4.2). If the louvred roof is instead part of the dwelling's roof, H6V2(3)(h) ("roof cladding") leads to the same result. On either reading the structure must appear in both models with the same geometry and the same twelve factors. A reference-only structure is then contrary to the words.
- **Awning fixed to the dwelling.** For this, the express provisions do not resolve the question.
- **My interpretation (any such device, including the awning).** Shading that no DTS calculation counts should be in the reference only if the same device is in the proposed design, and it should then be modelled identically in both. This is an inference from the definition of *reference building* and the structure of H6V2, not express wording.

### (b) May the factor vary by month?

- **Wording.** Nothing in H6V2 addresses shading operation, months or seasons. Monthly factors are not prohibited as a modelling technique.
- **My interpretation.** Monthly variation is acceptable if the timetable records a realistic, documented way of operating the device and is applied identically wherever the device appears in both models.

### (c) The 1.0 / 0.2 example

- **Wording.** The example breaches no express term of H6V2 or Part 13.3, except as set out under (a) for a louvred roof (H6V2(3)(c), or (3)(h) if it is part of the dwelling's roof). A literal reading permits it.
- **What it does.** It puts the device in whichever of its two states gives the higher load for the end use that dominates each month. The months are classified from a run without the added shading, which I take to be the reference's own unshaded run.
- **Effect against a reference without the device.** This assumes the software treats the plane only as an obstruction to solar radiation (section 4.4). The example:
  - raises the heating limit in climate zones 2–8;
  - lowers the cooling limit in climate zones 1–7;
  - in climate zone 1, can only tighten the single test that applies.
- **Effect against conventional operation.** It normally raises both limits.
- **My view, applied to the reference building alone.** I do not regard it as a sound basis for verifying H6P1. It is a choice that no DTS calculation bounds, yet it moves the limit that, by definition, the reference building is "used to determine". This is my interpretation of the definition and structure of H6V2, supported by non-mandatory ABCB guidance. It is not an express prohibition.
- **The same timetable applied identically in both models.** This satisfies (3)(c) where (3)(c) applies, and the wording is otherwise silent. On my interpretation it still lacks a proper basis: the months are assigned to states by load, not by how the device is operated, and the assignment reverses the usual seasonal logic of shading. A documented operating rule is needed. An opaque winter state can also hide differences in SHGC between the two models' glazing (section 4.5).
- **Recommendation.** Do not rely on the example unless the appropriate authority has expressly accepted it. If the authority considers the input falls outside H6V2, the analysis could not rely on H6V2. It would need another Assessment Method under A2G2(2), such as an Other Verification Method accepted by that authority (A2G2(2)(b)(ii)) or a Comparison with the Deemed-to-Satisfy Provisions (A2G2(2)(d)).

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
  - (h) "roof cladding and roof lights"
  - (m) "ventilation"
  - (n) "function and use of the building and spaces, including zoning and hours of occupation"
  - (o) "operating schedules for heating and cooling in Table H6V2a"
  - (p)–(t) thermostat settings, occupancy, internal heat gains and air infiltration.

  No item names shading, shading devices or their operation. Tables H6V2a, H6V2c and H6V2d are 24-hour profiles with no monthly or seasonal variation.
- **H6V2(4):** "The calculation method used must comply with ANSI/ASHRAE Standard 140 and be capable of assessing the heating load and cooling load by modelling—", including "(b) glazing and shading" and "(e) relevant built-environment and topographical features".
- **H6V2(5):** "Climatic data employed in the calculation method must be based on hourly recorded values and be representative of a typical year for the proposed location."
- **H6V1(1):** "The Verification Methods in this Part only apply to—" "(a) a Class 1 building; and" "(b) an enclosed Class 10a building attached to a Class 1 building." Its Explanatory Information reads: "The Verification Methods are not intended to apply to detached garages or to open carports."

### 2.2 Definitions (Schedule 1) and classification

- **Reference building** (Volume Two): "a hypothetical building that is used to determine the maximum allowable heating load and cooling load for the proposed building."
- **Heating load:** "The calculated amount of energy delivered to the heated spaces of the building annually by artificial means to maintain the desired temperatures in those spaces." Cooling load is defined in parallel, so both are annual totals.
- **Separating wall:** "A wall that is common to adjoining Class 1 buildings".
- **A6G11(2)(a):** "Class 10a is a non-habitable building including a private garage, carport, shed or the like."
- **A1 Explanatory Information:** "Where a word is not defined in the NCC, the relevant common meaning of the word should be used."

### 2.3 Housing Provisions Part 13.3 (applied to the reference through H6V2(2))

- **13.3.2(3)(b)** (winter): "P/H must be determined in accordance with Figure 13.3.2b."
- **13.3.3(3)(b)** (summer): "P/H must be measured in accordance with Figure 13.3.2b."
- **13.3.4(1)** opens: "Where shading is required to comply with 13.3.2 or 13.3.3, it must—". Item (a) reads: "be provided by an external permanent projection, such as a verandah, balcony, fixed canopy, eaves, shading hood or carport, which—". Item (b) reads: "be provided by an external shading device, such as a shutter, blind, vertical or horizontal building screen with blades, battens or slats, which— (i) is capable of restricting at least 80% of the summer solar radiation; and (ii) if adjustable, is readily operated either manually, mechanically or electronically by the building occupants."
- **Figure 13.3.2b, Note (a)** (mandatory): "An external shading device that complies with 13.3.4(b) is considered to achieve a P/H value of 2.00."
- **Exposure-factor tables.** In all 32 tables (13.3.2b–q winter, 13.3.3b–q summer), the exposure factor falls or stays the same as P/H rises. This reads two evident source typos, "0,43" and "023", as 0.43 and 0.23. For example, Table 13.3.2b (climate zone 2, north) gives E_W of 1.49 at P/H 0.00 and 0.12 at P/H 2.00.
  - Winter table Notes: "For P/H between those shown in this Table, either use the next highest P/H or interpolate."
  - Summer table Notes: "For P/H between those in this Table, either use the next lowest P/H or interpolate."
- **13.3.4 Explanatory Information** (non-mandatory):
  - "Shading devices can include fixed louvres, shading screens and other types of perforated or fixed angle slatted shades. However, such devices need to be designed for the climate and latitude to ensure that summer sun penetration is restricted, while winter sun access is achieved. Winter access refers to the availability of winter solar gains to offset conducted heat losses."
  - "The requirements of 13.3.2 and 13.3.3 consider solar heat gain to be either beneficial or detrimental to the energy efficiency of a building based on seasonal variation (winter/summer), climate zone, orientation and P/H."
  - "Shading devices can be either attached or located adjacent to the building. For example, a free-standing lattice screen may be considered to provide shading to glazing if it complies with 13.3.4(b)."

### 2.4 Governing Requirements

- **A2G2(2)** lists the Assessment Methods: (a) Evidence of suitability; (b) a Verification Method, "(i) The Verification Methods provided in the NCC." or "(ii) Other Verification Methods, accepted by the appropriate authority that show compliance with the relevant Performance Requirements."; (c) Expert Judgement; (d) "Comparison with the Deemed-to-Satisfy Provisions."
- **A2G2(4)(a):** "Prepare a performance-based design brief in consultation with relevant stakeholders."
- **A2G2(4)(d)(v):** the final report must include "details of conditions or limitations, if any exist, regarding the Performance Solution."
- **Performance-based design brief:** "The report that defines the scope of work for the performance-based analysis, the technical basis for analysis, and the criteria for acceptance of any relevant Performance Solution as agreed by stakeholders."

### 2.5 Volume One comparisons (not applicable to Class 1)

- **S45C3(1)** (J1V5, Class 2 sole-occupancy units) requires the same:
  - "adjacent structures and features" ((1)(e)); and, separately,
  - "internal shading devices, including their colour and criteria for operation" ((1)(i)(ii)).
  
  S34C3(5)(d) (J1V3) has a similar provision for internal shading devices. Neither provision addresses the operation of external shading.
- **S37C7(1)(b)** (2022 lettering): the 0.35 shading multiplier applies to an external shading device that, among other conditions, "if adjustable, will operate automatically in response to the level of solar radiation."

### 2.6 ABCB handbook v1.1 (non-mandatory)

- **pp 10 and 111:** "A key principle underpinning the NCC 2022 housing energy efficiency requirements is that all compliance options aim to offer an equivalent level of performance." The handbook links this principle to Objective H6O1.
- **p 91:** the 2022 changes include "Inclusion of operating schedules for heating and cooling, thermostat settings, and maximum occupancy to provide more clarity for modelling." Shading is not mentioned.
- **p 92:** "The theoretical reference house characteristics are those of a house modelled using certain elemental DTS Provisions contained in the Housing Provisions."
- **p 93:** "Prior to NCC 2022, the VURB included a table with input values that had to be used in the model for the theoretical reference house. This is no longer the case."
- **p 94:** the same-parameter requirements exist "to ensure that only the thermal performance of the building fabric for the reference and proposed house affects the simulated energy demand, rather than any differences in underlying simulation assumptions. Essentially, a fair and equal comparison of parameters between the 2 building models is required."
- **p 95:** "The calculation method is the energy rating software used to undertake the modelling runs."
- **p 103:** "parameters that can be changed include" "type of glazing - this includes the thermal performance of the glazing (Total System U-Value and Total System SHGC), ability to open, degree of shading, and the size and location of the glazing". Its reference to glazing size and location conflicts with H6V2(3)(f).
- **p 113:** "The intent of VURB is to provide a pathway that utilises the principle underpinning the Comparison with the DTS Provisions Assessment Method, in that the outcome must be better than, or at least equivalent to, a DTS Solution (see Chapter 4)." … "VURB provides a set of reasonable assumptions, parameters and exclusions to help ensure a Performance Solution produced using this Verification Method provides the intended level of performance."
- **p 114:** "This means both Performance Requirements contain measurable benchmarks that should be used in the acceptance criteria for a PBDB for housing energy efficiency." This appears in Chapter 7, which deals with other Performance Solutions.
- **Appendix D.7**, Table D.12 (worked example): the reference window Total System U-Value is 6.0 and the proposed is 5.6. The example does not say how 6.0 was chosen. Under H6V2(2), it must be a DTS-compliant value chosen by the assessor.
- Chapter 5 and Appendix D.7 do not address adjustable, operable or time-varying shading.

### 2.7 Other material

I did not review NatHERS guidance on modelling adjustable shading and have not relied on it. NatHERS guidance applies only to NatHERS ratings, and H6V2(1)(a) excludes house energy rating software.

---

## 3. What the wording decides and what it leaves open

**Decided by the wording**
1. The reference must comply with the DTS Provisions of Parts 13.2, 13.3 and 13.5 (H6V2(2)). On the premise, its glazing passes 13.3.2 and 13.3.3 without this shading, and 13.3.4 is not engaged.
2. The matters listed in H6V2(3)(a)–(t) must be the same in both models. These include the impact of adjoining structures and features and the roof cladding. The operating inputs prescribed in (o)–(t) are fixed 24-hour profiles and values with no monthly variation.
3. The calculation method must comply with ASHRAE 140 and be capable of modelling glazing and shading, using hourly typical-year climate data (H6V2(4), (5)).
4. The work is a Performance Solution, so the A2G2(4) steps apply. A Verification Method other than those in the NCC needs the appropriate authority's acceptance (A2G2(2)(b)(ii)).

**Left open by the wording**
1. Whether the reference may carry shading that no DTS calculation counts and that the proposed building does not have.
2. Whether shading operation must be the same in both models, and how a timetable may be chosen.
3. Whether a given device falls within "adjoining structures and features" in H6V2(3)(c), a term that is not defined.
4. Whether the reference's 13.3.2 winter check may disregard a device that the reference simulation extends over the glazing in winter. This is the narrow issue under H6V2(2), and here it is settled only by the premise.

---

## 4. Interpretation

### 4.1 Monthly variation as a technique

H6V2(4)(b) requires only that the method be *capable of* modelling "glazing and shading". Nothing requires shading to be static or to respond hour by hour. Real adjustable devices do change position, so a fixed factor for each month is a coarse but legitimate way to represent operation. I do not read H6V2 as prohibiting it.

### 4.2 Whether the reference building may carry this shading at all

**Louvred roof: H6V2(3)(c) or (3)(h).**

Several points support treating an open louvred-roof structure over an outdoor area as an "adjoining" structure:
- H6V1(1) confines the method to the Class 1 building and an *enclosed* attached Class 10a building, and its Explanatory Information excludes "open carports".
- An open roofed structure of that kind is ordinarily Class 10a ("a private garage, carport, shed or the like"), outside the building whose loads H6V2 determines.
- The NCC uses "adjoining" for physical contiguity, as in "common to adjoining Class 1 buildings", and an undefined word takes its ordinary meaning.

Such a structure enters the model through its impact. H6V2(3)(c) requires that impact to be the same in both models, and (4)(e) requires the method to be capable of modelling "relevant built-environment and topographical features".

Against this reading, 13.3.4(1)(a), which is mandatory, lists a "verandah, balcony, fixed canopy, eaves, shading hood or carport" as an external permanent projection that shades the dwelling's glazing. The handbook repeats that list (p 61, Table 4.10). The 13.3.4 Explanatory Information says the same of attached or adjacent devices. The DTS therefore treats a roofed structure over an outdoor area, even a Class 10a carport, as the dwelling's own shading. That points to H6V2(4)(b) "glazing and shading" rather than (3)(c). The two categories are not mutually exclusive: an attached carport can be both a shading projection and an adjoining structure.

If the louvred roof is instead part of the Class 1 building's roof, (3)(h) requires the same "roof cladding". On balance I regard a reference-only louvred roof, or one given different factors in each model, as contrary to H6V2(3). That is my reading of express words, but it is finely balanced. Victoria's replacement H6V1 keeps the operative wording but omits the "open carports" Explanatory Information.

**Awning fixed to the dwelling.** An awning fixed to the dwelling is part of the Class 1 building and is "shading" within (4)(b). It is unlikely to fall within (3)(c) or (3)(h). For it, the text leaves the question open.

**The general position.**
- Apart from the H6V2(3) items, H6V2(2) is the only express constraint on what the reference contains. The handbook confirms that the pre-2022 table of prescribed reference inputs was removed (p 93).
- The assessor already chooses the reference's characteristics; Appendix D.7 uses a reference window U-Value of 6.0. Those choices are bounded by DTS calculations or minimums. Glazing and permanent projections enter 13.3.2 and 13.3.3, and insulation is set by Part 13.2. In the glazing calculations, a change that helps one check generally costs the other.
- Shading that, on the premise, no DTS calculation counts is not bounded at all. The decision whether to include it, and on what timetable, would let the assessor move the compliance limit without any DTS calculation registering it.

That sits poorly with:
- the definition, under which the reference is "used to determine the maximum allowable heating load and cooling load";
- the handbook's account of the method as "a fair and equal comparison" whose outcome "must be better than, or at least equivalent to, a DTS Solution";
- the handbook's "equivalent level of performance" principle.

The p 103 tip that "degree of shading" can be changed is the strongest guidance the other way. In context it lists design variables available for trade-offs. It does not license adding a feature that no DTS calculation counts to the reference alone. It is also loosely drafted, since it lists glazing size and location, which H6V2(3)(f) fixes.

My reading is therefore:
- where the device is part of the proposed design, model it in both buildings;
- where it is not, leave it out of the reference.

This is interpretation, not express wording.

### 4.3 Operation where the device appears in both models

H6V2(3)(n)–(t) standardise every occupant-behaviour and operating input the 2022 edition addresses, and the handbook gives the reason: to avoid "differences in underlying simulation assumptions" (p 94). A shading timetable is an assumption of that kind. If the same device appears in both models, it should have the same timetable in both; otherwise the comparison measures assumed behaviour, not design.

H6V2 does not say this expressly:
- The handbook reads (3)(a) "calculation method" as the software (p 95), so (3)(a) does not obviously carry modelling assumptions such as a shading timetable.
- Item (3)(n) is illustrated only by zoning and hours of occupation.
- Volume One states operating criteria expressly, but only for internal shading devices, and neither volume addresses the operation of external shading in a reference-building comparison. The omission from H6V2 can therefore be read either way.

Where (3)(c) applies, sameness is mandatory.

### 4.4 The 1.0 / 0.2 example

The statements about direction below assume the software treats the plane only as an obstruction to solar radiation. The factor describes the plane, not the share of radiation excluded at the window, so the size of each effect depends on geometry. Low winter sun may pass largely beneath a horizontal louvred roof.

**Effect on the reference loads.** Both loads are annual totals, and H6V2's thermostats and schedules run in every month.

| Compared with | Reference heating load | Reference cooling load |
|---|---|---|
| No device (as the DTS calculation treats it) | higher | lower |
| Device held at 1.0 all year | lower or equal (differs only in cooling-dominated months) | higher |
| Device held at 0.2 all year | higher (differs only in heating-dominated months) | slightly lower |
| Conventional operation (open in heating-dominated months, deployed in cooling-dominated months) | normally higher | normally higher |

The first three rows hold in every case, because each compares states that differ in one direction only. The last row is the net of opposing monthly changes, so it is the expected direction rather than a certainty.

The timetable assigns the opaque state to months that a run without the added shading (taken here to be the reference's own) classes as heating-dominated, and the open state to cooling-dominated months. In each month it therefore uses whichever of the two states gives the higher load for that month's dominant end use. Classifying months from the reference's own run ties the timetable to the benchmark. The direction, however, comes from the assignment rule: the same classification with the opposite assignment would give conventional operation.

**Effect by climate zone, compared with a reference without the device:**
- **Zone 1** (cooling only, H6V2(1)(a)(i)): the reference cooling load falls, so the example only tightens the test.
- **Zone 8** (heating only, (1)(a)(ii)): the heating limit rises, so the example only relaxes the test.
- **Zones 2–7** (both, (1)(a)(iii)): the heating limit rises and the cooling limit falls. The example helps a design that is limited by its heating load and can hurt one limited by its cooling load.

**Relation to the DTS treatment of shading.** The DTS has no concept of seasonal operation. There are two DTS-consistent ways to simulate this element:
- absent, as the DTS calculation treats it on the premise;
- deployed all year, as Figure 13.3.2b Note (a) treats a *qualifying* device (P/H 2.00 in both the winter and the summer check). Note (a) does not apply to this device on the premise, so this is an analogy only.

The example takes the deployed state in heating-dominated months, which gives a higher heating load than absent. In cooling-dominated months it is close to the absent state, which gives a higher cooling load than deployed. In each season it adopts whichever of the two gives the higher reference load. The 13.3.4 Explanatory Information describes the opposite seasonal logic, restricting summer sun and admitting winter sun. It is non-mandatory and framed around fixed devices, so I apply it only by analogy.

**Interaction with the premise** (noted, not re-argued):
- The exposure factors fall as P/H rises, so shading never helps in the winter check. 13.3.4 governs only reliance on shading to comply, so it is not what keeps a winter-deployed device out of 13.3.2. That exclusion rests on the premise.
- Leaving the device out is favourable to the reference in the winter check and unfavourable to it in the summer check.
- The gap between a reference that passes 13.3.2 and the same reference simulated with an opaque winter shade comes from the winter-deployed state. It would exist equally if the device were held at 1.0 all year. What the monthly variation adds is withdrawal in cooling-dominated months. That avoids most of the lower reference cooling load, and so the tighter cooling limit, that holding the device at 1.0 all year would produce.

**My view on the example.** Applied to the reference building alone, the example uses a feature that no DTS calculation counts. It assigns states in the direction that raises the reference load in each season, and its timetable is classified from the reference's own results. Its practical use is to relax the heating limit in climate zones 2–8, at some cost to the cooling limit in climate zones 2–7. The size of each effect depends on geometry. I do not regard it as a sound reference input. It is not contrary to any express term, unless the device falls within (3)(c) or (3)(h).

### 4.5 Cases

| Device present in | Position |
|---|---|
| Neither model | No issue. |
| Both models, same geometry and same twelve factors | Required if (3)(c) or (3)(h) applies, and acceptable in principle in any case. The timetable still matters: an opaque winter state hides differences in solar transmission (SHGC) between the reference and proposed glazing behind it, so it should reflect realistic operation. |
| Reference only | Louvred-roof structure: on balance contrary to H6V2(3)(c) or (3)(h). Awning fixed to the dwelling: not expressly prohibited; in my view not a sound reference input, especially with the example timetable. |
| Proposed only | Outside the question as framed. If (3)(c) or (3)(h) applies, this is equally contrary to the words. If the device is part of the dwelling, it is a design feature of the proposed building, and its timetable should meet the same standard of realistic, documented operation. |

**Plausibility of winter closure.** A louvred roof may well be closed in winter against rain or wind, and motorised roofs often close automatically on a rain sensor. That is a reason to model the real device's real control logic in both models, hourly where the tool allows. It is not a reason to put the device in the reference building alone.

### 4.6 The strongest argument the other way

**The literal case.**
- H6V2(3) is a closed list. In 2022 it gained operating schedules for heating and cooling, thermostat settings and occupancy (handbook p 91), but none for shading, although (4)(b) shows the drafters had shading in mind.
- The 2022 edition shows how a rule on operating criteria is written when intended: for internal shading devices, S45C3(1)(i)(ii), new for 2022.
- The handbook says the 2022 edition removed the prescribed reference inputs (p 93) and lists "degree of shading" as a parameter that "can be changed" (p 103).
- H6V2(2) is met on the premise, and 13.3.4 by its own terms does not reach shading that is not relied on.
- A real house with such a device, operated this way, would be DTS-compliant.
- Explanatory Information and statements of purpose cannot add words the drafters left out.

**My assessment.** That case is respectable, and it is why I do not describe the example as expressly prohibited. I do not adopt it, for three reasons:
1. It lets a feature that no DTS calculation bounds set the "maximum allowable" loads. That is a kind of reference choice the DTS anchor in H6V2(2) cannot discipline.
2. It conflicts with the comparative method and the equivalence principle in the ABCB's own guidance.
3. Volume One can be read as evidence of a consistent policy as readily as of a deliberate omission.

The DTS's built-in caution is a further pointer, though not a reason in its own right. The rounding in the table Notes always favours caution for the building being checked, and so does Note (a)'s deemed P/H 2.00 in the winter check. Cautious assumptions of this kind, applied to a benchmark, relax it. I accept that my position rests on purpose and context rather than on express words.

---

## 5. Weight of the ABCB handbook

The handbook is non-mandatory and has drafting errors:
- p 103 lists glazing size and location as changeable, contrary to H6V2(3)(f).
- Appendix D.7 Step 2 says the *proposed* house must comply with H6V2(2).
- Table D.13 still carries the NCC 2019 label "V2.6.2.2(a)(i)".

It is useful evidence of the ABCB's intent (a DTS-based reference, a fair comparison, equivalent performance). It does not decide this question.

---

## 6. Requirements and restrictions on the monthly variation

**A. Express wording (mandatory)**
1. The reference must comply with the DTS Provisions of Parts 13.2, 13.3 and 13.5 (H6V2(2)). On the premise, the shading is excluded from the glazing calculation and so cannot contribute to that compliance. 13.3.4(1) also confines reliance on shading to qualifying shading.
2. Where the element is within "adjoining structures and features", its impact must be the same in both models (H6V2(3)(c)). If a louvred roof is part of the Class 1 building's roof, the same "roof cladding" is required (H6V2(3)(h)). Whether either applies to a given device is a matter of interpretation (section 4.2).
3. The same calculation method must be used for both models. It must comply with ANSI/ASHRAE Standard 140, be capable of modelling glazing and shading, and use hourly typical-year climate data (H6V2(3)(a), (3)(b), (4)(b), (5)).
4. The inputs prescribed by H6V2(3)(o)–(t) are fixed 24-hour profiles and values with no monthly or seasonal variation, so they cannot be varied by month alongside the shading. Items (3)(f), (m) and (n) must be the same in both models.
5. The A2G2(4) steps must be followed:
   - a performance-based design brief;
   - analysis;
   - evaluation against acceptance criteria;
   - a final report including "details of conditions or limitations".

   An analysis that departs from H6V2 is no longer the NCC Verification Method and needs another Assessment Method under A2G2(2). An Other Verification Method needs the appropriate authority's acceptance (A2G2(2)(b)(ii)).

**B. Interpretation (my reading of H6V2 in context)**

6. Shading that no DTS calculation counts should be in the reference only if the same element is in the proposed design.
7. Where the element is in both models, it should carry the same twelve factors in each.
8. The timetable should record a realistic, documented operating rule for the device: its specified operation, its control logic, or a stated occupant rule. It should be fixed before the comparison, and its direction should not be chosen to raise the reference loads.
9. A timetable that reverses the usual seasonal logic of shading needs specific, evidenced justification. The example has none.
10. The assumption, and how it was derived, belong in the design brief's "technical basis for analysis" so that stakeholders can agree it.

**C. Recommendations**

11. If the device is not part of the proposed design, leave it out of the reference. If it is, model it identically in both buildings. This satisfies (3)(c) and (3)(h) whichever way those questions are resolved.
12. If seasonal variation is used, define the seasons from climate data or the device's specification, not from the reference's loads. Model the device's real control logic where the tool can represent it.
13. Report sensitivity cases:
    - element absent;
    - element held at 0.2;
    - element held at 1.0;
    - a documented operating rule;
    - the proposed timetable.

    Where the element is in the proposed design, apply each case to both models, and show that the compliance result is the same in every case. If it is not, rely on the documented-operating-rule case and record the dependence as a condition or limitation under A2G2(4)(d)(v). Do not mix cases: no single case gives both the lowest reference heating load (element absent) and the lowest reference cooling load (element held at 1.0).
14. Re-run 13.3.2 for the reference with the device counted in its winter-deployed position. If the reference still passes, the H6V2(2) question disappears whatever the premise. If it fails, state that the result depends on the premise.
15. Report:
    - what the factor means (opacity of the plane);
    - the separately modelled geometry;
    - the twelve values and how the software applies them;
    - the change each causes in the reference heating and cooling loads.
16. Include the Specification 44 load limits (H6P1) in the acceptance criteria, as handbook p 114 suggests. That gives a check that does not depend on the reference assumptions.
17. Obtain the appropriate authority's written agreement before relying on any reference-only or load-derived timetable.

---

## 7. Remaining uncertainty

- **The central question.** Whether the assessor may choose features of the hypothetical reference that H6V2(2) and (3) leave open, or whether those features should follow the proposed design. The text does not say, and my answer is an inference.
- **H6V2(3)(c) and (3)(h).** Whether a particular louvred roof or awning is within "adjoining structures and features", or forms part of the roof. My reading: on balance yes for an open, separately classified louvred-roof structure, though 13.3.4(1)(a) points the other way; probably not for an awning fixed to the dwelling. Where either provision applies, sameness is mandatory.
- **H6V2(2) and the winter check.** Whether the reference's 13.3.2 check may disregard a device that its own simulation deploys in winter. This is settled here only by the premise.
- **H6V2(3)(n).** Whether "function and use" extends to occupant operation of devices.
- **Acceptance.** How far an appropriate authority may refuse an analysis that meets every express term because of an operating assumption the clause does not mention. This depends on state legislation and practice.
- **Size of the effect.** Directions are stated in section 4.4. The size depends on geometry, orientation, climate zone and how the software applies the factor.
- **Jurisdiction.** The XML records the following:
  - NSW deletes H6V2.
  - In Tasmania, Part H6 is replaced with BCA 2019 Amendment 1 Part 2.6.
  - The NT has its own H6V2 with a similar same-impact item ((2)(c)).
  - Victoria replaces H6V1 with the same operative wording but without the "open carports" Explanatory Information.

  Confirm the current position for the site.
