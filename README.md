# CMPG-323-project-4--32369689


Overview
Testing is a crucial part of any solution and can be done from many different perspectives; the
internal development team testing, business user acceptance testing (UAT), etc. There are also
many different types of testing that can be conducted on a solution and user acceptance testing
is usually done very manually. UAT is often included in most development lifecycles as a crucial
step that acts as the ‘go/no-go’ decision maker. UAT is focused on ensuring that the input entered
into the solution generates the expected output. If the solution does not generate the desired
output, the solution needs to be amended and retested as the solution would generally not be
published to production unless it passes all tests in UAT.
Robotic Process Automation (RPA) refers to the use of technology to mimic human tasks in the
same way that a person would execute a process. This usually refers to, what we would call,
‘front-end’ or UI (User Interface) automation. RPA is often used to automate time-consuming and
highly repetitive tasks to allow people the availed capacity to work on more intuitive tasks.
Let’s take the web application that you worked on in Project 3 – before the solution can be
deployed into production, it would need to go through UAT where a team of ‘testers’ would have
a test dataset containing input data and desired output data. The testers would then insert each
record of input data into each field of the web application and test that the desired output is
generated. In this case, the desired output would be a new record being displayed on the web
application once the item has been added. This would resort in a highly repetitive process which
can and should (in this case) be automated using RPA.


NOTE* All the creates for categories, zones , and device is working perfect
    * the delete,update ,create and insert are having correct structure following right steps but not running 100%

This repository contains  automation scripts for Project 4 of CMPG 323 created in UIPath Studio Community, the script test Basic CRUD activities on the Connected Office Web app

REQUIREMENT:

Before running this project please ensure that you have the following software installed on your computer:

UIPath Studio (Community) Minimum version 2022.10.2 (Recommended)
Microsoft Excel
Microsoft Edge
.Net SDK Version 6.0 (Recommended)
Installation and usage
Clone the Git repository into a local folder
Open "ConnectedOffice Webapp User Acceptance Testing" project in UIPath Studio

The Structure of the test suite is broken up as follows:

Delete - where you delete the selected item permanently and will never be recovered back.
Insert- is when you add an category to the office 
update - is when you change data from something to something eg. from maths to science 

NB: each of the test is done on each of the categories, device, and zones 

Category

*DeleteCategories
*InsertCategories
*UpdateCategories
*Main.xaml

Devices

*DeleteDevices
*InsertDevice
*UpdateDevices
*Main.xaml

Zones

*DeleteZones
*InsertZones
*UpdateZones
*Main.xaml

PROCEDURE:

NB: when you run the uipath studio , it will open the connected office , please always logout when you want to do the testing, and they might be errors which i couldnt solve , however the steps are there which i have provided but still not 100%

Click on the test that you would like to run and click the run button in UiPath Studio , when its displayed please press logout and then the automation will take place smoothly.
Once the test is successfully You will return to UiPath Studio where you can run another test

![Screenshot 2022-10-27 144617](https://user-images.githubusercontent.com/110628936/198290920-fd95fd31-0b98-48a0-94a2-7487d51685db.png)








REFERENCE:

https://www.dropbox.com/sh/p8fiokfpiqv4gud/AAC5X8SdanTnduTWYzVq4kQ7a?dl=0&preview=10+CMPG322++-+Project+4+20+Oct.mp4

Adit Kansara. 2019. Excel Automation with RPA - Excel Application RPA | UiPath. UiPath Blog. https://www.uipath.com/community/rpa-community-blog/excel-automation-application-rpa Date of access: 25 Oct. 2022.

Boboc, M. s.a. Excel Automation Tutorial - DataTables Automation | UiPath. https://www.uipath.com/learning/video-tutorials/excel-datatables-automation Date of access: 25 Oct. 2022.

Changrui Cheng. 2021. How to retrieve the url of a hyperlink on a webpage? - Help. UiPath Community Forum. https://forum.uipath.com/t/how-to-retrieve-the-url-of-a-hyperlink-on-a-webpage/153379/3 Date of access: 25 Oct. 2022.

Chris Dease. 2021. Looping through links on a website - Help / Studio. UiPath Community Forum. https://forum.uipath.com/t/looping-through-links-on-a-website/316999/3 Date of access: 25 Oct. 2022.

David Martinez. 2020. How to correctly loop through an HMTL UL element with For Each - Help / Studio. UiPath Community Forum. https://forum.uipath.com/t/how-to-correctly-loop-through-an-hmtl-ul-element-with-for-each/228378 Date of access: 25 Oct. 2022.

Excel Automation with Studio. 2021. https://www.youtube.com/watch?v=7SrdrREJtcc Date of access: 25 Oct. 2022.

Filipe Ferreira. 2017. For each UiElement - Help. UiPath Community Forum. https://forum.uipath.com/t/for-each-uielement/1515/3 Date of access: 25 Oct. 2022.

Guillermo Cruz. 2019. Add Data Row, there is no row at position 0 - Help. UiPath Community Forum. https://forum.uipath.com/t/add-data-row-there-is-no-row-at-position-0/151163 Date of access: 25 Oct. 2022.

Harsh. 2020. https://github.com/harshvchawla/UiPath-best-practices/blob/61bc7b77d3acae031ae1c995f2e7c5f6a46fe39e/UiPath%20Automation%20Best%20Practices%20Guide.pdf Date of access: 25 Oct. 2022.

JaxXult. 2021. Click on item in the drop-down menu - Help / Activities. UiPath Community Forum. https://forum.uipath.com/t/click-on-item-in-the-drop-down-menu/336908 Date of access: 25 Oct. 2022.

Marko Kostic. 2019. How to get all selectors from one web page - Random and other categories. UiPath Community Forum. https://forum.uipath.com/t/how-to-get-all-selectors-from-one-web-page/126074 Date of access: 25 Oct. 2022.

Muller, J. 2022a. Automation Solutions Using Design Patterns | Community Blog. UiPath Blog. https://www.uipath.com/community/rpa-community-blog/automation-solutions-using-design-patterns Date of access: 25 Oct. 2022.

Muller, J. 2022b. Test Driven Development (TDD) - An Approach to Automation | Community Blog. UiPath Blog. https://www.uipath.com/community/rpa-community-blog/understanding-test-driven-development-an-approach-to-automation Date of access: 25 Oct. 2022.

Nathan Smith. 2021. How to Convert excel to DataTable in UIPath? - Help / Studio. UiPath Community Forum. https://forum.uipath.com/t/how-to-convert-excel-to-datatable-in-uipath/321763 Date of access: 25 Oct. 2022.

Rohit Kashyap. 2021. UiPath Best Practices Guidelines | RPA Implementation. SOAIS. https://www.soais.com/rpa-uipath-best-practices-guidelines/ Date of access: 25 Oct. 2022.

Shaikh, I. 2019. Reading An Excel File In UiPath. C# corner. https://www.c-sharpcorner.com/article/reading-an-excel-file-in-uipath/ Date of access: 25 Oct. 2022.

UiPath. 2021a. Get Row Item. UiPath Activities. https://docs.uipath.com/activities/docs/get-row-item Date of access: 25 Oct. 2022.

UiPath. 2021b. Manage DataTables. UiPath Activities. https://docs.uipath.com/activities/docs/manage-data-tables Date of access: 25 Oct. 2022.

UiPath. 2021c. Read from Excel Files. UiPath Activities. https://docs.uipath.com/activities/docs/read-from-excel-files Date of access: 25 Oct. 2022.

UiPath. 2021d. UI Automation. UiPath Studio. https://docs.uipath.com/studio/docs/ui-automation Date of access: 25 Oct. 2022.

UiPath. s.a. Deployment and configuration considerations. UiPath Orchestrator. https://docs.uipath.com/orchestrator/docs/deployment-and-configuration-considerations Date of access: 25 Oct. 2022 a.

UiPath. s.a. Deployment and configuration considerations. UiPath Orchestrator. https://docs.uipath.com/orchestrator/docs/deployment-and-configuration-considerations Date of access: 25 Oct. 2022 b.

UiPath. s.a. Organization modeling in Orchestrator. UiPath Orchestrator. https://docs.uipath.com/orchestrator/docs/organization-modeling-in-orchestrator Date of access: 25 Oct. 2022 c.

Vinnyt1984. 2021. Looping through similar elements from a desktop application screen by clicking each of those elements. List/Count of elements vary each time the screen gets displayed - Help / Studio. UiPath Community Forum. https://forum.uipath.com/t/looping-through-similar-elements-from-a-desktop-application-screen-by-clicking-each-of-those-elements-list-count-of-elements-vary-each-time-the-screen-gets-displayed/352922 Date of access: 25 Oct. 2022.

What is a UiPath Software Robot? 2021. https://www.youtube.com/watch?v=3R67RGjZoOM Date of access: 25 Oct. 2022.


