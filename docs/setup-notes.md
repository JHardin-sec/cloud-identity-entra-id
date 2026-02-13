# Setup Notes – Microsoft Entra ID IAM Lab

## Environment
- Tenant: Microsoft Entra ID (Free)
- Purpose: Identity and access management lab
- Scope: Tenant-level IAM + Azure RBAC

## Users Created
- Alice IT – IT Analyst (configured)
- Bob HR – HR Analyst (created, not yet assigned)
- Michael Finance – Finance Manager (created, not yet assigned)

## Groups
- IT-Admins (Security group)
- HR (planned)
- Finance (planned)

## Access Model
- Users assigned to security groups
- RBAC applied to groups (not individuals)
- Incremental rollout by role/function

## RBAC Assignment (Completed)
- Role: Reader
- Assigned to: IT-Admins group
- Scope: This resource

## Next Steps
- Create HR and Finance security groups
- Assign appropriate RBAC roles per group
- Enforce least-privilege access model

