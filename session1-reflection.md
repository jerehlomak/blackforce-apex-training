# Session 1 Reflection

## 1. What is multi-tenancy and why does it mean Apex has governor limits?

Multi-tenancy in Salesforce means that multiple customers (tenants) share the same infrastructure, including servers, databases, and resources. Because all organizations run on the same platform, Salesforce must ensure that no single tenant consumes excessive resources. This is why Apex has governor limits, which restrict things like CPU time, number of queries, and records processed. These limits maintain performance, fairness, and stability across all users on the platform.

---

## 2. What is the difference between declarative and programmatic customisation? Give one real example of each.

Declarative customization involves using point-and-click tools in Salesforce to build features without writing code, while programmatic customization involves writing code such as Apex or Lightning Web Components. Declarative tools include Flow, Process Builder, and validation rules. A real example of declarative customization is creating a validation rule to ensure a phone field is not blank. A programmatic example is writing an Apex trigger to automatically update related records when a new record is created.

---

## 3. Why do we use Git and source control for Salesforce development instead of making changes directly in the org?

Git and source control are used to track changes, collaborate with teams, and maintain a history of all modifications made to the codebase. Working directly in the org can lead to untracked changes, conflicts, and difficulty in managing deployments. With Git, developers can work on feature branches, review changes, and safely merge updates into the main codebase. It also enables rollback to previous versions if something breaks, which is critical for maintaining system stability.