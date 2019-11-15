---
title: User types
type: docs
---

# User types

In Work Tyme there are two main types of users:

* **Admin:** _An administrator has full control of a company's entire Work Tyme account. You can have as many admins as you would like. To make an employee an admin you will need to be an admin yourself and then visit the [advanced settings]({{< relref "/docs/employees.md" >}}#edit-an-employee) for their account._
* **Regular user:** _If an employee's account is not an admin they are what we refer to as a regular user account._


Regular users can then be given additional permissions:

* **Manager:** _If a regular user account is the direct supervisor for any other employee account that person is known as a "manager". Their account will have a menu item called [time slips]({{< relref "/docs/time_slips.md" >}}) where they can view the time slips that have been entered by the employees they are responsible for_
* **Approver:** _If a regular user account is responsible for [approving]({{< relref "/docs/approvers.md" >}}) any time slips that person is known as an "Approver". Their account will have a menu item called [time slips]({{< relref "/docs/time_slips.md" >}}) where they can view the time slips that have been entered for any [divisions]({{< relref "/docs/divisions.md" >}}) they are responsible for approving_
* **Certifications admin:** _A certifications admin is a regular user account that has been given administrative rights to the [certification]({{< relref "/docs/certifications.md" >}}) module for the company. They will have an additional menu option titled "Certifications" where they can upload and assign certifications to any employee in the company. To make an employee an certifications admin you will need to be logged in as an admin and then visit the [advanced settings]({{< relref "/docs/employees.md" >}}#edit-an-employee) for their account._
* **Expenses admin:** _An expenses admin is a regular user account that has been given administrative rights to the [expenses]({{< relref "/docs/expenses.md" >}}) module for the company. They will be able to manage the company cards as well as manage all expenses uploaded to your company. They will also be able to download expense reports and lock expenses from being edited by regular users. To make an employee an expenses admin you will need to be logged in as an admin and then visit the [advanced settings]({{< relref "/docs/employees.md" >}}#edit-an-employee) for their account._

If you have enabled the [expense tracking]({{< relref "/docs/expenses.md" >}}) module you will have access to two more types of user accounts:

* **Expenses Only user:** _This type of user can only add expenses to your Work Tyme account. They will not appear in the [organization chart]({{< relref "/docs/org_chart.md" >}}) or in the [staff directory]({{< relref "/docs/directory.md" >}}) when viewed by a Regular user. An example for this type of account would be your company's travel agent._
* **Auditor:** _This is a sub-type of the Expenses Only user. They are able to view all expenses in the company but will still only be allowed to edit their own expenses. An example use case would be during a financial audit you may need to create an Auditor account for the auditor so they can review your expenses. Once the audit is finished, you would delete their account._