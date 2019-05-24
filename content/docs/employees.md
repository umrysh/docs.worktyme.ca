---
title: Employees
type: docs
---

# Employees

_**Note: Work Tyme is free for up to three employees. Once you attempt to create your fourth employee you will be prompted to enter your credit card details into Stripe but this doesn't necessarily mean you will start being billed (see [billing]({{< relref "/docs/billing.md" >}}) for more information).**_

## Add an employee

To add an employee navigate to the "Directory" menu option and click on the green "Add Employee" button above the list of employees

![Directory](/docs/img/directory.png)

You will then be asked to fill in information about the new employee. If an item has a red asterisk beside it that means this field must be filled in when creating a new employee.

The first section is for the basic account information:

* **Name:** _Enter the employee's name. If you are exporting time slips to Sage 50 this must match the employee's name in your Sage 50 system_
* **Login username:** _Employees can log into Work Tyme using either their email address or username_
* **Email:** _Work Tyme utilizes an employee's email for forgot password links, [time-off]({{< relref "/docs/time_off.md" >}}) requests, login, etc_
* **Account admin:** _If an employee is an account admin they have full control of your entire Work Tyme account. Usually HR managers would be the only admins for your account_
* **Certifications admin:** _Work Tyme has a [certifications]({{< relref "/docs/certifications.md" >}}) module that allows you to upload PDFs of training certifications and assign them to the specific employees. Usually this is not handled directly by HR but by the Health & Safety team members._

![Employee information](/docs/img/add_employee_info.png)

The next section deals more closely with HR specific information about the employee.

* **Position/title:** _An employee's title will show up on their listing in the [staff directory]({{< relref "/docs/directory.md" >}}), their internal [company profile page]({{< relref "/docs/profile_pages.md" >}}), and on the [organization chart]({{< relref "/docs/org_chart.md" >}})_
* **Hire date:** _The date the employee joined your team. This date is also displayed on the employee's internal [company profile page]({{< relref "/docs/profile_pages.md" >}})_
* **Gender:** _Can be set to "Male", "Female" or "Other". Helpful as a reference to which pronouns an employee prefers to be addressed with_
* **Direct supervisor:** _An employee's direct supervisor will be the person who receives all [time-off]({{< relref "/docs/time_off.md" >}}) requests for this employee and will be able to view all [time slips]({{< relref "/docs/time_slips.md" >}}) they submit. This employee will be linked to on their supervisor's internal [company profile page]({{< relref "/docs/profile_pages.md" >}}) as well as their supervisor will be linked from theirs. The integrated [organization chart]({{< relref "/docs/org_chart.md" >}}) also utilizes this information to build the chart._
* **Department:** _The company [department]({{< relref "/docs/departments.md" >}}) to which the employee belongs. This is displayed on the employee's [profile page]({{< relref "/docs/profile_pages.md" >}}) as well it is used to specify which [todo list]({{< relref "/docs/todo_lists.md" >}}) (onboarding template) should be assigned to them_
* **Employee type:** _This information is displayed on the employee's [profile page]({{< relref "/docs/profile_pages.md" >}}). If the employee has left the company select the "Former employee" option and enter the date they left the company. Visit the [former employees]({{< relref "/docs/former_employees.md" >}}) page for more information_

![Employee information](/docs/img/add_employee_hr.png)

Following the basic HR information we have a section about the employee's time and cost.

* **Vacation days per year:** _How many vacation days does this employee receive per year_
* **Vacation days remaining:** _How many vacation days does this employee still have available for the remainder of the current calendar year. This value is replenished each January 1st with the value entered in "Vacation days per year". We also use this value when sending out [time-off]({{< relref "/docs/time_off.md" >}}) requests to the employee's supervisor so that the supervisor is aware of how many vacation days the employee has remaining before they approve/deny the request. This value is allowed to go into the negative as we feel it is up to the supervisor and HR if they will to approve additional vacation days for an employee_
* **Sick days remaining:** _How many sick days does this employee still have available for the remainder of the current calendar year. Each January 1st this value will be updated with the amount entered for "Allowed sick days per year" on the [general settings]({{< relref "/docs/company_settings.md" >}}) page for your company. There is no carry over of unused sick days in Work Tyme. We also use this value when sending out [time-off]({{< relref "/docs/time_off.md" >}}) requests to the employee's supervisor so that the supervisor is aware of how many sick days the employee has remaining before they approve/deny the request. This value is allowed to go into the negative as we feel it is up to the supervisor and HR if they will to approve additional sick days for an employee_
* **Default hours for statutory holidays:** _When an admin enters a [company wide holiday]({{< relref "/docs/holidays.md" >}}) and chooses to not set custom hours this will be the amount of hours this employee is entitled to_
* **Employee cost per hour:** _This is currently utilized in the [Payroll]({{< relref "/docs/payroll_report.md" >}}) report_

![Employee information](/docs/img/add_employee_hr2.png)

Next we can set if this employee will be responsible for approving any time slips as well we can set if they should be BCC'd on any time-off requests.

* **Employee can approve time allocated to the following divisions:** _Rather then have an employee be responsible for approving all [time slips]({{< relref "/docs/time_slips.md" >}}) entered for a particular department (for example, "Manufacturing") we instead go one level further and set [approvers]({{< relref "/docs/approvers.md" >}}) based on the [divisions]({{< relref "/docs/divisions.md" >}}) inside of the [departments]({{< relref "/docs/departments.md" >}}). For smaller companies you may have the same individual approving all the divisions in a department but in larger organizations you may have front line supervisors approving the hours for their individual job items. To make this employee an approver for a division select the division from the drop down list and click the "Add to approvers" button. Repeat this process for all the divisions they will need to approve._

* **Employee will receive alerts for time off in the following company divisions:** _When an employee requests [time-off]({{< relref "/docs/time_off.md" >}}) their direct supervisor will receive an email with information about the request and buttons to either approve/deny the request. If this particular employee should also be made aware of all time-off being requested in a particular [department]({{< relref "/docs/departments.md" >}}) you can enable it here. For example your HR manager will likely wish to be alerted for all time-off in every department, or you may have a VP that oversees an entire department but does not have any employees directly reporting to them. To have this employee be alerted for time-off in a department select the department from the drop down list and click the "Enable notifications" button. Repeat this process for all the departments they will want to receive alerts from._

![Employee information](/docs/img/add_employee_hr3.png)

And finally we set the password for the new employee. You have an option of whether you wish for Work Tyme to send the employee a welcome email with their new password or not.

![Set employee password](/docs/img/add_employee_password.png)

When finished entering all the data click the button labeled "Create employee" to create the employee.

## Edit an employee

To edit an employee navigate to the "Directory" menu option and click on the name of the employee you wish to edit. You will then see a green button near the top right of the screen titled "Switch to advanced settings". Click this button to edit the employee's account information.

![Directory](/docs/img/home_page.png)

You will then be shown all the currently entered information about the employee's account and be able to make changes to their information. If an item has a red asterisk beside it that means this field must be filled in.

The first section is for the basic account information:

* **Name:** _Enter the employee's name. If you are exporting time slips to Sage 50 this must match the employee's name in your Sage 50 system_
* **Login username:** _Employees can log into Work Tyme using either their email address or username_
* **Email:** _Work Tyme utilizes an employee's email for forgot password links, [time-off]({{< relref "/docs/time_off.md" >}}) requests, login, etc_
* **Account admin:** _If an employee is an account admin they have full control of your entire Work Tyme account. Usually HR managers would be the only admins for your account_
* **Certifications admin:** _Work Tyme has a [certifications]({{< relref "/docs/certifications.md" >}}) module that allows you to upload PDFs of training certifications and assign them to the specific employees. Usually this is not handled directly by HR but by the Health & Safety team members._

![Employee information](/docs/img/add_employee_info.png)

The next section deals more closely with HR specific information about the employee.

* **Position/title:** _An employee's title will show up on their listing in the [staff directory]({{< relref "/docs/directory.md" >}}), their internal [company profile page]({{< relref "/docs/profile_pages.md" >}}), and on the [organization chart]({{< relref "/docs/org_chart.md" >}})_
* **Hire date:** _The date the employee joined your team. This date is also displayed on the employee's internal [company profile page]({{< relref "/docs/profile_pages.md" >}})_
* **Gender:** _Can be set to "Male", "Female" or "Other". Helpful as a reference to which pronouns an employee prefers to be addressed with_
* **Direct supervisor:** _An employee's direct supervisor will be the person who receives all [time-off]({{< relref "/docs/time_off.md" >}}) requests for this employee and will be able to view all [time slips]({{< relref "/docs/time_slips.md" >}}) they submit. This employee will be linked to on their supervisor's internal [company profile page]({{< relref "/docs/profile_pages.md" >}}) as well as their supervisor will be linked from theirs. The integrated [organization chart]({{< relref "/docs/org_chart.md" >}}) also utilizes this information to build the chart._
* **Department:** _The company [department]({{< relref "/docs/departments.md" >}}) to which the employee belongs. This is displayed on the employee's [profile page]({{< relref "/docs/profile_pages.md" >}}) as well it is used to specify which [todo list]({{< relref "/docs/todo_lists.md" >}}) (onboarding template) should be assigned to them_
* **Employee type:** _This information is displayed on the employee's [profile page]({{< relref "/docs/profile_pages.md" >}}). If the employee has left the company select the "Former employee" option and enter the date they left the company. Visit the [former employees]({{< relref "/docs/former_employees.md" >}}) page for more information_

![Employee information](/docs/img/add_employee_hr.png)

Following the basic HR information we have a section about the employee's time and cost.

* **Vacation days per year:** _How many vacation days does this employee receive per year_
* **Vacation days remaining:** _How many vacation days does this employee still have available for the remainder of the current calendar year. This value is replenished each January 1st with the value entered in "Vacation days per year". We also use this value when sending out [time-off]({{< relref "/docs/time_off.md" >}}) requests to the employee's supervisor so that the supervisor is aware of how many vacation days the employee has remaining before they approve/deny the request. This value is allowed to go into the negative as we feel it is up to the supervisor and HR if they will to approve additional vacation days for an employee_
* **Sick days remaining:** _How many sick days does this employee still have available for the remainder of the current calendar year. Each January 1st this value will be updated with the amount entered for "Allowed sick days per year" on the [general settings]({{< relref "/docs/company_settings.md" >}}) page for your company. There is no carry over of unused sick days in Work Tyme. We also use this value when sending out [time-off]({{< relref "/docs/time_off.md" >}}) requests to the employee's supervisor so that the supervisor is aware of how many sick days the employee has remaining before they approve/deny the request. This value is allowed to go into the negative as we feel it is up to the supervisor and HR if they will to approve additional sick days for an employee_
* **Default hours for statutory holidays:** _When an admin enters a [company wide holiday]({{< relref "/docs/holidays.md" >}}) and chooses to not set custom hours this will be the amount of hours this employee is entitled to_
* **Employee cost per hour:** _This is currently utilized in the [Payroll]({{< relref "/docs/payroll_report.md" >}}) report_

![Employee information](/docs/img/add_employee_hr2.png)

Next we can set if this employee will be responsible for approving any time slips as well we can set if they should be BCC'd on any time-off requests.

* **Employee can approve time allocated to the following divisions:** _Rather then have an employee be responsible for approving all [time slips]({{< relref "/docs/time_slips.md" >}}) entered for a particular department (for example, "Manufacturing") we instead go one level further and set [approvers]({{< relref "/docs/approvers.md" >}}) based on the [divisions]({{< relref "/docs/divisions.md" >}}) inside of the [departments]({{< relref "/docs/departments.md" >}}). For smaller companies you may have the same individual approving all the divisions in a department but in larger organizations you may have front line supervisors approving the hours for their individual job items. To make this employee an approver for a division select the division from the drop down list and click the "Add to approvers" button. Repeat this process for all the divisions they will need to approve._

* **Employee will receive alerts for time off in the following company divisions:** _When an employee requests [time-off]({{< relref "/docs/time_off.md" >}}) their direct supervisor will receive an email with information about the request and buttons to either approve/deny the request. If this particular employee should also be made aware of all time-off being requested in a particular [department]({{< relref "/docs/departments.md" >}}) you can enable it here. For example your HR manager will likely wish to be alerted for all time-off in every department, or you may have a VP that oversees an entire department but does not have any employees directly reporting to them. To have this employee be alerted for time-off in a department select the department from the drop down list and click the "Enable notifications" button. Repeat this process for all the departments they will want to receive alerts from._

![Employee information](/docs/img/add_employee_hr3.png)

When finished entering all the data click the button labeled "Update employee information" to save the changes made to the employee.


## Change an employee's password

To edit the employee navigate to the "Directory" menu option and click on the name of the employee you wish to edit. You will then see a green button near the top right of the screen titled "Switch to advanced settings". Click this button to edit the employee's account information.

![Directory](/docs/img/home_page.png)

Scroll all the way to the bottom of the employee's advanced settings page and you will see a section titled "Change employee's passphrase". If you do not wish for Work Tyme to email the employee a copy of their new password unselect the check box titled "Email the employee". For example, if the employee has left your company you may wish to lock them out of their account by changing their password and therefore do not want Work Tyme to send them this new password. After you have entered the new password click on the button titled "Update employee passphrase" to save your changes.

![Set employee password](/docs/img/edit_employee_password.png)


## Delete an employee

To delete an employee navigate to the "Directory" menu option and click on the name of the employee you wish to edit. You will then see a green button near the top right of the screen titled "Switch to advanced settings". Click this button to edit the employee's account information.

![Directory](/docs/img/home_page.png)

Scroll all the way to the bottom of the employee's advanced settings page and you will see a section titled "Delete Employee". As is mentioned on the page itself please note you are not billed for inactive employees. If an employee does not submit a time record or login for 30 days they will automatically be marked inactive until they do. Please see [billing]({{< relref "/docs/billing.md" >}}) for more information. If you truly wish to delete this employee and all associated records click on the button labeled "Delete Employee"

![Set employee password](/docs/img/edit_employee_delete.png)