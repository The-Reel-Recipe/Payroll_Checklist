# Payroll Checklist — Handoff

**What this is:** an interactive checklist for running the monthly payroll close, for HR.
Open **`Payroll Checklist.html`** in any browser (double-click). Works offline, on Mac or
Windows. Tap a step to see the how-to; tap the circle on the right to check it off.
Progress saves in that browser. Ctrl / ⌘ + P prints it.

Last updated **2026-08-24**.

---

## The run — 9 steps, 3 phases

**Before the run (last day or two)**
1. **Everything's approved** — managers approve OT / Leaves / KPIs (HR only checks & chases, in *My Team*); **HR** approves the *Bonuses, advances & penalties* page.
2. **Set up the Working Days Calendar** — holidays, closures, late-opening grace.
3. **Check every leaver's exit date** — set *Termination Date* first, **then** tick *Contract Terminated*.
4. **Import the attendance** — open the **TRR Attendance** page, click **Update attendance**.

**Check the payslips (from the 1st — they build automatically)**
5. **Everyone has a payslip** — commission + payslips are generated automatically on the 1st.
6. **Clear every blocker** — set a payslip to *Under Review*; a problem one turns *Blocked* and shows what's wrong. Fix the cause; it clears itself.
7. **Totals look right** — quick look down Net Pay.

**Approve & pay (one-way — the point of no return)**
8. **Approve** — freezes the figures (snapshot). Nothing is sent yet.
9. **Mark Paid** — emails the employee their breakdown. Only after the money is actually out.

---

## Key facts baked into the wording (don't undo these)

- **HR works only from the Interface**, never the raw data tables.
- **Leaves & KPIs** are approved by managers in **My Team**, not in the Payroll interface.
- **The attendance importer is a web page** ("TRR Attendance") with an **Update attendance** button — not a double-click tool, and not "Import to Airtable".
- **Commission + payslip generation run automatically on the 1st.** There is no manual run step anymore.
- **A payslip only reveals its blockers after it's set to Under Review.**
- **Termination: date first, then the tick** — ticking with an empty date stamps today.
- The payslip **email is what "Paid" sends** — for the first live month it's switched on last.

---

## Updating the screenshots

The 5 images live in the **`Screenshots/`** folder next to the HTML:

| File | Step it appears in |
|---|---|
| `ss01.png` | 1 · Approvals (Overtime to approve, Pending) |
| `ss02.png` | 2 · Working Days Calendar |
| `ss04.png` | 4 · TRR Attendance page |
| `ss08.png` | 6 · Payslips (Needs fixing) |
| `ss10.png` | 9 · Payslip Status options |

To refresh one, replace the file **keeping the same name**. It appears automatically —
no code change. (Keep the folder named `Screenshots` with a capital S.)

To change wording or steps, edit the HTML directly — each step is one `<li class="task">`
block; the short line is `<span class="s">`, the how-to is inside `<div class="how">`.

---

## Where the source lives

Master copy: `D:\TheReelRecipe\TRR HTMLS\Payroll_Monthly_Run_Checklist.html`
This folder is a shareable bundle of that file + its screenshots.
