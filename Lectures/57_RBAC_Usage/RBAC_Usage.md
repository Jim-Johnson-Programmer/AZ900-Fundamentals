# RBAC Usage

Azure role-based access control, or RBAC, is used to manage who can perform actions on Azure resources. It is Azure's main authorization model for resource access.

## Core Ideas

- Roles define allowed actions.
- Assignments apply roles to users, groups, or identities.
- Scope determines where the permissions apply.

## Common Scopes

- Management group
- Subscription
- Resource group
- Individual resource

## Exam Focus

- RBAC is for authorization.
- Least privilege is a key best practice.# RBAC Usage

Role-based access control, or RBAC, is how Azure grants permissions to users, groups, service principals, and managed identities. Access is assigned through roles at different scopes.

## Core Parts

- Security principal.
- Role definition.
- Scope.

## Scopes

- Management group.
- Subscription.
- Resource group.
- Resource.

## Exam Focus

- RBAC controls what actions identities can perform.
- Broader scopes inherit downward.
- Follow least-privilege principles when assigning roles.
