# NeoNephos Special Interest Groups

**Version:** 1.2 
**Status:** Draft - or review  
**Maintained by:** NeoNephos Governing Board (GB)

---

A NeoNephos Special Interest Group (SIG) is a long-lived working group within the NeoNephos Foundation. Each SIG coordinates work in a specific domain within the remit of its parent committee (e.g. technical, community, or strategic). SIGs are the primary way NeoNephos organizes sustained collaboration across projects and member organizations. SIGs may also facilitate initiatives that span multiple projects or provide foundation-level services.

Each SIG is governed by its **terms of reference (ToR)**, a document or structured format that defines the SIG’s name, purpose, scope, deliverables and governance rules. The ToR is approved by the parent committee (as defined below) and reviewed annually. It may add to the rules of this framework, for example eligibility criteria for Maintainers or higher voting thresholds, but must not contradict them. In particular, it cannot change the parent committee’s oversight rights, the reporting obligations, the health criteria or the lifecycle rules.

## Definitions

- **Parent Committee:** the NeoNephos committee (TAC, OC or GB) that hosts a SIG.
- **Dayz**: calendar days.
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

Anyone may propose a SIG to the parent committee by submitting a draft terms of reference, including name, scope, deliverables, initial Leads, and at least 3 interested Maintainers (the initial Leads included). The parent committee approves the SIG by majority vote.

## Choosing the parent committee

A SIG proposal is submitted to the committee whose remit best fits its scope. If a committee considers the proposal outside its remit, it forwards it to the appropriate committee. If the scope fits more than one committee, the committees concerned agree on the parent committee before voting; if they cannot agree, the GB decides.

If a committee rejects a SIG proposal on its merits, no other committee may approve the same or a substantially similar proposal within 6 months. The proposers may appeal the rejection to the GB, whose decision is final.

A SIG may transfer to another parent committee with the approval of both committees.

## Scope of autonomy

Within their chartered scope, SIGs make technical and process decisions independently. Any decision outside that scope requires approval from the NeoNephos Governing Board or the parent committee. SIGs must escalate decisions with cross-SIG impact, budget or staffing implications, or changes to Foundation-wide policy to the parent committee.

## Relationship to projects

SIGs operate at the NeoNephos Foundation level, not within individual projects. SIGs do not host NeoNephos projects directly; hosted projects govern themselves under their own terms of reference. A SIG may propose, sponsor, or advise projects within its domain. It may also support or lead cross-project initiatives.

## SIG registry

All SIGs are listed in the NeoNephos SIG registry ```sigs.yaml``` at [https://github.com/neonephos/metadata](). For each SIG, ```sigs.yaml``` contains its name, parent committee, lifecycle status and link to the project specific ```sig.yaml```. The registry repository provides the authorative structure of ```sig.yaml`` which alls SIGs must fill out and display in their main repository.

For each SIG, ```sig.yaml``` lists its specifics such as Leads, Maintainers, SIG liaison, primary communication channel, and a link to the SIG's GitHub home. The registry and its templates are authoritative.
The GB ensures that the registry is maintained and accessible. Leads keep their SIG's entry up to date. The SIG liaison confirms changes to Leads and lifecycle status.

## Code of conduct

The NeoNephos Code of Conduct governs all SIG activity.

## Code of conduct

The [NeoNephos Code of Conduct](https://github.com/neonephos/.github/blob/main/CODE_OF_CONDUCT.md) governs all SIG activity.

## Roles and membership

| Role | Responsibilities | Eligibility |
|---|---|---|
| Contributor | Submit PRs, participate in discussions | Open to all |
| Maintainer | Review and approve contributions, vote on SIG decisions | Nominated by a Lead; approved unless a Maintainer objects within 5 business days |
| Lead (2) | Facilitate meetings, represent SIG externally, break ties | Elected by Maintainers; see Lead appointment below |

### Lead appointment

The parent committee appoints the initial Leads at founding, with staggered terms (one for 6 months, one for 1 year). Thereafter, Leads are elected by majority vote of current Maintainers. Any Maintainer may self-nominate. Nomination and voting periods are each 1 week. Lead terms are 6 months, renewable. If a seat becomes vacant, remaining Leads may appoint an interim. A formal election must follow within 90 days.

### Inactivity and removal

Leads may move a Contributor or Maintainer inactive for 12 months to emeritus status by majority vote, after giving written notice. The parent committee may remove a Lead at any time. Maintainers may also remove a Lead by majority vote.

## Decision making

1. Lazy consensus is the default for all decisions. A proposal stands if no objection is raised within 5 business days.
2. Leads resolve contested decisions by majority vote if consensus cannot be reached.
3. Unresolved disputes escalate to the parent committee. The parent committee must respond no later than the second parent committee meeting after the escalation.

## Meetings and communication

SIGs must conduct their primary communication in public. This allows anyone inside or outside the NeoNephos Foundation to follow the work and contribute. Each SIG must designate one channel as its primary communication channel and list it in its repository.

- Scheduling — The SIG schedules meetings via Linux Foundation Events (LFX). The SIG sets the cadence.
- Minutes — Leads are responsible that written minutes are provided after each meeting.
- Recordings — The SIG decides whether to record meetings. It also decides whether to upload recordings to the [NeoNephos YouTube channel](https://www.youtube.com/@NeoNephos).
- GitHub — Each SIG has a repository at `https://github.com/neonephos/sig-[shortname]`
- Zulip — Each SIG may have a channel at `#sig-[shortname]` in the NeoNephos Zulip.
- Mailing list — Each SIG may have a mailing list at `sig-[shortname]@lists.neonephos.org`.
- Async decisions — SIG members may make decisions asynchronously on GitHub, Zulip, or the mailing list using lazy consensus.

## Reporting

- Quarterly report — The SIG submits a report to the parent committee at most every 3 months. The SIG may present the report at a parent committee's meeting or deliver it in written form. It must cover:
  - Current Lead roster and SIG liaison
  - Active subprojects and their status
  - Key deliverables completed
  - Community health metrics: contributor count and meeting attendance
  - Blockers or unresolved escalations
  - Goals for the coming quarter
- Health criteria — The SIG is considered at-risk if it has had no meetings and no recorded activity for 3 consecutive months. Recorded activity includes merged PRs, issues, or discussions on GitHub, messages on the primary communication channel, or published meeting minutes. A SIG that misses two consecutive quarterly reports is also considered at-risk. After 6 months at-risk, the parent committee reviews whether to declare the SIG dormant.

## Amendments

Current Leads may amend a SIG's terms of reference by majority vote. Leads must present proposed amendments at a parent committee's meeting before they take effect. The parent committee votes on approval at that meeting or the next. The terms of reference are reviewed annually from the date of parent committee's approval.

## Lifecycle

| Phase | Trigger |
|---|---|
| Active | Terms of reference approved by the parent committee |
| At-risk | No meetings and no recorded activity for 3 consecutive months, or two consecutive quarterly reports missed. The parent committee is notified in both cases. |
| Dormant | The parent committee declares the SIG dormant after 6 months without meetings or recorded activity, or after an unresolved Lead vacancy of 6 months. |
| Dissolved | Parent committee majority vote; 30 days written notice on the SIG's primary communication channel. |
