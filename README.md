CameraTools
===========

Currently CameraTools contains the following utilities:

camera-import-gtk
-----------------

Allows the batch import of all RAW or JPEG files from a mounted memory card to a folder designated by the user. Within the generated folder imported photos will be automatically sorted into subdirectories for RAW, JPEG, and edited- to be used further on in the workflow (in my usage case this was adding of said folders to my Corel Aftershot Pro catalogue). The program also allows the wiping of the memory card after import for the next use. Configuration is done via a GUI prompt with no editing of config files neccessary.


image-resize-gtk
----------------

Allows the easy resizing of all images in a selected folder for web upload. Desired size is set via a slider and all resized images are output to a new subdirectory within the original folder.


photo-backup
------------

Simple command line script to check for changes or new files in a given folder tree (indexed recursively), and if so new photos will be backed up to a set location, which is defined by the config in /home/user/.CameraTools.  Designed as a command line script to be run as a cron job in the background for hassle-free backing up.


Notes and dependencies
----------------------

* GUIs are generated using zenity, which is required for installation
* CameraTools was designed and tested for use in ubuntu, but scripts will run fine on other distros after a little editing of the installer. 
* more features to be added shortly!
