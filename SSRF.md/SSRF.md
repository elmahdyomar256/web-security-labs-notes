# Server-Side Request Forgery (SSRF)

## Overview
SSRF is a web application vulnerability that can occur when an application fetches a URL or resource supplied or influenced by a user without sufficient validation.

## Learning Objectives
- Understand how SSRF vulnerabilities occur.
- Learn how applications process server-side requests.
- Understand the potential security impact of unsafe URL handling.

## Testing Approach
- Identify application features that fetch external URLs or resources.
- Test URL handling in an authorized training lab.
- Observe whether the server makes requests to unintended destinations.

## Potential Impact
Depending on the application and its environment, SSRF may expose internal services or allow unintended server-side requests.

## Mitigation
- Validate and restrict permitted destinations.
- Block access to sensitive internal services and network ranges.
- Apply network-level controls and safely handle redirects.

## Practice Environment
PortSwigger Web Security Academy: https://portswigger.net/web-security/ssrf

All testing should be performed in authorized labs or environments where permission has been granted.
