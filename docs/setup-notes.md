# Setup Notes – Microsoft Entra ID IAM Lab

## Environment
- Tenant: Microsoft Entra ID (Free)
- Purpose: Identity and access management lab
- Scope: Tenant-level IAM + Azure RBAC

## Users Created
- Alice IT – IT Analyst (assigned to IT-Admins, RBAC applied.)
- Bob HR – HR Analyst (assigned to HR group, RBAC applied)
- Michael Finance – Finance Manager (created, not yet assigned)

## Groups
- IT-Admins (Security group) - configured
- HR (Security group) - configured
- Finance (planned)

## Access Model
- Users assigned to security groups
- RBAC applied to groups (not individuals)
- Incremental rollout by role/function

## RBAC Assignments
- Reader role assigned via Azure RBAC
- Applied to:
  - IT-Admins group
  - HR group
- Scope: This resource
- Model: Group-based (no direct user assignments)


## Next Steps
## Next Steps
- Create Finance security group
- Assign appropriate RBAC role to Finance group
- Add Michael Finance to Finance group
- Validate sign-in and effective permissions


