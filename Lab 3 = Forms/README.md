# ServiceNow Lab – Creating a Problem Record

## Objective

The objective of this lab was to create a Problem record in ServiceNow to document a recurring network issue and understand how the platform automatically calculates priority based on impact and urgency.

---

## Skills Practiced

- Navigating the ServiceNow Application Navigator
- Creating a new Problem record
- Completing a Problem form
- Assigning records to the appropriate support group
- Understanding the relationship between Impact, Urgency, and Priority
- Documenting recurring IT issues

---

## Lab Tasks Completed

### 1. Navigated to the Problem Module

- Opened the **All** menu.
- Navigated to:

```
Problem → Create New
```

**Result:** Successfully opened a new Problem record.

---

### 2. Completed the Problem Form

Entered the following information:

| Field | Value |
|--------|-------|
| Category | Network |
| Service | IT Services |
| Impact | 2 - Medium |
| Urgency | 2 - Medium |
| Assignment Group | Network |
| Problem Statement | Unable to connect to network server. |
| Description | The department network server seems to be going down multiple times a week and I currently can't connect to it. We would like a more permanent solution. |

---

### 3. Observed Automatic Priority Calculation

After setting:

- **Impact:** 2 - Medium
- **Urgency:** 2 - Medium

ServiceNow automatically updated the **Priority** field to:

```
3 - Moderate
```

**Result:** Verified that ServiceNow automatically calculates Priority based on the selected Impact and Urgency values.

---

### 4. Submitted the Record

- Reviewed all entered information.
- Submitted the Problem record.

**Result:** Successfully created the Problem record.

---

## Concepts Learned

### What is a Problem?

A **Problem** in ServiceNow represents the underlying cause of one or more incidents. Rather than resolving a single outage, Problem Management focuses on identifying and eliminating the root cause to prevent future occurrences.

### Problem vs. Incident

| Incident | Problem |
|-----------|---------|
| Restores service quickly | Identifies and resolves the root cause |
| Reactive | Proactive |
| May occur once | Often addresses recurring incidents |

---

### Impact

Impact measures how many users, systems, or business functions are affected by an issue.

For this lab:

```
2 - Medium
```

indicates that the issue affects multiple users or a department but is not organization-wide.

---

### Urgency

Urgency reflects how quickly the issue needs to be addressed based on business requirements.

For this lab:

```
2 - Medium
```

indicates that timely attention is required, but the issue is not considered critical.

---

### Priority

Priority is automatically determined by ServiceNow using the selected Impact and Urgency values.

In this exercise:

| Impact | Urgency | Priority |
|---------|----------|----------|
| 2 - Medium | 2 - Medium | 3 - Moderate |

This automation helps standardize ticket prioritization and ensures consistent handling across support teams.

---

## Key Takeaways

- Problem records document recurring issues rather than individual incidents.
- Accurate categorization helps route work to the appropriate support team.
- ServiceNow automatically calculates Priority using Impact and Urgency.
- Problem Management focuses on long-term solutions instead of temporary fixes.
- Clear documentation improves troubleshooting and root cause analysis.

---

## Challenges Encountered

- Understanding the distinction between Incident Management and Problem Management.
- Learning how Impact and Urgency interact to determine Priority.

---

## Outcome

Successfully created a Problem record for a recurring network server issue, assigned it to the Network support group, and verified that ServiceNow automatically calculated the ticket's Priority based on the selected Impact and Urgency values.

---

## Technologies Used

- ServiceNow Platform
- ServiceNow Problem Management
- IT Service Management (ITSM)

---

## Skills Gained

- Problem record creation
- ITSM workflow familiarity
- Root cause documentation
- Ticket prioritization
- ServiceNow form navigation
- IT operations documentation

---

**Lab Status:** ✅ Completed
