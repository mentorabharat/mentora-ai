# Block-09 Lock Decisions

This document records final canonical architecture decisions
approved during Phase-2 mapping.

## LOCK-1: Exams as Independent Canonical Root

Decision:
- Exams will NOT be a sub-node of education.
- Exams exist as a separate canonical pillar.

Reason:
- Exams are time-bound, policy-driven, and country-specific.
- Education is lifelong and concept-based.
- Separation prevents future architectural rewrites.

Status: LOCKED 🔒

---

## LOCK-2: IT as Independent Canonical Pillar

Decision:
- IT learning is NOT treated as a traditional education stream.
- IT exists as an independent canonical pillar.

Reason:
- IT is skill + practice + employability driven.
- Requires theory + practical + tools + projects.
- Enables future job, income, and hiring integrations.

Status: LOCKED 🔒

---

## Canonical Root (Final)

mentora
 ├── education
 ├── exams
 ├── it
 ├── languages
 └── meta

These decisions are permanent and cannot be altered
in Phase-3 or future phases.

Approved By: Founder (Human Authority)
Phase: 2
