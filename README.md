# Cloud-Based Identity & Access Management using Microsoft Entra ID

## Overview
This project demonstrates cloud-native identity and access management using Microsoft Entra ID.
The lab focuses on user provisioning, group-based access control, role-based access control (RBAC),
and SOC-relevant identity monitoring in a modern cloud environment.

## Objectives
- Implement centralized cloud identity management
- Provision and manage users and groups
- Enforce least-privilege access using Azure RBAC
- Monitor authentication and identity-related events
- Generate artifacts relevant to SOC investigations

## Architecture
- Platform: Microsoft Azure
- Identity Provider: Microsoft Entra ID (Free Tier)
- Access Control: Azure RBAC (Resource Group scope)
- Logging: Entra ID Sign-in Logs and Audit Logs
- Environment Type: Lab / Non-production

## SOC Relevance
This project mirrors real SOC workflows by focusing on:
- Identity-based attack detection
- Authentication failures and sign-in analysis
- Privilege escalation via role assignments
- Audit trails for user and access changes

## Tools Used
- Microsoft Azure
- Microsoft Entra ID
- Azure RBAC
- Entra ID Sign-in & Audit Logs
