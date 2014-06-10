===============
Getting Started
===============

*************************************
How to update my deployed application
*************************************

To update your deployed application all you need to do is push your new code to your application's remote repository.
This can be done using the Studio's PaaS Extension, GIT Command Line or any IDE supporting GIT Smart HTTP.

Using the Studio
================

.. raw:: html

 <iframe width="560" height="315" src="//www.youtube.com/embed/Pg7FlJdx64o" frameborder="0" allowfullscreen></iframe>

* How to install the paas extension

Using the command line
======================

If your application's address is ::

 http://[my-application-name].us.wakapps.com

your application's remote repository will be ::

 http://git.[my-application-name].us.wakapps.com

Push your application to the remote repository using the following command ::

 $ git push http://git.[my-application-name].us.wakapps.com master
 
**************************************
What port should my projects listen to
**************************************

All the projects of your application should listen to the port 8081.
This means that if you have a multi projects application, each project should have a different host, this can be done by adding sub-domains or custom domains to your application.

*****************************************
How to deploy a multi project application
*****************************************


***************************************************
How to access my application's administration panel
***************************************************
