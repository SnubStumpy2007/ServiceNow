# ServiceNow Lab: Request a New Employee Resources Knowledge Base

## Objective
Submit a request to create a new Knowledge Base titled **New Employee Resources** through the Employee Center.

---

## Lab Environment

- **Platform:** ServiceNow
- **Module:** Employee Center
- **Category:** Knowledge Management

---

## Task Steps

### Step 1: Open Employee Center

Navigate to:

**Self-Service → Employee Center**

> **Tip:** You can also access the Employee Center by replacing the end of your ServiceNow instance URL with:
>
> ```
> /esc
> ```

Example:

```
https://instance.service-now.com/esc
```

---

### Step 2: Navigate to IT Services

From the Employee Center:

1. Select the **Technology services** dropdown.
2. Choose **IT**.

---

### Step 3: Request a Knowledge Base

Select:

**Request Knowledge Base**

---

### Step 4: Complete the Request Form

Fill in the following information.

| Field | Value |
|-------|-------|
| **Reason for KB to be created** | New employees need resources to help with Week 1 tasks on the job. |
| **Knowledge Base Name** | New Employee Resources |

After completing the form:

1. Select **Submit**.
2. Observe the generated request number.

> **Note:** The request number begins with **REQ** and will be different for every user.

Example:

```
REQ0012345
```

---

### Step 5: Return to the Platform View

After submitting the request, your browser URL will resemble:

```
https://instance.service-now.com/esc?id=ticket&table=sc_request&sys_id=...
```

To return to the standard ServiceNow Platform view:

1. Remove everything beginning with:

```
/esc?id=ticket
```

2. Press **Enter**.

This returns you to the normal ServiceNow interface.

---

## Validation

After completing the exercise:

1. Select **Validate Task**.
2. If validation fails:
   - Review each field for accuracy.
   - Verify the request was submitted successfully.
   - Ensure the Knowledge Base name exactly matches **New Employee Resources**.

---

# Lab Summary

### Objective Achieved

- Accessed the Employee Center.
- Navigated to IT services.
- Submitted a request for a new Knowledge Base.
- Created the Knowledge Base request:
  - **Name:** New Employee Resources
  - **Purpose:** Help new employees complete Week 1 onboarding tasks.
- Returned to the ServiceNow Platform view.
- Validated the completed task.

---

## Skills Practiced

- Employee Center navigation
- Service Catalog requests
- Knowledge Management
- IT self-service workflows
- ServiceNow interface navigation
- Request submission process

---

## Key Takeaways

- The Employee Center serves as the primary portal for employee service requests.
- Knowledge Base requests allow organizations to expand internal documentation.
- Every submitted request receives a unique **REQ** identifier.
- Understanding URL shortcuts (such as `/esc`) can improve navigation efficiency within ServiceNow.
