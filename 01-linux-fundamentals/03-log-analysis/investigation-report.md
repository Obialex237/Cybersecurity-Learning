# Authentication Log Investigation

## Objective

Practice identifying suspicious authentication activity
using fictional security logs.

## Evidence

The sample log contains three failed login attempts
against the admin account.

## Findings

- Target account: admin
- Failed attempts: 3
- Source IP: 198.51.100.25
- Time window: 9 seconds

## Initial Assessment

Repeated failed authentication attempts may indicate
suspicious login activity.

The available evidence is insufficient to confirm
a brute-force attack.

## Recommended Next Steps

1. Review surrounding authentication events.
2. Check whether a successful login followed the failures.
3. Review other activity associated with the account.
4. Correlate the events with other available security logs.
5. Escalate according to the organization's procedures
   if additional evidence indicates a threat.

## Conclusion

This exercise demonstrates how to extract key facts
from authentication logs and document an initial
security assessment.
