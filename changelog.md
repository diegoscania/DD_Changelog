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
