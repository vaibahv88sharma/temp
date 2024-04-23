##########
##########

# App Principal

## Display name
### DevOps_CiCd

## Application (client) ID
### 2a22ed2f-15ee-4589-a741-b0b510499224

## Object ID
### 5387d6d2-7d58-437d-af8c-c2c673d8a94d

## Directory (tenant) ID
### 7ce9b6c3-7c60-4979-9d40-3b7282483f99

## Custom Secret 7

## Value
### Vjy8Q~xhbrQGsZreY5O2maGQKz2BaFq3mcNu3b3b

## Secret ID
### 9e1bdd8d-c99a-4420-840a-816b5584391f

##########
##########

# Canvas App

## ComponentLibrary_MenuLeftNav (2 level menu)
## Mobile_RsponsveAttrib_CstmActonAPI_MenuComponent
### https://www.youtube.com/watch?v=3S0h2nODcxM&ab_channel=RezaDorrani

## Lptop_Rsponsiv_Breakpnt_Popup_SecrityRol
### https://www.youtube.com/watch?v=8T9Pa58H1Co&ab_channel=RezaDorrani
### https://www.youtube.com/watch?v=J-hMMXrKMVE&t=1277s&ab_channel=RezaDorrani
### https://www.youtube.com/watch?v=HIS36rspx6g&ab_channel=RezaDorrani

## Responsive_Screen_Gallery_Filters_A
## Rsponsve_Scren_Galery_Filter_A_GrdEdit_ManualBtnPerRow

## Rsponsve_Scren_Galery_Filter_A_GrdEdit_OnHidenRowSelect
### https://www.youtube.com/watch?v=ubnPqwWdBL0&ab_channel=RezaDorrani
### https://www.youtube.com/watch?v=1QflzfPyPe0&ab_channel=RezaDorrani
### https://www.youtube.com/watch?v=wI6SHGQ9ATg&ab_channel=RezaDorrani

## Edit_Grid_Modern_Controls_Patch_UpdateIf_ShowColumns_B
### https://www.youtube.com/watch?v=76RJyaoW0BQ&t=916s&ab_channel=RezaDorrani
### https://www.youtube.com/watch?v=1QflzfPyPe0&ab_channel=RezaDorrani

## Rsponsve_Edit_Grid_Bulk_CRUD_UpdateIF_FirstError_C
## Rsponsve_Edit_Grid_Bulk_CRUD_UpdateIF_FirstError_C2
### https://www.youtube.com/watch?v=P6yqIpjmPrs&ab_channel=RezaDorrani
### https://www.youtube.com/watch?v=wI6SHGQ9ATg&ab_channel=RezaDorrani

## GalleryAndFormOnSameScreen_FormLastSubmit_D
### https://www.youtube.com/watch?v=HHXKfB1iAH4&ab_channel=RezaDorrani
### https://www.youtube.com/watch?v=S0Zs66RVka4&ab_channel=RezaDorrani
### https://www.youtube.com/watch?v=N8DWvS7P9lw&ab_channel=ShaneYoung

## Tab_Single_Form_Multi_Screen_Coalesce_E
### https://www.youtube.com/watch?v=rFDFWQWk81k&ab_channel=RezaDorrani
### https://www.youtube.com/watch?v=p1tXRy_hyrQ&ab_channel=ShaneYoung
### https://www.youtube.com/watch?v=XvevCq6qhX4&ab_channel=RezaDorrani

## Tab_Multi_Screen_Multi_Form_Valid_Updates_Error_F
### https://www.youtube.com/watch?v=9gI9OscTLD0&ab_channel=RezaDorrani
### https://www.youtube.com/watch?v=rxL_Wcs3kJA&ab_channel=RezaDorrani


########
########
# FLow error

### https://learn.microsoft.com/en-us/power-platform/admin/power-automate-licensing/types#can-i-use-service-principal-in-flows-and-does-it-count-against-my-request-limits
### https://learn.microsoft.com/en-us/power-platform/admin/powerapps-powershell#power-automate-commands
### https://medium.com/@mustaque.plr/power-automate-tenant-pool-failure-troubleshooting-b9c70cbf60db

########
########
# Portal

## File Download
### Authentication/FilesDownloadLink
### https://nhficgrantsuat.powerappsportals.com/File/download.aspx?Entity=nhfic_applicationdocument&Attribute=nhfic_fileuploaded&Id=

## File Upload
### createUploadFile
### const odataQuery = "/\_api/nhfic_applicationdocuments?$expand=nhfic_Documentrequired($select=nhfic_description,nhfic_documenttype,nhfic_item,nhfic_informationtosupply)&$filter=_nhfic_application_value eq " + applicationGuid + "&$orderby=createdon asc";

#########
#########
# pac solution --
### online-version Sets version for solution loaded in Dataverse.
### version Update build or revision version for the solution.

#########
#########
# PCF
### root\components\D365ChoicePicker> pac pcf init --namespace D365PcfNamespace --name D365ChoicePickerField --template field

### root\components\D365ChoicePicker> npm install

### root\components\D365ChoicePicker> npm run refreshTypes

### root\components\D365ChoicePicker> npm run build
### root\components\D365ChoicePicker> npm start
### root\components\D365ChoicePicker> npm start watch

### [Environment URI]/api/data/v9.2/publishers?$select=uniquename,customizationprefix
### root\solution> pac solution init --publisher-name D365Dev --publisher-prefix d365dev
### root\solution> ## pac solution add-reference --path ..\..\component\D365ChoicePickerField
### root\solution> pac solution add-reference --path C:\Repos\1Work\D365\Dynamics365CRM_CICD\SoluionItems\Code\components\D365ChoicePickerField

### root\solution> msbuild /t:restore
### root\solution> dotnet build

### Fiddler Add Rule > Pattern > REGEX:(._?)((?'folder'css|html)(%252f|\/))?YOUR_NAMESPACE\.YOUR_CONTROL_NAME[\.\/](?'fname'[^?]_\._)(._?)$
### Fiddler Add Rule > Pattern > REGEX:(.*?)((?'folder'css|html)(%252f|\/))?D365PcfNamespace\.D365ChoicePickerField[\.\/](?'fname'[^?]*\.*)(.*?)$
### Fiddler Add Rule > Path > C:\COMPONENT_ROOT_FOLDER\out\controls\YOUR_CONTROL_NAME\${folder}\${fname}
### Fiddler Add Rule > Path > C:\Repos\1Work\D365\Dynamics365CRM_CICD\SoluionItems\Code\components\D365ChoicePickerField\${folder}\${fname}


## PCF sample
### https://github.com/microsoft/PowerApps-Samples

## Field Control
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\IncrementControl\IncrementControl\index.ts
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\LinearInputControl\LinearInputControl\index.ts
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\ControlStateAPI\ControlStateAPI\index.ts
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\FormattingAPIControl\FormattingAPIControl\index.ts
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\WebAPIControl\WebAPIControl\index.ts
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\LookupSimpleControl\LookupSimpleControl\index.ts
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\TableControl\TableControl\index.ts
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\MultiSelectOptionSetControl\MultiSelectOptionSetControl\index.ts
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\NavigationAPIControl\NavigationAPIControl\index.ts
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\IFrameControl\IFrameControl\index.ts
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\MapControl\MapControl\index.ts

## Field Control Device API
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\DeviceApiControl\DeviceApiControl\index.ts
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\ImageUploadControl\ImageUploadControl\index.ts
- https://community.dynamics.com/api/data/v9.1/msdyn_richtextfiles%288ACC9725-428F-4F6E-AE86-2BA92C8BAD7C%29/msdyn_imageblob/$value?size=full

## Field Control React
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\ReactStandardControl\ReactStandardControl\index.ts
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\ChoicesPickerReactControl\ChoicesPickerReact\index.ts
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\FacepileReactControl\FacepileReact\components\Facepile.tsx
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\FluentThemingAPIControl\FluentThemingAPIControl\components\FluentV9ThemingAPIComponent.tsx

## Dataset Control
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\DataSetGrid\DataSetGrid\index.ts
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\TableGrid\TableGrid\index.ts
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\PropertySetTableControl\PropertySetTableControl\index.ts

## Dataset Control React
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\ModelDrivenGridControl\ModelDrivenGrid\Grid.tsx

## Canvas App
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\CanvasGridControl\CanvasGrid\Grid.tsx
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\ObjectOutputControl\ObjectOutputControl\index.ts

## Virtual Control
### C:\Users\vaibhav.bo.sharma\Downloads\PowerApps-Samples-master\PowerApps-Samples-master\component-framework\PowerAppsGridCustomizerControl\PAGridCustomizer\index.ts
