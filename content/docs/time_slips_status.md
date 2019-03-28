---
title: Time slip status options
type: docs
---

# Time slip status options

Time slips can have the following statuses:

* **New:** _When a time slip has just been submitted by an employee it will appear with the status "- - - -" and be highlighted in gray. It is awaiting the approval or rejection of the [approver]({{< relref "/docs/approvers.md" >}}) and is still editable by the employee_
* **Denied:** _If the approver rejects the time slip it will have the status of "Denied" and be colored blue. The time slip is still editable by the employee and is awaiting them to make their changes and resubmit_
* **Approved:** _When a time slip has been approved it will be colored green. The employee is no longer allowed to make changes to the time slip but the approver is still able to make changes_
* **Locked:** _When an admin [exports the time slip to Sage 50]({{< relref "/docs/export_sage.md" >}}) the time slip becomes locked and is colored red. Only admins are able to make changes to locked time slips_
* **NA:** _A time slip that is set with a status of NA is colored brown and can be thought of as deleted. Work Tyme retains deleted time slips for reference purposes and instead refers to them as NA_