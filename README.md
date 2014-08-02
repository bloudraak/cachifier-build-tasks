Cachifier
=========

When developing high performance websites, you'd like to cache static resources for the longest extent allowed under the RFC, which is 1 year.  However, when you make a change to the static resources, you'd like the browser and intermedatary caches to be busted to avoid any issues.  You may want to host those static resources in a CDN, like CloudFlare, Akamai and Amazon CloudFront. If you deploy frequently, you'd like to bust the cache only for those files that changes.

Given an folder with static resources, Cachifier will 

  * Create a folder public
  * Copy all the static files into the public folder
  * Rename the file so that filenames contains the hash of the contents of the file
  * References within the folder will be renamed

This was written in C# and Visual Studio 2013. 




