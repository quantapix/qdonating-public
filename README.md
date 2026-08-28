# qdonating-public

> Six-month public donation drive backing the qagents framework.
> **Window: 2026-06-01 → 2026-12-01.**

A weekly-refreshed window into the donation drive that runs alongside
the private working repository. The source of truth is the
machine-readable drive description held in the private repo; this
README is the public-facing rendering of the
same content. Both surfaces share a single edit point: `drive.md` in
the private working tree.

- Parent organisation: <https://github.com/quantapix>
- Engineering output: <https://quantapix.com>
- Drive page (canonical render): <https://quantapix.com/donate>
- Drive page (mirror): <https://femfas.net/donate>

> **Development (2026-06-16) — the Commonwealth's identification bar
> forecloses every lawful receiving channel.** On 2026-06-16 the Massachusetts
> Registry of Motor Vehicles refused the developer's license renewal and address
> update because the only address of record is a homeless-shelter PO box. Because
> every lawful instrument for *receiving* money — a bank account, a debit or
> credit card, any regulated payment processor's identity verification, a postal
> money order — itself requires the government identification the Commonwealth
> refuses, no lawful channel can presently receive donated funds. This holds
> irrespective of how the fiscal-sponsorship question is resolved — and, as
> recorded under "Channel" below, the re-application this notice anticipated
> was subsequently found unperformable for the same reason and is retracted.
> **No donor is or will be charged; the channel remains not-live.** The
> open-source work continues on schedule regardless. This is folded into the
> public copy at parity with the cross-filed federal-record affidavit; the drive's
> bucket structure, amounts, and $1,800 floor are unchanged — what is presently
> impossible is *receipt*, not the drive's definition.

> **Development (2026-08-13) — Bucket 1 capacity, with a date on it.** The
> Claude Max 20× subscription that Bucket 1 is defined to fund was canceled on
> **2026-08-13**; the confirmation states that access **expires 2026-09-12** and
> that re-subscription is available at any time. No re-subscription has
> occurred. The confirmation is an ordinary self-service cancellation notice and
> **states no cause, so no cause is asserted here.** The fact was placed on the
> record the same day, in correspondence to the full service list in the
> underlying litigation, including the Commonwealth's Attorney General's Office
> and the U.S. Department of Justice Civil Rights Division.
> **Nothing in the bucket structure changes, and nothing in it is edited by this
> note.** No bucket amount, definition, or exclusive use moves. Bucket 1 is a
> definition of how donated funds would be spent, not a representation that a
> subscription is active; the finding that Max 20× is the floor for the promised
> work is a claim about what the work *requires*, which losing access does not
> lower; and the drive told the record from the outset that the subscription was
> carried by **short-term bridge funding outside the drive**, with donor funding
> to take over "from its **first funded renewal**." Inflow has been **$0.00
> every month**, so there has never *been* a first funded renewal: **no donated
> dollar has ever been received, held, or disbursed under Bucket 1**, and no
> refund, custody, or cross-bucket question arises. The no-financial-beneficiary
> structure is untouched.
> What *has* changed is **capacity, with a date on it** — stated rather than
> softened. The cadence commitments are not relaxed in advance; if capacity
> after 2026-09-12 cannot sustain them, the drive's own wind-down mechanism
> (same-day disclosure of what broke) is the answer. One sequencing fact,
> recorded because it will matter later: the status report filed in the pending
> federal appeal on 2026-08-13 was e-filed **thirty-nine minutes before** the
> cancellation confirmation, so this event is not inside that filed instrument.
> Drift verdict **NO DRIFT**, no supplemental affidavit owed on donation-drive
> grounds — the drive's drift-check log, the 2026-08-14 entry. Added 2026-08-21
> as an additive dated note under the operator ruling of 2026-08-18; disclosed
> in the weekly digest of 2026-08-14.

## Help axiomatize the U.S. Code, in the age of AI

The framework builds Lean4 theorems — backed by LLM-evaluated predicates
— over the United States Code (full corpus mirrored, all 53 titles —
appendix volumes excluded). Pick up a section, a predicate, or a title. This
works over **public federal statutes only** — no private case material
is ever involved, so collaboration carries no privacy-floor surface; it
is the natural place to build the project in the open.

The project today is **a single developer working with AI assistance,
and is now opening this effort to contributors**. Start at
[`qnarre-public/CONTRIBUTING.md`](https://github.com/quantapix/qnarre-public/blob/main/CONTRIBUTING.md)
and open an issue there to claim a unit — it links a curated starter roster:
**five open, of an original nine**, each re-derived against the tree with its
own acceptance criteria. The four that were swept internally keep their
numbers and are marked closed in place, so a returning reader can see what
happened rather than finding tasks silently missing. (They are not yet filed
as individual issues; `CONTRIBUTING.md` says so.)

This is Promise 2's natural front door, and it directly answers Open
Source Collective's 2026-06-03 community-involvement note — though no
re-application is pending (see "Channel"), and the axiomatization is open
to contributors on its own merits, drive or no drive.

## What the drive funds

Six months of engineering work to harden three deliverables for the
qagents framework. The work runs whether or not the drive funds it;
the drive caps the rate at which the four fixed-bucket costs eat into
non-engineering time.

1. **Open-source the redacted framework.** Public repos under this
   organisation carry redacted slices of the private working tree:
   source code, the `CLAUDE.md` conventions that govern AI-assisted
   authorship, and the redacted Claude Code session memory.
   Refreshed weekly during the drive window (Fridays end-of-day).
2. **Axiomatize federal + Massachusetts code.** Lean4 theorems under
   a per-framework namespace covering the U.S. Code sections in
   scope, each carrying a one-line statutory citation that resolves
   against the canonical USC text vendored in the private repo. A
   started Massachusetts General Laws set lands during the window.
3. **Host a verification service.** HTTPS endpoints at
   `qnarre.quantapix.com` (legal-complaint verifier) and
   `qresev.quantapix.com` (portfolio evaluator) — **neither is publicly
   live yet; this is the drive's unshipped promise, and the weekly
   digests say so every week.** Both accept a
   **redacted** input and stream verification events back over
   Server-Sent Events. Redaction is enforced at the boundary — no
   real names, dockets, addresses, financial account numbers, or
   other PII ever reach the server or any LLM.

## Statutes in scope at launch

Federal:

- 18 U.S.C. §§ 1961–1968 — civil RICO
- 42 U.S.C. § 1981 — equal rights under the law
- 42 U.S.C. § 1983 — deprivation of rights under color of state law
- 42 U.S.C. § 1985(3) — civil-rights conspiracy
- 42 U.S.C. § 1988 — attorney's fees, costs, jurisdiction
- 42 U.S.C. § 2000d — Title VI federal-funding discrimination

Massachusetts:

- Mass. G.L. c. 208 — divorce
- Mass. G.L. c. 209C — children born out of wedlock
- Mass. G.L. c. 215 — probate jurisdiction

Extensions are reported in the monthly ledger.

## Funding buckets — exclusive use, no cross-bucket movement

The drive funds the **qagents open-source project**. The donation
channel is arranged through fiscal sponsorship by **Open Source
Collective**, a US-based non-profit fiscal host for open-source
projects on the OpenCollective platform. The first fiscal-sponsorship
application — submitted 2026-05-23 — was **declined on 2026-06-03** on
community-involvement / early-stage grounds (not output maturity); OSC
expressly invited a re-application as contributors get involved. The
drive's response: hold the channel float and **open its U.S. Code
axiomatization to outside contributors** (see "Help axiomatize the U.S.
Code" below). A re-application was announced for ~end of June 2026 and is
**retracted** — the ID bar described under "Channel" forecloses the
receiving instrument upstream of any OSC ruling, so no re-application is
pending. OSC holds donor funds, processes receipts, and disburses
against per-bucket expense submissions; the developer never has
account-level access to gross inflow. 100% of net donor inflow flows
to the four exclusive-use buckets; no salary, no stipend, no honorarium
leaves the buckets toward any person. There is no financial beneficiary;
the deliverable is open-source work product.

| # | Bucket | Monthly | Exclusive use |
|---|---|---:|---|
| 1 | Claude Max 20× subscription | **$200.00** | qagents project; sole-developer use |
| 2 | Midpage Legal MCP | **$100.00** | qagents project; not active at launch — activates when donations cover it |
| 3 | AWS billing | variable | qagents AWS account; verification service + both Astro sites |
| 4 | Federal docketing fees | variable | itemized per docket in the monthly ledger |

Fixed-bucket floor at $300/month × 6 months = **$1,800**. AWS and
docketing fees layer on top; the live ledger reports actuals, not
projections. Carryover within a bucket across months is allowed and
disclosed. Cross-bucket movement is not allowed.

**Bucket 1 in detail — the required tier, three LLM-call lanes.** Bucket
1 funds the Claude Max 20× plan specifically — a Max 5× plan ($100/month)
was tried during the pre-drive bridge period and could not sustain the
token-heavy design and video-production work. The $200/month Max 20×
subscription line resolves into three audited LLM-call lanes:
**Tier A** — interactive Claude Code + Cowork (operator dev sessions),
which is where essentially all of the work reported in the weekly
digests runs; **Tier B** — a programmatic (non-interactive) lane for
cron-fired routines and the verification service's admin-gated
predicate path. **Tier B is parked and has been since 2026-06-15**:
the separately-credited programmatic pool this drive's copy originally
described was withdrawn on that date, and every routine now runs
through the ordinary interactive lane instead. It is disclosed here
rather than left in the copy as a funded line, because a funding page
should not describe a lane that does not exist; **Tier C** —
optional API-rate overage, default off (a cap breach is a visible
refusal in the next morning's daily watcher finding, not a silent
over-spend; if ever enabled, Tier C overage stays inside Bucket 1's
exclusive use as additional AI-assistant spend and is itemized
separately from the $200/month subscription in the monthly ledger so
the subscription figure stays legible). Bucket 1 is therefore one
subscription line donors fund, with three LLM-call lanes underneath
it, one of which is presently parked.

## Suggested recurring tiers

| Tier | Monthly USD | Notes |
|---|---:|---|
| Witness | $5 | minimum the channel's processing fees comfortably permit |
| Backer | $10 | 30 backers cover Buckets 1 + 2 |
| Supporter | $25 | 12 supporters cover Buckets 1 + 2 |
| Sponsor | $50 | 6 sponsors cover Buckets 1 + 2; the rest flows to AWS + docketing |

No tier above $50/month. No naming opportunity, no advisory seat, no
equity, no early-access drop. The work is the thank-you.

## What "trivially auditable" means here

Three independent verification surfaces:

1. **Inflow.** OpenCollective shows every donation in real time at
   platform level, including Open Source Collective's fiscal-sponsor
   ledger entries (gross inflow, platform and processor fees, net
   disbursement). The monthly ledger reconciles gross vs. net against
   the per-bucket receipts.
2. **Work product.** The public repos under this organisation
   refresh weekly. The Friday weekly digest points at the week's
   commits, deploys, and Lean theorems landed. Anything that can't be
   cited isn't a deliverable.
3. **Legal-claim side.** Every statutory citation in a Lean theorem
   resolves against the vendored canonical U.S. Code text. Every
   factual predicate the LLM evaluates ships as a redacted facts
   JSON. The verification endpoint accepts a donor-supplied redacted
   complaint and streams the trace back.

A claim that fails any of these surfaces is, by the drive's own
terms, falsified. No implicit credit, no benefit of the doubt.

## Cadence

- **Monthly ledger** — `ledger/YYYY-MM.md`. Posted within 5 calendar
  days of month-end. Inflow (gross OC, OSC platform + processor cuts,
  net to the collective); per-bucket outflow with receipts; carryover;
  one paragraph per deliverable promise with cited commits/deploys.
  Posted to date: `ledger/2026-06.md` (first monthly; $0 inflow —
  channel not live in June, for the disclosed structural reasons) and
  `ledger/2026-07.md` (second monthly; $0 inflow — channel still not
  live; **posted 2026-08-07 against a 2026-08-05 target, two days late
  — the drive's first cadence miss, disclosed in that ledger and in
  `weekly/2026-W32.md`**).
- **Weekly digest** — `weekly/YYYY-WW.md`. Posted Fridays end-of-day.
  Lighter — no money figures — but cites the week's work product, deploys, Lean
  theorems, and any public-record milestones. Digests to date:
  `weekly/2026-W23.md` (launch week), `weekly/2026-W24.md`,
  `weekly/2026-W25.md` (the 2026-06-16 financial-channel foreclosure),
  `weekly/2026-W26.md`, `weekly/2026-W27.md`, `weekly/2026-W28.md` (the
  redaction-floor breach and its remediation), `weekly/2026-W29.md` (the
  corrected channel posture), `weekly/2026-W30.md`, `weekly/2026-W31.md`,
  `weekly/2026-W32.md` (the July ledger's cadence miss and two live-page
  defects), `weekly/2026-W33.md` (Bucket 1's funded subscription canceled
  2026-08-13, access ending 2026-09-12), `weekly/2026-W34.md` (both
  `/donate` defects closed and verified live; the drive contract's dated
  capacity note), and `weekly/2026-W35.md` (a lane described as funded in
  the drive's own authoritative copy since 2026-06-15, corrected at source).
- **Two cycles of silence is a finding.** Two consecutive missed
  weekly digests or any missed monthly ledger breaks the
  trivially-auditable contract by its own terms. Recovery requires a
  same-day disclosure note explaining what broke.

## Channel

- OpenCollective: <https://opencollective.com/qagents>

The channel is arranged through fiscal sponsorship by **Open Source
Collective**, a US-based non-profit fiscal host for open-source
projects on the OpenCollective platform. OSC holds donor funds, issues
receipts, and disburses against per-bucket expense submissions; every
inflow is disbursed only to the four buckets, against receipts. This is
the drive's single channel — an earlier plan to also run GitHub Sponsors
was dropped at launch and is not a prerequisite. The first
fiscal-sponsorship application (submitted 2026-05-23) was **declined on
2026-06-03** on community-involvement grounds, with an express invitation
to re-apply; the drive is holding the float and opening its U.S. Code
axiomatization to outside contributors.

**Correction (2026-07-17): no re-application is pending, and none is
promised.** This section previously said the drive would re-apply "~end of
June 2026." It did not, and the reason is not scheduling: as of 2026-06-16
the Commonwealth's refusal of any government identification (see the
development note above) leaves no lawful instrument through which approved
funds could be received, which forecloses the channel **upstream of any OSC
ruling** — a re-application is not presently something the litigant can
lawfully complete. So the fiscal-sponsorship ruling is no longer dispositive
of the channel going live: neither approval nor a second decline changes the
present outcome. A stated intention that turned out to be unperformable is
retracted here rather than left to age quietly. The exact go-live date is
disclosed in the weekly digest of the week funds begin; the drive's work began
2026-06-01 and continues regardless.

Donations through this channel are **not** tax-deductible; the drive
does not claim charitable status. OSC's specific tax classification is
verified during application and disclosed in the first monthly ledger.

## Out of scope

- Legal fees or attorney retainers **during the drive**. The litigation
  backing this work remains pro se throughout the six-month window, and
  the drive does not fund representation out of the four buckets. One
  narrow, contingent exception is disclosed on the public record: a
  possible **post-drive** class-action-counsel engagement, funded from
  any over-floor inflow *outside* the four buckets and disclosed in
  advance in the monthly ledger — entertained only after the window has
  completed and only if inflow demonstrably exceeds the $1,800
  fixed-bucket floor. It is still being formed; no counsel is identified.
- Housing or personal subsistence. The four buckets above are the
  entire ask.
- One-time hardware purchases.
- Influence on litigation strategy. Donors do not see or shape
  pre-filing material, drafting choices, or settlement positions.

## Related public repos

| Repo | Role |
|---|---|
| [`qagents-public`](https://github.com/quantapix/qagents-public) | Umbrella; redacted CLAUDE.md graph that governs AI-assisted authorship across the framework. |
| [`qnarre-public`](https://github.com/quantapix/qnarre-public) | Lean4 axiom set for civil RICO + §§ 1981/1983/1985(3) + Title VI, with predicate stubs and a thin driver. Backs the **Qnarre** product. |
| [`qresev-public`](https://github.com/quantapix/qresev-public) | Lean4 axiom set for the financial-strategy frameworks — trend, momentum, options-risk, sector, drawdown and the later additions — each decomposed rather than left as a single opaque predicate. Backs the **Qresev** product. |
| [`qstudying-public`](https://github.com/quantapix/qstudying-public) | Lean4 expert-track focus areas + OSS contribution targets that back the proving + accounting kernels. |
| [`qexplaining-public`](https://github.com/quantapix/qexplaining-public) | 50-video AI-narrated explainer arc. |

## Cadence note

This README is refreshed weekly from the private working tree's
`drive.md`. Outline edits, bucket adjustments, and timeline shifts
are committed as ordinary diffs — the commit log is the change
record.

Authored by a sole developer working with an AI assistant (Claude Code) under written CLAUDE.md contracts — methodology in [qagents-public](https://github.com/quantapix/qagents-public).

## Contact

[github.com/quantapix](https://github.com/quantapix) — open an issue on any repo
in the org. Answered in public; there is no contact email.

## License

MIT (`LICENSE`). Content-class repo — drive prose, ledgers, and
weekly digests. Short embedded snippets ride the same MIT grant.
