# Azure Management Groups

Management groups are a governance layer above subscriptions in Azure. They help organizations apply policies, access control, and standards across multiple subscriptions at once.

## Why They Matter

- Large organizations often have many subscriptions.
- Repeating the same governance setup across each subscription is inefficient.
- Management groups allow inheritance of policy and RBAC from higher scopes.

## Hierarchy Placement

- Tenant root group sits at the top.
- Management groups can contain other management groups or subscriptions.
- Subscriptions contain resource groups and resources.

## Exam Focus

- Management groups are for governance at scale.
- They are above subscriptions in the Azure hierarchy.
- Policies and permissions can inherit downward from them.
