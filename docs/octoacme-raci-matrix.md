# OctoAcme — RACI Matrix (Lightweight)

## Purpose
Define clear accountability for recurring project activities across the OctoAcme lifecycle.

## RACI Legend
- **R** = Responsible (does the work)
- **A** = Accountable (owns final outcome/decision)
- **C** = Consulted (provides input)
- **I** = Informed (kept updated)

## Role Key
- PM = Project Manager
- PdM = Product Manager (Product Lead)
- Dev = Developers
- QA = QA/Testing
- SH = Internal Stakeholders
- UX = UX Designer
- DevOps = DevOps / Platform Engineer
- Sec = Security Lead
- CSL = Customer Support Lead
- ES = Executive Sponsor
- Ext = External Stakeholder

## Activity Matrix
| Activity | PM | PdM | Dev | QA | SH | UX | DevOps | Sec | CSL | ES | Ext |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| One-pager approval (Initiation) | R | A | C | I | C | C | I | C | C | C | C |
| Backlog prioritization (Planning) | R | A | C | C | C | C | C | C | C | I | C |
| Definition of Done ownership (Planning) | R | A | R | R | I | C | C | C | C | I | I |
| Risk register ownership (Planning/Execution) | A | C | R | C | C | C | C | C | C | I | I |
| Release readiness decision (Release) | R | A | C | R | C | C | R | C | C | I | I |
| Incident escalation coordination (Execution/Release) | A | C | R | C | I | I | R | R | C | C | I |
| Retro action tracking (Close & Retrospective) | A | R | R | R | C | C | C | C | C | I | I |

## Usage Notes
- Use this matrix with the lifecycle docs from initiation through retrospective.
- If multiple teams are involved, keep one **A** per activity per team/workstream.
- Reconfirm roles during kickoff and at release readiness checkpoints.
