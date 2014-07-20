Packages:
================

**dpkg.alfredworkflow** - [Click to download from Packal](http://www.packal.org/workflow/dpkg). 

This semi-automates the creation of Debian packages. It should be compatible from 10.7 - 10.10. Collect all of your files on the desktop in a folder named *"package"*, correctly formatted into the Debian format including [control file](http://manpages.ubuntu.com/manpages/lucid/man5/deb-control.5.html). For more information on dpkg formatting see [here](http://manpages.ubuntu.com/manpages/lucid/man1/dpkg.1.html).

It uses [Homebrew](https://github.com/Homebrew/homebrew) as its backbone, and dpkg is installed & updated via Homebrew. This is largely because Homebrew is a great way to sandbox the formulas in a non-destructive, safe way without any interference with the system.

Obviously, this makes installing Homebrew & updating your $PATH a prerequisite to using this workflow.

*Commands*:

* dpkg install - Installs dpkg via Homebrew
* dpkg upgrade - Upgrades dpkg via Homebrew
* dpkg create - Creates a .deb file from the "package" folder on your desktop. Also automatically removes all .DS_Store (OS X system junk) files from that package before creation.

**Developer Tools.alfredworkflow** - Opens a number of popular development tools for OS X using configurable hotkeys. Super-simple alfred workflow.
