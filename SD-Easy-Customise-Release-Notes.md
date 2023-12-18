## SD Easy Customise Releases

### 2.1.0

#### Enhancements

- AppSource App - The message displayed when the Remove Extension action is chosen in the SD Easy Customise Tables list or when the Delete Line action in the Table Card is chosen was updated to inform the user that if a field is deleted it is also removed from all pages and reports that it has been placed to and all data stored in the field will be irretrievably lost.

- AppSource App - A change was made to not allow users choose the Remove Extension action in the SD Easy Customise Tables list or the Delete Line action in the Table Card if the Extension Sync Mode on Setup Card is set to Add.

- AppSource App - Functionality was created to allow users to commit their extension app changes to DevOps.

- AppSource App - To make changing of FlowField formulas less restrictive for published/pending fields users can now modify FlowField filters even if the field is published.

- AppSource App - A change was made to how symbols for per tenant extensions are retrieved.

#### Bug Fixes

- AppSource App - The Object ID was not picked up after downloading symbols. Table ID 50000 was in use by another App published as Dev. Symbols are now also downloaded for extensions published as Dev.

- AppSource App - The Place Selected to Pages action on the Table Card was not working.

- AppSource App - An error was raised when publishing the extension app that a CodeUnit with the same ID already existed. To fix this the field morphism CodeUnit ID was surfaced on the Setup Card so users can update this ID if needed.

- AppSource App - An error was raised when publishing the extension app that the Page ID already exists. This was due to an API page using the same ID as an extension published as Dev. SD Easy Customise now also downloads symbols for extensions published as Dev.

- AppSource App - On first install of SD Easy Customise when the Setup cue was selected and the user chose yes to updating symbols an error was raised. This was fixed. The prompt to update symbols is now not raised until the Setup record is initialised.

- AppSource App - An error was raised on publishing the extension app when an API Page for the Customer table was created. This was fixed.

- AppSource App - With Published or Pending fields users could update the Field Name, Field Type, Field Class from the Fields FastTab in the Table Card. This was fixed.

### 2.0.0

#### Enhancements

- BCv22 App - The app and objects were renamed to SD Easy Customise. 

- BCv22 App - A Role Centre page was created for SD Easy Customise. 

- BCv22 App - A Setup card and table were created for SD Easy Customise. 

- BCv22 App - A change was made to limit SD Easy Customise to Sandbox environments only. Changes are made in a Sandbox environment, tested by users in the Sandbox environment, and then users can download the Extension App and install in the Production environment. 

- BCv22 App - Our licence controller was added to the App. 

- BCv22 App - A permission set was created for SD Easy Customise. 

- BCv22 App - On the Table Field Card for a Field Type of Text can the positions of the Extended Data Type and ToolTip fields were swapped so that the ToolTip field displays under the Deployment Status field for all Field Types.  

- BCv22 App - A small change was made to the message displayed when you delete a field in the Table Card.  

- BCv22 App - Changes were made to the default values in the Setup Card for the App Name and the Publisher. 

- BCv22 App - ToolTips on the Setup Card were updated.  

- BCv22 App - A small typo in the Page Card on the Placed Table Fields list was fixed.  

- BCv22 App - The Obsolete State field on the Table Card is now updated to Yes if a field is set to obsolete.  

- BCv22 App - New columns Table Fields, Page Fields and Report Fields were added to the SD Easy Customise Code Triggers List to allow users to drill through and view information on the fields. 

- BCv22 App - The Allow HttpClient Request option for SD Easy Customise is automatically set to on when the app is installed.  

- BCv22 App - Functionality was added to create field morphisms from table to table. 

- BCv22 App - The message displayed when a user chooses to add Trigger Code was updated.  

- BCv22 App - A small typo was fixed in the message displayed when enabling field morphism on a table. 

- BCv22 App - A FactBox was added to the Table Field card with a count of Placed on Pages, Placed on Reports and allows for drill through to associated pages.  

- BCv22 App - A change was made to the message displayed when prompting users to update symbol files.  

- BCv22 App - Changes were made to the message displayed when the Update Symbols action in the Setup Card is chosen.  

- BCv22 App -  Adding a field with an option member value of <blank> displays the option as 0. A change was made to display the value as <blank>.

- BCv22 App - The App was prepared for AppSource Submission.

- BCv22 App - The RunTime Version field was removed from the Setup Card.

#### Bug Fixes

- BCv22 App - In the Report Card you could not place the same field to the report more than once. This was fixed.  

- BCv22 App - The SD Easy Customise Report Controls page was showing a field that was initially placed on the report but the field and extension had since been removed. This was fixed.  

- BCv22 App - Selecting the Remove Layout action in the Report card opened the Import dialog.  

- BCv22 App - Adding a Field to a table with a Field Type of Option with numeric Option Members raised an error on publishing the app that the Option Members cannot be blank. This was fixed.  

- BCv22 App - Setting an additional page property did not take affect when the Extension App was published. This was fixed.   

- BCv22 App - An error was raised on publish of the extension App that the field must have a value for the ApplicationArea property. 

- BCv22 App - Placing the same field twice on the same page displayed an incorrect Field Type for the field. This was fixed.   

- BCv22 App - An error was raised on publish of the extension app when a new field was created and placed on a report. 

- BCv22 App - A small typo on the SD Easy Customise Setup card was fixed.   

- BCv22 App - Fields placed on pages were not displaying the selected Field Style. This was fixed. 

### 1.0.0

#### Enhancements

- BCv22 App - Initial Build of SD Easy Customise.  

- BCv22 App - Functionality was created to allow users surface newly created fields to reports in Business Central from within SD AL Object Builder.  

- BCv22 App - Functionality was created to allow users surface newly created fields to pages in Business Central from within SD Easy Customise.  

- BCv22 App - Functionality was created to allow users add a field to tables in Business Central from within SD AL Object Builder.  



