# NeoNephos Special Interest Groups

**Version:** 1  
**Status:** Active  
**Maintained by:** NeoNephos Technical Advisory Council (TAC)

---

A NeoNephos Special Interest Group (SIG) is a long-lived working group within the NeoNephos Foundation. Each SIG coordinates work in a specific technical or community domain. SIGs are the primary way NeoNephos organizes sustained collaboration across projects and member organizations. SIGs may also facilitate initiatives that span multiple projects or provide foundation-level services.

Each SIG is governed by a **terms of reference (ToR)** — a document that defines the SIG's purpose, scope, deliverables, and governance rules. The ToR is approved by the TAC and reviewed annually.

## Authority and conformance

The NeoNephos TAC creates all technical SIGs and governs them. A SIG's terms of reference take effect upon TAC approval and remain subject to TAC oversight. The TAC may dissolve a SIG by majority vote. The TAC must give 30 days written notice through the SIG's primary communication channel.

## Scope of autonomy

Within their chartered scope, SIGs make technical and process decisions independently. Any decision outside that scope requires approval from the NeoNephos Governing Board or the TAC. SIGs must escalate decisions with cross-SIG impact, budget or staffing implications, or changes to Foundation-wide policy to the TAC.

## Relationship to projects

SIGs operate at the NeoNephos Foundation level, not within individual projects. SIGs do not host NeoNephos projects directly; hosted projects govern themselves under their own terms of reference. A SIG may propose, sponsor, or advise projects within its domain. It may also support or lead cross-project initiatives.

## TAC liaison

The TAC appoints one of its members as TAC liaison to each SIG and reappoints the liaison annually. The liaison attends SIG meetings as a non-voting observer, unless the liaison is also a SIG member. The liaison is the primary escalation contact between the SIG and the TAC. If needed, the liaison presents the SIG's quarterly report to the TAC on behalf of the Leads. The current liaison for each SIG is listed in that SIG's repository.

## Code of conduct

The [NeoNephos Code of Conduct](https://github.com/neonephos/.github/blob/main/CODE_OF_CONDUCT.md) governs all SIG activity.

## Roles and membership

| Role | Responsibilities | Eligibility |
|---|---|---|
| Contributor | Submit PRs, participate in discussions | Open to all |
| Maintainer | Review and approve contributions, vote on SIG decisions | Nominated by a Lead; approved unless a Maintainer objects within 5 business days |
| Lead (2) | Facilitate meetings, represent SIG externally, break ties | Elected by Maintainers; see Lead appointment below |

### Lead appointment

The TAC appoints the initial Leads at founding, with staggered terms (one for 6 months, one for 1 year). Thereafter, Leads are elected by majority vote of current Maintainers. Any Maintainer may self-nominate. Nomination and voting periods are each 1 week. Lead terms are 6 months, renewable. If a seat becomes vacant, remaining Leads may appoint an interim. A formal election must follow within 90 days.

### Inactivity and removal

Leads may move a Contributor or Maintainer inactive for 12 months to emeritus status by majority vote, after giving written notice. The TAC may remove a Lead at any time. Maintainers may also remove a Lead by majority vote.

## Decision making

1. Lazy consensus is the default for all decisions. A proposal stands if no objection is raised within 5 business days.
2. Leads resolve contested decisions by majority vote if consensus cannot be reached.
3. Unresolved disputes escalate to the TAC. The TAC must respond no later than the second TAC meeting after the escalation.

## Meetings and communication

SIGs must conduct their primary communication in public. This allows anyone inside or outside the NeoNephos Foundation to follow the work and contribute. Each SIG must designate one channel as its primary communication channel and list it in its repository.

- Scheduling — The SIG schedules meetings via Linux Foundation Events (LFX). The SIG sets the cadence.
- Minutes — Leads provide written minutes after each meeting.
- Recordings — The SIG decides whether to record meetings. It also decides whether to upload recordings to the [NeoNephos YouTube channel](https://www.youtube.com/@NeoNephos).
- GitHub — Each SIG has a repository at `https://github.com/neonephos/sig-[shortname]`.
- Zulip — Each SIG may have a channel at `#sig-[shortname]` in the NeoNephos Zulip.
- Mailing list — Each SIG may have a mailing list at `sig-[shortname]@lists.neonephos.org`.
- Async decisions — SIG members may make decisions asynchronously on GitHub, Zulip, or the mailing list using lazy consensus.

## Reporting

- Quarterly report — The SIG submits a report to the TAC every 3 months. The SIG may present the report at a TAC meeting or deliver it in written form. It must cover:
  - Current Lead roster and TAC liaison
  - Active subprojects and their status
  - Key deliverables completed
  - Community health metrics: contributor count and meeting attendance
  - Blockers or unresolved escalations
  - Goals for the coming quarter
- Health criteria — The SIG is considered at-risk if it has had no meetings and no recorded activity for 3 consecutive months. Recorded activity includes merged PRs, issues, or discussions on GitHub, messages on the primary communication channel, or published meeting minutes. A SIG that misses two consecutive quarterly reports is also considered at-risk. After 6 months at-risk, the TAC reviews whether to declare the SIG dormant.

## Amendments

Current Leads may amend a SIG's terms of reference by majority vote. Leads must present proposed amendments at a TAC meeting before they take effect. The TAC votes on approval at that meeting or the next. The terms of reference are reviewed annually from the date of TAC approval.

## Lifecycle

| Phase | Trigger |
|---|---|
| Active | Terms of reference approved by the TAC |
| At-risk | No meetings and no recorded activity for 3 consecutive months, or two consecutive quarterly reports missed. The TAC is notified in both cases. |
| Dormant | The TAC declares the SIG dormant after 6 months without meetings or recorded activity, or after an unresolved Lead vacancy of 6 months. |
| Dissolved | TAC majority vote; 30 days written notice on the SIG's primary communication channel. |
