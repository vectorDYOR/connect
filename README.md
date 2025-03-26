# connect

## A plug-in for Rhino Grasshopper allowing for the connection to different Databases.

I’ve created a new plug-in which connects your Grasshopper window to GitHub, allowing you and your team/company to store, retrieve, update and switch versions of files and clusters from GitHub as a cloud library. It’s available as a pre-release (beta) in the PackageManager, for Rhino 7 & 8.

I always wanted a better way to manage versions of my files and clusters from within Grasshopper itself. I’ve also seen professional teams finding it difficult to collaborate across a shared set of GH files and clusters. This plug-in is my contribution to solving those problems!

With this plug-in you still open and run files locally, but the plug-in offers the ability to download files, to update the versions of files/clusters (in-line) and publish new or new versions of existing files/clusters. Each local file has a revision entry (in File → Document properties → Revisions) which stores details of its cloud library (GitHub) address.

It even displays published name and versions above each cluster.

## Some principles in its design:

offer as much functionality within the Grasshopper window itself, at least for day-to-day actions
avoid proprietary platforms (GitHub doesn’t count in my book as it’s so generic)
maximise portability of GH files/clusters such that they can be saved anywhere and shared with people who don’t have the plug-in
enable collaboration within teams, in organisations and also teams that collaborate with 3rd parties
make visual identification of file/cluster versions, and how far behind they are from the latest version (if relevant) as easy as possible
If you have some time to try it out, I’ve created a landing page for it as a starting point for you: https://www.definitionlibrary.com . It includes a video on the necessary one-off GitHub account configuration

