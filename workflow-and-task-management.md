# Workflow and Task Management

## Purpose

This guide outlines how to plan, execute, and report on tasks effectively. It complements our culture and expectations by focusing specifically on execution strategy, delivery habits, and workflow systems that improve velocity and clarity.

---

## Task Lifecycle Framework

### 🧭 Plan First

**Do:**

* Break down large tasks into subtasks or phases.
* Clarify business goals, inputs, and dependencies.
* Identify unknowns or risks early.
* Write down assumptions and confirm them.

**Don't:**

* Start based on rough understanding.
* Wait until the task is overdue to raise questions.

**Example:** \
✅ Good: "For the invoice module, I’ll start with schema design, then API, then UI. Blocked on email template spec." \
❌ Bad: "Started coding invoice feature — unsure how totals should be calculated."

---

### 🛠 Make It Work (First)

**Do:**

* Focus on delivering basic functionality quickly.
* Prioritize correctness and completeness.
* Leave inline TODOs for future improvements.

**Don't:**

* Over-refactor without validation.
* Block the team with polish before function.

**Example:** \
✅ Good: "Checkout works with test card. UX is rough — improving in next phase." \
❌ Bad: "Spent two days animating buttons — backend integration still pending."

---

### 🎨 Make It Nice

**Do:**

* Polish UX once flow is validated.
* Follow design system and accessibility.
* Improve error messages, visual feedback.

**Don't:**

* Skip validation or feedback just to "make it look done."
* Spend too long on nice-to-have styling.

**Example:** \
✅ Good: "Added error states, form validation, responsive layout." \
❌ Bad: "Only tested layout on desktop — input error is just console.log."

---

### 🚀 Make It Fast

**Do:**

* Measure before optimizing.
* Address top pain points in performance.
* Share metrics for improvements.

**Don't:**

* Obfuscate code for premature speed gains.
* Optimize areas users don't even hit.

**Example:** \
✅ Good: "Search went from 4s to 0.8s by indexing and limiting payload." \
❌ Bad: "Split functions aggressively for reuse, made it unreadable."

---

## Task Status Updates

### 📌 Use the 4-Point Structured Update

**Recommended Format:**

```
[Ticket ID/Name]
Status: [To Do / In Progress / Blocked / Review / Done]
ETA: [Target completion date or range]
Blockers: [If any — name + reason. If none, say "None"]
```

**Do:**

* Update in threads, project boards, or standup logs.
* Use specific language and dates.

**Don't:**

* Use unclear language like "almost done" or "should be ok"
* Hide delays or blockers

**Examples:** \
✅ Good:
```
[FE-112: Update Product Listing Page]
Status: In Progress
ETA: Friday EOD
Blockers: Waiting for final product card design from UX (requested Tuesday)
```

❌ Bad:
```
"Still working on it — will update later."
```

---

## Task Ownership

### 🎯 Be the Driver, Not the Passenger

**Do:**

* Own every step: planning → building → testing → shipping.
* Follow up with QA, DevOps, or PMs as needed.
* Close the loop — confirm the task is used and working.

**Don't:**

* Stop at "code complete."
* Let blockers sit without escalation.

**Example:** \
✅ Good: "Fix merged, tested in staging, and validated with QA — good to deploy." \
❌ Bad: "Code’s there, didn’t check the actual behavior after deploy."

---

## Task Breakdown & Visibility

### 🔍 Break Work Down

**Do:**

* Split tickets by component (API, UI, tests).
* Label sub-tasks visibly (Jira, Notion, Linear).
* Track progress transparently for all team members.

**Don't:**

* Let one task cover 3+ days of unclear work.
* Hide sub-work in your head or personal notes.

**Example:** \
✅ Good: "Login upgrade = backend JWT, frontend token sync, and session expiry UI" \
❌ Bad: "Doing the whole login update myself — will check in later."

---

## Final Reminders

* Plan thoroughly, but iterate fast.
* Start with correctness, end with polish.
* Be specific, visible, and proactive in updates.
* Your work is only complete when it’s tested, shipped, and adopted.

This is a tactical companion to the culture document — revisit it when taking on new work or preparing for handoff.
