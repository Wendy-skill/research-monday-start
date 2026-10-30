# Optional v3 Research-Group Interface

Load only for a task that actually calls for handoff or consolidated findings. This Skill is standalone otherwise.

- **Owner:** Recover real research status, select weekly priorities, define a 25-minute first step.
- **Not responsible for:** Pretending weekly planning has executed simulations, read sources, reviewed claims or monitored time.
- **Chinese activation:** 科研周一启动、恢复研究进度、25分钟开工.
- **English activation:** start research week, 25-minute research starter.
- **Avoid triggering for:** unrelated scientific validity review, generic formatting, or an unrequested batch of all specialists.
- **Optional downstream:** ai-literature-member, ai-research-execution, ai-paper-editor, ai-strict-reviewer or ai-quality-inspector, according to the actual next task; requires actual availability and user-authorised action.

## Role-specific safeguard

Only plan and route the next action. A plan is not evidence that a research task was executed. After the user reports completion, update only actual reported progress.

## Shared issue and evidence contract

`ID | owner | document/version/location | issue/claim | located evidence | source status | assessment | local scientific Severity or QA Impact/urgency | next action | author decision | state`.

Source status is `Reported / Documented / Independently checked / Not available`. Assessment `Confirmed / Reasoned inference / Unverified` must specify what was checked. State `Open / Waiting for evidence / Awaiting author / Resolved / Recheck needed`. Do not claim an external call, completed work, a saved ledger or source verification without actual evidence.

## Ledger and efficient routing

If supplied/authorised, reuse Claim ID, Data ID, sources and locations, conditions/baseline, units, dataset or script versions, verification status, and linked issue IDs; this ledger does **not** automatically sync across apps. One issue owner; optional specialist handles a distinct subquestion, not a duplicate full review. Route only when justified. After approved changes, revisit only affected records. Default workflow is literature → approved execution → scientific review → editing → final QA, with feedback loops; do not impose it on narrow requests.
