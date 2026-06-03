# Majorcentre
Based on everything we've built in this session, here's a concise manager update:

---

**Subject: SRS Enhancement Update — Major Centre (MC) Feature**

---

**Background**

Major Centres (MCs) were previously tracked under Areas, meaning Area users managed MC data. As MCs are now independent entities managed at Zone level, the system required structural changes to reflect this.

---

**What Changed & Why**

**1. Major Centre Master (New)**
A dedicated MC Master has been introduced under Masters, separate from Beas Master. This includes Major Centres, MC Departments, MC Sewa Names, and MC Periods — all independent from their Beas equivalents. *Reason: MCs are no longer associated with Areas and needed their own data structure.*

**2. Period Manager — Beas / MC Toggle**
The existing Period Manager now has a toggle to switch between setting periods for Beas and Major Centre independently. Both maintain separate period calendars with the same 5 period types, clearly labelled. *Reason: MC operations run on different period schedules than Beas.*

**3. Sewa Requirement — Area + MC Grouped Dropdown**
The Area dropdown in Add Sewa Requirement now includes all 11 Major Centres under a separate "Major Centres" group header. *Reason: Since MCs are now Zone-level, the Zonal Admin needed a way to add sewa requirements directly for MCs, not through Areas.*

**4. Sewa Destination Toggle (Beas / Major Centre)**
Both the Sewa Requirement and Create Sewa screens now have a destination toggle. Selecting "Major Centre" switches departments, periods, and data to MC-specific options and tags the record accordingly. *Reason: Sewadars can now be assigned to either Beas or an MC, and reports need to differentiate between the two.*

**5. Consolidated Report — List Type Filter Enhanced**
The List Type filter in Consolidated Reports now offers three options: **Beas**, **Major Centre**, and **All** — replacing the previous Beas-only option. Selecting Major Centre also switches the Area filter to a Major Centre selector and updates department options. *Reason: ZOs needed visibility into MC sewa data in reports, separately from Beas data.*

**6. Visibility & Access Control**
All MC-related screens and data are restricted to Zonal Admin, Zonal Coordinator, and Local Zonal Users only. Area, State, and Centre users have no access to MC data. *Reason: MC management is a Zone-level responsibility.*

---

**Scope**

---

Want me to convert this into a formal Word document or email format for sending?
