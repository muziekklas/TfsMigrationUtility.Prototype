# TfsMigrationUtility Prototype project
Starting from this small project, I will try to make a clean and usefull TFS migration utility to migrate projects from A to B with their history in sequence.

When the prototype is working, I will start building following compontents, based of the prototype (in order):
- TfsMigrationUtility.Core: the core Migration logic
- TfsMigrationUtility.WPF: a WPF View
- TfsMigrationUtility.CLI: a console application to assist migrations

#Supported Changes
- Add:
  - File: Done
  - Folder: Done
- Delete: 
  - File: Done
  - Folder: Done
- Rename:
  - File: Done
  - Folder: Done
- Branching:
  - File: Done
  - Folder: Done
- Rollback: 
  - File: Done => if the rollback uses Delete, Add or Rename
  - Folder: Done => if the rollback uses Delete, Add or Rename
- Merge:
  - File: Not tested
  - Folder: Not tested

#Own use
You can use this code (if it helps).
The "core" of this application is the following viewmodel: https://github.com/muziekklas/TfsMigrationUtility.Prototype/blob/master/TFSMigrationTool/ViewModels/MigrateHistoryViewModel.cs
Find the method "Runner".
I know, the code is not clean. But it was just a test :)

#Contributing
Help is always welcome! If you know something which can help development, Shoot!

#Sources
- MSDN: TFS C# API documentation
- http://blog.jessehouwing.nl/2015/11/work-around-now-commercial-features-of.html
- https://blogs.msdn.microsoft.com/granth/2010/02/27/tfs2010-create-a-new-team-project-collection-from-powershell-and-c/
- http://stackoverflow.com/questions/213873/forcing-a-tfs-checkin-of-a-file-via-c-sharp
- and other Stackoverflows

*Big Thanks to all who helped me directly by showing me the light or indirectly by posting these blogs and stackoverflows!*


