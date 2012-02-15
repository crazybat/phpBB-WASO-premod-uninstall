====================================================================================
Project: 
phpBB Web and Accessibility Standards Overhaul (phpBB WASO) UNINSTALL
Based on phpbb 2.0.23 - http://phpbb.com

phpBB WASO Version:
2.0.06

Date: 
06 March 2008

Author:
Marco Battilana - crazybat@gmail.com
Crazy Bat Designs - http://crazybat.ca

Notes:
The overall goal of these MOD and style changes you'll be missing;
	- Attempting to meet the W3C Web Content Accessibility Guidelines - Level A 
	- Striving to validate all forum pages as XHTML 1.0 Strict 
	- Separating structure/semantics from presentation using CSS for layout


Uninstallation using EasyMOD v0.3.0
To uninstall;

	- Unzip the file 'phpbb-waso-2006-uninstall.zip' into your forum admin/mods directory. (ie: http://yoursite.com/forums/admin/mods/)
	- Log in with your administration name and password to access your Administration panel 
	- Navigate to 'General Admin', then 'Configuration'
	- Next to 'Default Style', choose 'subSliver' as the style
	- Next to 'Override user style - Replaces users style with the default', choose 'No'
	- Hit 'Submit'
	- In the admin panel, navigate to 'Style Admin', then 'Management'
	- You should see 'crazybat' as one of the themes available. If so, select 'delete' 
	- You should see 'Are you sure you want to delete this style?' Select 'Yes'
	- If successful, you should see 'The selected style has been removed from the database
	-  You can now safely proceed with deleting the 'crazybat' folder and it's contents from your forum's template directory (http://yoursite.com/forums/templates/crazybat)
	- In the admin panel, navigate to 'MOD center', then 'Install MODs' 
	- Enter your EasyMOD Password, then 'Access EasyMOD' 
	- You should see in your list of 'Unprocessed MODs', you should see a listing for 'phpBB WASO UNINSTALL'. Inline with this listing, select 'Process' 
	- You will see 'Step 1 of 3 - Processing completed successfully!'. If so, then select 'Next Step' 
	- You will then see 'Step 2 of 3 - Proposed Database Alterations'. For this MOD, this is not applicable. Therefore, select 'Complete Installation' 
	- You will then see 'Step 3 of 3 - Installation Complete!'. Feel free to see the list of changes to the applicable files 
	- You can now safely delete the following files; 1. http://yoursite.com/forums/about.php 2. http://yoursite.com/forums/phpbb-waso-release-notes.txt, 3. http://yoursite.com/forums/templates/subSilver/screen-subsilver-waso.css
	- Your phpBB WASO is now fully uninstalled

Manual preMOD Uninstallation
To uninstall;

	- Log in with your administration name and password to access your Administration panel 
	- Navigate to 'General Admin', then 'Configuration'
	- Next to 'Default Style', choose 'subSliver' as the style
	- Next to 'Override user style - Replaces users style with the default', choose 'No'
	- Hit 'Submit'
	- In the admin panel, navigate to 'Style Admin', then 'Management'
	- You should see 'crazybat' as one of the themes available. If so, select 'delete' 
	- You should see 'Are you sure you want to delete this style?' Select 'Yes'
	- If successful, you should see 'The selected style has been removed from the database. 
	- You can now safely proceed with deleting the 'crazybat' folder and it's contents from your forum's template directory. (http://yoursite.com/forums/templates/crazybat)
	- You can now safely delete the following files; 1. http://yoursite.com/forums/about.php 2. http://yoursite.com/forums/phpbb-waso-release-notes.txt, 3. http://yoursite.com/forums/templates/subSilver/screen-subsilver-waso.css
	- Unzip the file 'phpbb-waso-2006-uninstall-premod.zip' into your forum directory. (ie: http://yoursite.com/forums/) 
	- You will be warned that files of the same name will be overwritten. Select 'Yes' to overwrite the necessary files 
	- Back at the admin section, navigate to 'Administration' and go to 'Forum Index'
	- Your phpBB WASO MOD is now fully uninstalled
	
Again, please take the appropriate caution when using these files. I have taken great care to assure quality assurance, but please remember to back up your files before installing this MOD.
====================================================================================
====================================================================================
**Changes to the forum front-end and functionality**
====================================================================================

Revision History
------------------------------------------------------------------------------------
Version 2.0.05 - 19 December 2007
------------------------------------------------------------------------------------

    * Incorporate phpBB 2.0.22 fixes

------------------------------------------------------------------------------------
Version 2.0.04 - 24 June 2006
------------------------------------------------------------------------------------

    * Created

------------------------------------------------------------------------------------
~ end of line