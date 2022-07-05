# Corporate Operations Portal Page
## Introduction
Some text

## Page Description

### 1. Page
<img src="" width=80%; height=80%/>

1. The tiles which show the links to Elements
2. Elements from the folders
3. Elements from the sub-folders
4. Your Logo
5. Your Dashboard Title

### 2. Menu
<img src="" width=80%; height=80%/>

1. Elements from Favorite folder
2. Elements from the folders
3. Elements from the sub-folders


## Installation
### 1. Access Admin > Portal Pages > Templates
<img src="" width=70%; height = 70%/>

1. Below the grid, click **[+ New Template]**
2. **Internal Name**: “links-page”
3. **[Save]**

### 2. Upload Assets
There are several ways of uploading assets:
* manually via a ZIP archive 
* syncing with a Git repository

### 2.1. [Upload Assets via ZIP archive](https://help.metricinsights.com/m/Managing_the_Metric_Insights_Environment/l/1361186-upload-portal-page-template-assets-via-zip-archive)
  
### 2.2. [Sync with Git](https://help.metricinsights.com/m/Managing_the_Metric_Insights_Environment/l/1359676-sync-portal-page-templates-with-github)

### 3. Add Variables
<img src="" width=70%; height = 70%/>

On the _Info_ tab, add the next Variables, (paths are provided for convenience):

* _Tableau Template_, _Microsoft Power BI Template_, _Qlik Sense Template_
  * These are External Report Templates, can be found under **Admin > Reference Objects > Object Templates > External Report tab**
* Digest Template: 
  * Admin > Distribution > Email Templates
* Default Notification Schedule: 
  * Admin > Distribution > Notification Schedules

 Repeat the next steps for the Variables listed above: 
1. At _Variables_ section, select **[+ Variable]**
2. Enter the **Name** and **Default Value** of the Variable. 
     * **Name**: Names of the Variables are listed above
     * **Default Value** is the ID of the Element (can be found in the URL of the element)
3. **[Apply]**

### 4. Add Portal Page:  Admin > Portal Pages
<img src="" width=70%; height = 70%/>

1. Below the grid, select **[+ New Page]**
2. **Template**: select the Portal Page Template created at Step 1
3. **[Save]**

### 5. Configure Variables
<img src="" width=70%; height = 70%/>

Optionally, you can change the values of Variables. 
<br>
Once you have made all the changes, click **[Save]**.

### 6. View the Portal Page
<img src="" width=80%; height=80%/>

1. To display the Portal Page, select **[View]** in the **_Portal Page Editor_**. 
<br>
The Links Portal Page is displayed. 

