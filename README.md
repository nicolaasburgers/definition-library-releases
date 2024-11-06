# DefinitionLibrary
Use the links on this page to find installation files, documentation, issue tracking and discussions related to the DefinitionLibrary plug-in for Grasshopper.  Please read the Wiki for documentation: https://github.com/nicolaasburgers/definition-library-releases/wiki 

### Summary
DefinitionLibrary offers searchable cloud library, with version histories, for your Grasshopper files, clusters and Hops definitions. It currently supports GitHub as a storage plaform, with more platforms to come and stores:
- binary .gh files (all definitions, encompassing files, clusters and Hops definitions are saved as .gh files in the library)
- text files containing meta data, and 
- markdown files containing version-agnostic basic documentation for the definition

The aim in developing DefinitionLibrary was to help individuals and teams manage a set of Grasshopper files, clusters and Hops definitions that makes re-using logic safer and easier, and improving productivity in the process.

It consists of a top-level menu in the Grasshopper window, and pop-up windows, offering functions like:
- publishing definitions to the library, and new versions thereof
- updating (including rolling back to a previous version) of published clusters and Hops definitions in the current file
- downloading files (at a particular version) from the library to a local directory
- importing a cluster or Hops definition (at a particular version) from the library and place it on the canvas
- setting up optional Azure Application Insights tracking of definition open, close and solve (calculate) events

There is also a YouTube channel containing videos about this plug-in: https://www.youtube.com/@definitionlibrary

The plug-in is currently in the beta stage and is currently free to use.  When it transitions into production a small per-person-per-year fee will apply.

### How to get yourself up and running with DefinitionLibrary
Install using PackageManager.  DefinitionLibrary can be found on PackageManager, with the "include pre-releases" checkbox ticked.

#### 2. Run through this once-off GitHub set-up procedure
This video shows you how to configure your GitHub account, obtain a Client ID, create a repository and save the details of these in your DefinitionLibrary settings:
https://github.com/nicolaasburgers/definition-library-releases/assets/3597587/603030b0-8b96-407d-8bbe-cc42b7fad487

After that procedure is done, you're up and running!

### Notes
#### Sharing connection details
If you're working in a team, only one person needs to go through the above GitHub procedure.  The other team members do need their own GitHub accounts, but don't need to obtain a Client ID or invite collaborators to a repository.  

There is a convenient way for the person who did go through that procedure to share the Client ID and repository URL(s) to their teammates however: there is a Shareable Settings Code in the Settings window.  This code can be copied to clipboard and pasted in an email or chat message to the others in the team, who simply need to paste it into the relevant box in their Settings window.


