---
title: Export to Sage 50
type: docs
---

# Export to Sage 50

Work Tyme gives you the ability to export your collected time slips into Sage 50.

We do this in a two step process. First you download an export data file from the Work Tyme website for your pay period. Then secondly you run the "Work Tyme Import software" on a Windows computer that is running Sage 50 and select the data file you downloaded in the first step.

## Export data from Work Tyme

Only admins are able to export data from Work Tyme to Sage 50 (see [user types]({{< relref "/docs/user_types.md" >}}) for more information). In the left hand menu click on the menu option titled "Export to Sage". You will be shown the Export to Sage 50 screen.

![Export to Sage](/docs/img/export_to_sage_page.png)

First select the pay period you are wanting to export. This will update the list of employees.

Next, select whether you are wanting to export all employees, only hourly employees, or only salary employees. Changing this selection will update the list of employees.

Beside the name of each employee you are shown how many time slips they have approved out of the total time slips they have submitted in this pay period (see [status options]({{< relref "/docs/time_slips_status.md" >}}) for more information).

Employees that have all of their time slips approved are automatically selected for the export. If an employee still has time slips to be approved they will be unselected by default. If you try to export data for employees with unapproved time slips you will be denied with the following message.

![Export to Sage](/docs/img/export_to_sage_page_denied.png)

Once you have selected the employees you wish to export and all of their time slips are approved click on the button titled "Export the data".

You will be prompted to download the export file to your computer.

All of the exported time slips are now changed to have a status of locked inside of Work Tyme (see [status options]({{< relref "/docs/time_slips_status.md" >}}) for more information)

## Import data into Sage

In order to import the Work Tyme data into Sage 50 you will need to download the "Work Tyme Import software". You can obtain a copy by clicking on the link on the top right hand side of the "Export to Sage" page in Work Tyme

![Export to Sage](/docs/img/export_to_sage_page_download.png)

Once you have the Work Tyme Importer and the exported data file the next step is to start Sage 50 and open your Sage 50 company file.


Next open the Work Tyme Importer by double-clicking on the file. Windows will likely intervene with a security warning. Click through the warning stating you do indeed wish to run the software.

The Work Tyme Importer will ask you for some information before it begins importing your Work Tyme data

![Work Tyme Importer](/docs/img/importer.png)

* **Sage 50 IP:** _If your Sage 50 company file is stored on your computer leave this as "127.0.0.1". If however your Sage 50 company file is located on a server on your network set this to the IP address of that server_
* **Sage 50 Port:** _Sage 50 usually uses port 13540. If you get an error during the import about not being able to connect to Sage 50 try incrementing this value by one_
* **Sage 50 username:** _The username you use to log into Sage 50_
* **Sage 50 password:** _The password you use to log into Sage 50 (This password is never stored so you will be asked to enter it each time you use the Importer)_
* **Work Tyme file:** _This is the location of the file you downloaded from the Work Tyme site earlier_

Once you have filled in all the information click on the button titled "Import" to begin the import process.

The Importer will begin logging it's progress in the lower window. If the Importer encounters any errors it will also report them in this log window.

The most common errors are usually when an employee's name in Work Tyme does not match their name in Sage 50, or if the names of the [departments]({{< relref "/docs/departments.md" >}}) and [divisions]({{< relref "/docs/divisions.md" >}}) in Work Tyme do not match the Timeslip Items and Timeslip Divisions. If you run into these types of issues adjust the names in Sage 50 or Work Tyme. If you make changes in Work Tyme you will need to re-download your data file for the pay period so it contains your changes.

**_Note: If you encounter errors during the import process and are not sure how to resolve them we are always here to help. We can be reached via email (dave@worktyme.ca) or phone (780.554.2447) as well as via the chat window within the_ <a href="https://worktyme.ca" target_blank>_Work Tyme_</a> _website._**


## Finding the port Sage 50 is using

If you are having connection issues running the Importer it may be caused by Sage 50 using an uncommon port. To find the port Sage 50 is using open the "help" menu and click on "About Sage 50"

![Sage port](/docs/img/sage_port_1.png)

Click on the button on the bottom right titled "Support Info"

![Sage port](/docs/img/sage_port_2.png)

In the window that appears you will find the port specified in the top right corner

![Sage port](/docs/img/sage_port_3.png)