RPA Framework
=============

.. contents:: Table of Contents
   :local:
   :depth: 1

.. include-marker

Introduction
------------

`RPA Framework` is a collection of open-source libraries and tools for
Robotic Process Automation (RPA), and it is designed to be used with both
`Robot Framework`_ and Python_. The goal is to offer well-documented and
actively maintained core libraries for Software Robot Developers.

Learn more about RPA at `Robocorp Documentation`_.

**The project is:**

- 100% Open Source
- Sponsored by Robocorp_
- Optimized for Robocorp `Control Room`_ and `Developer Tools`_
- Accepting external contributions

.. _Robot Framework: https://robotframework.org
.. _Robot Framework Foundation: https://robotframework.org/foundation/
.. _Python: https://python.org
.. _Robocorp: https://robocorp.com
.. _Robocorp Documentation: https://robocorp.com/docs/
.. _Control Room: https://robocorp.com/docs/control-room
.. _Developer Tools: https://robocorp.com/downloads
.. _Installing Python Packages: https://robocorp.com/docs/setup/installing-python-package-dependencies

Links
^^^^^

- Homepage: `<https://www.github.com/robocorp/rpaframework/>`_
- Documentation: `<https://rpaframework.org/>`_
- PyPI: `<https://pypi.org/project/rpaframework/>`_
- Release notes: `<https://rpaframework.org/releasenotes.html>`_
- RSS feed: `<https://rpaframework.org/releases.xml>`_

------------

.. image:: https://img.shields.io/github/workflow/status/robocorp/rpaframework/main?style=for-the-badge
   :target: https://github.com/robocorp/rpaframework/actions?query=workflow%3Amain
   :alt: Status

.. image:: https://img.shields.io/pypi/dw/rpaframework?style=for-the-badge
   :target: https://pypi.python.org/pypi/rpaframework
   :alt: rpaframework

.. image:: https://img.shields.io/pypi/l/rpaframework.svg?style=for-the-badge&color=brightgreen
   :target: http://www.apache.org/licenses/LICENSE-2.0.html
   :alt: License

------------

Packages
--------

.. image:: https://img.shields.io/pypi/v/rpaframework.svg?label=rpaframework&style=for-the-badge
   :target: https://pypi.python.org/pypi/rpaframework
   :alt: rpaframework latest version


.. image:: https://img.shields.io/pypi/v/rpaframework-core.svg?label=rpaframework-core&style=for-the-badge
   :target: https://pypi.python.org/pypi/rpaframework-core
   :alt: rpaframework-core latest version



.. image:: https://img.shields.io/pypi/v/rpaframework-dialogs.svg?label=rpaframework-dialogs&style=for-the-badge&color=blue
   :target: https://pypi.python.org/pypi/rpaframework-dialogs
   :alt: rpaframework-dialogs latest version



.. image:: https://img.shields.io/pypi/v/rpaframework-google.svg?label=rpaframework-google&style=for-the-badge&color=blue
   :target: https://pypi.python.org/pypi/rpaframework-google
   :alt: rpaframework-google latest version



.. image:: https://img.shields.io/pypi/v/rpaframework-pdf.svg?label=rpaframework-pdf&style=for-the-badge&color=blue
   :target: https://pypi.python.org/pypi/rpaframework-pdf
   :alt: rpaframework-pdf latest version



.. image:: https://img.shields.io/pypi/v/rpaframework-recognition.svg?label=rpaframework-recognition&style=for-the-badge&color=blue
   :target: https://pypi.python.org/pypi/rpaframework-recognition
   :alt: rpaframework-recognition latest version



.. image:: https://img.shields.io/pypi/v/rpaframework-windows.svg?label=rpaframework-windows&style=for-the-badge&color=blue
   :target: https://pypi.python.org/pypi/rpaframework-windows
   :alt: rpaframework-windows latest version



Libraries
---------

The RPA Framework project currently includes the following libraries:

+----------------------------+----------------------------------------------+
| `Archive`_                 | Archiving TAR and ZIP files                  |
+----------------------------+----------------------------------------------+
| `Browser.Selenium`_        | Control browsers and automate the web        |
+----------------------------+----------------------------------------------+
| `Browser.Playwright`_      | Newer way to control browsers                |
+----------------------------+----------------------------------------------+
| `Cloud.AWS`_               | Use Amazon AWS services                      |
+----------------------------+----------------------------------------------+
| `Cloud.Azure`_             | Use Microsoft Azure services                 |
+----------------------------+----------------------------------------------+
| `Cloud.Google`_            | Use Google Cloud services                    |
+----------------------------+----------------------------------------------+
| `Crypto`_                  | Common hashing and encryption operations     |
+----------------------------+----------------------------------------------+
| `Database`_                | Interact with databases                      |
+----------------------------+----------------------------------------------+
| `Desktop`_                 | Cross-platform desktop automation            |
+----------------------------+----------------------------------------------+
| `Desktop.Clipboard`_       | Interact with the system clipboard           |
+----------------------------+----------------------------------------------+
| `Desktop.OperatingSystem`_ | Read OS information and manipulate processes |
+----------------------------+----------------------------------------------+
| `Desktop.Windows`_         | Automate Windows desktop applications        |
+----------------------------+----------------------------------------------+
| `Dialogs`_                 | Request user input during executions         |
+----------------------------+----------------------------------------------+
| `Email.Exchange`_          | E-Mail operations (Exchange protocol)        |
+----------------------------+----------------------------------------------+
| `Email.ImapSmtp`_          | E-Mail operations (IMAP & SMTP)              |
+----------------------------+----------------------------------------------+
| `Excel.Application`_       | Control the Excel desktop application        |
+----------------------------+----------------------------------------------+
| `Excel.Files`_             | Manipulate Excel files directly              |
+----------------------------+----------------------------------------------+
| `FileSystem`_              | Read and manipulate files and paths          |
+----------------------------+----------------------------------------------+
| `FTP`_                     | Interact with FTP servers                    |
+----------------------------+----------------------------------------------+
| `HTTP`_                    | Interact directly with web APIs              |
+----------------------------+----------------------------------------------+
| `Images`_                  | Manipulate images                            |
+----------------------------+----------------------------------------------+
| `JavaAccessBridge`_        | Control Java applications                    |
+----------------------------+----------------------------------------------+
| `JSON`_                    | Manipulate JSON objects                      |
+----------------------------+----------------------------------------------+
| `Notifier`_                | Notify messages using different services     |
+----------------------------+----------------------------------------------+
| `Outlook.Application`_     | Control the Outlook desktop application      |
+----------------------------+----------------------------------------------+
| `PDF`_                     | Read and create PDF documents                |
+----------------------------+----------------------------------------------+
| `Robocorp.Process`_        | Use the Robocorp Process API                 |
+----------------------------+----------------------------------------------+
| `Robocorp.WorkItems`_      | Use the Robocorp Work Items API              |
+----------------------------+----------------------------------------------+
| `Robocorp.Vault`_          | Use the Robocorp Secrets API                 |
+----------------------------+----------------------------------------------+
| `Salesforce`_              | Salesforce operations                        |
+----------------------------+----------------------------------------------+
| `SAP`_                     | Control SAP GUI desktop client               |
+----------------------------+----------------------------------------------+
| `Tables`_                  | Manipulate, sort, and filter tabular data    |
+----------------------------+----------------------------------------------+
| `Tasks`_                   | Control task execution                       |
+----------------------------+----------------------------------------------+
| `Twitter`_                 | Twitter API interface                        |
+----------------------------+----------------------------------------------+
| `Windows`_                 | Alternative library for Windows automation   |
+----------------------------+----------------------------------------------+
| `Word.Application`_        | Control the Word desktop application         |
+----------------------------+----------------------------------------------+

.. _Archive: https://rpaframework.org/libraries/archive/
.. _Browser.Playwright: https://rpaframework.org/libraries/browser_playwright/
.. _Browser.Selenium: https://rpaframework.org/libraries/browser_selenium/
.. _Cloud.AWS: https://rpaframework.org/libraries/cloud_aws/
.. _Cloud.Azure: https://rpaframework.org/libraries/cloud_azure/
.. _Cloud.Google: https://rpaframework.org/libraries/cloud_google/
.. _Crypto: https://rpaframework.org/libraries/crypto/
.. _Database: https://rpaframework.org/libraries/database/
.. _Desktop: https://rpaframework.org/libraries/desktop/
.. _Desktop.Clipboard: https://rpaframework.org/libraries/desktop_clipboard/
.. _Desktop.Operatingsystem: https://rpaframework.org/libraries/desktop_operatingsystem/
.. _Desktop.Windows: https://rpaframework.org/libraries/desktop_windows/
.. _Dialogs: https://rpaframework.org/libraries/dialogs/
.. _Email.Exchange: https://rpaframework.org/libraries/email_exchange/
.. _Email.ImapSmtp: https://rpaframework.org/libraries/email_imapsmtp/
.. _Excel.Application: https://rpaframework.org/libraries/excel_application/
.. _Excel.Files: https://rpaframework.org/libraries/excel_files/
.. _FileSystem: https://rpaframework.org/libraries/filesystem/
.. _FTP: https://rpaframework.org/libraries/ftp/
.. _HTTP: https://rpaframework.org/libraries/http/
.. _Images: https://rpaframework.org/libraries/images/
.. _JavaAccessBridge: https://rpaframework.org/libraries/javaaccessbridge/
.. _JSON: https://rpaframework.org/libraries/json/
.. _Notifier: https://rpaframework.org/libraries/notifier/
.. _Outlook.Application: https://rpaframework.org/libraries/outlook_application/
.. _PDF: https://rpaframework.org/libraries/pdf/
.. _Robocorp.Process: https://rpaframework.org/libraries/robocorp_process/
.. _Robocorp.WorkItems: https://rpaframework.org/libraries/robocorp_workitems/
.. _Robocorp.Vault: https://rpaframework.org/libraries/robocorp_vault/
.. _Salesforce: https://rpaframework.org/libraries/salesforce/
.. _SAP: https://rpaframework.org/libraries/sap/
.. _Tables: https://rpaframework.org/libraries/tables/
.. _Tasks: https://rpaframework.org/libraries/tasks/
.. _Twitter: https://rpaframework.org/libraries/twitter/
.. _Windows: https://rpaframework.org/libraries/windows/
.. _Word.Application: https://rpaframework.org/libraries/word_application/

Installation
------------

Learn about installing Python packages at `Installing Python Packages`_.

Default installation method with Robocorp `Developer Tools`_ using conda.yaml:

.. code-block:: yaml

   channels:
     - conda-forge
   dependencies:
     - python=3.7.5
     - pip=20.1
     - pip:
       - rpaframework==12.0.0

To install all extra packages (including Playwright dependencies), you can use:

.. code-block:: yaml

   channels:
     - conda-forge
   dependencies:
     - python=3.7.5
     - tesseract=4.1.1
     - pip=20.1
     - nodejs=14.17.4
     - pip:
       - rpaframework[aws]==12.0.0
       - rpaframework-google==1.0.0
       - rpaframework-recognition==1.0.0
       - rpaframework-windows==1.2.1
       - robotframework-browser==10.0.3
   rccPostInstall:
     - rfbrowser init

Separate installation of PDF and Dialogs libraries without main rpaframework:

.. code-block:: yaml

   channels:
     - conda-forge
   dependencies:
     - python=3.7.5
     - pip=20.1
     - pip:
       - rpaframework-dialogs==0.4.2  # included in the rpaframework by default
       - rpaframework-pdf==1.26.11  # included in the rpaframework by default


.. note:: Python 3.6 or higher is required

Example
-------

After installation the libraries can be directly imported inside
`Robot Framework`_:

.. code:: robotframework

    *** Settings ***
    Library    RPA.Browser.Selenium

    *** Tasks ***
    Login as user
        Open available browser    https://example.com
        Input text    id:user-name    ${USERNAME}
        Input text    id:password     ${PASSWORD}

The libraries are also available inside Python_:

.. code:: python

    from RPA.Browser.Selenium import Selenium

    lib = Selenium()

    lib.open_available_browser("https://example.com")
    lib.input_text("id:user-name", username)
    lib.input_text("id:password", password)

Support and contact
-------------------

- `rpaframework.org <https://rpaframework.org/>`_ for library documentation
- `Robocorp Documentation`_ for guides and tutorials
- **#rpaframework** channel in `Robot Framework Slack`_ if you
  have open questions or want to contribute
- `Robocorp Forum`_ for discussions about RPA
- Communicate with your fellow Software Robot Developers and Robocorp experts
  at `Robocorp Developers Slack`_

.. _Robot Framework Slack: https://robotframework-slack-invite.herokuapp.com/
.. _Robocorp Forum: https://forum.robocorp.com
.. _Robocorp Developers Slack: https://robocorp-developers.slack.com

Contributing
------------

Found a bug? Missing a critical feature? Interested in contributing?
Head over to the `Contribution guide <https://rpaframework.org/contributing/guide.html>`_
to see where to get started.

License
-------

This project is open-source and licensed under the terms of the
`Apache License 2.0 <http://apache.org/licenses/LICENSE-2.0>`_.
