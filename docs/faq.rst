===
FAQ
===

**************************************************
How many free applications am I allowed to create?
**************************************************

The Wakanda Cloud beta program puts an upper limit on the number of free applications that you can create.
The limit is currently two free applications per Wakanda Cloud account.

*************************************************************************************
Do applications shared with me decrease the number of free applications I can create?
*************************************************************************************

No. You can have as many applications shared with you as you want. You will still have the same upper limit of the number of free applications.

******************************************************************************
What happens if my application is not used for a long time? does it get idled?
******************************************************************************

The current policy is to keep all deployed applications running.

*****************************************************************
What happens to my application's data in case of a major failure?
*****************************************************************

In the free beta program, we don't guarantee the availability of your data in case of unexpected failure events.
Backup features are undergoing continuous enhancements at the moment. they will be available in the next release of our service.

***********************************************
How do I report bugs to the Wakanda Cloud team?
***********************************************

To report a bug to the Wakanda Cloud team you can contact the Cloud Support Team at cloudsupport@wakanda.org

****************************
How can I reset my password?
****************************

You can send a request to the Wakanda Cloud support team at (cloudsupport@wakanda.org) using your account email address. Once your request is confirmed you will receive an email with your new password.

******************************************************************
What version of Wakanda is used on the Wakanda Cloud beta service?
******************************************************************

Wakanda Cloud beta program uses Wakanda Enterprise 9.

**********************************************************************************************************
Can I use Wakanda Enterprise's "connectors" or "connectors pro" in the applications I deploy to the Cloud?
**********************************************************************************************************

Wakanda Cloud beta program does not currently support Wakanda Enterprise's "connectors" or "connectors pro". However, they will be included in the service as it evolves.
We will keep you updated as new features are integrated in the service.

***************************************************
How do I report a feature request to Wakanda Cloud?
***************************************************

To report a feature request to Wakanda Cloud use the Cloud Support email address or post your requests on the following forum thread http://forum.wakanda.org/xxxxxxxxxxx

**************************************************************
Do I have access to Wakanda's default administration solution?
**************************************************************

Wakanda Cloud beta program does not provide access to Wakanda's default administration solution. You can, however, manage the state of your applications using the console.

***************************************
What port should my projects listen on?
***************************************

All the projects of your application should listen on the port 8081.
This means that if you have a multi project application, each project should have a different host, this can be done by adding sub-domains or custom domains to your application.
