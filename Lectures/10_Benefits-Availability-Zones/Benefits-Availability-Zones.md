# Benefits of Availability Zones

Availability zones are physically separate datacenters within an Azure region. They are designed to provide protection from datacenter-level failures while keeping workloads in the same general regional area.

## What They Provide

- Fault isolation for power, cooling, and networking failures.
- Higher resiliency within a region.
- Support for zone-redundant architectures.

## Typical Benefits

- Improved uptime.
- Better support for mission-critical workloads.
- Reduced impact from a single datacenter outage.

## Design Considerations

- Not all regions support availability zones.
- Some services are zonal while others are zone-redundant.
- Higher resiliency can increase complexity or cost.

## Exam Focus

- Availability zones exist inside a region.
- They are different from regions and from region pairs.
- Their purpose is to improve resiliency against localized failures.
