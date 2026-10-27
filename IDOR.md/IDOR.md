# IDOR and Broken Access Control

## Overview
Broken Access Control occurs when an application does not properly enforce restrictions on what users can access or do. IDOR (Insecure Direct Object Reference) is one example of this vulnerability.

## Learning Objectives
- Understand how IDOR vulnerabilities occur.
- Learn to test whether users can access resources belonging to other users.
- Understand the importance of server-side authorization checks.

## Testing Approach
- Review how the application references specific resources.
- Test access controls in an authorized training lab.
- Observe whether the application properly restricts access to other users' resources.

## Mitigation
- Enforce authorization checks on the server side.
- Verify that each user is permitted to access the requested resource.
- Do not rely on unpredictable identifiers alone as an authorization mechanism.

## Practice Environment
PortSwigger Web Security Academy: https://portswigger.net/web-security/access-control

All testing should be performed in authorized labs or environments where permission has been granted.
