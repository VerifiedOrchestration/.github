## Summary

> [!IMPORTANT]
> **Required:** as a minimum, summary should contain a link to the Jira item that this PR implements.

Optionally, copy the description from Jira.

This field should not contain any information that isn’t already in the linked Jira item, except notes for testers or reviewers.

Example:

- `https://verifiedorchestration.atlassian.net/browse/ABC-123`

## Branch name check

> [!IMPORTANT]
> **Required:** branch name must start with the Jira ID.

Examples:

- `ABC-123-add-user-endpoint`
- `XYZ-999-fix-number-formatting`

If your branch name doesn’t follow this format, please fix it before continuing.

## Reviewer notes (optional)

Add any context the **reviewers** or **testers** need that *is not appropriate to store in Jira*.

Examples:
- How to verify the change manually  
- Caveats, temporary trade-offs, migration notes  
- Anything that would help the reviewer but shouldn’t live in Jira long-term

## Checklist

Please confirm the following:

- [ ] Jira work item is linked above  
- [ ] Branch name starts with the Jira ID  
- [ ] All assigned reviewers will be required to approve before merging  
- [ ] PR description contains no information that should instead live in Jira  
- [ ] Only reviewer/tester-specific notes (if any) are included here  

