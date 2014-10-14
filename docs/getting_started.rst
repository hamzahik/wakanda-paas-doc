===============
Getting Started
===============

The following video demonstrates how to create an application from the dashboard and then to deploy and update it using Wakanda Studio.

.. raw:: html

 <div id="player" class="align-center"></div><br><br><script>function onYouTubeIframeAPIReady(){player=new YT.Player("player",{height:"315",width:"420",videoId:"8YkEv0ueFpw",events:{onReady:onPlayerReady}})}function onPlayerReady(){player.setPlaybackQuality("hd1080")}var tag=document.createElement("script");tag.src="https://www.youtube.com/iframe_api";var firstScriptTag=document.getElementsByTagName("script")[0];firstScriptTag.parentNode.insertBefore(tag,firstScriptTag);var player;</script>

*******************************
Creating your first application
*******************************

Once you are connected to the dashboard, click on the ``New Application`` button to open the application creation wizard.

.. image:: images/noapps.png
	:align: center
	
Start by choosing an application type from the suggestions. In our example, we will be creating a free application. To proceed, click on the ``Try it now`` button.

.. image:: images/try_it_now.png
	:align: center
	
By default, your application will be created in the US. If you prefer a different region, you can select it from the list.

.. image:: images/region.png
	:align: center
.. note::

    Only the US region is available in the beta program

Choose a valid application name:

.. image:: images/domain.png
	:align: center

Optionally, you can add subdomains and custom domains to your application's configuration.

.. image:: images/subdomains.png
	:align: center

.. image:: images/custom_domains.png
	:align: center

To create your application, click on the ``Finish`` button.

.. image:: images/finish.png
	:align: center


**************************************
Publishing & updating your application
**************************************

Publishing your code the first time is the same as updating an already deployed application. All you need to do is push your code to your application's remote repository, which can be done using Wakanda Studio, Git Command Line, or any IDE that supports Git Smart HTTP.

Application remote repository
=============================

You can get your application's remote repository URL in the app's git repository section. 

.. image:: images/2_git_repository.png
	:align: center

Using Wakanda Studio
====================

Once you have opened your solution in Wakanda Studio, click on the Cloud button in the toolbar and select the ``Publish`` menu item.

.. image:: images/studio_update_menu.png
	:align: center

Fill in your Wakanda Cloud login information and click  ``Login``. If you want Wakanda Studio to remember your credentials, check the ``Remember me`` checkbox.

.. image:: images/studio_login_dialog.png
	:align: center

.. note::

    If you check the ``Remember me`` checkbox, your credentials will be saved as plain text in the Wakanda Cloud's preferences.
	
If this is your first deployment, you will need to associate a domain name to your application.

.. image:: images/select_app.png
	:align: center

If the operation was successful, you will receive details about the update. Otherwise, you will receive a message explaining any errors that occurred.

.. image:: images/studio_published_dialog.png

Using the command line
======================

Push your application to the remote repository by using the following command ::

    $ git push https://[my-application-name].us-git.wak-apps.com master

.. note::

    If your local repository is using a branch name other than ``master``, you must use the following command to push your application to the remote repository ::

    $ git push https://[my-application-name].us-git.wak-apps.com [local-branch-name]:master
    
.. _download: http://www.wakanda.org/downloads
.. _installation: http://doc.wakanda.org/home2.fr.html#/Installing-Wakanda/Installing-Wakanda.100-689089.en.html
.. _here: http://doc.wakanda.org/home2.fr.html#/Quick-Start/Quick-Start.100-695763.en.html
