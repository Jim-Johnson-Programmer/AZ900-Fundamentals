# Management Groups

Management groups provide a governance layer above subscriptions. They help apply policies and access control across multiple subscriptions at scale.

## Why Use Management Groups

- Standardize governance across many subscriptions.
- Apply Azure Policy and RBAC inheritance broadly.
- Organize subscriptions by business unit, geography, or environment.

## Hierarchy

- Tenant root group sits at the top.
- Management groups can contain child management groups or subscriptions.
- Policies and permissions can inherit downward.

## Common Scenarios

- Separate production and non-production subscriptions.
- Apply security standards across an entire organization.
- Delegate administration by department.

## Exam Focus

- Management groups are above subscriptions.
- They are used for governance, not for directly deploying resources.
- Inheritance is a major concept to remember.
