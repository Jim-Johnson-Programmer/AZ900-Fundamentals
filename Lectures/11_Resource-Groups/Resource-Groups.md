# Resource Groups

A resource group is a logical container for Azure resources. It helps organize related resources so they can be managed together.

## Key Characteristics

- A resource can belong to only one resource group at a time.
- Resource groups can contain resources from different regions.
- Actions such as access control, tagging, and policy can be applied at this level.

## Why They Matter

- Simplify organization by application, environment, or team.
- Help manage lifecycle for related resources.
- Support governance and cost tracking.

## Common Grouping Patterns

- One resource group per application.
- One resource group per environment, such as dev or prod.
- One resource group per business unit or project.

## Exam Focus

- A resource group is not the same as a subscription.
- Resources can be moved between resource groups in some cases.
- Deleting a resource group deletes the resources inside it.
