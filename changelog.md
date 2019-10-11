## 11 October 2019

### General improvements in "Vehicle Information" widgets
The whole section dedicated to Vehicle Information has been improved.
- Vehicle details and contract details are now exposing information in a simpler way. The visualization of the information is now better on different resolutions.
- Contact information is now presented with an updated layout. It is now possible to change the title (Driver, Manager, ...) of an already existing contact. The widget is now responsive and performs better.

## 08 October 2019

### In production list is now ordered on the base of the check in date instead of booked date
The workorder list in "In production" is now exposing check in date in place of booked date.

### Jobs to be performed widget exposes all jobs
In preparation of the release of Ad hoc Jobs and VHC, the Jobs to be performed is showing all jobs present in the workorder. As a result, users will start to always see the VHC job inserted.

## 07 October 2019

### Work Order Information widget
The Work Order Information widget is now always presented as collapsed when the Service Advisor enters in the lead for the first time. 

## 26 September 2019

### Fault Code widget moved into opportunities
The fault code widget has been graphically redesigned to expose information in a simpler way.
The fault code widget has been moved inside the opportunities section. 

### Add a note on chassis or on workorder
Users reported that saving notes only on chassis level was not enough since many information are only relevant for the current workshop visit. It is now possible to save a note on the current workshop visit. A note saved on a workorder will be lost when the workorder is checked-out.

## 13 September 2019

### Software module ELC4 updated
Software module ELC4 is updated from Swedish to English. It’s now displayed in English in the dashboard.

### Estimated time for arrival
Under the vehicle section you will now see ETA to the workshop that are current active on the screen.

### Maintenance plan always visible
Users reported that it was hard to find the maintenance plan after recent changes. Maintenance plan is always expanded in the opportunities.

### Loading indicator to add opportunities to workorders
A loading indicator has been added to the checkboxes so the user can understand the opportunity is getting added to the workorder.

### Event not selectable if already added on another workorder
It was possible for users to add the same event twice, on two different workorders, creating a duplication. 
It is no longer possible to add an event on more than one workorder.

## 30 August 2019

### Plan Type and Agreement removed from workorder lists
The information regarding plan type or agreement is removed from the workorder list. It is now possible to see the type of plan and agreement in the maintenance widget instead. This is a temporary change. Soon DD will add the reason why a lead is generated to make this information available again.

### Vehicle header
Vehicle header has been updated to better expose information. 

### CSV Export functionality for Aptum users
Some users are relying on unofficial Scania DMSs which will not be integrated with Digital Dealer. In order to simplify their activities, DD will allow users to download the maintenance event summary in CSV format. A new download option is now available for the current maintenance event.

### Merge maintenance widget (opportunity) with maintenance plan
Digital Dealer merged the maintenance widget (in opportunity) with the maintenance plan. Additional information has been added to the widget: 
- The Planned Distance for the event is now exposed in the current maintenance 
- More details regarding time are now provided into the plan 
- More information regarding additional jobs to be performed on modules are now exposed in the plan 
- External status and MAC status are now merged into a single column: an event will go through statuses in the following order NOT PERFORMED>TRR>TR>WO>Performed 

The current maintenance plan widget is removed. 

### Change archiving rule for workorders
DD will only archive workorder in LEAD phase. Workorders in BOOKED and IN PRODUCTION will not be automatically archived.

## 16 August 2019

### Show Location of the vehicle
Digital Dealer added the possibility for service advisors to see the location of the vehicle. It will be shown on a map that now has been zoomed out a bit to be compliant to GDPR regulations. We will continue working on the zoom level to get the right level of zoom.

### Self Help FAQ
It is now possible to find “Frequently Asked Questions” (FAQ) in the Self Help. The Self Help will display useful questions depending on your dashboard location. You can also search for questions not found in current displayed set of questions. All questions are based on feedback from users.

### Factory Warranty End Date
Users feedback reported the need to change “Warranty End Date” to include Factory. Digital Dealer now displays: “Factory Warranty End Date”.

### Translations
Users feedback reported the need to have better translations. Digital Dealer has now updated translations for 20 languages.

## 2 August 2019

### Tooltip on check-in when mileage is missing 
Users reported that it was hard to identify why it was not possible to check-in a vehicle when the mileage was missing in Booked page. A tooltip has been added on the checkbox which is explaining the reason why the user cannot proceed further.

## 22 July 2019

### Customer Interface Released
A new widget has been released in Digital Dealer for the Service Advisor and a Customer Page for the customer which together enable both parties to have a conversation upon a due maintenance in order to book the vehicle in.

### Workshop Schedule widget
On the booked page, without having selected a workorder, the user can see an overview of the workorders that are in status booked and beyond. 
- It shows one bar per workorder with drop-off-, start-, end- and pick-up- time. 
- Within the bar it states chassis-number, registration number and customer name. 
- Mouseover gives additional information about the content of the workorder. 
- Clicking the bar opens the workorder. 
- Different colours indicate the status of the workorder. 
- A red line shows the current time. 

## 5 July 2019

### Notes widget - edit functionality
- Users feedback reported the need to be able to edit a note in the notes widget. It is now possible to update the text saved into notes.

### Release notes moved to the start page
- The news regarding releases on Digital Dealer Dashbaord are now available in the start page to make it easier for the users to access them.

## 19 June 2019

### Link to SPII (Scania Product Individual Information) in vehicle details widget
- Users feedback reported the need to access more information regarding the vehicle. It is now possible to access SPII directly from a link in the vehicle details widget.

### Mileage not available due – FMS subscription
- In specific conditions, mileage from C200/C300 cannot be retrieved. In those situation it was not possible for the service advisor to understand the reason.
A short description of the issue is exposed into the vehicle details widget.
Reasons:
  1. No communicator available for the vehicle – error message: Missing communicator
  2. No active subscription with FMS available for the vehicle – error message: No subscription
  3. Customer didn’t allowed Scania to access the information – error message: Not allowed

## 4 June 2019

### Maintenance widget - general improvement
- Takeover and Handover are now only available in “blank” and “TRR” status
- It is not possible anymore to select a maintenance in the opportunities widget which is not assigned to the workshop

## 21 May 2019

### Expose multiple results in the “Search”
- In case the service advisor is looking for a registration number or a chassis number which are not unique, it is now possible to see multiple options displayed om a drop-down list in the search results.

### Sorting of workorders list
- It is now possible to re-order workorders in the lists (Leads, Saved, Booked and In production) so to see newest leads on top.

### Notes widget exposed on all pages
- The note widget is now exposed in every step of the workorder flow(Leads, Saved, Booked, In production).

## 15 May 2019

### Takeover
- It is now possible to take over a single maintenance event from another workshop.
- To perform a Takeover, search for a vehicle and expand the details in the maintenance widget in the result page. 
- In order to do it the maintenance event should be in status "empty" or "TRR" (takeover will not be available on "TR" and "WO" status)

### Handover
- It is now possible to hand over a single maintenance event to another workshop.
- To perform a Handover, expand the details in the maintenance widget. 

## 10 May 2019

### Automatic filling of mileage in Booked and In production pages
- The system is now automatically fetching the latest available mileage in the Mileage widget in booked and in production pages.

### Counter for available occasion in each list
- A new counter indicating how many workorder are present in the current list has been added into the header.

## 26 Apr 2019

### WhatFix
- To simplify the process of informing users and giving them an automated way to get informed and learn new way of workings and procedure, Digital Dealer deployed WhatFix to simplify the communication to users. 
- Guided tours available are now available for users in the “SelfHelp” label in Digital Dealer Dashboard. 

### "Mark as done" button only available if a maintenance is selected
- Users feedback reported that it was simple to move a lead as “done” without selecting any maintenance. This behaviour is considered confusing for users. From now on, users can move a lead to the next step (done/saved) only if a maintenance occasion have been selected.

### Summary for maintenance event
- A summary exposing all parts, standard times and fluids, is added in the maintenance widget so to expose in a single place all what is needed to perform the maintenance event.

### Operation code added to module details 
- Users feedback reported the need of knowing the operation code included in each module. The operation code has been added for each standard time in the maintenance event.

## 25 Apr 2019

### Work Order Flow

Starting from today, Digital Dealer is supporting the whole journey of the vehicle in the workshop, from the moment a lead on a vehicle is received (a maintenance is due) to the point when the truck leaves the workshop.

This flow includes four new phases to follow up the vehicle during the activities:
  1. Leads: here you can select WHAT needs to be performed on the truck, selecting from the proposed opportunities.
  2. Saved: in this phase, you define WHEN to perform the activities you selected.
  3. Booked: in this phase, you wait for the customer and you check in the vehicle when it physically arrives to the workshop.
  4. In production: this phase exposes the information related to the activities ongoing on the vehicle while it is in the workshop.    This phase ends when he vehicle is handed over to the customer.
  
## 24 Apr 2019

### New information in Vehicle details - brake pads
- Improved the visualization of the brake pads details, exposing details per axle in operational analysis widget in opportunities.

## 18 Apr 2019

### Date updates in the lead if the maintenance gets recalculated
- When the maintenance planned date is changed due to recalculation, the planned date of the lead is updated according to the same date.

## 16 Apr 2019

### Search in dropdown list for selecting a workshop
- Search functionality added to the dropdown list for selecting the workshop by clicking the dropdown list and simply start typing.

## 25 Mar 2019

### Number of available occasions 
- New counter added for each opportunity, exposing number of available occasions. New indication exposed to indicate the widget is not working properly in order to distinguish the case when there is no available occasion (0 campaigns for the vehicle) or when the information is not possible to retrieve due to technical issues.

## 15 Mar 2019

### Changed behaviour for leads marked as done but still in TRR status
- Leads marked as done will not be recreated into “Open leads” list.

### Corporate EPC contracts
- EPC contracts added to the dashboard in contract widget.

## 06 Mar 2019

### Performing workshop
- Performing workshop added to the details of the maintenance event.

### New information in Vehicle details
- Delivery date and Warranty end date added to Vehicle details in dashboard.

## 01 Mar 2019

### Beacon for news in “Dashboard updates”
- A small red blinking beacon will inform the user every time new content is available in the "Dashboard updates" section.

### New leads list layout
- New graphical layout.

### Alert for session time out
- Today, session times out without notification and this causes problems for users trying to use the dashboard.
To alert user when the log in session is timed out, an alert function is implemented to notify and to reload the page.
When this message appears, user is prompted to press “Renew session” button. Same page will be reloaded and user can continue to work.

### Added country code to contracts
- Contracts for different markets are now shown in the dashboard. Country code is added to information so user easy can identify which contract is valid.

## 18 Jan 2019
### Software update widget improved
- Software update widget has been graphically improved so to expose more content and display it in a tidier and richer format.

## 11 Jan 2019
### Preparation for coming Role - Service Sales Person now added as user when requesting access
- From now the user has to specify the role for whom the access is requested. Either Service Advisor or Service Sales Person can be chosen and gives the user access to the respective dashboard. The default is set to Service Advisor.

## 2 Jan 2019
### New layout of search in header
- This update changes the layout of the search field in the header. It also changes the icon to access release information.

## 21 Dec 2018
### User is now able to order leads by customers' name
- This update allows the user to order leads according to the customers' name via the filter function in the leads list.

### Minor bug fixes
- Lead doesn't expose customers' name even if the information is present
- Created lead is re-created when chassis number has been translated to VIN
- Bad chassis not filtered out in Planned Maintenance properly

All of the above has been solved!

## 7 Dec 2018
### Empty leads moved to "done leads" automatically
- The lead is now reflecting changes in the planned date of the maintenance event. If the maintenance is managed without the support of the dashboard and it is reported as performed, the lead is automatically moved to “Done Leads”.
Furthermore, if a maintenance event which generated a lead is moved in time and the planned date is changed, the lead will now properly reflect this change.
Please note! Existing leads should be marked as done manually!


## 30 Nov 2018
### Vehicle details widget
- Mileage now to be found in vehicle information.
- Separate mileage widget has been removed.

### Free text field for notes.
- Delete function added.

## 23 Nov 2018
### Maintenance widget improvements
Details regarding maintenance modules have been added to the the maintenance widget:
- Module details;
- Parts with details of description, parts number and quantity;
- Fluids with details of which kind of fluid and the required volume;
- Labour with the description of the standard time and duration.

### Fault codes in local languages 
Fault codes widget is now exposing alerts and details in the user’s language.

## 16 Nov 2018
### Search improvements
Search function is now updated with the possibility to use space and hyphen when searching for a registration number, for example 70-BKN-9.
Information about vehicle will appear when user hits search button.

## 09 Nov 2018
### Maintenance protocol
Additional data is now available in the maintenance protocol for Flexible maintenance in the maintenance widget.

## 02 Nov 2018
### Search improvements
Now the user can also search a vehicle using registration/VIN number in the search field as it was possible to do using chassis number.

## 29 Oct 2018
### Feedback feature available in the dashboard
Users can now provide their feedback regarding the Dashboard, pressing "Give feedback" on the right side of the page.
All feedbacks are collected by Digital Dealer Team (centrally at factory level) in order to improve the quality of the dashboard.

## 26 Oct 2018
### Changelog feature available in the dashboard
Starting from today, all new features will be announced using this channel also.
- Major features (features which might impact users' way of using Dashboard) will be announced here and additional details will reach superusers before the deployment;
- Minor features (features which might *NOT* impact users' way of working) will be described here.

### Maintenance widget improvement and protocol for Flexible maintenance
The maintenance protocol for Flexible maintenance has been added to the maintenance widget;
- General improvements to the maintenance widget: header added
- In the widget, a new section called "download" is available;
- A "PDF" button allows the user to download the document;
- The protocol is available in the same language of the user's dashboard;
- Additional information on the protocol will be added in the next update.

### Free text field for Notes
A field for free text is added to the upper right corner when you open a Lead in the dashboard. Press Write to open the widget.
- Number of characters not limited;
- Notes are saved in relation to the Chassi number.

### New tabs in Dashboard, Open and Done Leads
The Service Advisor now have the possibility to categorise the leads in “Open” and “Done”.
- “Open leads” and “Start” will have the same content for the moment. This is showing all the leads that the Service Advisor did not book time for in the workshop. A lead should be marked as “Done” when a booking has been agreed with the customer.
- “Done leads” will show the 40 latest Leads, marked as Done.
