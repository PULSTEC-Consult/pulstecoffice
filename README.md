PULSTEC OFFICE
==============

A lightweight office suite that runs in a browser. Nothing is installed.

Each editor is a single HTML file. Unpack this folder anywhere you can write
to - a disk, a network share, a USB stick - open one file in a browser, and
the suite is running. No installer, no background service, no account, and no
server: your documents stay on the machine you open them on.


WHAT IS IN THIS FOLDER
----------------------

  pulsoffice.html    Start here. The shell: recent files, opens the editors.
  pulssheets.html    Tables - spreadsheets, formulas, pivot tables, macros
  pulsdocs.html      Documents - text documents, page layout, styles
  pulsslides.html    Presentations - slides, masters, presenter view
  pulsproject.html   Projects - task tree, Gantt chart, calendars, costs
  tabula.html        Diagrams - flowcharts, shape libraries, connectors

  LICENSE                   Licence agreement (English translation)
  LICENSE.ru.md             Licence agreement (Russian; governing text)
  THIRD-PARTY-NOTICES.md    Third-party components and their terms


HOW TO START
------------

  1. Unpack the whole folder. Keep the files together.
  2. Open pulsoffice.html - double-click it, or drag it onto a browser
     window.
  3. Pick an editor, or open a document from the recent list.

You can also open an editor directly: pulssheets.html for a spreadsheet,
pulsdocs.html for a text document, and so on. The shell is a convenience,
not a requirement.


WHAT YOU NEED
-------------

A Chromium-based browser: Chrome, Edge, Yandex Browser, or Chromium itself.
Keep it reasonably current.

Firefox and Safari will open the editors and let you download your work, but
they cannot save a file back in place: they do not implement the browser
interface that makes that possible. If you want saving in place in those
browsers, use the Windows build instead (see below).

Nothing else is required. No runtime, no framework, no administrator rights.


SAVING YOUR WORK
----------------

The first time you save a new document, the browser asks where to put it.
After that, "Save" writes straight back to the same file - no dialog, no
duplicate in the Downloads folder.

A document opened from disk saves back to where it came from. A document
opened from an e-mail attachment or a download saves back into the folder you
chose for it.

Keep backup copies of work that matters. A browser, a disk or a network share
can fail, and the suite cannot protect you from that.


SETTINGS AND PLUGINS
--------------------

In the browser version, your settings, recent-files list, autosave data and
installed plugins are kept by the browser for the location you opened the
files from. Two consequences worth knowing:

  - clearing the browser's site data, or using a different browser, starts
    the suite with its defaults again;
  - moving the folder to a different path may do the same.

Your documents are never affected by this - they are ordinary files on disk.

If you want the settings to travel with the folder, use the Windows build:
it keeps everything in a "data" folder next to the program.


PLUGINS
-------

Plugins -> Catalogue opens the plugin store. A plugin is a single file, and
before it is installed you are shown what it asks for: which servers it wants
to call, which formula functions it defines, what it reads from the document.
Nothing is granted silently.

The official store is at https://pulstec.ru/pstore/ and is listed first. You
can add your own source: a repository, your own server, a folder on a disk or
network share, or a zip archive for machines with no internet connection.


WORKING OFFLINE
---------------

Everything runs locally. The suite reaches the network only when you ask it
to - to refresh the plugin catalogue or download a plugin and its resources.
With no network at all, the editors work exactly as they do with one.


THE WINDOWS BUILD
-----------------

A Windows build is published separately: an installer, and a portable zip that
needs no installation either. It adds what a browser cannot do - file
associations, opening a document by double-clicking it, saving in place
without any dialog, and a recent-files list in the window menu.

Get it from https://pulstec.ru/install.html


IF SOMETHING DOES NOT WORK
--------------------------

The page stays blank, or opens as plain text
    The browser is not Chromium-based, or the HTML file was modified after
    unpacking. Try another browser, and unpack the archive again.

"Save" asks for a location every time
    The browser cannot save in place. Use a Chromium-based browser, or the
    Windows build.

Installed plugins have disappeared
    The browser's site data was cleared, or the folder is being opened from a
    different path than before. Install them again from the catalogue.

The plugin catalogue says the store cannot be read
    No network connection, or the store server is unreachable from this
    machine. You can add the store as a folder or a zip archive instead.


LICENCE AND LINKS
-----------------

Use of this software is governed by the licence agreement in LICENSE.ru.md
(Russian, governing) and LICENSE (English translation). The free edition may
be used without charge, including commercially, and may be passed on unmodified
and free of charge.

  Overview and downloads     https://pulstec.ru
  Deployment and setup       https://pulstec.ru/install.html
  User manual                https://pulstec.ru/docs.html
  Plugin store               https://pulstec.ru/pstore/
