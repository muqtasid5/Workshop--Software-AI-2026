# Open Issues - Release 2.4.0
 
## Release Overview
 
The Release 2.4.0 is scheduled for deployment on Friday. The following open issues have been identified during testing and validation activities. The release management team must review these issues and determine whether the release is ready for production.
 
---
 
## Open Issues
 
### BUG-101
**Severity:** Critical
**Status:** Open
**Component:** Authentication
 
Users are randomly logged out during active sessions. Unsaved changes may be lost, resulting in poor user experience and potential data loss.
 
---
 
### BUG-102
**Severity:** Major
**Status:** Open
**Component:** API Gateway
 
API requests occasionally return HTTP 500 errors under moderate load conditions, affecting system reliability.
 
---
 
### BUG-103
**Severity:** Minor
**Status:** Open
**Component:** User Interface
 
The dashboard title is truncated on screens with resolutions below 1366x768 pixels.
 
---
 
### BUG-104
**Severity:** Major
**Status:** In Progress
**Component:** Reporting
 
Monthly reports fail to generate when users select a date range exceeding 12 months.
 
---
 
### BUG-105
**Severity:** Critical
**Status:** Open
**Component:** Payments
 
Duplicate payment transactions can be created when users refresh the checkout page during payment processing.
 
---
 
### BUG-106
**Severity:** Minor
**Status:** Open
**Component:** Notifications
 
Email notification templates contain formatting inconsistencies and excessive whitespace.
 
---
 
### BUG-107
**Severity:** Major
**Status:** Resolved
 
**Component:** Search
 
Recently created records were not appearing in search results. A fix has been implemented and is awaiting verification.
 
---
 
### BUG-108
**Severity:** Medium
**Status:** Open
**Component:** Logging
 
Detailed internal error information is written to logs that are accessible by support staff, creating a potential security concern.
 
---
 
### BUG-109
**Severity:** Major
**Status:** Open
**Component:** Mobile Application
 
The application crashes when users attempt to upload image attachments larger than 10 MB.
 
---
 
### BUG-110
**Severity:** Medium
**Status:** In Progress
**Component:** Performance
 
Page load times exceed five seconds when displaying more than 1,000 records.
 
---
 
## Current Build Status
 
| Check | Status |
|---------|---------|
| Backend Build | PASS |
| Frontend Build | FAIL |
| API Integration Tests | PASS |
| Performance Tests | FAIL |
| Security Scan | PASS |
| End-to-End Regression Tests | PASS |
