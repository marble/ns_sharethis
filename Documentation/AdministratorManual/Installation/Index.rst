.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../../Includes.txt

.. _installation:

Installation
============
The extension needs to be installed as any other extension of TYPO3 CMS:

Install Extension from EM:
--------------------------

#. Switch to the module “Extension Manager”.

#. Get the extension

#. **Get it from the Extension Manager:** Press the “Retrieve/Update” button and search for the extension key *ns_sharethis* and import the extension from the repository.

#. **Get it from typo3.org:** You can always get current version from `https://extensions.typo3.org/extension/ns_sharethis/ <https://extensions.typo3.org/extension/ns_sharethis/>`_ by downloading either the t3x or zip version. Upload the file afterwards in the Extension Manager.

.. figure:: Images/TYPO3-EXTns_sharethis-Install_1.png
    :alt: Install_1


Preparation: Include static TypoScript
--------------------------------------

The extension ships some TypoScript code which needs to be included.

#. Switch to the root page of your site.

#. Switch to the **Template module** and select *Info/Modify*.

#. Click the link **Edit the whole template record** and switch to the tab *Includes*.

#. Select **[NITSAN] ns_sharethis** at the field *Include static (from extensions):*

.. figure:: Images/TYPO3-EXTns_sharethis-Install_2.png
    :alt: Install_2

