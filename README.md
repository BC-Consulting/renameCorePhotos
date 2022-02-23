# renameCorePhotos
Rename core photos from mineral exploration drilling

Two versions:
- Desktop app: if running Jupyterlab locally and access to filesystem is granted.
- Web app: if photos are located in a website folder.

Web app requires a file named `list.txt`, which is a list of all photos to process.\
In Windows create it from the commandline with: `dir /b *.jpg >list.txt`\
On *nix create it from terminal with: `ls -b -1 >list.txt`
