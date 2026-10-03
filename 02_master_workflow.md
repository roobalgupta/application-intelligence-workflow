# Master UK Sponsorship Application Workflow

This file contains the core methodology of the UK Sponsorship Application Intelligence Workflow.

The workflow is designed for candidates applying for UK jobs who require Skilled Worker sponsorship now or in the future.

The professional context changes from candidate to candidate.

The methodology remains fixed.

Do not begin by rewriting the CV.

Sponsorship viability must be assessed before significant application tailoring begins.

## Required Inputs

Obtain:

1. Completed Candidate Setup
2. Master CV
3. Complete job description
4. Employer name
5. Original job posting link where available
6. Salary where stated
7. Location
8. Any sponsorship or right to work wording included in the vacancy

The AI should also have access to:

* `03_cv_tailoring_rules.md`
* `04_recruiter_reality_check.md`
* `05_gap_and_factuality_check.md`

If important information is unavailable, identify the uncertainty rather than assuming an answer.

## Source Hierarchy for Sponsorship Verification

Where current web access is available, prioritise:

1. Official UK government information
2. The official UK register of licensed worker sponsors
3. The employer's official careers website
4. The original job advertisement
5. Official employer recruitment or immigration information
6. Reliable secondary sources only where additional context is genuinely useful

Do not rely on outdated sponsor lists or search snippets when current official information can be checked.

If current web access is unavailable, state that sponsorship cannot be verified reliably and do not present an unverified result as confirmed.

# Stage 1: Sponsorship Verification

Complete this stage before detailed professional analysis or CV tailoring.

## 1. Employer Sponsor Licence Check

Verify whether the employer can be reliably identified on the current official UK register of licensed worker sponsors.

Check:

* Legal organisation name
* Trading name
* Parent organisation
* Subsidiary
* Relevant UK legal entity
* Location where useful for disambiguation
* Relevant worker route where available

Do not assume that the brand name displayed in a vacancy is necessarily the legal employing entity.

Classify the result as:

### Confirmed Licensed Sponsor

A sufficiently reliable current match has been identified.

### Possible Entity Match

A parent, subsidiary, trading name or related entity appears to match, but the relationship requires confirmation.

### Not Found on Current Register

No sufficiently reliable current match has been identified.

### Unable to Verify

Available information is insufficient.

Record:

Employer brand:

[RESULT]

Legal entity matched:

[RESULT]

Sponsor status:

[RESULT]

Source:

[SOURCE]

Date checked:

[DATE]

Confidence:

[High / Moderate / Low]

Notes:

[RESULT]

If the brand name is not found, investigate plausible legal entities before concluding that the employer is not licensed.

Do not treat an unverified related company as confirmed.

## 2. Vacancy Sponsorship Check

Review the specific job advertisement and official employer information.

Look for wording relating to:

* Skilled Worker sponsorship
* Visa sponsorship
* Sponsorship consideration
* Right to work requirements
* Existing UK work rights
* Unrestricted work rights
* Sponsorship exclusions
* Role eligibility for sponsorship

Classify the vacancy as:

### Confirmed Sponsorship Available

The employer explicitly indicates that sponsorship is available for this vacancy or relevant candidate group.

### Sponsorship Appears Possible

Credible evidence suggests sponsorship may be considered, but it is not guaranteed.

### Sponsorship Not Stated

The vacancy does not clearly address sponsorship.

### Sponsorship Appears Unlikely

The wording creates a meaningful concern without completely ruling sponsorship out.

### Explicitly No Sponsorship

The vacancy or official employer source clearly states that sponsorship is unavailable.

Record:

Vacancy sponsorship position:

[RESULT]

Source:

[SOURCE]

Date checked:

[DATE]

Confidence:

[High / Moderate / Low]

Relevant wording or summary:

[RESULT]

## 3. Skilled Worker Role Viability

Where sufficient information exists, assess whether the role appears broadly compatible with current Skilled Worker requirements.

Use current official UK government information.

Consider where relevant:

* Whether the role appears to correspond to an eligible occupation
* Occupation code where it can be identified reliably
* Salary stated
* Current applicable salary requirements
* Current going rate requirements
* Relevant current exceptions or concessions
* Candidate circumstances where they materially affect eligibility

Do not hardcode immigration thresholds into the workflow.

Do not guess an occupation code simply to make a role appear viable.

Classify the result as:

### Appears Eligible

Available information supports broad Skilled Worker viability.

### Likely Eligible but Requires Confirmation

The role appears viable but one or more details require confirmation.

### Unclear

Not enough reliable information exists.

### Appears Ineligible

Available information indicates a significant eligibility problem.

Record:

Role viability:

[RESULT]

Occupation or classification considered:

[RESULT OR UNKNOWN]

Salary assessment:

[RESULT]

Source:

[SOURCE]

Date checked:

[DATE]

Confidence:

[High / Moderate / Low]

Outstanding questions:

[RESULT]

# Stage 2: Sponsorship Gate

Return:

## Sponsorship Verification

Employer Sponsor Licence:

[RESULT]

Legal Entity Matched:

[RESULT]

Vacancy Sponsorship Position:

[RESULT]

Skilled Worker Role Viability:

[RESULT]

Overall Sponsorship Verdict:

[Proceed / Proceed with Caution / Stop]

Date Verified:

[DATE]

Sources Used:

[LIST]

Confidence:

[High / Moderate / Low]

Unresolved Questions:

[RESULT]

## Proceed

Proceed where:

* The employer is a confirmed licensed sponsor or another credible sponsorship route has been verified
* The vacancy does not rule sponsorship out
* No major Skilled Worker eligibility problem has been identified

## Proceed with Caution

Use this where:

* The employer is licensed but the vacancy is silent about sponsorship
* A legal entity match requires further confirmation
* Role eligibility requires additional verification
* Sponsorship appears possible but is not confirmed

Keep the uncertainty visible throughout the assessment.

## Stop

Stop before CV tailoring where:

* The vacancy explicitly states that sponsorship is unavailable
* The employer cannot reasonably be verified as a sponsorship target and no credible alternative evidence exists
* The role appears clearly incompatible with current Skilled Worker requirements
* The vacancy requires work authorisation that the candidate does not possess

Explain the reason clearly.

Do not continue to CV tailoring unless the candidate explicitly asks to continue despite the identified barrier.

# Stage 3: Role Screening

If the Sponsorship Gate allows the opportunity to continue, assess professional fit.

Evaluate:

* Alignment with target roles
* Professional background
* Seniority
* Required years of experience
* Essential requirements
* Preferred requirements
* Functional or technical capabilities
* Industry relevance
* Transferability of experience
* Location
* Salary
* Employment type
* Candidate non negotiables
* Practical hiring barriers

## Capability Fit

Score out of 10.

Assess how closely the candidate's verified professional experience matches the work required.

Consider:

* Relevant experience
* Functional or technical capability
* Evidence quality
* Seniority
* Transferable experience
* Required responsibilities
* Essential requirements

Do not artificially reduce Capability Fit because sponsorship is required.

## Realistic Shortlist Probability

Score out of 10.

This is a heuristic assessment score.

It is not a statistical prediction of receiving an interview.

Consider:

* Capability Fit
* Directness of experience
* Seniority
* Industry familiarity
* Essential requirements
* Candidate competition
* Location
* Salary alignment
* Sponsorship certainty
* Work authorisation timing
* Practical hiring barriers
* Major missing capabilities

Capability Fit and Realistic Shortlist Probability must remain separate.

# Stage 4: Application Decision

Return:

Capability Fit:

[X/10]

Realistic Shortlist Probability:

[X/10]

Application Decision:

[Proceed / Borderline / Skip]

Explain the reasoning.

Use the candidate's personal application rules.

If no personal threshold has been supplied, 7 out of 10 Capability Fit may be used as a general reference rather than an automatic rule.

If the role clearly violates a non negotiable requirement, recommend skipping.

If recommending Skip, stop before CV tailoring unless the candidate explicitly asks to continue.

# Stage 5: Employer and Role Research

Where current information is available, research:

* Organisation
* Products or services
* Customers or users
* Business model
* Industry
* Current strategic priorities
* Relevant growth or organisational changes
* Employer terminology
* Relevant team information
* UK operations
* Information directly relevant to the vacancy

Distinguish confirmed facts from interpretation.

Do not invent organisational strategy from generic industry assumptions.

# Stage 6: Job Description Analysis

Analyse the entire job description before changing the CV.

Automatically extract:

1. Job title
2. Primary purpose of the role
3. Five to eight highest priority requirements
4. Essential requirements
5. Preferred requirements
6. Required functional or technical capabilities
7. Repeated keywords and terminology
8. Seniority signals
9. Leadership expectations
10. Decision making expectations
11. Stakeholder expectations
12. Commercial or organisational expectations
13. Likely success measures
14. Required tools or platforms
15. Industry knowledge requirements
16. Any unusual or high risk requirements

Do not ask the candidate to manually identify these.

Do not treat every sentence in the job description as equally important.

Give greater weight to:

* Repeated requirements
* Essential requirements
* Prominently positioned responsibilities
* Capabilities directly connected to the purpose of the role
* Requirements linked to measurable organisational outcomes
* Requirements clearly signalling seniority

# Stage 7: Evidence Mapping

Before rewriting the CV, map the highest priority requirements against verified candidate evidence.

For each requirement identify:

* Requirement
* Candidate evidence
* Relevant employer, role or project
* Candidate's actual contribution
* Metric or concrete outcome where available
* Strength of match
* Limitation
* Missing evidence where relevant

Use:

### Strong

Direct and convincing evidence.

### Moderate

Relevant evidence exists but is not an exact match.

### Partial

Some transferable evidence exists but an important element is missing.

### Missing

No verified evidence currently supports the requirement.

Never invent evidence to convert Partial or Missing into Strong.

If potentially relevant experience may exist but has not been captured, ask the candidate a targeted question.

## Attribution Rules

Distinguish carefully between:

* Owned
* Led
* Managed
* Built
* Designed
* Delivered
* Implemented
* Contributed
* Supported

Also distinguish:

* Individual result
* Team result
* Department result
* Company result

Do not strengthen wording beyond what the candidate can defend.

# Stage 8: CV Tailoring

Only proceed after completing:

1. Sponsorship Verification
2. Sponsorship Gate
3. Role Screening
4. Job Description Analysis
5. Evidence Mapping

Apply the complete instructions in:

`03_cv_tailoring_rules.md`

The AI must have access to that file.

The tailored CV should prioritise verified evidence corresponding to the employer's highest priority requirements.

Do not simply copy language from the job description.

Use employer terminology only where it truthfully describes the candidate's experience.

Do not include detailed visa or sponsorship information on the CV unless there is a specific strategic reason.

# Stage 9: Recruiter Reality Check

After producing the tailored CV, apply the complete instructions in:

`04_recruiter_reality_check.md`

The AI must have access to that file.

Do not inflate the assessment because the CV has already been tailored.

# Stage 10: Gap Analysis and Factuality Review

Apply the complete instructions in:

`05_gap_and_factuality_check.md`

The AI must have access to that file.

Identify:

* Genuine experience weaknesses
* Presentation weaknesses
* Evidence requiring confirmation
* Unsupported claims
* Sponsorship uncertainty
* Remaining competitive risks

# Required Output Order

## If the Sponsorship Gate fails

Return:

1. Sponsorship Verification
2. Sources and date checked
3. Sponsorship Verdict
4. Reason to stop
5. Remaining uncertainty

Do not tailor the CV unless explicitly requested.

## If sponsorship can proceed but professional fit is weak

Return:

1. Sponsorship Verification
2. Capability Fit
3. Realistic Shortlist Probability
4. Skip or Borderline rationale
5. Main professional gaps

Do not tailor unless requested.

## If the role should proceed

Return:

1. Sponsorship Verification
2. Sources and date checked
3. Sponsorship Verdict
4. Capability Fit
5. Realistic Shortlist Probability
6. Short role assessment
7. Job Description Analysis
8. Evidence Mapping
9. Complete tailored CV
10. Recruiter Reality Check
11. Ten Second Recruiter Test
12. Competitor Reality Check
13. Gap Analysis
14. Sponsorship Recheck
15. Factuality Review
16. Final recommended improvements

# Immigration Information Limitation

This workflow provides application screening based on publicly available information.

It does not provide legal or immigration advice.

Where eligibility depends on individual circumstances, occupation coding, salary calculations or immigration rules that cannot be established confidently, report the issue as requiring confirmation rather than providing a definitive legal conclusion.

# Final Principle

The goal is not to maximise application volume.

The goal is to identify realistic sponsorship opportunities where genuine professional fit exists and then produce the strongest truthful application for those opportunities.
