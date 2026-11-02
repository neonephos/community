# NeoNephos Special Interest Groups

**Version:** 1.2  
**Status:** Draft  
**Maintained by:** NeoNephos Governing Board (GB)

---

A NeoNephos Special Interest Group (SIG) is a long-lived working group within the NeoNephos Foundation. Each SIG coordinates work in a specific domain within the remit of its parent committee (e.g. technical, community, or strategic). SIGs are the primary way NeoNephos organizes sustained collaboration across projects and member organizations. SIGs may also facilitate initiatives that span multiple projects or provide foundation-level services.

Each SIG is governed by its **terms of reference (ToR)**, a document or structured format that defines the SIG’s name, purpose, scope, deliverables and governance rules. The ToR is approved by the parent committee (as defined below) and reviewed annually. It may add to the rules of this framework, for example eligibility criteria for Maintainers or higher voting thresholds, but must not contradict them. In particular, it cannot change the parent committee’s oversight rights, the reporting obligations, the health criteria or the lifecycle rules.

## Definitions

- **Parent Committee:** the NeoNephos committee (TAC, OC or GB) that hosts a SIG.
- **Days**: calendar days.
- **Recorded activity:** merged pull requests, issues or discussions on GitHub, messages on the primary communication channel, or published meeting minutes
- **Regular meeting:** a scheduled recurring meeting of a committee, including strategy meetings, excluding ad-hoc meetings.
- **SIG registry:** the foundation-wide list of all SIGs (see SIG registry).
- **GitHub home:** : the repository, or the folder within a shared repository, where a SIG keeps its files (see Meetings and communication).

## Authority and conformance

Each SIG is hosted by the NeoNephos committee ("the parent committee") that best suits the SIG's scope.

- The NeoNephos Technical Advisory Council (TAC) creates all technical SIGs and governs them. 
- The NeoNephos Outreach Committee (OC) creates all community & outreach related SIGs and governs them.
- The NeoNephos Governing Board (GB) creates all strategic & member related SIGs and governs them.

A SIG's terms of reference take effect upon the parent committee's approval and remain subject to its oversight. The parent committee may dissolve a SIG by majority vote. The parent committee must give 30 days written notice through the SIG's primary communication channel. The dissolution takes effect at the end of the notice period.

## Creation

Anyone may propose a SIG to the parent committee by submitting a GitHub issue at [https://neonephos.org/community](https://neonephos.org/community), including name, scope, deliverables, initial Leads, and at least 3 interested Maintainers (the initial Leads included). The parent committee approves the SIG by majority vote.

## Choosing the parent committee

A SIG proposal is submitted to the committee whose remit best fits its scope. If a committee considers the proposal outside its remit, it forwards it to the appropriate committee. If the scope fits more than one committee, the committees concerned agree on the parent committee before voting; if they cannot agree, the GB decides.

If a committee rejects a SIG proposal on its merits, no other committee may approve the same or a substantially similar proposal within 6 months. The proposers may appeal the rejection to the GB, whose decision is final.

A SIG may transfer to another parent committee with the approval of both committees.

## Scope of autonomy

Within their chartered scope, SIGs make technical and process decisions independently. Any decision outside that scope requires approval from the NeoNephos Governing Board or the parent committee. SIGs must escalate decisions with cross-SIG impact, budget or staffing implications, or changes to Foundation-wide policy to the parent committee.

## Relationship to projects

SIGs operate at the NeoNephos Foundation level, not within individual projects. SIGs do not host NeoNephos projects directly; hosted projects govern themselves under their own terms of reference. A SIG may propose, sponsor, or advise projects within its domain. It may also support or lead cross-project initiatives.

## SIG registry

All SIGs are listed in the NeoNephos SIG registry ```sigs.yaml``` at [https://github.com/neonephos/metadata](). For each SIG, ```sigs.yaml``` contains its name, parent committee, lifecycle status and link to the project specific ```<sig-slug>.yaml```. The registry repository provides the authorative structure of ```<sig-slug>.yaml``` which alls SIGs must fill out and display in their main repository.

For each SIG, ```<sig-slug>.yaml``` lists its specifics such as Leads, Maintainers, SIG liaison, primary communication channel, and a link to the SIG's GitHub home. The registry and its templates are authoritative.
The GB ensures that the registry is maintained and accessible. Leads keep their SIG's entry up to date. The SIG liaison confirms changes to Leads and lifecycle status.

## Code of conduct

The NeoNephos Code of Conduct governs all SIG activity.

## Code of conduct

The [NeoNephos Code of Conduct](https://github.com/neonephos/.github/blob/main/CODE_OF_CONDUCT.md) governs all SIG activity.

## Roles and membership

| Role | Responsibilities | Eligibility |
| --- | --- | --- |
| **Contributor** | Submit PRs, participate in discussions; may comment on proposals, but do not vote and cannot block a proposal | Open to all |
| **Maintainer** | Review and approve contributions, vote on SIG decisions; may object to proposals under lazy consensus; elect Leads and may remove them | Nominated by a Lead; approved unless a Maintainer objects within 7 days; after an objection, Maintainers vote |
| **Lead (2)** | Facilitate meetings, represent SIG externally; decide day-to-day organisational matters; ensure that minutes are provided; submit status reports; keep the SIG's registry entry up to date; nominate Maintainers | Elected by Maintainers; see Leads below |
| **SIG liaison** | Link between SIG and parent committee; attends SIG meetings as non-voting observer (unless also a SIG member); primary escalation contact; may present the status report on behalf of the Leads; reminds the Leads when a report is due; confirms changes to Leads and lifecycle status in the SIG registry | Member of the parent committee, appointed by it; see SIG liaison below |

### Contributors

**Appointment**: Open to all; no appointment needed.
**Inactivity and removal**: As for Maintainers (see below).

### Maintainers

**Appointment**: A Lead nominates a Maintainer. The nomination is approved unless a Maintainer objects within 7 days. If a Maintainer objects, the Maintainers decide by vote.

**Inactivity**: Leads may move a Contributor or Maintainer inactive for 12 months to emeritus status by majority vote, after giving written notice.

**Removal**: Leads may remove a Contributor or Maintainer for violation of the NeoNephos Code of Conduct, following the Code of Conduct process. The affected person may appeal to the parent committee.

### Leads

**Appointment**: Leads must be Maintainers of the SIG. The parent committee appoints the initial Leads at founding, including their assignment with respect to the staggered terms (one for 3 months, one for 6 months). Thereafter, Leads are elected by majority vote of current Maintainers. Any Maintainer may self-nominate. Nomination and voting periods are each 1 week. Lead terms are 6 months, renewable.

**Vacancy and interim Leads**: If a seat becomes vacant, the remaining Lead may appoint an interim Lead. A formal election must follow within 90 days. If a SIG has no Lead, the parent committee appoints interim Leads on the recommendation of the SIG liaison, preferably from the SIG's remaining Maintainers; otherwise from other interested people, who become Maintainers on appointment. The interim Leads can then nominate new Maintainers as usual. The parent committee may also appoint interim Leads to a dormant SIG to prepare its reactivation; the formal election then follows within 90 days of reactivation.

**Removal**: The parent committee may remove a Lead at any time. Maintainers may also remove a Lead by a two-thirds majority of the votes cast. (section moved to Maintainers and Leads)

### SIG liaison

**Appointment**: The parent committee appoints one of its members as SIG liaison to each of its hosted SIGs and reappoints the liaison annually.
**Listing**: The current liaison for each SIG is listed in the SIG registry.
**Removal**: The parent committee may remove the liaison at any time. The SIG may request the removal of the liaison: the Leads, or a majority of the Maintainers, submit a reasoned request to the parent committee, which decides within 30 days or by its second regular meeting, whichever is earlier. The liaison may also step down at any time; the parent committee then appoints a successor within 30 days.

## Decision making

### How decisions are made

Lazy consensus is the default for all decisions.

- **Lazy consensus:** A proposal stands if no objection is raised within 7 days. Any Maintainer may raise an objection. Contributors may comment, but their comments do not block a proposal.
- **Async decisions:** SIG members may make decisions asynchronously via their primary communication channel using lazy consensus.
- **Contested decisions:**  If consensus cannot be reached, the Maintainers decide by majority vote. Leads may decide day-to-day organisational matters (e.g. agenda, minutes) on their own.
- **Escalation:** Unresolved disputes escalate to the parent committee via the SIG liaison. The parent committee must respond within 30 days or at its second regular meeting after the escalation, whichever is earlier.

### Voting rules

Votes by Maintainers, including Lead elections and removals, are valid if at least half of the Maintainers participate. A majority means a majority of the votes cast. Abstentions count toward the quorum but not toward the majority. A tie means the proposal is not adopted. If quorum is not reached, the vote is repeated once. If quorum is again not reached, the matter is escalated to the parent committee.

### Overview of decisions

The table summarises who decides what. The detailed rules are in the sections referenced.

| Decision | Who decides | Rule |
| --- | --- | --- |
| Everyday SIG decisions | Maintainers | Lazy consensus: stands unless a Maintainer objects within 7 days |
| Contested decisions | Maintainers | Majority of votes cast (quorum applies) |
| Day-to-day organisation (agenda, minutes) | Leads | Leads decide on their own |
| New Maintainer | Lead nominates, Maintainers | Approved unless a Maintainer objects within 7 days; after an objection, Maintainer vote |
| Lead election | Maintainers | Majority of votes cast (see Leads) |
| Lead removal | Maintainers, or parent committee | Two-thirds of votes cast; parent committee at any time |
| Interim Lead | Remaining Lead, or parent committee if no Lead remains | See Leads |
| Emeritus status | Leads | Majority, after 12 months of inactivity and written notice |
| Removal for Code of Conduct violation | Leads | Code of Conduct process; appeal to parent committee |
| Amendment of the SIG's ToR | Maintainers, then parent committee | Maintainer majority; parent committee approval |
| Removal of the SIG liaison | Parent committee | At any time; on reasoned request of the Leads or a Maintainer majority, decision within 30 days or by the 2nd regular meeting |
| Unresolved disputes | Parent committee | Within 30 days or by the 2nd regular meeting |
| Creation of a SIG | Parent committee | Majority vote (see Creation) |
| Change of parent committee | Both committees concerned | Approval of both (see Choosing the parent committee) |
| Dormant status | Parent committee | After 6 months at-risk; immediately with no Maintainers |
| Reactivation of a dormant SIG | Parent committee | Majority vote (see Lifecycle) |
| Dissolution | Parent committee | Majority vote; effective after 30 days notice |

## Meetings and communication

SIGs must conduct their primary communication in public. This allows anyone inside or outside the NeoNephos Foundation to follow the work and contribute. Each SIG must designate one channel as its primary communication channel and list it in the SIG registry.

* **Scheduling:** The SIG schedules meetings via Linux Foundation Events (LFX). The SIG sets the cadence.
* **Minutes:** Leads ensure that minutes of each meeting are publicly available. Minutes may take any form that records the main points and decisions, e.g. written notes, a summary, or a recording.
* **Recordings:** The SIG decides whether to record meetings. It also decides whether to upload recordings to the NeoNephos YouTube channel.
* **GitHub:** Each SIG has a repository at https://github.com/neonephos/sig-[slug]
* **Zulip:** Each SIG may have a channel at #sig-[slug] in the NeoNephos Zulip.
* **Mailing list:** Each SIG may have a mailing list at sig-[slug]@lists.neonephos.org.
* (moved to Decision making)

## Reporting

**Status report:** The SIG submits a status report to the parent committee  at intervals of 1 to 3 months. The SIG chooses its reporting interval within this range and states the planned date of its next report in each status report. The SIG liaison reminds the Leads when a report is due. The first report is due within 3 months of the parent committee's approval of the terms of reference. The SIG may present the report at a regular parent committee meeting or deliver it in written form. It must cover:

- Current Lead roster and SIG liaison
-	Active subprojects and their status
-	Key deliverables completed
-	Community health metrics: contributor count and meeting attendance
-	Blockers or unresolved escalations
-	Goals  until the next report

## Amendments

Anyone may propose amendments to the SIG's terms of reference; Maintainers approve them by majority vote. Leads must present proposed amendments at a regular parent committee meeting before they take effect. The parent committee votes on approval at that regular meeting or the next. The terms of reference are reviewed annually from the date of the parent committee's approval.

## Lifecycle and Health Criteria

| Phase | Trigger |
| --- | --- |
| Active | Terms of reference approved by the parent committee, or all at-risk conditions resolved, or a dormant SIG reactivated by the parent committee |
| At-risk | No meetings and no recorded activity for 3 consecutive months, no status report for 6 months, or fewer than 3 Maintainers (but at least one). The parent committee is notified in all cases. |
| Dormant | The parent committee may declare the SIG dormant after it has been at-risk for 6 months, or after an unresolved Lead vacancy of 6 months. A SIG with no Maintainers is declared dormant immediately, without the 6-month waiting period. |
| Reactivation | A dormant SIG is reactivated when at least 3 Maintainers submit updated terms of reference, including two Leads, and the parent committee approves them by majority vote. The SIG then returns to Active. |
| Dissolved | Parent committee majority vote; 30 days written notice on the SIG's primary communication channel. Takes effect at the end of the notice period. |

## Transition

SIGs existing at the time this document is approved must adopt terms of reference conforming to it within 6 months. Until then, their current rules continue to apply. For the transition:

-	Each existing SIG is entered in the SIG registry within 30 days.
-	The current chairperson or Leads become Maintainers and the initial Leads. If a SIG has fewer than two Leads, its Maintainers elect the missing Lead(s).
-	Current voting members become Maintainers; other current members become Contributors unless nominated as Maintainers.
-	The current SIG chairperson becomes the SIG liaison, unless the Maintainers disagree. Otherwise, or if the SIG has no chairperson, the parent committee appoints a SIG liaison within 30 days.
-	SIGs without a GitHub home create one within the transition period.
-	The first status report is due at the end of the transition period; the health criteria apply from then on.
SIGs that have not adopted conforming terms of reference by the deadline are considered at-risk.


## Changes to this document

The GB maintains this document. Proposed changes are published for consultation for at least 2 weeks. All NeoNephos committees and all SIG Leads are notified and may comment, and the consultation is open to the public on the NeoNephos primary communication channels. The GB then approves changes by majority vote. Changes take effect upon approval; existing SIGs have 3 months to update their terms of reference if needed.
