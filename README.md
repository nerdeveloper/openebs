#OpenEBS
OpenEBS is a Software Defined Storage (SDS) platform, written in GoLang, that provides the block storage containers called Virtual Storage Machines or VSMs. A VSM is a fully isolated block storage container has it's own iSCSI stack, full set of storage management APIs and back up the data to another VSM or an S3 compatible storage.

OpenEBS can scale to millions of VSMs seamlessly as it manages the metadata of the block storage system at a file level. The block storage for each VSM is one single file. The IO to this file is managed through large size chunks rather than the typical small size blocks. This enables to OpenEBS to provide higher performance for each VSM and to easilyh scale to very large number of VSMs. 

#License
OpenEBS is developed under Apache2 License at the project level. Some components of the project are derived via the GPL license and will continue to be developed under GPL.

#Running a Simple OpenEBS server
<pre-requisites>
TBD

#Building from Sources
<setup the golang environemtn>
TBD

## Quick demo of OpenEBS 
[![OpenEBS Demo](https://s32.postimg.org/wm1p8p8x1/openebs9.png)](https://youtu.be/tYQCPZMzAq4)