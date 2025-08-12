# Identity and Access Management (IAM)

IAM controls who can access AWS resources and how.

## Users
- Individual identities with credentials
- Used for human access (e.g., developers, admins)

## Groups
- Collection of users
- Attach policies to groups for easier management

## Roles
- Temporary access with defined permissions
- Used for services or cross-account access

## Policies
- JSON documents defining permissions
- Attached to users, groups, or roles
- Types: Identity-based and Resource-based

Best Practice: Use roles for applications and services, not long-term credentials.