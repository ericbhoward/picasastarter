# Introduction #

**Enhancements in Picasa Starter Version 1.5.0:**
  * Allow the user to specify the location of the Picasa Starter settings file. This allows the users to have Picasa Starter on their own account or PC while still using a common settings file on the shared or network drive.
  * A new **First Run Wizard** that asks for some settings the first time Picasa Starter is run.
  * A new **Create Shortcut** function to make it simple to create shortcuts to Picasa Starter databases.

**Bug Fixes:**
  * Improved the ability of Picasa Starter to run in a mixed Windows7 x64 and windows XP x32 environment.
  * Fixed a bug with mixed English and other language environments.
  * Improved database naming and description to correctly recognize spaces and returns.


# Details #


**Allow the user to specify the location of the Picasa Starter settings file:**

In the "General Settings" dialog box, the user can specify where Picasastarter should look for it's settings file.  By default it goes in the same directory as Picasastarter, but the user can select any location including on external or network drives.

When Picasa Starter is on a network drive users can get UAC prompts asking them to approve running an exe file from the network drive.  The best way we have found so far to avoid this is for the user to have a local copy of Picasa Starter.  Now the user can point his local copy at the network Picasa Starter directory to avoid the UAC while still using the common copy of the Picasastartersettings.xml file.  This way when changes are made to the settings file it is up to date for all users.


**A new First Run Wizard that asks for some settings the first time Picasa Starter is run:**

When Picasa Starter runs for the first time, it asks the user to verify the location of Picasa on the local drive. This is usually not necessary, but some users might put Picasa in a different directory.

The second question asks where the settings file should be located. See the question above for details on this. By default it is put in the Picasastarter directory.


**A new Create Shortcut function to make it simple to create shortcuts to Picasa Starter databases:**

To run Picasastarter and automatically start Picasa with a different database, a shortcut to Picasastarter is required. In the past, the user had to manually create this shortcut and fill in the database parameters.

The **Create Shortcut** button allows the user to create these shortcuts at the press of a button.  Shortcuts can be named whatever the user wants, and can be created on the desktop and/or in the Application Directory.

A shortcut option "AskUser" has been added that brings up a selection menu of all databases when the shortcut is run. This makes it unnecessary to run PicasaStarter in background to select a database to run