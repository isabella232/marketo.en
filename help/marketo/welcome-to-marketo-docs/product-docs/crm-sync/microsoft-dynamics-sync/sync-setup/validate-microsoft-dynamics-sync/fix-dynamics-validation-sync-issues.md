---
unique-page-id: 10095429
description: Fix Dynamics Validation Sync Issues - Marketo Docs - Product Documentation
title: Fix Dynamics Validation Sync Issues
---

# Fix Dynamics Validation Sync Issues {#fix-dynamics-validation-sync-issues}

Fix Dynamics Validation Sync Issues - Marketo Docs - Product Documentation

### What's in this article? {#what-s-in-this-article}

[Validate Sync Tool Results](#fixdynamicsvalidationsyncissues-validatesynctoolresults)  
[URL is valid](#fixdynamicsvalidationsyncissues-urlisvalid)  
[Username and password are valid](#fixdynamicsvalidationsyncissues-usernameandpasswordarevalid)  
[Sync user is assigned to the Marketo Sync User role](#fixdynamicsvalidationsyncissues-syncuserisassignedtothemarketosyncuserrole)  
[Marketo solution is properly installed](#fixdynamicsvalidationsyncissues-marketosolutionisproperlyinstalled)  
[All steps in the solution are enabled](#fixdynamicsvalidationsyncissues-allstepsinthesolutionareenabled)  
[Sync user is assigned to the Marketo solution](#fixdynamicsvalidationsyncissues-syncuserisassignedtothemarketosolution)  
[Sync user matches username and password](#fixdynamicsvalidationsyncissues-syncusermatchesusernameandpassword)

#### Validate Sync Tool Results {#fixdynamicsvalidationsyncissues-validatesynctoolresults}

##### When you run the Dynamics Validate Sync, it generates this report. If there's an ![--](assets/delete.png) next to a step, see below to identify and fix the problem. Then rerun the sync validation steps until the result shows nothing but checkmarks. {#fixdynamicsvalidationsyncissues-whenyourunthedynamicsvalidatesync-itgeneratesthisreport.ifthere'sannexttoastep-seebelowtoidentifyandfixtheproblem.thenrerunthesyncvalidationstepsuntiltheresultshowsnothingbutcheckmarks.}

![](assets/image2015-9-22-15-3a58-3a12.png)

#### URL is valid {#fixdynamicsvalidationsyncissues-urlisvalid}

If you have an ![--](assets/delete.png) here, verify that the URL is valid. Find it here in Developer Resources and look at Organization Service. The URL could be invalid for a number of reasons.

##### 1. Log-in to Dynamics. Click the Settings icon and select Advanced Settings. {#fixdynamicsvalidationsyncissues-log-intodynamics.clickthesettingsiconandselectadvancedsettings.}

![](assets/one.png)

##### 2. Click Settings and select Customizations. {#fixdynamicsvalidationsyncissues-clicksettingsandselectcustomizations.}

![](assets/two.png)

##### 3. Click Developer Resources. {#fixdynamicsvalidationsyncissues-clickdeveloperresources.}

![](assets/three.png)

##### 4. The Organization Service URL can be found under Service Endpoints. {#fixdynamicsvalidationsyncissues-theorganizationserviceurlcanbefoundunderserviceendpoints.}

![](assets/four.png)

#### Username and password are valid {#fixdynamicsvalidationsyncissues-usernameandpasswordarevalid}

If you have an ![--](assets/delete.png) here, verify that your Microsoft Dynamics username and password are valid.

#### Sync user is assigned to the Marketo Sync User role {#fixdynamicsvalidationsyncissues-syncuserisassignedtothemarketosyncuserrole}

If you have an ![--](assets/delete.png) here, you need to verify that the Marketo Sync User role is checked in Microsoft Dynamics. See Step 2 of the MIcrosoft Dynamics installation documentation.

##### 1. In Dynamics, click the Settings icon and select Advanced Settings. {#fixdynamicsvalidationsyncissues-indynamics-clickthesettingsiconandselectadvancedsettings.}

![](assets/one.png)

##### 2. Click Settings and select Security. {#fixdynamicsvalidationsyncissues-clicksettingsandselectsecurity.}

![](assets/six.png)

##### 3. Click Users. {#fixdynamicsvalidationsyncissues-clickusers.}

![](assets/image2015-9-24-9-3a47-3a25.png)

##### 4. Click the link for the sync user. {#fixdynamicsvalidationsyncissues-clickthelinkforthesyncuser.}

![](assets/seven.png)

##### 5. Click Manage Roles. {#fixdynamicsvalidationsyncissues-clickmanageroles.}

![](assets/eight.png)

##### 6. Verify that the Marketo Sync User role is checked. If not, check it and click OK. {#fixdynamicsvalidationsyncissues-verifythatthemarketosyncuserroleischecked.ifnot-checkitandclickok.}

![](assets/image2015-9-24-9-3a59-3a21.png)

#### Marketo solution is properly installed {#fixdynamicsvalidationsyncissues-marketosolutionisproperlyinstalled}

If you have an ![--](assets/delete.png) here, Go to Microsoft Dynamics to verify the Marketo installation is there. See Step 1 of the MIcrosoft Dynamics setup documentation.

##### 1. In Dynamics, click the Settings icon and select Advanced Settings. {#fixdynamicsvalidationsyncissues-indynamics-clickthesettingsiconandselectadvancedsettings..1}

![](assets/one.png)

##### 2. Click Settings and select Solutions. {#fixdynamicsvalidationsyncissues-clicksettingsandselectsolutions.}

![](assets/eleven.png)

##### 3. Verify the solution is listed. {#fixdynamicsvalidationsyncissues-verifythesolutionislisted.}

![](assets/twelve.png)

#### All steps in the solution are enabled {#fixdynamicsvalidationsyncissues-allstepsinthesolutionareenabled}

If you have an ![--](assets/delete.png) here, verify that none of the default steps have been deactivated. All steps are automatically enabled at installation, but they could be deactivated during a customization.

#### Sync user is assigned to the Marketo solution {#fixdynamicsvalidationsyncissues-syncuserisassignedtothemarketosolution}

If you have an ![--](assets/delete.png) here, make sure the Sync user is assigned on the Marketo Default page in Microsoft Dynamics.

##### 1. In Dynamics, click the Settings icon and select Advanced Settings. {#fixdynamicsvalidationsyncissues-indynamics-clickthesettingsiconandselectadvancedsettings..2}

![](assets/one.png)

##### 2. Click Settings and select Marketo Config.  {#fixdynamicsvalidationsyncissues-clicksettingsandselectmarketoconfig.}

![](assets/thirteen.png)

##### 3. Verify that the sync user is assigned as the default. {#fixdynamicsvalidationsyncissues-verifythatthesyncuserisassignedasthedefault.}

![](assets/fourteen.png)

#### Sync user matches username and password {#fixdynamicsvalidationsyncissues-syncusermatchesusernameandpassword}

If you have an ![--](assets/delete.png) here, be sure to assign the proper sync user in the Marketo User field in the Marketo Config Default setup step in Microsoft Dynamics.

>[!NOTE]
>
>**Related Articles**
>
>[Validate Microsoft Dynamics Sync](../../../../../../welcome-to-marketo-docs/product-docs/crm-sync/microsoft-dynamics-sync/sync-setup/validate-microsoft-dynamics-sync.md)
