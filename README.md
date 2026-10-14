# ArcGIS Online Administration 2026 — Administering ArcGIS Online Content
### Study Guide (README) · Esri Training

> Covers: finding items, item pages, creating and evaluating groups, sharing options, and transferring ownership.
> At the end: answers to the course quizzes, common traps, and a cheat sheet.

---

## Table of Contents
1. [Finding items — making content discoverable](#1-finding-items--making-content-discoverable)
2. [Category sets](#2-category-sets)
3. [Evaluating items — the item page](#3-evaluating-items--the-item-page)
4. [Creating groups — the 4 steps](#4-creating-groups--the-4-steps)
5. [Group membership settings](#5-group-membership-settings)
6. [Group designations](#6-group-designations)
7. [Group roles](#7-group-roles)
8. [Item sharing options](#8-item-sharing-options)
9. [Evaluating groups — group details](#9-evaluating-groups--group-details)
10. [Transferring items and groups](#10-transferring-items-and-groups)
11. [Course quiz answers](#11-course-quiz-answers)
12. [Cheat sheet & traps](#12-cheat-sheet--traps)

---

## 1. Finding items — making content discoverable

ArcGIS Online uses **two types of keywords** to make items discoverable: **search** and **filter**.

When publishing an item, fill out the item details completely: **title, summary, description, tags, categories**, and an attractive, representative **thumbnail**.

### Search
- A user's search query is compared against keywords in the item's **title, tags, or summary**.
- Use keywords **consistently** in tags and summaries so similar content is easier to find.

### Filters
Filters let users **refine search results** based on **tags, categories, and content status**.

| Filter | Details |
|---|---|
| **Tags** | Keywords you think people will search for. Can be added to **any item** (layers, maps, apps, groups) and **can be edited**. They boost search results. |
| **Categories** | Help members discover maps, scenes, apps, and other content. Used as a **filter** by thematic category. Can be configured for the **organization** and for content shared with specific **groups**. |
| **Status** | **Authoritative** → encourages the use of accurate, reliable items and makes them easier to find. **Deprecated** → discourages the use of out-of-date items but **keeps them available** as historical records. |

> ⚠️ Trap: a **deprecated** status does **not** prevent people from using an item. It only discourages it. A thumbnail does **not** boost an item to the top of search results.

---

## 2. Category sets

- **Administrators** and members with privileges to **manage categories** can configure categories for the **organization** or a **group**.
- Standard starting sets: **ArcGIS**, **ISO**, **INSPIRE**, or your own **Custom** categories.
- A **subcategory** can be added to any existing category, but **only the ArcGIS category set comes preconfigured with subcategories**.
- **All category sets can be customized.**
- To create a new category: **choose a category set, then add a category**.
- To assign a category to an item: use the **item page** to edit its categories.
- Key planning factor: consider the **longevity of the category**.

| Category set | Description | Example scenario |
|---|---|---|
| **ArcGIS** | Supports **ArcGIS Living Atlas of the World**. **Two tiers**: high-level general topics (e.g., *People*) + more specific **subcategories** (e.g., *Housing*). | Large municipality with **many items** that need more specific categorizing. |
| **ISO** (International Organization for Standardization) | Topic categories for describing and cataloging geographic information (e.g., *Biota, Oceans, Society*). **No subcategories.** | **Global** organization aligning with **international standards**. |
| **INSPIRE** | Spatial data themes from the **INSPIRE Directive**, which aims to create an **EU spatial data infrastructure** for **EU environmental policies** (e.g., *Hydrography, Land Use, Protected Sites*). **No subcategories.** | **International environmental** organization working with **European** spatial data. |
| **Custom** | Created by the administrator for the organization's own needs. | **Retail business** with unique content. |

> 🧠 Memory trick: **ArcGIS = Atlas + subcategories · ISO = International · INSPIRE = EU environment · Custom = unique**

---

## 3. Evaluating items — the item page

Each item has an **item page** organized by tabs. **The tabs available depend on the item type**, your **privileges**, and whether you are the **owner** or an **administrator**.

| Tab | Available for | What it contains / lets you do |
|---|---|---|
| **Overview** | **All items** | Description, tags, data source, **creation date**, **size**, **sharing status**, authoritative/deprecated status, **owner**. Includes an **Item Information** section that flags missing or incomplete metadata and suggests improvements (e.g., add tags or a summary). |
| **Data** | Only some items (e.g., **feature layers, table layers**) | View and work with the **attribute table**. The **layer owner or an administrator** can add a **field description** or a **new field**. |
| **Visualization** | Items that can be visualized (e.g., **feature layers**) | Change the layer's **default properties** without opening Map Viewer: **style**, **filter**, **pop-ups**, **labels**. |
| **Usage** | **Generally all items** | For owners and admins: gauges **popularity**. Number of **views, requests, or downloads** and the **average per day** for a selected time period. |
| **Settings** | **Only item owners and administrators** can see it | Change **extent**, attach code to apps, allow others to **save a copy**, enable **delete protection**, set status to **authoritative/deprecated**, enable/disable **feature editing**. |

### Typical scenarios
- Monitor an item's usage → **Usage**
- Identify who owns an item → **Overview**
- Choose the best month to update a layer → **Overview** (last update date) + **Usage** (views per day)
- Prevent a web map from being deleted → **Settings** (delete protection)

---

## 4. Creating groups — the 4 steps

A **group** is a collection of items, often related to a **region, subject, or project**.

Why use groups:
- **Organize** content so it's easier to find
- **Collaborate** on item creation and editing
- **Limit access** to an item to a specific set of members

### The 4 steps (always in this order)
1. **Define the group's purpose**: decide how and by whom the group will be used (**purpose + audience**). This tells you which settings to choose next.
2. **Set up the group**: name, summary, description, **tags** (searchability), who can **contribute content**, and who can **view/access** the group.
3. **Add members**: add them directly, **invite** them, or **require approval** of join requests. Admins can also allow **open access** (no invitation and no approval needed).
4. **Share items**: the group owner and managers share items and can allow others to share theirs. **Ownership does NOT change** when an item is shared with a group. By default, the **item's settings** determine how group members can use it (e.g., if editing is enabled, group members can edit).

> 🧠 **Purpose → Set up → Members → Items** ("**P**lease **S**et **M**y **I**tems")

---

## 5. Group membership settings

| Setting | What it controls | Things to consider |
|---|---|---|
| **Who can view this group?** | Who can **search for and discover** the group and view its details. Options: group members only / organization / everyone (public). | Is it for a specific project? Should org members discover it and request access? Is it public? |
| **Who can be in this group?** | **Your organization's members only**, or also members of **other organizations** (if they have privileges to join external groups). | Only org members? External members allowed? |
| **How can people join this group?** | **Invited** / **request to join** (approval) / **add themselves**. | Do you need to review requests? Is there a dedicated set of people? Can anyone join? |
| **Who can contribute content?** | **All group members**, or **only the group owner and managers**. | How much control do you need over shared items? |
| **Who can see the full list of members on the Members tab?** | **Everyone in the group**, or **only the group owner and managers**. | Do members need privacy? |

### Matching scenarios to settings
- **Confidential project**, private group → view: **group members only** + join: **invited only**
- Restrict membership to a **list of project team members** → **Require members to be invited**
- Ensure **only specific members** get access (police crime analysis example) → **Require group managers to approve membership requests**

---

## 6. Group designations

Configured by an **administrator**, or by a user with a **custom role** that has the administrative privilege to create groups with update capabilities.

| Designation | Meaning |
|---|---|
| **Shared update** | Members can **update items shared with the group**: both the **item details** and the **content**. Useful when several people must update the same item. |
| **Administrative group** | Members **cannot leave** the group unless the **group owner or a group manager removes them**. |
| **Open Data** | Groups that can be accessed in **Open Data sites**. Only available in organizations with **open data settings enabled**. |

---

## 7. Group roles

When a member is added to a group, they get a **group role**. For groups **without** shared update or administrative group options, the group roles a member can have depend on their **ArcGIS Online user role and privileges**.

| Group role | Description | Default user roles that can hold it |
|---|---|---|
| **Organization administrator** | Create, view, and modify **all groups** in the org; **reassign group ownership**. Only an admin can create and own groups that let members **update all items**. | Administrator |
| **Group owner** | **Complete access** to the group: settings, content, members. Usually the creator. | Administrator, Facilitator, Publisher, User |
| **Group manager** | Helps with ownership tasks: **invite users**, manage **membership requests**, remove **content and members**, edit **group properties**. | Administrator, Facilitator, Publisher, User |
| **Group member** | Can **only contribute** based on the settings the owner/manager chose (otherwise just accesses and uses content). | Administrator, Facilitator, Publisher, User, **Data Editor, Viewer** |

> ⚠️ **Viewer** and **Data Editor** can **only be group members**, never owners or managers.

---

## 8. Item sharing options

Items can stay unshared or be shared with **groups**, the **organization**, **everyone**, or a **combination**.

| Option | Who can access | Key points |
|---|---|---|
| **Only the owner** | Owner (+ **org administrators**) | The **default**. Does **not appear in search results** and is not part of any group. |
| **The owner and group members** | Owner + members of the selected group(s) | **Semiprivate**. You can share with groups you **own or manage**, or groups that **allow member contributions**. For a **private** group, members must be **logged in**. |
| **Your organization and group members** | All org members, highlighted for a specific group | Only the org gets access, but the content is featured in a group. Group owners/managers can share **org-shared items** with their groups. |
| **Everyone and group members** | The public + the group | Requires being an **administrator**, or the org setting that allows **non-admins to share publicly**. Group owners/managers can share **publicly shared items** with their groups. |

### Scenarios
- Web map with **fieldworker home locations**, viewable only by the fieldworkers group, which must be private → **The owner and group members**; group viewable by **only group members**; joining by **invitation from the group owner only**.
- A **Fire Department group** uses an item a lot, but **others in the org** also need it → **Your organization and group members**.
- Feature layer shared with "owner + Education group", group viewable only by members → visible to **the item owner and group members**.

---

## 9. Evaluating groups — group details

Like an item page, **group details** show who owns the group, who can view it, how many members it has, etc.

| Section | Contents / actions |
|---|---|
| **Overview** | Description, **your role**, **creation date**, **owner**, **who can view the group** (e.g., check that a group is viewable by everyone). Share the group (if you have permissions) or **leave** it. |
| **Content** | Items shared with the group. Find them by changing **viewing options**, **keyword search**, **filters** (item type, location, date modified, tags, how shared), and **sorting** (title, owner, view count, date modified, date added; A–Z or Z–A). Then view details, open in apps, or **remove from group**. |
| **Members** | List of members, sortable by **name, group role, date joined**. Owners, managers, and admins can **invite** members, **update group roles**, **transfer group ownership**, and **remove** members. |
| **Settings** | Admins, owners, and managers adjust properties anytime: **member access**, **type of items displayed**, **delete protection** for the group. |

Reasons to evaluate a group: **change ownership**, **review its content**.

---

## 10. Transferring items and groups

### Reasons to transfer ownership
| Situation | What to do |
|---|---|
| **Member leaves the organization** | Delete the member so the **user type can be reassigned**. Best practice order: **1) Disable access → 2) Transfer items & groups → 3) Delete member**. |
| **Member changes positions** | They may no longer need access; transfer their content and groups, then delete them to **free a spot** for a new member. |
| **New member joins** | Transfer items/groups so they have **complete access** to the project material they take over. |
| **Project changes** | Transfer to the correct member, who then decides what to do with project content and groups. |

> 🧠 **D-T-D: Disable → Transfer → Delete**

### How to transfer
- **Items**: **select the item's owner**, then **transfer item ownership** to one or multiple members.
- **Groups**: **select the group** and **assign a new owner**.
- The **new owner must have the privileges** to own items/groups (join, create, own groups; for shared update groups, the matching privilege).

### Group ownership privileges by default role
| Privilege | Viewer | Data Editor | User | Publisher | Facilitator | Administrator |
|---|:-:|:-:|:-:|:-:|:-:|:-:|
| **Create and own groups** | ❌ | ❌ | ✅ | ✅ | ✅ | ✅ |
| **Create and own shared update groups** | ❌ | ❌ | ❌ | ❌ | ✅ | ✅ |

- Anyone with the **Administrator** role can create and own a **shared update group**.
- To let **non-admins** do it, create a **custom role** with the **Create With Update Capabilities** administrative privilege for groups. *(The course table also checks Facilitator.)*

---

## 11. Course quiz answers

### Quiz — Finding items
1. Assign a category to a specific item → **Use the item page to edit the category assigned to the item**
2. Create a new category → **Choose a category set, and then add a category**
3. INSPIRE describes → **Organizing geographic info aligned with the EU spatial data infrastructure and environmental policies**
4. Two ways to make items more discoverable → **Adding search keywords to title, tags, and summary** + **Applying tags that can filter search results**
5. Factor to consider when setting up categories → **Longevity of the category**

### Quiz — Evaluating items
1. Two reasons to review an item page → **Monitor usage** + **Identify item ownership**
2. Best month to update a trails layer → **Overview details (date of last update)** + **Usage information (views per day)**
3. Make sure a web map isn't deleted by someone else → **Settings** tab

### Quiz — Creating groups (scenario: local government)
1. Sharing option for the fieldworker web map → **The owner and group members**
2. Who should view the group → **Only group members**
3. Who should join → **Only individuals invited by a group owner**

### Quiz — Creating groups
1. Role that can only access/use content unless allowed to contribute → **Group member**
2. Fire Department group + rest of org needs access → **Your organization and group members**
3. Steps to create a group → **Define purpose, set up the group, add members, share items**
4. "Who can view a group" setting → **Defines who is able to search for and discover a group**
5. Police chief: only specific members have access → **Require group managers to approve group membership requests**
6. Feature layer shared to "owner + Education group" (members-only group) → **The item owner and group members**
7. Restrict members to a project team list → **Require members to be invited**

### Quiz — Evaluating groups
1. Verify the group is viewable by everyone → **Overview**
2. Why members-only + invitation required → **The group content for a specific project is confidential**
3. Two reasons to evaluate a group → **Change ownership of the group** + **Review content in the group**

### Quiz — Transferring items and groups
1. Transfer content ownership → **Select the item's owner, then transfer item ownership to one or multiple members**
2. Transfer group ownership → **Select the group to transfer and assign a new owner**
   *(⚠️ Your document highlights two different answers for this question in two places. Based on the course content, the correct one is "Select the group and assign a new owner": transferring the items doesn't transfer the group.)*
3. Two default roles that can create and own groups → **User** + **Publisher**
4. Member who owns groups leaves → **Disable access, transfer items and groups, then delete the member**

---

## 12. Cheat sheet & traps

| I want to… | Answer |
|---|---|
| Know which fields search looks at | **Title, tags, summary** |
| Filter search results | **Tags, categories, status** |
| Mark reliable content | **Authoritative** status |
| Discourage old content but keep it | **Deprecated** status |
| Category set with subcategories out of the box | **ArcGIS** (only one) |
| Align with international standards | **ISO** |
| Align with EU environmental policy | **INSPIRE** |
| Find missing metadata suggestions | Item page → **Overview → Item Information** |
| Add a field or field description | Item page → **Data** (owner or admin) |
| Change style/pop-ups/labels without Map Viewer | Item page → **Visualization** |
| See views/requests/downloads per day | Item page → **Usage** |
| Enable delete protection / editing / save a copy | Item page → **Settings** (owner/admin only) |
| Let several people edit the same items | **Shared update** group |
| Stop members from leaving a group | **Administrative group** |
| Use a group in Open Data sites | **Open Data** group (requires open data settings) |
| Default sharing for a new item | **Only the owner** (+ admins) |
| Share publicly as a non-admin | Requires the org setting that allows **non-admins to share publicly** |
| Invite members, change roles, transfer group ownership | Group → **Members** tab |
| Order when a member leaves | **Disable → Transfer → Delete** |

### ⚠️ Common traps
- Sharing an item with a group **does not change ownership**.
- **Deprecated ≠ blocked**: items stay available.
- A **thumbnail** helps people recognize an item; it doesn't change search ranking.
- **Viewer** and **Data Editor** can't create or own groups.
- The **Settings** tab of an item page is visible **only to owners and admins**.
- The **Data** tab only exists for certain items (feature layers, table layers).
- Items shared **only with the owner** don't appear in search results.
