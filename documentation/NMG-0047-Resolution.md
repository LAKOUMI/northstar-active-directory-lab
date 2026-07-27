Ticket number: NMG-0047

Affected user: Jane Smith

Issue reported: Unable to access HR shared resources. Desktop policies and mapped drives differ from HR teammates.

Root cause: Jane Smith's account was incorrectly placed in the Finance OU and was a member of the Finance-Users security group instead of HR-Users. The incorrect OU placement caused the wrong policies and environment settings to be applied, while the incorrect security group membership prevented access to HR shared resources.

Fix applied: Moved Jane Smith's account from the Finance OU to the HR OU. Removed Jane Smith from the Finance-Users security group and added her to the HR-Users security group.

Verification: Confirmed Jane Smith's account is located in the HR OU. Confirmed her group memberships include Domain Users and HR-Users and no longer include Finance-Users. Confirmed Jane Smith appears in the HR-Users group's Members list.

Date resolved: July 20, 2026

Resolved by: IT New Hire
