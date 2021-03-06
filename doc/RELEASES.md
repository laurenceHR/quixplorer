QuiXplorer -- VERSION HISTORY & RELEASE NOTES
=============================================

### Version 2.4.4

- Renamed '.config' and '.include' to '_config' and '_include'
  
  If you are upgrading from a previous installation, you have to
  manu copy your .config/conf.php to _config/conf.php and
  delete the old directories.

### Version 2.4.3 2010-09-05

	added lost directories .include and .config

### Version 2.4.2 2010-09-05

	This version is the first "official" release on git of QuiXplorer.

	There have been no changes on code, however, some minor documentation
	changed.

	Contribute on QuiXplorer using git:

	git://quixplorer.git.sourceforge.net/gitroot/quixplorer/quixplorer

### Version 2.4.1 BETA - 2008-10-03

	!! WARNING, THIS IS A UNSTABLE BETA VERSION !!

	This version may contain bugs as well as some security issues.
	Don''t use unless you did some tests and ensured that it works
	well for you.

	USAGE IS ALWAYS AT YOUR OWN RISK, THERE IS ABSOLUTELY NO WARRANTY
	ON CORRECT FUNCTIONALITY OR SECURITY ISSUES.
	
	Features:

	- Implemented combined anonymous access / registered access mode.
	  See the wiki documentation for details.

### Version 2.4.0 BETA - 2008-05-17

* WARNING, THIS IS A UNSTABLE BETA VERSION *

This version may contain bugs as well as some security issues.
Don't use unless you did some tests and ensured that it works
well for you.

USAGE IS ALWAYS AT YOUR OWN RISK, THERE IS ABSOLUTELY NO WARRANTY
ON CORRECT FUNCTIONALITY OR SECURITY ISSUES.

- Bulgarian language support added (thanks to the contributor)
- Danish language support added
- Czech language suppert added (thanks to the contributor)
- Fixed a bug so that the download from the search results is now possible.

This version implements the "upload only access permissions".
The permission engine has been completely recoded. Now you
may configure the user access permissions more individually.

You find the detail description to the new access permissions
in the file permissions.txt in this directory.

#### Upgrade notice:

The values of the permissions in the user database has changed.
So if you upgrade to this version, you have to check and change
the permissions of each user.

#### How to upgrade:

1. make a backup copy of your current Quixplorer installation directory
2. delete the current Quixplorer installation directory
3. download the new version of Quixplorer and install it into
   your installation directory
4. copy the .config/.htusers.php from backup copy to your installation
   directory
5. copy the .config/conf.php from your backup copy to your installation
   directory
6. login to quixplorer using the admin user
7. review the permissions of all users in your user database.
8. have much fun!
	    
### Version 2.3.2 - 2007-05-23:

- Bugs regarding the file download link solved
- Implemented "Download only" permissions
- PortuguÍs - Brasil Language Support by Diego Dmitruk Maturana (Thanks!)
- Polish Language Support by ADAM SWIERCZ
- Romanian Language Module (translated by Radmilo Felix)
- Italian Language Module (translated by Maurizio Pinotti)
- You may now configure the page title and the login prompt message
  within your config file.

#### Upgrade notice:

Version 2.3.2 should be compatible to the other versions. However,
you may want to use the template of the new config file (.config/conf.php)
to use configure the site name and login prompt message in this place.

These may reduce upgrading efforts if you changed this values for the future.

### Version 2.3.1 - 2004-08-12:
- File-access vulnerability discovered by Cyrille Barthelemy.
- This version contains the fix.
- Some other minor fixes are included as well.

### Version 2.3 - 2003-04-27:
- Russian translation thanks to Mikhail M. Pigulsky.
- Improved download-function for Internet Explorer & Opera.
- Small changes to support PHP4 < 4.1.0.
- New Icon-theme: KDE's Crystal.
- Improved (sym)link support.

--------------------------------------------------------------------------------
## Older History (unformatted)
Version 2.2 - 2003-04-08:
	Improved search-function by adding '?' and '*' wildcards.
	Upload & Search as separate functions.
	French translation thanks to Olivier Pariseau.
	A few cosmetic/practical improvements.
--------------------------------------------------------------------------------
Version 2.1 - 2003-03-23:
	Fixed filetype bug thanks to David Klein. (who also helped with row highlight)
	Spanish translation thanks to J. Pedro Flor P.
	Begun development of Zip/Tar/Gzip library to work with QuiXplorer.
	Fixed small bug regarding apostroph.
--------------------------------------------------------------------------------
Version 2.0 - 2003-03-03:
	Added user-management.
	Begun multi-language support with modules English, Dutch and German.
--------------------------------------------------------------------------------
Version 1.6 - 2003-02-12:
	Fixed some stupid "bugs".
	"Register_globals = On" no longer needed for user-authentication.
--------------------------------------------------------------------------------
Version 1.5 - 2003-02-11:
	Fixed major "bug" in root_dir control.
	"Register_globals = On" no longer needed to run properly.
--------------------------------------------------------------------------------
Version 1.4 - 2003-02-06:
	Added optional user-authentication.
	User-authentication may not work in PHP 4.1.2.
	(there is a bug in PHP 4.1.2 regarding $_SESSION)
--------------------------------------------------------------------------------
Version 1.2 - 2003-01-31:
	Added displaying of free disk space & fixed some minor bugs.
--------------------------------------------------------------------------------
Version 1.1 - 2003-01-28:
	Fixed some "bugs" in QuiXplorer.
--------------------------------------------------------------------------------
Version 1.0 - 2003-01-27:
	First release with basic functions.
--------------------------------------------------------------------------------
