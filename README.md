# DefinitionLibrary

### Elevator pitch
Teams working together with Grasshopper find it difficult to catalog and version their shared Grasshopper resources and end up with unnecessary re-work. DefinitionLibrary enables teams to create searchable, version controlled external library of their files, snippets, clusters and script code across multiple platforms. It saves time by enabling easy discovery and re-use of previous work. It offers what is possible using several software tools into a simple UI inside Grasshopper itself and uses teams' own GitHub and Microsoft resources.

### How to use this guide
Use the links on this page to find installation files, documentation, issue tracking and discussions related to the DefinitionLibrary plug-in for Grasshopper.  Please read the Wiki for documentation: https://github.com/nicolaasburgers/definition-library-releases/wiki 

### Summary
DefinitionLibrary offers searchable cloud library, with version histories, for your Grasshopper files, clusters, Hops definitions and snippets and script code (C# and Python). It currently supports GitHub as a storage plaform, with SharePoint, OneDrive and local/network folders, and stores:
- binary .gh files (all Grasshopper files, clusters, Hops definitions and snippets are saved as .gh files in the library)
- pure C# and Python source code
- meta data, either in separate text files or attached to the files themselve 
- markdown files containing version-agnostic basic documentation for the definition

The aim in developing DefinitionLibrary was to help individuals and teams manage a set of Grasshopper logic that makes re-use logic safer and easier, and thereby improving productivity.

It consists of a top-level menu in the Grasshopper window, and pop-up windows, offering functions like:
- publishing new definitions and script code to the library
- publishing new versions of definitions and script code to the library
- updating (including rolling back to a previous version) of published definitions or script code used in the currently-open file
- downloading files from the library to a local directory
- importing a cluster, Hops definition or snippet at a particular version from the library and place it on the canvas
- setting up optional Azure Application Insights tracking of definition open, close and solve (calculate) events

There is also a YouTube channel containing videos about this plug-in: https://www.youtube.com/@definitionlibrary

The plug-in is currently in the beta stage and is currently free to use.  When it transitions into production a small per-person-per-year fee will apply.

### How to get yourself up and running with DefinitionLibrary
Install using PackageManager.  DefinitionLibrary can be found on PackageManager, with the "include pre-releases" checkbox ticked.

If you want to use GitHub to store some definitions or script code, then this video shows you how to configure your GitHub account, obtain a Client ID, create a repository and save the details of these in your DefinitionLibrary settings:
https://github.com/nicolaasburgers/definition-library-releases/assets/3597587/603030b0-8b96-407d-8bbe-cc42b7fad487

If you want to use SharePoint and/or OneDrive for business then your company would either need to create a registered app in Azure or approve the default registered app.

After that procedure is done, you're up and running!

### Notes
#### Sharing connection details
If you're working in a team:
- if using GitHub, only one person needs to go through the above GitHub procedure; the other team members do need their own GitHub accounts, but don't need to obtain a Client ID or invite collaborators to a repository
- if using SharePoint/OneDrive, the IT administrator would need to either approve the default DefinitionLibrary registered app or create either create a registered app within the company's Azure tenancy and share the the Client ID and Tenant ID with employees

There is a convenient way for the person who did go through that procedure to share the IDs to their teammates however: there is a Shareable Settings Code in the Settings window.  This code can be copied to clipboard and pasted in an email or chat message to the others in the team, who simply need to paste it into the relevant box in their Settings window.


