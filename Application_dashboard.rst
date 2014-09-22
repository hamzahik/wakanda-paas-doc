=========================
The application dashboard
=========================

By selecting an app in the application list, you will have access to a control panel with different views.

************
General view
************

The general view gives you a summary of the application’s details. 
It contains information about real-time usage statistics of memory and disk, as well as a control panel and the application’s history.


Stop/Start/Reload your application
==================================

You can access the control panel to manage the state of your remote application: stop it, start it or reload it.

.. image:: images/1_control_panel.png
	:align: center

Summary
=======

The summary block displays the current information related to the git repository

.. image:: images/2_git_repository.png
	:align: center

or the RAM and Disk currently in use by your application

.. image:: images/3_memory_disk_statistics.png
	:align: center

It will help you to make the correct decisions to scale your application up and down.

Application logs
================

The recent actions you have executed are displayed in the associated view. 

.. image:: images/4_recent_operations.png
	:align: center

If you want more detailed logs you can click on the ``application logs`` button to be redirected to the application logs view.

.. image:: images/5_application_log_link.png
	:align: center

***************
Monitoring view
***************

The monitoring view allows you to monitor the activity of your application, by charting usage statistics of memory, storage and network I/O.

Graph's time-frame
==================

You can configure the time frame of your graphs by setting a display window 

.. image:: images/6_graph_display_window.png
	:align: center

and a starting point	

.. image:: images/7_graph_start_date.png
	:align: center

Add metrics
===========

You can add new metrics to a graph simply by clicking on the add button ``+`` , selecting the metric you want from the list and then clicking on ``add to graph`` button 

.. image:: images/9_add_metrics.png
	:align: center

You can also hide or show your selected metrics from the graph by clicking on the control button.

.. image:: images/10_graph_parameter_button.png
	:align: center

Delete/add graphs
=================

The ``x`` button allows you to delete the graph from the monitoring view.

To add a new graph, you simply click on the ``new chart`` button 

.. image:: images/11_add_chart.png
	:align: center

************
Domains view
************

Wakanda allows for multi-project applications. To get them running you need subdomains or custom domains to relay received requests to the correct project.

Add a sub domain
================

You can add new subdomains by typing the subdomain you want and clicking on the add button.

.. image:: images/12_subdomains_view.png
	:align: center

The newly created subdomain will be automatically added to the list of your application’s subdomains.

.. note::

	A subdomain must be unique.

Add a custom domain
===================

If you have domains you want to bind with your application, you simply have to add it in the custom domains section.
You insert your custom domain and then click on the add button 

.. image:: images/13_custom_domain_view.png
	:align: center

The newly bound custom domain will be automatically added to the list of your application’s custom domains.

****************
Permissions view
****************

The Permissions view offers the ability to work in a collaborative mode by managing user and group permissions.

Create a group
==============

You can create a new group by clicking on the ``add group`` button 

.. image:: images/14_add_group_button.png
	:align: center

A new pop up appears inviting you to type in:

-	The name of the group 
-	The collaborators emails in the add users section 
-	The permissions for this group of users 

Then you click on the save changes button and your newly created group will be added to the groups list

.. image:: images/15_add_group_window.png
	:align: center

.. note::

    The owner group is automatically created with your application and contains your email only; no other user can be added to it.


Manage users
============

Within the users panel, you can add or remove collaborators from the selected group.
To add a new user to the group you click on the ``add users to the group`` link or the ``manage users`` button

.. image:: images/17_manage_user_button.png
	:align: center

and then type in the user’s email and click on invite or select an existing user from one of your application’s existing groups

.. image:: images/18_add_user_window.png
	:align: center

You can also delete a user from a group by clicking on the ``X`` button in the user panel or in the manage users view by deselecting it.

Configure group permissions
===========================

You can configure group permissions by clicking on the ``lock`` button.

.. image:: images/19_permission_button.png
	:align: center

A predefined list of permissions appears where you can select/deselect the permissions you want to attribute to the group and then save the changes.

Delete a group
==============

You delete a group by simply clicking on the ``X`` button of the group.