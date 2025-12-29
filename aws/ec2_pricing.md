# Amazon EC2 — Pricing & Billing Options

## Big Question
“How much does EC2 cost?”

Answer: **It depends on how you choose to pay.**  
EC2 offers multiple pricing models so you can balance **flexibility, cost, and predictability**.

---

## On-Demand Instances
**Pay only for what you use.**

- Billed per second(ct) or per hour (depending on instance & OS)
- No upfront payment
- No long-term commitment
- Start and stop anytime

### Best For
- Getting started with AWS
- Testing and experimentation
- Short-term or unpredictable workloads

---

## Savings Plans
**Commit to usage, get major discounts.**

- Commit to a consistent spend (USD/hour)
- Term lengths: **1 year or 3 years**
- Savings of **up to 72%**
- Applies across:
  - Instance families
  - Instance sizes
  - Operating systems
  - AWS Regions
- Also applies to:
  - AWS Fargate
  - AWS Lambda

### Best For
- Long-running workloads
- Flexible architectures
- Teams confident about baseline usage

---

## Reserved Instances (RIs)
**Predictable workloads, predictable savings.**

- Commit for **1 year or 3 years**
- Discounts of **up to 75%** vs On-Demand
- Three payment options:
  - All upfront
  - Partial upfront
  - No upfront

### Best For
- Steady-state workloads
- Known, consistent capacity needs

---

## Spot Instances
**Massive savings, but interruptible.**

- Up to **90% cheaper** than On-Demand
- Uses spare AWS capacity
- AWS can reclaim instances anytime
- **2-minute interruption warning**

### Best For
- Fault-tolerant workloads
- Batch processing
- Data analysis
- CI/CD jobs
- Non-critical compute tasks

---

## Dedicated Hosts
**Physical servers for exclusive use.**

- Entire physical server reserved for one customer
- No multi-tenancy
- Full control over:
  - Instance placement
  - Resource allocation

### Best For
- Compliance or regulatory requirements
- Security-sensitive workloads
- Licensing constraints (e.g., Windows, SQL Server)

---

## Choosing the Right Option
| Workload Type | Recommended Pricing |
|---------------|---------------------|
| Experimentation | On-Demand |
| Predictable usage | Reserved Instances |
| Flexible long-term usage | Savings Plans |
| Interruptible workloads | Spot Instances |
| Compliance-heavy workloads | Dedicated Hosts |

---

## Key Takeaways
- EC2 pricing is **usage-based and flexible**
- Bigger discounts require longer commitments
- Not one-size-fits-all — match pricing to workload behavior
- You can mix pricing models within the same architecture

## Bottom Line
EC2 pricing lets you **optimize for flexibility, savings, or control**—as long as you understand your workload patterns.
