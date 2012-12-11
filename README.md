JMultiDrive
===========

A cross-platform client for multiple webdrive providers, allowing multiple simultaneous accounts.

###Background:
There are various webdrive systems that all have their own clients, but often don't allow you to login to multiple accounts at the same time and all require you to do a full sync.

Wouldn't it be nice if you'd have one client that allows you to add multiple accounts (even for the same provider) that you can tell where to store your files and also allow you mount your webdrive as a virtual drive. Mounting your webdrive as a virtual drive gives you some extra security because not all the the data is downloaded to the client. Only the files you open are downloaded. Your laptop stolen? How unfortunate, but no worries at least your files are safe, just change your password of your webdrive account and your files won't be open to the world. A full directory sync would have all your files on your client, so even if you change your password, all your files would still be on the stolen laptop. Of course, if you do wish to be able to edit offline, you can enable this.

###Implementation
For the Alpha version I'll try to implement Windows Drive Mapping through JDokan and Linux FUSE mapping through JFuse and of course the full directory sync.
The providers that will be supported out of the box will be Google Drive and Dropbox.

This is still very much in development. See https://docs.google.com/drawings/d/1fi9WOTfpwbLnBNOQwk987naCdp-UNKcEb82kDAXaW64/edit
for a overview of the various objects in the architecture.

###License
This project will be released under the GNU Lesser General Public License version 3