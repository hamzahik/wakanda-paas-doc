===============
Getting Started
===============

The following video demonstrates how to create an application from the dashboard and how to delpoy and update it using the studio.

.. raw:: html

 <iframe width="420" height="315" src="//www.youtube.com/embed/5c2BeD-S958" frameborder="0" allowfullscreen></iframe><br><br>

You can read the rest of this guide for a more detailed explanation.

*****************************
Creating my first application
*****************************

Once you are connected to your dashboard, click on the "create your first app" link to open the application creation wizard.

.. image:: images/noapps.png

Start by choosing an application type from the suggested offers, in our case we will be creating a free application. To do so click on the "Try it now" button.

.. image:: images/try_it_now.png

By default, your application will be created in the US region, you can change that by choosing a different region from the list.

.. image:: images/region.png

Choose a valid application name

.. image:: images/domain.png

Optionally, you can add subdomains and custom domains to your application's configuration.

.. image:: images/subdomains.png

.. image:: images/custom_domains.png

To create your application click on the "Finish" button.

.. image:: images/finish.png

*************************************
How to update my deployed application
*************************************

To update your deployed application all you need to do is push your new code to your application's remote repository.
This can be done using the Studio's PaaS Extension, GIT Command Line or any IDE supporting GIT Smart HTTP.

Application remote repository
=============================

You can get your application's remote repository URL by clicking the "copy repository" button 

.. image:: images/git_copy_repo.png

Using the Studio
================

.. raw:: html

 <iframe width="420" height="315" src="//www.youtube.com/embed/5c2BeD-S958" frameborder="0" allowfullscreen></iframe><br><br>

Using the command line
======================

Push your application to the remote repository using the following command ::

 $ git push http://git.[my-application-name].us.wak-apps.com master
 
If your local repository is using a different branch than "master" ::

 $ git push http://git.[my-application-name].us.wak-apps.com [local-branch-name]:master

 
**************************************
What port should my projects listen on
**************************************

All the projects of your application should listen on the port 8081.
This means that if you have a multi projects application, each project should have a different host, this can be done by adding sub-domains or custom domains to your application.

