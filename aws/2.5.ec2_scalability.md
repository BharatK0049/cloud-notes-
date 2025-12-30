# EC2 — Scalability, Elasticity & High Availability

## Context
EC2 instances run workloads such as:
- Handling web requests
- Processing data
- Hosting applications

---

## Core Concepts

### Scalability
- Ability to **increase or decrease capacity** as business needs change
- Handles growth and seasonal or cyclical traffic

### Elasticity
- Ability to **automatically match capacity to demand**
- Scale up during peaks, scale down during lows
- Avoids overprovisioning and underutilization

---

## The Capacity Problem
- Average usage ≠ peak usage
- Peaks may be:
  - Short-lived
  - Unpredictable
  - Unknown (new business)
- Planning for peak = expensive
- Planning for average = risky

**Goal:**  
> Exact capacity, at the exact time it’s needed

---

## AWS Solution: Redundancy + Automation

### Redundant EC2 Instances
- Run **multiple instances** of the same role
- If one instance fails, another continues serving traffic
- No single point of failure

### High Availability Design
- Deploy instances across **multiple Availability Zones**
- If one AZ fails, others handle the load
- Backend services must also be redundant

---

## Resulting Benefits
- Continuous service availability
- Fault tolerance
- Cost efficiency
- Customer satisfaction
- Operational resilience

---

## Best Practices
- Never rely on a single EC2 instance
- Always deploy redundant instances
- Distribute across multiple AZs
- Prepare infrastructure to scale with demand

---

## Key Takeaway
**High availability handles failures.  
Elasticity handles demand changes.**

Together, they ensure:
- Reliability
- Scalability
- Cost control
