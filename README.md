# DefinitionLibrary
Use the links on this page to find installation files, documentation, issue tracking and discussions related to the DefinitionLibrary plug-in for Grasshopper.

DefinitionLibrary offers a searchable library, with version history, for your files and clusters - hosted in GitHub.  It consists of a top-level menu offering functions like:
- publishing definitions (i.e. files and clusters, including nested clusters) to the library, and new versions thereof
- comparing current file & clusters on the canvas with the library so you can update to the latest version, or roll back to previous versions
- downloading files (at a particular version) from the library to a local directory
- importing a cluster (at a particular version) from the library and place it on the canvas
- setting up optional Azure Application Insights tracking of definition open, close and solve (calculate) events

There is also a YouTube channel containing videos about this plug-in: https://www.youtube.com/@definitionlibrary

The plug-in is currently in the alpha stage so currently all versions of the installer binaries have expiry dates; after these dates, you will need to download and install an updated version of the plug-in.  There might be different kinds of restrictions for the upcoming beta version, and introducting a small fee for the production version is under consideration.

### How to get yourself up and running with DefinitionLibrary
#### 1. Install using one of the binaries
Either as a YAK package, manually using the ZIP package by extracting the files and copying (and unblocking file-by-file if necessary) into a new folder you create inside your `%appdata%\Grasshopper\Libraries` folder, or using the (unsigned!) MSI installer

#### 2. Run through this once-off GitHub set-up procedure
This video shows you how to configure your GitHub account, obtain a Client ID, create a repository and save the details of these in your DefinitionLibrary settings:
https://github.com/nicolaasburgers/definition-library-releases/assets/3597587/603030b0-8b96-407d-8bbe-cc42b7fad487

After that procedure is done, you're up and running!

### Notes
#### Sharing connection details
If you're working in a team, only one person needs to go through the above GitHub procedure.  The other team members do need their own GitHub accounts, but don't need to obtain a Client ID or invite collaborators to a repository.  

There is a convenient way for the person who did go through that procedure to share the Client ID and repository URL(s) to their teammates however: there is a Shareable Settings Code in the Settings window.  This code can be copied to clipboard and pasted in an email or chat message to the others in the team, who simply need to paste it into the relevant box in their Settings window.


