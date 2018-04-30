Web-4-All Installation Manual

Start Installation:

Overview:
During the installation of Web-4-All, additional software packages will also be installed 
on the computer to ensure that individuals with disabilities have full access to the World 
Wide Web. As part of the installation process, a Smart Card reader and a trackball (an 
accessible mouse alternative) will be added to the system as well.

Web-4-All's master installer utilizes the installation programs of each accessibility 
software/hardware package included with the application. Instructions are provided with 
the various dialogs describing the actions required to complete each step of the 
installation process.

As each step is completed, users have the option of reinstalling a specific technology if 
the installation fails. Web-4-All's Installer also determines whether a particular 
technology has been previously loaded onto a computer. If so, the "Install" button is 
greyed out and the "Reinstall?" button becomes active. The reinstall option also allows 
users to add a specific software/hardware package at a later date without having to 
reinstalling the entire Web-4-All system.

Detailed information on each stage of the installation process – including specific 
instructions displayed on a particular dialog – can be found in the "Help" files. Because 
most of the installer programs block access to the Windows taskbar, the "Alt" plus "Tab" 
keys must be used to toggle between the installer and Web-4-All screens.

To ensure that each program functions correctly, users must accept all default pathways 
and configurations recommended by the Web-4-All Install program. In addition, before 
running Web-4-All for the first time certain defaults must be established for the eReader 
and Home Page Reader software packages. (See each section for specific instructions.) 
Once a component has been successfully added, use the "Next" button to advance to the 
next step in the installation process.

Once all of Web-4-All's accompanying software/hardware has been installed, select 
"Finish" to restart the computer. Web-4-All will launch automatically each time the 
computer is turned on.

Start Installation:
Insert the Web-4-All disk into the CD-ROM drive. The installation program should 
launch automatically – if it does not, select "Start" then "Run" from the Windows taskbar. 
Enter: d:\Web4allinstaller.exe in the text field window (where "d" is the location of the 
hard drive) and then select "Ok". The first dialog to appear on-screen is "Start 
Installation". Select "Next" to advance to the "Serial Number" dialog screen or "Cancel" 
to abort the Web-4-All installation process altogether.


Serial Number dialog:
Enter the serial number found on the Smart Card reader or Trackball device included with 
Web-4-All in the text field provided on the "Serial Number" dialog. Note: the installation 
process will be terminated if this number is not entered correctly.

If Web-4-All is being installed on multiple workstations, select the appropriate 
workstation letter from the drop down list (i.e. "A" for the first workstation, "B" for the 
second, and so on).

Select "Back" to return to the "Start Installation" dialog, "Cancel" to quit the installation 
or "Next" to advance to the "Java JRE" install dialog.


Java? JRE dialog:
Select the "Install Java" button to launch Sun Microsystems Java 2 setup program. (Note: 
selecting "Skip" at this stage will bypass the Java install altogether and advance users to 
the "Java Configuration files" dialog screen. If this component has not yet been installed 
and "Skip" is selected, Web-4-All will not function properly.)

Software Licence Agreement:
The first dialog displayed after selecting "Install Java" is the "Software License 
Agreement". It presents users with the following three button options: "Back", "Yes", 
and "No". To proceed with the installation, accept the licensing agreement by choosing 
"Yes". This will launch the "Choose Destination Location" dialog. The "Back" button 
returns users to the top of the licensing agreement while "No" enables users to exit the 
Java 2 setup altogether. 

Choose Destination Location:
The "Choose Destination Location" dialog includes a "Browse" button, "Back", "Next", 
and "Cancel". Do NOT change the default pathway of the Destination Folder 
recommended by Web-4-All. To have Java 2 installed on the system select "Next". Use 
the "Back" button if you wish to revisit the "Software Licensing Agreement". Select 
"Cancel" to terminate the Java 2 installation. After the installation is complete, users are 
returned to Web-4-All's "Java JRE" dialog.

Reinstall:
Once Java 2 has been installed and the user returned to the "Java JRE" dialog, the "Install 
Java" button becomes "greyed out". "Reinstall?" now becomes the active default button. 
If the Java 2 install was unsuccessful, select "Reinstall?" Otherwise, use the "Next" 
button to advance to the "Java Configuration Files" installer or the "Back" button to 
return to the "Serial Number" dialog. "Cancel" ends the Web-4-All installation process 
altogether.

 
Java? Configuration Files dialog:
Select the "Install Java (Step 2)" button to add the configuration files required by Web-4-
All to run Java. (Note: selecting "Skip" at this stage will bypass the Java Configuration 
Files install and advance users to the "OpenCard Framework" dialog. If this component 
has not yet been installed and "Skip" is selected, Web-4-All will not function properly.) 
After the configuration files have been added, users are returned to Web-4-All's "Java 
Configuration Files" dialog.

Reinstall:
After the files have been added and the user is returned to the "Java Configuration Files" 
dialog, the "Install Java (Step 2)" button becomes "greyed out". The message "Java 
Configuration Files (2) installed" should also appear immediately following "Install Java 
(Step 2)" button and "Reinstall?" becomes the active default.

If the installation was unsuccessful, select "Reinstall?" Otherwise, select "Next" to 
advance to the "OpenCard Framework" dialog or use "Back" to return to the "Java JRE" 
install screen. "Cancel" exits the Web-4-All installation altogether.


OpenCard Framework dialog:
Select "Install OCF". This button opens the MS-DOS Prompt window, which then auto-
launches the OpenCard Framework 1.2 Setup Program. (Note: selecting "Skip" at this 
stage will bypass the OpenCard Framework installation altogether and advance users to 
the "OpenCard Configuration Files" dialog. If this component has not yet been installed 
and "Skip" is selected, Web-4-All will not function properly.)

OpenCard Framework 1.2 Setup Program:
The first dialog displayed is the "Welcome to the OpenCard Framework Setup Program". 
Select "Next" to launch the "Choose Destination Location" dialog or "Cancel" to 
terminate the "OpenCard Framework" installation.

Choose Destination Location:
The "Choose Destination Location" dialog includes a "Browse" button, "Back", "Next", 
and "Cancel". Do NOT change the default pathway of the Destination Directory 
recommended by Web-4-All. To continue the setup and advance to the "Folder" dialog, 
choose "Next". Use the "Back" button if you wish to return to the "Welcome" dialog or 
select "Cancel" to terminate the OpenCard Framework installation.

Folder:
The "Folder" dialog includes a "Program Folder" text field and, beneath it, a list of 
"Existing Folders". Do NOT change the default placed into the text field by Web-4-All. 
Use the "Back" button to return to the "Choose Destination Location" dialog or "Cancel" 
to terminate the install. Selecting "Next" will open the "Build opencard.properties?" 
dialog.

The "Build opencard.properties?" dialog asks users: "Would you like to build a 
configuration file for OCF now? (opencard.properties)". You MUST select "No". 
Selecting "No" will also automatically launch the "Install Options Selected" dialog.

Install Options Selected:
This dialog displays the options selected for the OCF install. Choose "Back" to return to 
the "Build opencard.properties?" dialog or "Cancel" to terminate the install. To continue 
with the setup, select "Next".

A new dialog appears asking users: "Do you want to begin copying files? Press OK to 
continue, or CANCEL to backup." Select "OK". This will automatically launch the 
"Replace File" dialog. Selecting "Yes to All" from this dialog will install OCF on your 
computer and open the "Setup Complete" dialog.

Setup Complete:
Select "Finish" from this dialog (you may also wish to view the OCF ReadMe file at this 
time) and then close the MS-DOS Prompt window if you have not done so earlier. 

Reinstall:
Once OCF has been installed and the MS-DOS Prompt window is closed, users will be 
returned to Web-4-All's "OpenCard Framework" dialog. Note, however, "Install OCF" is 
now "greyed out" and "Reinstall?" has become the active default button. If the OCF 
install was unsuccessful, select "Reinstall?" Otherwise, use the "Next" button to advance 
to "OpenCard Configuration files" installer or the "Back" button to return to the "Java 
Configuration files" dialog. "Cancel" terminates the Web-4-All installation process 
altogether.


OpenCard Configuration Files dialog:
Select the "Install OCF (Step 2)" button to continue the installation. (Note: selecting 
"Skip" at this stage will bypass the "OpenCard Configuration Files" installation 
altogether and advance users to the "Microsoft Card Reader" dialog screen. If this 
component has not yet been installed and "Skip" is selected, Web-4-All will not function 
properly.) After the install is complete, users are returned to Web-4-All's "OpenCard 
Configuration Files" dialog.

Reinstall:
The "Install OCF (Step 2)" button becomes "greyed out" after the installation is complete 
and the user is returned to the "OpenCard Configuration Files" dialog. The message 
"OpenCard Configuration Files (2) installed" should also appear immediately following 
the "Install OCF (Step 2)" button. "Reinstall?" now becomes the active default button.

If the installation was unsuccessful, select "Reinstall?" Otherwise, select "Next" to 
advance to the "Microsoft Card Reader" dialog or use the "Back" button to return to 
"OpenCard Framework" (Step 1) installer. "Cancel" ends the Web-4-All installation.


Microsoft Card Reader dialog:
Select the "Install MS Card Reader" button to install the Smart Card base components 
required by Microsoft Windows. (Note: selecting "Skip" at this stage will bypass the MS 
Card Reader install altogether and advance users to the "Opera" dialog screen. If this 
component has not yet been installed and "Skip" is selected, Web-4-All will not function 
properly.) The "Back" button returns users to the "OpenCard Configuration files" dialog, 
while "Cancel" terminates the Web-4-All installation altogether.

Microsoft Smart Card Base Components:
When "Install MS Card Reader" is selected, a dialog appears asking users: "Do you want 
to install the Smart Card Base components?" Choose "Yes". This displays Microsoft's 
license agreement. To continue, choose "Yes". This automatically launches Notepad and 
displays the "readme" file. (You must close the "readme" file before proceeding.) A 
dialog is then launched indicating that the install is complete. Select "OK" and a prompt 
appears informing users that they must restart their computer for the new settings to take 
effect. Users are also asked if they wish to restart their computer at this time.

Reinstall:
Once the Smart Card components have been installed, the user is returned to the Web-4-
All "Microsoft Card Reader" dialog. Note that the "Install MS Card Reader" button is 
now "greyed out" and "Reinstall?" is the active default button. If the MS Card Reader 
install was unsuccessful, select "Reinstall?" Otherwise, use the "Next" button to advance 
to "Opera" or the "Back" button to return to the "OpenCard Configuration files" dialog. 
"Cancel" ends the Web-4-All installation process altogether.


Opera dialog:
Select the "Install Opera" button to launch the Opera 5 (Win32) Installation program. 
(Note: selecting "Skip" at this stage will bypass the Opera install altogether and advance 
users to the "Hitachi Driver" dialog screen. If this component has not yet been installed 
and "Skip" is selected, Web-4-All will not function properly.) Use the "Back" button to 
return to the "Microsoft Card Reader" dialog or "Cancel" to terminate the Web-4-All 
installation.

Welcome:
The "Welcome" dialog provides basic information about the Opera browser. Select 
"Next" to advance to the "Software License Agreement" or "Cancel" to exit the Opera 
setup.

Software License Agreement:
This dialog presents users with the following three button options: "Back", "I Accept", 
and "I Disagree". To proceed with the installation, accept the licensing agreement by 
choosing "I Agree". This will launch the "Select Destination Directory" dialog. The 
"Back" button returns users to the "Welcome" dialog while "I Disagree" allows users to 
abort Opera's installation.

Select Destination Directory:
The "Select Destination Directory" dialog includes a "Browse" button, "Back", "Next", 
and "Cancel". Do NOT change the default pathway of the destination directory. To 
continue the setup and advance to the "Icon Creation" dialog, choose "Next". Use the 
"Back" button to return to the "Software License Agreement" dialog or "Cancel" to 
terminate the Opera installation.

Icon Creation:
This dialog allows users to add Opera to their "Start Menu" and/or add an Opera icon to 
their desktop via two checkboxes. To proceed, use the "Next" button to advance to the 
"Select Group" dialog. The "Back" button returns users to the "Select Destination 
Directory" while "Cancel" terminates the Opera installation.

Select Group:
Users are asked to enter the name of the program group in the text field provided. "Opera 
5" is the default text. Do NOT change this information. Use the "Back" button to return 
to the "Icon Creation" dialog or "Cancel" to abort the installation altogether. Select 
"Next" to advance to the "Ready to Install!" dialog.

Ready to Install!:
To begin installing Opera on the system, select "Next". Use the "Back" button to return 
to the "Select Group" dialog or "Cancel" to exit the Opera installation. Once the 
installation has finished, the "Installation Completed!" dialog appears.

Installation Completed!:
This dialog informs users that a backup of all files altered or replaced during the 
installation process have been saved in a subdirectory entitled "Uninst\Backup". Select 
"Finish" to exit the installation and return to Web-4-All's "Opera" dialog. 

Reinstall:
Note, that "Install Opera" is now "greyed out" and "Reinstall?" is the active default 
button. If the installation of Opera was unsuccessful, select "Reinstall?" Otherwise, use 
the "Next" button to advance to "Hitachi Driver" or the "Back" button to return to the 
"Microsoft Card Reader" dialog. "Cancel" terminates the Web-4-All installation process 
altogether.


Hitachi Driver:
Select the "Install Hitachi Driver" button to add the hardware specific drivers for the 
Card Reader. (Note: selecting "Skip" at this stage will bypass the Hitachi Driver 
installation altogether and advance users to the "Kensington Trackball" dialog screen. If 
this component has not yet been installed and "Skip" is selected, Web-4-All will not 
function properly.) Use the "Back" button to return to the "Opera" dialog or "Cancel" to 
terminate the Web-4-All installation.

Welcome:
The "Welcome" dialog provides basic information about the setup program. To begin the 
install, select "Next". To exit the Hitachi Driver setup program, choose "Cancel".

Setup Complete:
The "Setup Complete" dialog appears once the install has ended. Before selecting 
"Finish" you MUST plug the Card Reader hardware into serial port 1 (see diagram) and 
into the keyboard port in series with the keyboard. Both ports are located in back of the 
computer. Once this is done enable the radio button "Yes, I want to restart my computer 
now" and select "Finish" to complete the installation process. 

Reinstall:
Note that when you return to the "Hitachi Driver" dialog, the "Install Hitachi Driver" 
button is now "greyed out" and "Reinstall?" is the active default button. If the "Hitachi 
Driver" installation was unsuccessful, select "Reinstall?" Otherwise, use the "Next" 
button to advance to the "Kensington Trackball" installer or the "Back" button to return 
to the "Opera" dialog. "Cancel" terminates the Web-4-All installation process altogether.


Kensington Trackball dialog:
Select the "Install Kensington" button to launch the "Kensington MouseWorks Setup" 
program. (Note: selecting "Skip" at this stage will bypass the Kensington Trackball 
installation altogether and advance users to the "eReader" dialog screen. If this 
component has not yet been installed and "Skip" is selected, Web-4-All will not function 
properly.) Use the "Back" button to return to the "Hitachi Driver" dialog or "Cancel" to 
terminate the Web-4-All installation.

Welcome:
To begin the install, select "Next". This launches the "Software Licence" dialog. If you 
wish to exit the Kensington MouseWorks Setup Program, choose "Cancel".

Software License:
The "Software License" dialog presents users with the following three button options: 
"Back", "Yes", and "No". To continue the setup, select "Yes". This will launch the 
"Choose Destination Location" dialog. Use the "Back" button to return to the "Welcome" 
dialog or select "Cancel" to exit the setup altogether.

Choose Destination Location:
The "Choose Destination Location" dialog includes a "Browse" button, "Back", "Next", 
and "Cancel". Do NOT change the Destination Folder default. To continue the setup and 
advance to the "AOL Option" dialog, choose "Next". Use the "Back" button to return to 
the "Software License" dialog or "Cancel" to terminate the setup.

AOL Option dialog:
This dialog presents users with the following checkbox: "The AOL browser is used for 
Internet access." Do NOT check this box. Select "Next" to install Kensington 
MouseWorks on the computer. Use the "Back" button to return to the "Choose 
Destination Location" dialog or "Cancel" to exit the setup. 

Installation Complete:
After the installation process has concluded, a dialog appears advising users that they 
must reboot their computer before running the Kensington MouseWorks software. Before 
restarting your computer you must first remove the current pointing device and replace it 
with the Kensington Trackball. Once this has been done enable the radio button "Yes, I 
want to restart my computer now" and select "Finish" to complete the installation.

Reinstall:
Note that when you return to the "Kensington Trackball" dialog, the "Install Kensington" 
button is "greyed out" and "Reinstall?" is now the active default button. If the 
Kensington Trackball installation was unsuccessful, select "Reinstall?" Otherwise, use 
the "Next" button to advance to the "eReader" dialog or the "Back" button to return to 
the "Hitachi Driver" dialog. "Cancel" terminates the Web-4-All installation process 
altogether.


eReader dialog:
Select the "Install eReader" button to launch the "eReader Setup" program. (Note: 
selecting "Skip" at this stage will bypass the eReader installation altogether and advance 
users to the "Home Page Reader" dialog screen. If this component has not yet been 
installed and "Skip" is selected, Web-4-All will not function properly.) Use the "Back" 
button to return to the "Kensington Trackball" dialog or "Cancel" to terminate the Web-
4-All installation.

Welcome:
The "Welcome" dialog provides basic information about the eReader setup program. To 
begin the installation, select "Next". To exit the eReader setup program, choose 
"Cancel".

Software License Agreement:
The "Software License" dialog presents users with the following three button options: 
"Back", "Yes", and "No". To continue the setup, select "Yes". This will launch the "User 
Information" dialog. Use the "Back" button to return to the "Welcome" dialog or select 
"Cancel" to exit the setup.

User Information:
Accept the defaults listed in the "Name", "Company", and "Serial" text fields. Use the 
"Back" button to return to the "Software License Agreement" or "Cancel" to terminate 
the eReader setup program. To continue on with the installation, select "Next". This will 
launch the "Choose Destination Location" dialog.

Choose Destination Location:
The "Choose Destination Location" dialog includes a "Browse" button, "Back", "Next", 
and "Cancel". Do NOT change the Destination Folder default. To continue choose 
"Next" to advance to the "Setup Type" dialog. Use the "Back" button to return to the 
"User Information" dialog or "Cancel" to exit the setup.

Setup Type:
Do NOT change the default that appears in the text field. Select "Next" to advance to the 
"Select Program Folder" or "Back" to return to the "Choose Destination Location". To 
terminate the setup, select "Cancel".

Select Program Folder:
Once again, do NOT change the default in the "Program Folders" text field. To install 
eReader, select "Next". Use the "Back" button to return to the "Setup Type" dialog or 
"Cancel" to terminate the installation.

Microsoft Text-to-Speech Engine:
Once the install has ended, this license agreement dialog appears. You must select "Yes" 
to advance to the "Setup Complete" dialog.

Setup Complete:
To conclude the installation process, select "Finish". This will return users to Web-4-
All's "eReader" dialog.

Reinstall:
Note the "Install eReader" button is now "greyed out" and "Reinstall?" is the active 
default button. If the eReader installation was unsuccessful, select "Reinstall?" 
Otherwise, use the "Next" button to advance to the "Home Page Reader" dialog or the 
"Back" button to return to the "Kensington Trackball" dialog. "Cancel" terminates the 
Web-4-All installation altogether.

Default Reading Voice:
eReader's default reading voice must be set before the program is run for the very first 
time. Launch eReader by selecting "Start", "Programs", and then "CAST eReader" from 
the Windows taskbar. Choose "Read" from eReader's menu bar and then "Select Voice". 
Determine which voice you wish eReader to use when accessing Web pages from the list 
displayed and then select "OK". Close eReader.


Home Page Reader dialog:
Select the "Install HPR" button to launch the "Home Page Reader Setup" program. 
(Note: selecting "Skip" at this stage will bypass the Home Page Reader setup program 
altogether and advance users to the "Card Preference Setup Software" dialog screen. If 
this component has not yet been installed and "Skip" is selected, Web-4-All will not 
function properly.) Use the "Back" button to return to the "eReader" dialog or "Cancel" 
to terminate the Web-4-All installation.

Welcome:
The "Welcome" dialog asks users if they want Home Page Reader's instructions read 
aloud to them. You MUST select "No". To continue with the installation, select "Next" 
to advance to the "Software License Agreement". To exit the setup, choose "Cancel".

Home Page Reader Software License Agreement:
The "Software License Agreement" dialog presents users with the following three button 
options: "Back", "Yes", and "No". To continue the setup, select "Yes". A dialog appears 
advising users that they MUST upgrade their version of Internet Explorer (IE) to 5.5. If 
the IE browser version you are using is 5.5 or higher select "No". To upgrade your 
version of IE, select "Yes".

Microsoft Internet Explorer License Agreement:
The "Microsoft Software License Agreement" dialog presents users with the following 
three button options: "Back", "Yes", and "No". To continue, select "Yes". This will 
launch the "Choose Destination Location" dialog. Use the "Back" button to return to the 
HPR license agreement or "No" to exit this setup.

Choose Destination Location:
The "Choose Destination Location" dialog includes a "Browse" button, "Back", "Next", 
and "Cancel". Do NOT change the Destination Folder default. To have HPR installed on 
your computer, choose "Next". Use the "Back" button to return to the "Microsoft 
Software Licensing Agreement" dialog or "Cancel" to exit the setup.

Setup Complete:
This dialog appears after the installation is complete and allows users to view the 
accompanying README.TXT file. (You must close the "README.TXT" file before 
proceeding.) When "Finish" is selected a dialog appears warning users that the computer 
must be restarted before Home Page Reader can be used. Enable the radio button "Yes, I 
want to restart my computer now" and then select "OK" to complete the installation 
process. 

Reinstall:
Note that when you return to Web-4-All's "Home Page Reader" dialog, "Install HPR" is 
"greyed out" and "Reinstall?" is now the active default button. If the Home Page Reader 
installation was unsuccessful, select "Reinstall?" Otherwise, use the "Next" button to 
advance to the "Card Preference Setup Software" dialog or the "Back" button to return to 
the "eReader" dialog screen. "Cancel" terminates the Web-4-All installation process.

Default Screen Reader Setting:
The first time Home Page Reader is launched, you will be asked if you wish to make it 
your default Web browser. Do NOT select "Yes". Instead, uncheck the box "Always 
perform this check when starting" and then select "No". You may now exit Home Page 
Reader.


Card Preference Setup Software dialog:
Select the "Install Preference Setup" button to install software that permits users to save 
customized settings onto their Smart Card. (Note: selecting "Next" at this stage will 
bypass the Card Preference setup program altogether and advance users to the "Finish 
Installation dialog screen. If this component has not yet been installed and "Skip" is 
selected, Web-4-All will not function properly.) Use the "Back" button to return to the 
"Home Page Reader" dialog or "Cancel" to terminate the Web-4-All installation.

Reinstall:
After the software has been installed, the user is returned to the "Card Preference Setup 
Software" dialog. Note, "Install Preference Setup" is now "greyed out" and "Reinstall?" 
becomes the active default button. In addition, the message "Preference software 
installed" should also appear immediately after the "Install Preference Setup" button.

If the installation was unsuccessful, select "Reinstall?" Otherwise, select "Next" to 
advance to the "Finish Installation" dialog or use "Back" to return to the "Home Page 
Reader" dialog. "Cancel" exits the Web-4-All installation.

Registering Web-4-All Workstations:
Each Web-4-All workstation must be registered with Industry Canada. This helps ensure 
that each workstation is functioning correctly and also enables administrators to 
customize the site to meet the needs of their particular community. Registering a site also 
allows administrators to add or edit content to their site's community home page.

Registering a workstation during installation
1.	Selecting the "Register" button automatically launches the system's Web browser 
and takes users to the Industry Canada "Web-4-All Workstation Registration" 
form. 
2.	Locate the "Create a new local administrator account" section and choose a Log-
in name and Password. Log-in names and passwords can include any combination 
of letters, numbers or underscores but special characters and spaces are not 
permitted. 
3.	Confirm the password by re-entering it in the text field provided and then select a 
default language for the site. 
4.	Choose the province in which the site is located and enter an email address for 
administrators (you may wish to create a new email account specifically for this 
purpose) then select "Submit". 
5.	The final step in the "Web-4-All Workstation Registration" form is selecting a 
default community for your site. The list is based on the electoral districts or 
ridings for a particular province. If your community does not appear in the list, 
select the one closest to your location. 
6.	The registration process is now complete. Close the browser and return to the 
Web-4-All install program. Whenever the administrator's log-in name and 
password is entered in the "Web-4-All Favourites Site Log-in" page, the default 
community home page will be launched automatically. This enables 
administrators to add announcements and/or Web site links to their community 
home page quickly and easily.

Registering Multiple Workstations
1.	Select the "Register" button to automatically launch the system's Web browser 
and open the Industry Canada "Web-4-All Workstation Registration" form. 
2.	Locate the section entitled, "Use an existing local administrator account" and 
enter the administrator log-in name and password created during the registration 
process for the initial workstation. 
3.	Select "Submit". All subsequent workstations are automatically associated with 
your site's default community home page. 
4.	The registration process is now complete. Close the browser and return to the 
Web-4-All installation program. 

Re-register: 
After the Web-4-All workstation has been registered with Industry Canada and the 
browser window is closed, the user is returned to the "Register Workstation" dialog. 
Note, the "Register" is now "greyed out" and "Re-register?" has become the active default 
button.

If the registration process was unsuccessful, select "Re-register?" Otherwise, select 
"Next" to advance to the "Finish Installation" dialog or use "Back" to return to the "Card 
Preference Setup" dialog. "Cancel" exits the Web-4-All installation.

Finish Installation dialog:
This dialog informs users that Web-4-All is now installed on their computer. To return to 
the "Card Preference Setup Software" dialog, use the "Back" button. Select "Finish" to 
reboot your computer. After restarting, Web-4-All (and all of its accompanying 
components) will be available to users.

