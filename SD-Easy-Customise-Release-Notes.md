## SD Easy Customise Releases

### 3.1.2

#### Bug Fixes

- AppSource App - An error raised when downloading symbols was fixed.

### 3.1.1

#### Enhancements

- AppSource App - The SDY EC In Symbol Mgt. Codeunit was updated to allow for a new obsolete state of "PendingMove".

- AppSource App - The notification prompting users to activate a free trial of SD Easy Customise on a fresh install has been limited to display no more than once per hour on standard role centres.

### 3.1.0

#### Enhancements

- AppSource App - The Field Morphisms structure was reviewed.

- AppSource App - A change was made to the areas where user controls, i.e. the HTML editor, can be placed on pages. User controls can now only be placed before or after controls and not before or after fields.

- AppSource App - The event "Sales-Post" OnBeforePostCustomerEntry was moved to "Sales Post Invoice Events" OnPostLedgerEntryOnBeforeGenJnlPostLine and the field morphism functionality was updated to reflect this.

- AppSource App - The event "Purch.-Post" OnBeforePostVendorEntry was moved to "Purch. Post Invoice Events" OnPostLedgerEntryOnBeforeGenJnlPostLine and the field morphism functionality was updated to reflect this.

- AppSource App - An action was added to the Trigger Code page to clear existing trigger code. 

- AppSource App - A link to the user guide on the DynamicsShop page was added to the About page and to the Manage Subscriptions page.

- AppSource App - A minor change was made to the Product Activation page.

### 3.0.1

#### Enhancements

- AppSource App - A modification was made to the Setup Wizard.

- AppSource App - A minor enhancement was made to the user experience flow on initial install of SD Easy Customise.

### 3.0.0

#### Enhancements

- AppSource App - Changes were made to the SD Easy Customise functionality to allow users to use SD Easy Customise in a Live environment. Users cannot publish the extension app they have created directly into the Live environment. Users can only download the extension app from their Live environment, test the extension app in their Sandbox environment and having tested their changes, load the tested extension app up to their Live environment using Extension Management.

- AppSource App - Changes were made to the use of SD Easy Customise in Sandbox environments. Users can no longer download the extension app from a Sandbox environment. The extension app can only be published in the Sandbox environment. To free trial SD Easy Customise, users install SD Easy Customise in their Sandbox environment where they can publish the extension app directly into the Sandbox environment.

- AppSource App - The Export Data and Restore From Backup options were removed from SD Easy Customise as all the data needed for SD Easy Customise and the details of the created extension app will now always be in the Live environment.

- AppSource App - Changes were made to limit a free trial activation of SD Easy Customise Users to a Sandbox environment. A subscription licence is required to use SD Easy Customise in a Live environment. 

- AppSource App - Changes were made to the functionality used to download symbols in a Production environment.

- AppSource App - A minor change was made to the Setup Card to display a message if the Extension Sync Mode is changed from Add to Force.

- AppSource App - A new Licence Install and Setup Wizard was created.

- AppSource App - The Lead Subscription Link from the Request Subscription action in the Product Activation page was updated.

- AppSource App - The notification to activate the app, displayed on fresh install of SD Easy Customise, was added to the standard Business Central role centres.

- AppSource App - A new action was added to the Setup Card called View Our Apps. This action opens a page on AppSource pointing to all our Simply Dynamics Ltd apps.

- AppSource App - Functionality was added to provide clearer API messages in commit errors when committing changes to a GitHub or DevOps repo.

- AppSource App - The SD Easy Customise Source Control Entries page was surfaced.

- AppSource App - A minor change was made to the About page.

- AppSource App - ToolTips were updated on the Setup Card.

- AppSource App - ToolTips were updated on the Table Field Card.

- AppSource App - ToolTips were updated on the Table Fields List Part.

- AppSource App - ToolTips were updated on the Table Card.

- AppSource App - ToolTips were updated on the Page Card.

- AppSource App - ToolTips were updated on the Page Fields List Part.

- AppSource App - ToolTips were updated on the Report Card.

### 2.3.0

#### Enhancements

- AppSource App - A change was made to the licence expiry notification. The logic for checking for expiry dates was reworked.

- AppSource App - Enhancements were made to the App Request Subscription page.

- AppSource App - ToolTips were updated in the About, Product Activation, and Tenant Subscription pages.

- AppSource App - Additional phrases were added as search phrases for the SD Easy Customise pages.

#### Bug Fixes

- AppSource App - A fix was made to the error "The JSON path 'Kind' does not match any tokens." raised when Downloading Symbols.

### 2.2.2

#### Enhancements

- AppSource App - Functionality was added to migrate SD Easy Customise data from the original UAT Sandbox to a new UAT Sandbox environment. This ensures that users can now make additional changes to the extension app in a new Sandbox environment.

- AppSource App - Action ToolTips in the SD Easy Customise Setup Card were updated.

- AppSource App - A change was made when adding fields to a table to set the Enum No. field visible when Field Class is FlowField and Field Type is Enum.

### 2.2.1

#### Enhancements

- AppSource App - A new option of moved was added to the ObsoleteState options and added in SD Easy Customise.

- AppSource App - Due to a change made by Microsoft on how symbol files are now accessed, a fix was made to how the symbols are downloaded in SD Easy Customise.

### 2.2.0

#### Enhancements

- AppSource App - New functionality was introduced to change the order of field input, changing the quick entry sequence, on a page. 

- AppSource App - Functionality was added to allow users to associate a blob field on a table with a HTML Editor and surface the HTML Editor onto pages. 

- AppSource App - The Default Object ID starting range was updated to default to 80,000 instead of 50,000 on new installs of SD Easy Customise. 

- AppSource App - The caption on the new Quick Entry Sequence FastTab on the SD Easy Customise Page Card was updated.

- AppSource App - The text in a message displayed in the Page Controls page was updated.

#### Bug Fixes

- AppSource App - The Placed option for HTML Editor Fields was showing as false even though field was placed on the Card. This was fixed.

- AppSource App - The content in the HTML Editor was not updating if you navigated through the records on which it was placed. This was fixed.

- AppSource App - A fix was made for the "Content record cannot be saved because some information on the page is not up-to-date." error which ws raised on the Code Trigger list. 

### 2.1.2

#### Enhancements

- AppSource App - The logo in the SD Easy Customise App was updated to use our new logo.

#### Bug Fixes

- AppSource App - A fix was made to an intermittent message raised when downloading symbols.

### 2.1.1

#### Bug Fixes

- AppSource App - A fix was made to an error raised when a user chose yes to the validate licence prompt.

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






