# ServiceNow Lab – Creating a Visual Task Board (VTB)

## Objective

The objective of this lab was to create a Visual Task Board (VTB) in ServiceNow and organize submitted requests by category. This exercise demonstrated how Visual Task Boards provide a Kanban-style interface for tracking work items such as Problems, Incidents, and Changes.

---

## Skills Practiced

- Navigating the ServiceNow Application Navigator
- Creating a Visual Task Board (VTB)
- Using a Freeform Board
- Renaming boards and lanes
- Adding records to a Visual Task Board
- Organizing work visually
- Tracking requests using Kanban boards

---

## Lab Tasks Completed

### 1. Created a Visual Task Board

Navigated to:

```
All → Self-Service → Visual Task Boards
```

Selected **New**, then chose **Freeform Board**.

**Result:** Successfully created a new Visual Task Board.

---

### 2. Customized the Board

Renamed the board:

```
My Requests
```

Renamed the default lanes:

| Original Lane | New Lane |
|--------------|----------|
| To Do | Problem |
| Doing | Incident |
| Done | Change |

**Note:** Changes were automatically saved by ServiceNow.

---

### 3. Opened the Existing Problem Record

Navigated to the previously created Problem record using the Favorites menu.

Problem:

```
Unable to connect to network server.
```

**Result:** Successfully opened the Problem record.

---

### 4. Added the Record to the Visual Task Board

Selected:

```
Form Context Menu
    → Add to Visual Task Board
```

Selected:

```
My Requests
```

ServiceNow displayed the confirmation message:

> "Unable to connect to network server. Has been added to My Requests."

**Result:** Problem record successfully added to the Visual Task Board.

---

### 5. Verified the Board

Selected:

```
View Board
```

Confirmed the submitted Problem appeared under the **Problem** lane.

**Result:** Successfully verified the record was organized correctly on the board.

---

## Concepts Learned

### Visual Task Boards (VTBs)

Visual Task Boards provide a Kanban-style workspace that allows users to organize and track records visually using draggable cards.

VTBs help teams:

- Track work progress
- Organize tasks
- Improve workflow visibility
- Collaborate more effectively

---

### Freeform Boards

A Freeform Board allows users to manually organize records into custom lanes rather than relying on automatic filtering.

This provides flexibility for organizing work based on a team's preferred workflow.

---

### Kanban Workflow

The customized board used three lanes:

| Lane | Purpose |
|------|---------|
| Problem | Tracks submitted Problem records |
| Incident | Tracks Incident records |
| Change | Tracks Change Requests |

This layout creates a simple workflow for organizing different types of ITSM requests.

---

### Adding Records to a Board

Existing records can be added directly from their form by selecting:

```
Form Context Menu
→ Add to Visual Task Board
```

This allows users to quickly organize records without manually recreating tasks.

---

## Key Takeaways

- Visual Task Boards provide a simple, visual method for organizing work.
- Freeform Boards allow complete customization of workflow lanes.
- Existing ServiceNow records can be added directly to Visual Task Boards.
- Kanban-style organization improves visibility into ongoing work.
- Changes to board names and lane names are automatically saved.

---

## Challenges Encountered

- Learning where the Form Context Menu is located.
- Understanding the difference between Freeform Boards and automatically generated task boards.
- Becoming familiar with how existing records are linked to Visual Task Boards.

---

## Outcome

Successfully created a customized Visual Task Board named **My Requests**, configured custom workflow lanes, added an existing Problem record, and verified that it appeared in the appropriate lane for visual task tracking.

---

## Technologies Used

- ServiceNow Platform
- Visual Task Boards (VTB)
- ServiceNow Problem Management
- IT Service Management (ITSM)

---

## Skills Gained

- Visual Task Board creation
- Kanban workflow management
- ServiceNow navigation
- Record organization
- Task visualization
- ITSM workflow management

---

**Lab Status:** ✅ Completed
