# cm1705qu1-dshand
Review of Document Version Control

A version control system (VCS) is of benefit for those working in software development by providing an organised method of recording and managing changes to code files. VCS fall into one of three categories: Local Version Control System, Centralised Version Control System and Distributed Version Control System. 

Local Version Control System

This VCS occurs when a developer is managing version control of code held within the local system on their own device.  Nothing is shared.  This may be acceptable for an individual working alone, however, collaborating with others is very difficult or almost impossible.  It should also be noted that as everything is stored locally work could be lost if there is an issue with the device. 

Centralised Version Control System

This VCS exists when a master repository is shared with a number of developers.  Whenever a change is committed it is reflected directly in the repository. A developer would not keep copies of old code they are working on their hard drive as it is always possible to retrieve any prior version held in the master repository.  A drawback of this VCS is; one developer could overwrite changes made by another during collaboration due to changes being committed directly into the central repository.  In addition to this, if any issues were to occur where the master repository is held, developers would only be able to rely on versions they hold in their local system.

Distributed Version Control System 

This VCS exists when each developer clones a copy of the same repository and saves this to their hard drive. They can make any changes and commit this to the copy of the code they hold on their hard drive without affecting the master repository.  This provides a developer with the opportunity to experiment with bugfixes or feature development and commit changes to their own copy of code and then only ‘push’ this to the master repository when they wish to share their work.
When a developer pushes their changes to the master repository ‘conflicts’ are highlighted. For example, if the merge would result in part or all of the edit being lost due to changes pushed by another developer on the same part of code.  In many cases, it takes intervention by a person to decide which changes should be committed.
Another feature of this VCS is the fact any developer can send a copy of the repository they hold to others in a team if the server becomes unavailable or corrupt.
One of the few disadvantages with this VCS is projects with a long history and therefore a high number of associated files.  This can result in an infeasibly long time to download and could use up a lot of local disk space. 
