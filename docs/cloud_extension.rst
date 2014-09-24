=======================
Wakanda Cloud extension
=======================

The Cloud Extension allows you to interact with the Wakanda PaaS Service from Wakanda Studio.

.. image:: images/20_cloud_extension.png
	:align: center

***************************
Publishing your application
***************************

At any time during your development, you can publish your application to Wakanda PaaS by clicking on the ``Cloud`` button.

Once published, you can update your remote application by simply clicking on the ``Cloud`` button or on the ``Publish`` menu item.

Publishing for the first time
=============================

To deploy your application to the cloud for the first time:

1.	Open your local application in Wakanda Studio.
2.	Click on the ``Cloud`` button.
3.	Type in your Wakanda PaaS credentials.
4.	Select the target remote application.
5.	Click on the ``Publish`` button.

.. image:: images/21_publish_window.png
	:align: center

Updating the remote application
=============================

After the first deployment, you can update your remote application by clicking on the ``Cloud`` button or the ``Publish`` menu item. If you want to select the exact files to publish the remote application, disable the `Auto-Commit`_ option.

***********************
Cloning the application
***********************

The clone feature allows you to download your entire remote application, including its modification history.

To clone an already published Wakanda application, click on the ``Clone`` menu item

.. image:: images/22_clone_selection.png
	:align: center

Select the target application from the list and click on ``Clone``.

.. image:: images/26_clone_window.png
	:align: center

Once the  apllication is cloned, the solution will be opened automatically in Wakanda Studio.

********
Settings
********

Customize the behavior of the Wakanda Cloud extension by selecting Settings from the Cloud menu.

.. image:: images/23_setting_selection.png
	:align: center

.. image:: images/24_setting_window.png
	:align: center

Wakanda Cloud credentials
========================

To modify your Wakanda Cloud credentials just type in the new values on the corresponding areas. It is also possible to completely remove your existing credentials by erasing both the login and password fields.

To save your modifications click on ``Save`.

Remote Git Repository
=====================

//Contenu

Auto-commit
===========

By activating this feature, the studio will automatically publish all the local modifications to the remote application.

If the ``auto-commit`` option is disabled, you choose the files to be published to the remote application whenever you click on the ``Cloud`` button or the ``Publish`` menu item.

.. image:: images/25_deactivated_autocommit.png
	:align: center

Click on the ``Save`` button to save your settings.
