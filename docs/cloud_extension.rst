===========================
The Wakanda Cloud extension
===========================

The Cloud Studio Extension allows you to interact with the Wakanda PaaS Service.

.. image:: images/20_cloud_extension.png
	:align: center

*******
Publish
*******

At any time during your development, you can publish your application to Wakanda PaaS by clicking on the ``Cloud`` button.

Once published, updating your remote application will simply require a click on the ``Cloud`` button or on the ``Publish`` menu item.

First publish
=============

To deploy your application to the cloud for the first time:

1.	Open your local application in Wakanda Studio
2.	Click on the ``Cloud`` button
3.	Type in your Wakanda PaaS credentials
4.	Select the target remote application
5.	Click on the publish button.

.. image:: images/21_publish_window.png
	:align: center

Update the remote application
=============================

After the first deployment, you can update your remote application by a simple click on the ``Cloud`` button or the ``Publish`` menu item. To select the exact files to be published to the remote application, you can disable the `Auto-Commit`_ option.

*****
Clone
*****

The clone feature allows you to download your whole remote application's code and modifications, history included.

To clone an already published Wakanda Application, click on the clone menu item

.. image:: images/22_clone_selection.png
	:align: center

Select the target application from the list then click on the ``clone`` button

.. image:: images/26_clone_window.png
	:align: center

Once the clone operation is completed, the solution will be opened automatically in the Studio.

********
Settings
********

The settings dialog helps you customize the PaaS extension's behaviour.

.. image:: images/23_setting_selection.png
	:align: center

.. image:: images/24_setting_window.png
	:align: center

Wakanda PaaS Credentials
========================

To modify your Wakanda PaaS credentials just type in the new values on the corresponding areas. It is also possible to completely remove your saved credentials by cleaning both the login and password fields.

To save your modifications click on the save button.

Remote Git Repository
=====================

//Contenu

Auto-commit
===========

By activating this feature, the studio will automatically publish all the local modifications to the remote application.

If the ``auto-commit`` option is deactivated, you'll be asked to choose the files to be published to the remote application whenever you click on the ``Cloud`` button or the ``Publish` menu item.

.. image:: images/25_deactivated_autocommit.png
	:align: center

Click on the ``Save`` button to save your settings.
