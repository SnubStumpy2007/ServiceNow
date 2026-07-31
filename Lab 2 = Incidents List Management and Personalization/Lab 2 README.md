# Lab 02 - Incident List Management and Personalization

## Overview

This lab focuses on working with Incident lists in ServiceNow. The exercise demonstrates how to filter records, sort data, perform bulk updates using the List Editor, personalize list layouts, and modify individual incident records.

---

## Objectives

By completing this lab, I was able to:

* Navigate to the Incident list.
* Filter incidents using multiple conditions.
* Sort incidents by priority.
* Perform bulk record updates using the List Editor.
* Personalize the Incident list by removing unnecessary columns.
* Modify an individual incident record.

---

## Environment

| Item      | Value           |
| --------- | --------------- |
| Platform  | ServiceNow      |
| Module    | Incident > All  |
| Interface | Next Experience |

---

## Task 1 - Navigate to the Incident List

Using the **All** navigation menu, I opened:

```text
Incident > All
```

This displayed all incident records available to the current user.

### Screenshot

```
images/01-incident-list.png
```

---

## Task 2 - Open the Filter

I selected the **Show/Hide Filter** (funnel) icon to display the condition builder.

The filter allows records to be narrowed using one or more logical conditions.


```

---

## Task 3 - Configure the Filter

I configured the following filter conditions:

| Field            | Operator     | Value  |
| ---------------- | ------------ | ------ |
| State            | is not       | Closed |
| Assignment Group | is not empty | —      |
| Assigned To      | is not empty | —      |

After configuring the conditions, I selected **Run** to display the filtered results.


```

---

## Task 4 - Sort by Priority

I selected the **Priority** column header to sort the incident list.

This placed all **1 - Critical** incidents at the top of the list, making them easier to identify.



---

## Task 5 - Update Multiple Records with the List Editor

Using the **List Editor**, I selected the **State** field for all **1 - Critical** incidents.

I changed the value to:

```text
In Progress
```

The updates were saved by selecting the green checkmark.

This exercise demonstrated how ServiceNow supports efficient bulk updates across multiple records.

### Skills Demonstrated

* Multi-record editing
* Bulk updates
* List Editor
* Incident management


```

---

## Task 6 - Personalize the List

I selected the **Personalize List** (gear) icon.

The following columns were removed:

* Opened
* Updated By

Personalizing lists allows users to display only the information most relevant to their workflow.

```

---

## Task 7 - Modify an Individual Incident

I located incident:

```text
INC0000055
```

I updated the **Category** field to:

```text
Software
```

After saving the record, the change was reflected in the Incident list.

### Screenshot

```
images/07-category-update.png
```

---

## Key Concepts

### Incident Lists

Incident lists provide a tabular view of records and support filtering, sorting, editing, and personalization.

### Filters

Multiple conditions can be combined to quickly locate specific records requiring attention.

### List Editor

The List Editor enables administrators and service desk personnel to update multiple records simultaneously, significantly improving efficiency during large-scale changes.

### Personalized Views

Users can customize list layouts by adding, removing, or reordering columns to better support their daily workflow.

---

## Skills Demonstrated

* ServiceNow Incident Management
* List filtering
* Record sorting
* Bulk record updates
* List Editor
* List personalization
* Record modification
* Technical documentation

---

## Lessons Learned

This lab demonstrated how ServiceNow provides efficient tools for managing large numbers of incidents. Features such as filtering, sorting, bulk editing, and personalized list views help service desk technicians quickly organize and update records while improving overall productivity.

---

## Related Skills

* IT Service Management (ITSM)
* Service Desk Operations
* Incident Lifecycle Management
* ServiceNow Navigation
* Administrative Efficiency
* Technical Documentation
