# Public and Private Endpoints

Azure services can often be reached through public endpoints or private endpoints. The difference affects exposure, routing, and security design.

## Public Endpoints

- Accessible over the public internet.
- Simpler to enable and useful for broad access.
- Usually require strong identity, firewall, and network controls.

## Private Endpoints

- Provide private connectivity using an Azure virtual network.
- Keep traffic off the public internet path.
- Useful for sensitive workloads and stricter network isolation.
- Cloud has concepts of virtual private networks (VNet) and subnets to manage private endpoints. Endpoints are not visible outside the VNet unless explicitly routed.

## Why This Matters

- Endpoint choice affects security posture.
- Private endpoints support zero-trust and internal-only access patterns.
- Public access may be appropriate when external users or services need reachability.

## Exam Focus

- Public means internet reachable.
- Private endpoint means private IP based access from a virtual network.
- Private connectivity is generally preferred for higher security requirements.
