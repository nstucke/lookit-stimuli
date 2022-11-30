# Developing Minds Lab Lookit Stimuli

The instructions below are primarily intended for people with limited experience using GitHub or Git. If you are already comfortable using git via the command line or a desktop client and pushing your changes to GitHub, there is no need to use the GitHub web interface.

## Adding your stimuli

1. Click on the appropriate directory. For images, that's `img`. For audio and video files, the appropriate directory depends on their file format.

2. Click 'Upload files.' Drag and drop the files from your computer that you want to put online.

3. Click 'Commit changes,' adding a brief message explaining what you added or changed for posterity.

By keeping the various file types in their own directories, and using the same filenames for equivalent files (like an mp4 and webm version of the same video), you will be ready to make use the ``baseDir`` feature of JSON.


## How to created new directories or sub-directories:

Click 'Create new file' (instead of the usual 'Upload files') from the place where you want to add a new directory (can be from the master folder or within existing folders). Then, in the box to type the file name, type `NewDirectoryName/README.md`, replacing NewDirectoryName with your desired directory name.  This will create the new directory and a README.md file inside it. Then you can add other files too.

## ``baseDir``

The base directory for this fork is: https://raw.githubusercontent.com/nstucke/lookit-stimuli/master/

## Making changes to stimuli 

**Deleting files**: You can delete individual files by navigating to them in GitHub and then clicking the "trash" icon. You'll be prompted to commit this change. 

**Changing files**: You can upload new versions of your files in the same directory where the old ones are to replace them.

Each time you delete a file or upload a new file, you will need to commit the change. Your commit history then shows a complete record of the changes you've made over time, which is very helpful for your future self.
