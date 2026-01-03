# SLA Concepts & Terminology

This document provides a concise overview of the most important concepts
used in Service Level Agreements (SLAs) and IT Service Management.

---

## Service Level Agreement (SLA)

A Service Level Agreement defines measurable service expectations between
a service provider and a customer. It specifies performance targets,
responsibilities, and consequences in case of non-compliance.

---

## Service Level Indicator (SLI)

A Service Level Indicator is a measurable metric used to evaluate service
performance, such as availability, latency, or error rate.

---

## Service Level Objective (SLO)

A Service Level Objective defines the target value for a specific SLI.
Example: *99.9% monthly availability*.

---

## Key Performance Indicator (KPI)

KPIs are operational metrics used to monitor service performance and
process efficiency. KPIs support SLA compliance but are not always
contractually binding.

---

## Availability vs. Reliability

- **Availability** measures whether a service is accessible.
- **Reliability** measures how consistently a service performs without failures.

Both aspects must be considered when defining service quality.

---

## MTTR & MTBF

- **MTTR (Mean Time to Repair):** Average time required to restore a service.
- **MTBF (Mean Time Between Failures):** Average time between service failures.

These metrics are commonly used in incident and reliability management.

---

## Incident & Priority Levels

An incident is an unplanned interruption or reduction in service quality.
Incidents are typically classified by priority, based on impact and urgency.

---

## Escalation

Escalation defines the process of transferring incidents to higher support
levels when resolution targets are at risk.

---

## Shared Responsibility Model

Responsibilities differ depending on the cloud service model:

- **SaaS:** Provider manages application and infrastructure
- **PaaS:** Shared responsibility
- **IaaS:** Provider manages infrastructure, customer manages systems and software

SLAs must reflect these responsibility boundaries.

---

## SLA vs. OLA vs. UC

- **SLA:** Agreement between provider and customer
- **OLA:** Internal agreement between service teams
- **UC:** Agreement with external suppliers
