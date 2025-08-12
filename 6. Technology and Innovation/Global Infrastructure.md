# AWS Global Infrastructure

## Regions
- Geographically isolated areas (e.g., us-east-1)
- Each region contains multiple Availability Zones
- Enables data residency and latency control

## Availability Zones (AZs)
- Physically separate data centers within a region
- Connected via low-latency links
- Designed for fault isolation and high availability

## Edge Locations
- Part of AWS Global Content Delivery Network (CDN)
- Used by services like CloudFront and Route 53
- Improves latency for end users

 Example: Deploying across multiple AZs ensures high availability; using Edge Locations speeds up content delivery.