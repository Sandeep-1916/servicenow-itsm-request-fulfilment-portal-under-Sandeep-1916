# Sprint Plan and Progress

Project: IT Service Request Fulfilment Portal (ServiceNow ITSM, Xanadu PDI).

Sprint dates are the planned sprint windows (25 Sep 2026 onward). GitHub issues and milestones were created on the date this document was generated, so their creation timestamps differ from the sprint windows.

| Sprint | Window | Status | Milestone |
|---|---|---|---|
| Sprint 0 - Initiation and GitHub Setup | 2026-09-25 to 2026-09-27 | Completed | [link](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/milestone/1) |
| Sprint 1 - Foundation | 2026-09-28 to 2026-10-01 | Completed | [link](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/milestone/2) |
| Sprint 2 - Service Catalog | 2026-10-02 to 2026-10-05 | Completed | [link](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/milestone/3) |
| Sprint 3 - Automation and Fulfilment | 2026-10-06 to 2026-10-09 | Completed | [link](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/milestone/4) |
| Sprint 4 - Security and Event Notifications | 2026-10-10 to 2026-10-24 | Open | [link](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/milestone/5) |
| Sprint 5 - Integration | 2026-10-25 to 2026-11-07 | Open | [link](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/milestone/6) |
| Sprint 6 - Reporting | 2026-11-08 to 2026-11-21 | Open | [link](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/milestone/7) |
| Sprint 7 - Testing and Release | 2026-11-22 to 2026-12-05 | Open | [link](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/milestone/8) |

## Sprint 0 - Initiation and GitHub Setup

- Window: 2026-09-25 to 2026-09-27
- Status: Completed
- Goal: Choose the ITSM portfolio project, set up the repository and documentation workflow.

Issues:
- [x] [#1 Select ITSM portfolio project and finalize scope](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/1)
- [x] [#2 Create GitHub repository and documentation structure](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/2)

## Sprint 1 - Foundation

- Window: 2026-09-28 to 2026-10-01
- Status: Completed
- Goal: Create the application, roles, groups and test users; decide application scope.

Issues:
- [x] [#3 Create application and decide scope (scoped to Global)](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/3)
- [x] [#4 Create roles and assignment groups](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/4)
- [x] [#5 Load test users with valid emails (import set)](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/5)
- [x] [#6 Test group access with impersonation](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/6)

## Sprint 2 - Service Catalog

- Window: 2026-10-02 to 2026-10-05
- Status: Completed
- Goal: Build catalog items, variables, the New Employee Setup order guide and Script Includes.

Issues:
- [x] [#7 Create catalog items](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/7)
- [x] [#8 Create catalog variables and choices (laptop type, OS)](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/8)
- [x] [#9 Build New Employee Setup order guide](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/9)
- [x] [#10 Manager reference qualifier using a Script Include](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/10)
- [x] [#11 Script Include practice (bRule1, getnumber, scriptcall)](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/11)
- [x] [#12 Fix Script Include syntax error (missing colon after type)](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/12)

## Sprint 3 - Automation and Fulfilment

- Window: 2026-10-06 to 2026-10-09
- Status: Completed
- Goal: Automate Laptop and VPN fulfilment with approvals, catalog tasks, SLAs and notifications; test end to end.

Issues:
- [x] [#13 Laptop Request fulfilment flow](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/13)
- [x] [#14 VPN Access fulfilment flow](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/14)
- [x] [#15 Manager approval and rejection handling](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/15)
- [x] [#16 Order guide parallel child fulfilment](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/16)
- [x] [#17 Response and resolution SLAs](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/17)
- [x] [#18 Dynamic task email notifications](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/18)
- [-] [#19 Dynamic assignment with Script Include (KeyboardAssignmentUtils)](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/19)
- [x] [#20 Fix RITM stuck in Work in Progress after tasks complete](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/20)
- [x] [#21 Investigate approval field showing Not yet requested](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/21)
- [x] [#22 Test approval, rejection, task sequencing, SLA and notifications](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/22)

## Sprint 4 - Security and Event Notifications

- Window: 2026-10-10 to 2026-10-24
- Status: Open
- Goal: In progress: ACLs and role access, plus the event-based task completion notification chain.

Issues:
- [ ] [#23 Implement ACLs and role-based access](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/23)
- [ ] [#24 Complete event-based task completion notification](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/24)

## Sprint 5 - Integration

- Window: 2026-10-25 to 2026-11-07
- Status: Open
- Goal: Inbound email to request creation and REST API catalog intake.

Issues:
- [ ] [#25 Inbound email to request creation](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/25)
- [ ] [#26 REST API catalog intake](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/26)

## Sprint 6 - Reporting

- Window: 2026-11-08 to 2026-11-21
- Status: Open
- Goal: Reports and dashboards; Incident, Problem and Change management extensions.

Issues:
- [ ] [#27 Reports and dashboards](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/27)
- [ ] [#28 Incident, Problem and Change management extensions](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/28)

## Sprint 7 - Testing and Release

- Window: 2026-11-22 to 2026-12-05
- Status: Open
- Goal: Regression pack, edge cases, release hardening and final GitHub packaging.

Issues:
- [ ] [#29 End-to-end regression pack and edge cases](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/29)
- [ ] [#30 Release documentation and GitHub packaging](https://github.com/Sandeep-1916/servicenow-itsm-request-fulfilment-portal-under-Sandeep-1916/issues/30)

## Errors and fixes

| Problem | Cause | Fix / outcome |
|---|---|---|
| sc_req_item not accessible from the scoped application | Cross-scope access limits | Switched the project to Global scope |
| Desktop group member could not see Group Work | Group membership alone does not grant UI access | Reviewed roles and access instead of group membership only |
| RITM stayed Work in Progress after all tasks were Closed Complete | Child task completion does not update the RITM state | RITM state handled explicitly (exact configuration to be added) |
| Approval field showed Not yet requested | Approval state is separate from task/RITM state | Investigated; exact correction to be added |
| Script Include scriptcall flagged by the editor | Missing colon: type 'scriptcall' | Use type: 'scriptcall' |
| Could not call a Script Include from Flow Designer | No generic Script action | Skipped; conditional assignment used instead |

_Screenshot pending: Script Include scriptcall syntax error_

## Testing

- Impersonation of requesters, managers and group members
- Approval and rejection paths
- Laptop type and OS branching
- Sequential task creation and assignment group routing
- Dynamic task email notifications
- Response (30 minutes) and resolution (3 days) SLAs on RITM0010021
- Parallel child execution from the New Employee Setup order guide
- Still to do: formal regression pack and edge cases (Sprint 7)

## Lessons learned

- Use standard tables (sc_request, sc_req_item, sc_task) unless a custom table adds real value.
- Scope decisions affect table access; Global was chosen for the PDI, which is not necessarily a production pattern.
- Keep each catalog item flow independent so it works both standalone and inside an order guide.
- Completing child tasks does not automatically close or progress the RITM.
- Static assignment (fixed group on a task) differs from conditional or dynamic assignment.
- Do not add a Script Include or event where a simple flow or notification is enough.
- Group membership alone does not grant access to work lists; roles matter.
