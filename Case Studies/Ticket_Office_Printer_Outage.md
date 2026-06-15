# Ticket Summary

A user reported that nobody in the office was able to print to the main office printer. Approximately 25 users were affected and documents required for customer interactions could not be printed. Print jobs remained in the queue and were not reaching the printer.

## Impact Assessment

- Approximately 25 users affected.
- Customer facing services impacted.
- No alternative printer immediately available.
- Business operations partially disrupted.

### Priority Assessment

**Impact:** High

**Urgency:** High

**Assigned Priority:** P2 High

Although the issue affected multiple users and customer facing operations, the business was still able to operate in a limited capacity. Therefore, the incident was classified as a High Priority (P2) incident rather than a Critical (P1) incident.

## Initial Investigation

The following information was gathered from the user:

- Printer was powered on.
- Paper was loaded.
- No obvious paper jams were present.
- Users reported print jobs remaining in the queue.
- Issue affected multiple users rather than a single workstation.

## Troubleshooting Steps

### Step 1: Verify Printer Status

Requested confirmation of:

- Power status.
- Paper and toner levels.
- Error messages displayed on the printer.
- Any flashing warning lights.

No hardware faults were identified.

### Step 2: Determine Scope

Confirmed:

- Multiple users affected.
- Issue occurring across the office.
- Not isolated to a single device.

This suggested a shared infrastructure issue rather than an individual workstation problem.

### Step 3: Network Connectivity Checks

- Obtained printer IP address.
- Performed connectivity tests to verify network communication.
- Confirmed whether the printer responded to network requests.

### Step 4 - Restart Devices

Requested a restart of:

- The printer.
- Affected workstation.

Retested printing after restart.

### Step 5 - Further Investigation

Considered:

- Print server issues.
- Network connectivity issues.
- Printer driver issues.
- Printer queue issues.

## Resolution

Following a restart of the printer and clearing of the print queue, normal printing functionality was restored and users were able to print successfully.

## Root Cause

A print queue fault caused jobs to become stuck, preventing documents from being processed by the printer.

## Lessons Learned

- Establish the scope of the issue before troubleshooting individual devices.
- When multiple users are affected, investigate shared infrastructure first.
- Verify simple causes such as printer status and queue health before escalating.
- Understanding business impact helps ensure the correct priority level is assigned.